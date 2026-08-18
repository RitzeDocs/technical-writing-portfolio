# CareBridge Connect Troubleshooting Guide

> **Portfolio Sample:** This fictional technical documentation sample demonstrates troubleshooting and user-support documentation for a healthcare software product. All company names, products, people, and workflows are fictional.

**Current Product Version:** v1.05.31

## Overview

Use this guide to resolve common issues when accessing or using CareBridge Connect and CRxeate.

**CRxeate is a browser-based application** used to access and maintain CareBridge Connect.

Before troubleshooting:

- Confirm that you have an active internet connection.
- Confirm that **CompanyVPN** displays as **Connected**.
- Note any error messages that appear.
- Save unsaved work only if you have confirmed that you are working in the correct environment.

If the issue continues after completing the recommended troubleshooting steps, follow the escalation instructions provided for that issue.

## 1. Unable to Sign In

### Symptoms

You may experience one or more of the following:

- CareBridge Connect does not load after you enter your company credentials.
- The message **Unable to connect to secure server** appears.
- CareBridge Connect cannot establish a secure connection after sign-in.

### Possible Causes

- CompanyVPN is not connected.
- The CompanyVPN connection was interrupted.
- Your CompanyVPN session expired.

### Resolution

1. Open **CompanyVPN**.
2. Disconnect from the current VPN session.
3. Reconnect to **CompanyVPN**.
4. Confirm that the VPN status displays as **Connected**.
5. Try signing in to CareBridge Connect again.
6. If the issue continues, restart your computer.
7. After the restart, reconnect to **CompanyVPN**.
8. Confirm that the VPN status displays as **Connected**.
9. Try signing in to CareBridge Connect again.

### If the Issue Continues

If you are still unable to sign in after reconnecting to CompanyVPN and restarting your computer, contact **IT Support**.

When contacting IT Support, include:

- The error message displayed
- Whether CompanyVPN displays as **Connected**
- The troubleshooting steps you already completed
- A screenshot of the error, if appropriate

> **Important:** Do not include patient information or other sensitive data in screenshots or support messages.

## 2. Cannot Access a Patient Workspace

### Symptoms

You may experience one or more of the following:

- The patient workspace does not appear in your assigned patient list.
- CareBridge Connect displays **Access Denied** when you try to open the workspace.
- A patient you are assigned to does not appear in CareBridge Connect.

### Possible Causes

- You have not been granted access to the patient workspace.
- Your patient assignment was recently updated and access has not been added yet.

### Resolution

1. Confirm that the patient is assigned to you or that you are part of the patient's authorized care team.
2. If the assignment is correct, contact your **manager or clinical lead**.
3. Your manager or clinical lead will verify the assignment and submit an access request to the **Access Administration team**.
4. Wait until you receive confirmation that access has been granted.
5. Sign out of CareBridge Connect.
6. Sign back in using your company account.
7. Open the patient workspace again.

> **Important:** Do not attempt to bypass patient access restrictions or use another employee's account to access a workspace.

### If the Issue Continues

If access has been approved but the patient workspace is still unavailable:

1. Sign out of CareBridge Connect.
2. Confirm that **CompanyVPN** displays as **Connected**.
3. Sign back in to CareBridge Connect.
4. Try opening the patient workspace again.

If the issue continues, contact **IT Support**.

When contacting IT Support, include:

- The access request or support ticket number, if available
- Confirmation that access was approved
- The error message displayed
- The troubleshooting steps you completed

> **Important:** Do not include patient names, diagnoses, medical records, or other sensitive health information in general support messages.

## 3. CRxeate Shows the Wrong Environment

### Symptoms

You may experience one or more of the following:

- The CRxeate Environment Selector does not display **Training**.
- The workspace looks different from the environment used during onboarding.
- Expected training data or project settings are unavailable.

### Possible Causes

- CRxeate reopened your previously selected environment.
- A saved link opened a different environment.
- The incorrect environment was selected from the Environment Selector.
- The current CRxeate browser session did not load correctly.

### Resolution

Before troubleshooting, note any error message displayed.

1. Stop any work currently in progress.
2. Refresh the CRxeate browser tab.
3. Wait for the workspace to reload completely.
4. Check the **Environment Selector**.
5. If **Training** is not selected, open the Environment Selector.
6. Select **Training**.
7. Confirm that the Environment Selector now displays **Training**.
8. Open the **CareBridge Connect** workspace.
9. Verify that the current product version displays as **v1.05.31**.
10. Resume your assigned task only after confirming that you are in the correct environment.

> **Important:** Do not make or save additional changes if you are unsure which CRxeate environment you are using. If you have unsaved work, contact your project lead before continuing.

### If the Issue Continues

If refreshing the browser tab and selecting **Training** does not resolve the issue:

1. Confirm that **CompanyVPN** displays as **Connected**.
2. Sign out of CRxeate.
3. Sign back in using your company account.
4. Check the Environment Selector again.
5. If the issue continues, close the CRxeate browser tab.
6. Reopen CRxeate in your browser.
7. Confirm that **Training** is selected in the Environment Selector.

If the Training environment is still unavailable, contact **IT Support**.

When contacting IT Support, include:

- The environment currently displayed
- The error message, if one appears
- The troubleshooting steps you completed
- A screenshot of the issue, if appropriate

> **Important:** Do not include patient information or other sensitive data in screenshots sent to support.

## 4. Troubleshooting Quick Reference

| Issue | First Action | Escalate To |
| --- | --- | --- |
| Unable to sign in | Reconnect to CompanyVPN | IT Support |
| Cannot access a patient workspace | Confirm your patient assignment | Manager or Clinical Lead |
| Approved patient access still does not work | Sign out and sign back in | IT Support |
| CRxeate shows the wrong environment | Refresh the browser tab and check the Environment Selector | IT Support |

## Contact Support

If you cannot resolve an issue using this guide, contact the appropriate support team.

When reporting a technical issue, provide:

- Your name
- The affected application or feature
- A brief description of the issue
- The exact error message, if one appears
- The troubleshooting steps you already completed
- A screenshot, if appropriate

Providing this information can help the support team investigate the issue without repeating troubleshooting steps you have already completed.

> **Important:** Do not include patient names, diagnoses, medical records, or other sensitive information in screenshots or general support messages.

## Document Information

| | |
| --- | --- |
| **Document Owner** | CareBridge Documentation Team |
| **Product** | CareBridge Connect |
| **Product Version** | v1.05.31 |
| **Last Updated** | August 18, 2026 |
| **Review Cycle** | Each major product release |
