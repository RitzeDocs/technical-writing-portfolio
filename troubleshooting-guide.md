# CareBridge Connect Troubleshooting Guide

> **Portfolio Sample:** This fictional technical documentation sample demonstrates troubleshooting and user-support documentation for a healthcare software product. All company names, products, people, and workflows are fictional.

**Current Product Version:** v1.05.31

## Overview

Use this guide to resolve common issues when accessing CareBridge Connect and CRxeate.

CRxeate is a browser-based application used to access and maintain CareBridge Connect.

Before troubleshooting:

- Confirm that you have an active internet connection.
- Confirm that **CompanyVPN** displays as **Connected**.
- Note any error messages that appear.

## Troubleshooting Quick Reference

| Issue | Try First | Escalate To |
| --- | --- | --- |
| Unable to sign in | Reconnect to CompanyVPN | IT Support |
| Cannot access a patient workspace | Confirm your patient assignment | Manager or Clinical Lead |
| Wrong CRxeate environment during onboarding | Check the Environment Selector | IT Support |

---

<details>
<summary><strong>1. Unable to Sign In</strong></summary>

### Symptoms

- CareBridge Connect does not load after sign-in.
- **Unable to connect to secure server** appears.
- CareBridge Connect cannot establish a secure connection.

### Possible Causes

- CompanyVPN is disconnected.
- The VPN connection was interrupted.
- Your VPN session expired.

### Resolution

1. Open **CompanyVPN**.
2. Disconnect from the current VPN session.
3. Reconnect to **CompanyVPN**.
4. Confirm that the status displays **Connected**.
5. Try signing in to CareBridge Connect again.
6. If the issue continues, restart your computer.
7. Reconnect to CompanyVPN and try again.

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

### Resolution

1. Confirm that you are part of the patient's authorized care team.
2. If the assignment is correct, contact your **manager or clinical lead**.
3. Your manager or clinical lead will verify the assignment and submit a request to the **Access Administration team**.
4. Wait for confirmation that access has been granted.
5. Sign out of CareBridge Connect.
6. Sign back in and open the patient workspace again.

> **Important:** Do not attempt to bypass patient access restrictions or use another employee's account.

### If Access Was Already Approved

1. Confirm that **CompanyVPN** displays **Connected**.
2. Sign out of CareBridge Connect.
3. Sign back in.
4. Try opening the patient workspace again.

If the issue continues, contact **IT Support**.

</details>

---

<details>
<summary><strong>3. CRxeate Shows the Wrong Environment During Onboarding</strong></summary>

During onboarding, CRxeate should display the **Training** environment unless your manager instructs you otherwise.

### Symptoms

- The Environment Selector does not display **Training**.
- The workspace looks different from the onboarding environment.
- Expected training data or settings are unavailable.

### Possible Causes

- CRxeate reopened your previously selected environment.
- A saved link opened a different environment.
- The browser session did not load correctly.

### Resolution

> **Important:** If you have unsaved work and are unsure which environment you are using, do not refresh or save additional changes. Contact your project lead before continuing.

1. Stop any work currently in progress.
2. Check the **Environment Selector**.
3. If necessary, select **Training**.
4. If the correct environment does not load, refresh the CRxeate browser tab.
5. Open the **CareBridge Connect** workspace.
6. Verify that the product version displays as **v1.05.31**.
7. Resume work only after confirming that you are in the correct environment.

### If the Issue Continues

1. Confirm that **CompanyVPN** displays **Connected**.
2. Sign out of CRxeate and sign back in.
3. Check the Environment Selector again.
4. If needed, close and reopen the CRxeate browser tab.

If **Training** is still unavailable, contact **IT Support**.

</details>

---

## Contact Support

When reporting a technical issue, provide:

- The affected application or feature
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
| **Product Version** | v1.05.31 |
| **Last Updated** | August 18, 2026 |
| **Review Cycle** | Each major product release |
