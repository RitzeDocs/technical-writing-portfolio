# CareBridge Team Onboarding Guide

> **Portfolio Sample:** This fictional internal documentation sample demonstrates onboarding content for a healthcare software team. All company names, products, people, and workflows are fictional.

**Current Product Version:** v1.06.00  
**Last Updated:** September 2026  
**Document Owner:** CareBridge Documentation Team

---

## Welcome

Welcome to the CareBridge team!

CareBridge develops software that helps mental health professionals coordinate care for shared patients.

This guide will help you:

- Access required tools and systems
- Understand the CareBridge Connect product
- Locate project information
- Learn the team's core workflow
- Prepare for your first assignment

**Audience:** New team members joining the product and QA teams  
**Purpose:** Help new team members access required tools, understand documentation standards, and complete their initial setup.  
**Scope:** This guide covers general onboarding for product and QA team members. Role-specific training and access requirements may vary.

### About CareBridge Connect

**CareBridge Connect** is a secure patient coordination portal designed for mental health professionals who support the same patient.

Authorized providers, including therapists, psychiatrists, and care coordinators, can use the portal to access relevant patient information and communicate with other members of the treatment team.

By centralizing communication, CareBridge Connect reduces reliance on phone calls and disconnected follow-ups between providers.

## 1. Team & Project Overview

### Development Platform

CareBridge Connect is developed and maintained using **CareBridge Workspace**, the team's browser-based development and configuration platform.

During onboarding, new team members use a training environment containing mock patient data.

> **Important:** Do not enter real patient information into the CareBridge Workspace training environment.

## 2. Team Schedule

### Daily Stand-Up

The team meets each business day for a short stand-up.

Be prepared to briefly discuss:

- Your current assignment
- Progress since the previous stand-up
- Planned work for the day
- Questions or blockers

### Company Meeting

A company-wide meeting is held on the **third Thursday of each month**.

Topics may include:

- Product and release updates
- Department announcements
- Upcoming company goals
- Process or policy changes
- Team recognition

### Release Schedule

Release dates and assignments are maintained in **Jira**.

Check the appropriate Jira project for:

- Current release dates
- Task-specific deadlines
- Release assignments
- Changes to planned release scope

## 3. Required Access

Confirm access to the following systems before beginning project work:

| Tool | Purpose |
| --- | --- |
| Microsoft Teams | Team communication, meetings, and project discussions |
| Company Email | Company communication and account notifications |
| Confluence | Internal documentation and project information |
| Jira | Task assignments, bugs, feature requests, and project tracking |
| Miro | Collaborative diagrams, workflows, and planning |
| Company VPN | Secure access to internal systems |
| CareBridge Workspace | Browser-based development and configuration of CareBridge Connect |
| Company SSO/MFA | Secure authentication for company systems |
| Password Manager | Approved credential storage |

Additional tools may be required depending on your role.

> **Access Issue?** Contact IT Support if you cannot access a required system.

## 4. Initial Setup

Complete the following steps during onboarding:

- [ ] Sign in to your company email.
- [ ] Sign in to Microsoft Teams.
- [ ] Confirm access to Confluence.
- [ ] Confirm access to Jira.
- [ ] Confirm access to Miro.
- [ ] Configure and test the Company VPN.
- [ ] Complete SSO and multi-factor authentication setup.
- [ ] Sign in to CareBridge Workspace.
- [ ] Review this onboarding guide.
- [ ] Join your assigned Teams channels.
- [ ] Attend scheduled onboarding and setup meetings.
- [ ] Open the CareBridge Workspace training environment.
- [ ] Explore the CareBridge Workspace interface and settings.
- [ ] Report missing access to your manager or IT Support.

## 5. Using CareBridge Workspace

CareBridge Workspace is the primary browser-based platform used to develop and configure CareBridge Connect.

### Access CareBridge Workspace

1. Connect to the **Company VPN**.
2. Open **CareBridge Workspace** in your browser.
3. Select the required CareBridge Connect environment.
4. Confirm that you are in the correct project area.
5. Complete the assigned work.
6. Record relevant implementation details in Jira.

> **Important:** Use the Training environment during onboarding unless your manager instructs you otherwise.

### Open the CareBridge Connect Project

1. From the CareBridge Workspace dashboard, select **Projects**.
2. Select **CareBridge Connect**.
3. Verify that the current version displays as **v1.06.00**.
4. Select **Workspace** to open the project.

### Review an Assigned Work Item

Before making changes in CareBridge Workspace:

1. Open your assigned Jira ticket.
2. Review the requirements and acceptance criteria.
3. Identify any referenced feature, screen, or workflow.
4. Review linked Confluence documentation.
5. Return to CareBridge Workspace.
6. Locate the related project area.
7. Review the existing configuration before making changes.

If the Jira requirements do not match the current CareBridge Workspace configuration, contact the project lead before continuing.

### Explore the Workspace

During onboarding, locate the following areas:

- **Dashboard** — View recent activity and assigned work.
- **Projects** — Access CareBridge Connect project files.
- **Settings** — Manage account and workspace preferences.
- **Environment Selector** — Confirm the environment currently in use.
- **Help** — Access CareBridge Workspace documentation and troubleshooting resources.

You do not need to make project changes during this step. The goal is to become familiar with the interface and confirm that your access is working correctly.

### CareBridge Workspace Dashboard

The CareBridge Workspace dashboard provides access to assigned work, project information, environment settings, and support resources.

[![Annotated CareBridge Workspace dashboard showing project navigation, the Training environment selector, current product version, Settings, and Help.](images/carebridge-workspace-dashboard.png)](images/carebridge-workspace-dashboard.png)

## 6. Where to Find Information

Use existing documentation and project resources before requesting information from another team member.

| Information Needed | Where to Look |
| --- | --- |
| Project documentation | CareBridge Connect Confluence Space |
| Current assignments | CareBridge Jira Board |
| Team announcements | CareBridge Teams Channel |
| Development questions | **@Alex Morgan** — Development Lead |
| Product or requirement questions | **@Jordan Lee** — Product Manager |
| Testing questions | **@Taylor Reed** — QA Lead |
| Documentation questions | **@Morgan Chen** — Technical Writer |
| Access or account problems | **@IT Support** |

If you cannot find the information you need, contact the appropriate person in Microsoft Teams.

## 7. Core Workflow

Most CareBridge Connect work follows the same general process.

### 1. Review the Assignment

Open your assigned **Jira ticket** and review:

- Task description
- Requirements
- Acceptance criteria
- Supporting documentation
- Priority
- Target release

Clarify incomplete or conflicting requirements before beginning work.

### 2. Review Supporting Information

Review any linked **Confluence pages**, diagrams, or related Jira tickets.

Confirm that you understand:

- Expected behavior
- Existing functionality
- Dependencies
- Known limitations

### 3. Complete the Work

Use the appropriate tools to complete the assigned task.

For CareBridge Workspace-related work:

1. Connect to the **Company VPN**.
2. Open **CareBridge Workspace**.
3. Select the required CareBridge Connect environment.
4. Confirm that you are in the correct project area.
5. Complete the assigned change.
6. Record relevant implementation details in Jira.

### 4. Validate the Change

Confirm that the completed work meets the ticket's acceptance criteria.

Validation may include:

- Functional testing
- Peer review
- QA testing
- Requirement verification
- Documentation review

Record any issues discovered during validation in Jira.

### 5. Update Documentation

Determine whether the change affects existing documentation.

Update relevant Confluence pages when necessary, including:

- User workflows
- Internal processes
- Feature behavior
- Known limitations
- Troubleshooting information

### 6. Submit for Review

When the work is ready:

1. Update the Jira ticket status.
2. Add relevant implementation or testing notes.
3. Link supporting documentation.
4. Assign the ticket to the appropriate reviewer.

Complete any requested changes before approval.

### 7. Prepare for Release

Before the task is included in a release, confirm that:

- Required testing is complete.
- Documentation is current.
- Known issues are recorded.
- Jira reflects the final status of the work.

## 8. Communication & Collaboration

Use the communication method that best matches the type of information being shared.

- **Active work and task-specific questions:** Jira
- **Quick questions and team discussion:** Microsoft Teams
- **Permanent project information:** Confluence
- **Visual planning and workflows:** Miro
- **Access problems:** IT Support
- **Urgent blockers:** Manager or project lead

Avoid keeping important project decisions only in private messages. Record decisions in Jira or Confluence when they may affect future work.

## 9. First-Day Checklist

Before the end of your first day:

- [ ] Confirm access to all required tools.
- [ ] Configure the Company VPN and MFA.
- [ ] Join required Microsoft Teams channels.
- [ ] Review the CareBridge Connect project overview.
- [ ] Locate the team Confluence space.
- [ ] Locate the CareBridge Jira board.
- [ ] Sign in to the CareBridge Workspace training environment.
- [ ] Explore the CareBridge Workspace interface and settings.
- [ ] Attend scheduled onboarding meetings.
- [ ] Confirm your primary point of contact.
- [ ] Report any missing access or unresolved questions.

## 10. Getting Help

Start by checking:

1. The relevant Jira ticket
2. Existing Confluence documentation
3. Microsoft Teams discussions

If you still cannot find the information you need, contact the appropriate subject matter expert listed in [Where to Find Information](#6-where-to-find-information).

For account, Company VPN, or access problems, contact **IT Support**.

## Document Information

| | |
| --- | --- |
| **Document Owner** | CareBridge Documentation Team |
| **Product** | CareBridge Connect |
| **Product Version** | v1.06.00 |
| **Last Updated** | September 2026 |
| **Review Cycle** | Each major product release |
