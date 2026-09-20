
> **Portfolio Sample:** This fictional technical documentation sample demonstrates troubleshooting and user-support documentation for a healthcare software product. All company names, products, people, and workflows are fictional.

**Current Product Version:** v1.06.00  
**Last Updated:** September 2026  
**Document Owner:** CareBridge Documentation Team

---

## Overview

Use this guide to resolve common access and environment issues in CareBridge Connect and CareBridge Workspace.

**Audience:** CareBridge Connect users and internal product and QA team members  
**Purpose:** Help users resolve common issues before escalating them to the appropriate support team.  
**Scope:** This guide covers common access, patient workspace, and onboarding environment issues. Issues not covered here should be escalated to the appropriate support team.

CareBridge Workspace is the browser-based platform used to develop and configure CareBridge Connect.

Before troubleshooting:

- Confirm that you have an active internet connection.
- Confirm that the **Company VPN** displays as **Connected**.
- Note any error messages that appear.
- Confirm which CareBridge Workspace environment you are using.

## Troubleshooting Quick Reference

| Issue | Try First | Escalate To |
| --- | --- | --- |
| Unable to sign in | Reconnect to the Company VPN | IT Support |
| Cannot access a patient workspace | Confirm your patient assignment | Manager or Clinical Lead |
| Wrong CareBridge Workspace environment during onboarding | Check the Environment Selector | IT Support |

---

<details>
<summary><strong>1. Unable to Sign In</strong></summary>

### Symptoms

- CareBridge Connect does not load after you attempt to sign in.
- **Unable to connect to secure server** appears.
- CareBridge Connect cannot establish a secure connection.

### Possible Causes

- The Company VPN is disconnected.
- The VPN connection was interrupted.
- Your VPN session expired.

### Resolution

1. Open the **Company VPN**.
2. Disconnect from the current VPN session.
3. Reconnect to the **Company VPN**.
4. Confirm that the status displays **Connected**.
5. Try signing in to CareBridge Connect again.
6. If the issue continues, restart your computer.
7. Reconnect to the Company VPN.
8. Try signing in again.

If the issue continues, contact **IT Support**.

</details>

---

<details>
<summary><strong>2. Cannot Access a Patient Workspace</strong></summary>

### Symptoms

- The patient workspace does not appear in your assigned patient list.
- CareBridge Connect displays **Access Denied**.

### Possible Causes

- You have not been granted access to the patient workspace.
- Your patient assignment was recently updated.
- A recently approved access change has not yet appeared in your session.

### Resolution

1. Confirm that you are part of the patient's authorized care team.
2. If the assignment is correct, contact your **manager or clinical lead**.
3. Your manager or clinical lead will verify the assignment and submit a request to the **Access Administration team**, if needed.
4. Wait for confirmation that access has been granted.
5. Sign out of CareBridge Connect.
6. Sign back in.
7. Open the patient workspace again.

> **Important:** Do not attempt to bypass patient access restrictions or use another employee's account.

### If Access Was Already Approved

1. Confirm that the **Company VPN** displays as **Connected**.
2. Sign out of CareBridge Connect.
3. Sign back in.
4. Try opening the patient workspace again.

If the issue continues, contact **IT Support**.

</details>

---

<details>
<summary><strong>3. CareBridge Workspace Shows the Wrong Environment During Onboarding</strong></summary>

During onboarding, CareBridge Workspace should display the **Training** environment unless your manager instructs you otherwise.

### Symptoms

- The Environment Selector does not display **Training**.
- The workspace looks different from the expected onboarding environment.
- Expected training data or settings are unavailable.

### Possible Causes

- CareBridge Workspace reopened a previously selected environment.
- A saved link opened a different environment.
- The browser session did not load correctly.

### Resolution

> **Important:** If you have unsaved work and are unsure which environment you are using, do not refresh the page or save additional changes. Contact your project lead before continuing.

1. Stop any work currently in progress.
2. Check the **Environment Selector**.
3. Select **Training**, if available.
4. Confirm that the Environment Selector displays **Training**.
5. Open the **CareBridge Connect** project.
6. Verify that the product version displays as **v1.06.00**.
7. Resume work only after confirming that you are in the correct environment.

### If the Issue Continues

1. Confirm that the **Company VPN** displays as **Connected**.
2. Sign out of CareBridge Workspace.
3. Sign back in.
4. Check the Environment Selector again.
5. If needed, close and reopen the CareBridge Workspace browser tab.

If **Training** is still unavailable, contact **IT Support**.

</details>

---

## Escalate an Issue

When reporting a technical issue, provide:

- The affected application or feature
- The CareBridge Workspace environment, if applicable
- A brief description of the issue
- The exact error message, if one appears
- The troubleshooting steps you completed
- A screenshot, if appropriate

> **Important:** Do not include patient names, diagnoses, medical records, or other sensitive information in screenshots or general support messages.

## Document Information

| | |
| --- | --- |
| **Document Owner** | CareBridge Documentation Team |
| **Product** | CareBridge Connect |
| **Product Version** | v1.06.00 |
| **Last Updated** | September 2026 |
| **Review Cycle** | Each major product release |
