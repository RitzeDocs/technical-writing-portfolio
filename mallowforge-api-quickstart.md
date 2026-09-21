# Mallowforge API Quickstart

> **Portfolio Sample:** This fictional developer documentation sample demonstrates beginner-friendly API documentation for an AI-powered knowledge and support platform. All products, endpoints, credentials, responses, and workflows are fictional.

**Audience:** Developers with basic command-line familiarity who are new to the Mallowforge API  
**Purpose:** Send your first question to Mallowforge and receive a grounded answer from approved company documentation.  
**API Version:** v1  
**Last Updated:** September 2026

---

## What You'll Do

In this quickstart, you'll ask Mallowforge a support-related question and receive an answer supported by approved company documentation.

`Your question → Mallowforge API → Approved documentation → Grounded answer`

By the end of this guide, you'll have completed your first Mallowforge API request.

## Before You Begin

Make sure you have:

- [ ] A Mallowforge account
- [ ] A Mallowforge API key
- [ ] At least one connected knowledge source
- [ ] A terminal with `curl` installed

> [!NOTE]
> `curl` is a command-line tool used to send requests to websites and APIs.

This quickstart assumes your Mallowforge workspace already contains an approved knowledge source.

## Get Your API Key

Mallowforge uses an **API key** to authenticate your application.

To create one:

1. Sign in to Mallowforge.
2. Go to **Settings > Developer > API Keys**.
3. Select **Create API Key**.
4. Enter a name for the key.
5. Copy the generated key and store it securely.

An example key might look like this:

```text
mf_example_123456
```

> [!IMPORTANT]
> Keep your API key private. Do not publish it in a GitHub repository, client-side code, or public documentation.

## Set Your API Key

Save your API key as an environment variable before making a request.

### macOS, Linux, or Bash

```bash
export MALLOWFORGE_API_KEY="your_api_key_here"
```

### Windows PowerShell

```powershell
$env:MALLOWFORGE_API_KEY="your_api_key_here"
```

Replace `your_api_key_here` with the API key you created.

Using an environment variable keeps the key separate from your example code and makes it easier to reuse across requests.

## Send Your First Question

Questions are sent to the `/v1/answers` **endpoint**. An endpoint is a specific API address used to perform an action.

Use the command for your terminal.

### macOS, Linux, or Bash

```bash
curl -X POST https://api.mallowforge.example/v1/answers \
  -H "Authorization: Bearer $MALLOWFORGE_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "question": "What should I check before escalating a login issue?"
  }'
```

### Windows PowerShell

```powershell
curl.exe -X POST https://api.mallowforge.example/v1/answers `
  -H "Authorization: Bearer $env:MALLOWFORGE_API_KEY" `
  -H "Content-Type: application/json" `
  -d '{
    "question": "What should I check before escalating a login issue?"
  }'
```

This request:

- Sends a question to the `/v1/answers` endpoint.
- Uses your API key to authenticate the request.
- Sends the question as JSON for Mallowforge to process.

## Expected Result

If the request succeeds, Mallowforge returns a response like this:

```json
{
  "answer": "Before escalating a login issue, confirm the user's account status, verify that the authentication service is available, and review any recent access changes.",
  "sources": [
    {
      "title": "Login Issue Troubleshooting Guide",
      "source_id": "doc_1842"
    }
  ],
  "request_id": "req_7f21a9"
}
```

The response contains three main pieces of information:

- `answer` contains Mallowforge's answer to your question.
- `sources` identifies the approved documentation used to support the answer.
- `request_id` identifies the request and can help with troubleshooting.

> [!TIP]
> If you received an answer and at least one source, your first Mallowforge API request worked.

> [!NOTE]
> If Mallowforge cannot find enough supporting information in connected sources, it returns no answer instead of generating an unsupported response.

## Troubleshoot an Invalid API Key

If Mallowforge cannot verify your API key, it returns a `401 Unauthorized` response.

```json
{
  "error": {
    "code": "invalid_api_key",
    "message": "The provided API key is invalid."
  }
}
```

If you receive this error:

1. Confirm that your environment variable contains the correct API key.
2. Check that the API key is still active.
3. Confirm that the `Authorization` header begins with `Bearer`.
4. Try the request again.

## Next Steps

Now that you've completed your first request, you can:

- Try asking a different question.
- Connect additional knowledge sources.
- Explore the full Answers API reference.
