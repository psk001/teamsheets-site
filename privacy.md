---
title: Privacy policy
permalink: /privacy
---

# Teamsheets privacy policy

_Last updated: 18 November 2026_

Teamsheets ("the app") is a Jira Cloud app published on the Atlassian Marketplace by teamsheets
("we"). This policy explains what the app stores and where.

## Where data lives

Teamsheets runs entirely on Atlassian Forge. It has no servers of its own and sends no data outside
Atlassian ("Runs on Atlassian"). Everything the app stores is kept in Forge hosted storage for the
customer's Jira site, under Atlassian's security, data residency and retention controls. We cannot
read it.

## What the app stores

- **Settings** chosen by Jira admins: access lists (Atlassian account IDs and group IDs), approver
  account IDs, project keys, status IDs, week and working-day options, expected hours.
- **Teams**: team names and the account IDs of their leads and members.
- **Timesheet records**: for each person and week, the status (draft, submitted, approved, rejected),
  a snapshot of logged hours per issue and day taken at submission, timestamps, the reviewer's account
  ID and any review comment.
- **Personal preferences**: each person's time format.

The app does not store names, email addresses or avatars; it shows them by asking Jira at the time.
Logged time itself is saved as ordinary Jira worklogs, which belong to the customer's Jira site and
follow Jira's own permissions and retention.

## What the app does not do

No analytics, tracking, cookies, advertising or data sales. No data is shared with third parties.

## Closed Atlassian accounts

Every week the app reports the account IDs it stores to Atlassian's personal data reporting API. When
Atlassian reports an account as closed, the app removes it from settings, approvers and teams and
deletes that person's timesheet records and preferences.

## Retention and deletion

Data stays for as long as the app is installed. Jira admins can change settings and teams at any time.
When the app is uninstalled, Atlassian soft-deletes its storage and permanently destroys it after the
Forge retention period (about 28 days). Jira worklogs are not affected.

## Contact

Questions or requests: [support.teamsheet@gmail.com](mailto:support.teamsheet@gmail.com)
