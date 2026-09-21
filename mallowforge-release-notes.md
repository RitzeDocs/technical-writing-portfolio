# Mallowforge v1.2.0 Release Notes

> **Portfolio Sample:** This fictional release note demonstrates product documentation for an AI-powered knowledge and support platform. All products, features, versions, and workflows are fictional.

**Release Date:** September 2026  
**Product Version:** v1.2.0

---

## New Features

### Knowledge Gap Detection

Mallowforge can now identify repeated questions that do not have strong answers in connected knowledge sources.

Knowledge Gap Detection helps knowledge managers identify documentation that may be:

- Missing
- Outdated
- Too vague to support a grounded answer
- Difficult for users to find

Similar unanswered questions are grouped together to reduce duplicate gap reports and help teams prioritize documentation updates.

> [!NOTE]
> Mallowforge identifies potential knowledge gaps but does not automatically create or publish documentation.

### Answer History

Users can now review previously generated Smart Answers.

Answer History includes:

- The original question
- The generated answer
- The sources used
- The date and time the answer was generated

Users can reopen previous answers without submitting the same question again.

## Improvements

### Clearer Unsupported Answer Messages

Smart Answers now provides clearer guidance when Mallowforge cannot find enough supporting information to generate a grounded answer.

Users may be prompted to:

- Rephrase the question
- Review connected knowledge sources
- Check for a related knowledge gap

### Improved Knowledge Gap Grouping

Mallowforge now groups similar unanswered questions into a single knowledge gap when possible.

For example, questions such as:

- "How do I unlock my account?"
- "My account is locked. What should I do?"
- "Where can I find account unlock instructions?"

may be grouped together for review.

## Fixed Issues

- Fixed an issue where some recent answers did not appear immediately in Answer History.
- Fixed an issue where similar questions could create duplicate knowledge gaps.
- Fixed an issue where source details could load incorrectly when reopening an older Smart Answer.
- Fixed an issue where unavailable knowledge sources could return unclear error messages during answer generation.

## Known Limitations

- Knowledge Gap Detection currently analyzes Smart Answers activity only.
- Answer History does not include questions deleted by a workspace administrator.
- Newly detected knowledge gaps may take several minutes to appear.

## API & Developer Notes

The Mallowforge API remains on **v1**.

No breaking API changes or integration updates are required for this release.
