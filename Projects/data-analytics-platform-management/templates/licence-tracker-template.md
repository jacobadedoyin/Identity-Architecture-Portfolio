# Analytics Platform Licence Tracker Template

## Purpose

This template provides a simple way to track analytics platform licence allocation, usage, recovery, and review activity across platforms such as Qlik and Tableau.

The aim is to improve licence visibility, support joiner / mover / leaver activity, and reduce the risk of licences remaining assigned to users who no longer require access.

## Licence Tracker

| User ID | Platform | Licence Type | Access Level | Business Area | Status | Date Assigned | Last Reviewed | Review Outcome | Notes |
|---|---|---|---|---|---|---|---|---|---|
| USER-001 | Qlik | Viewer | Standard reporting access | Finance | Active | 2026-01-10 | 2026-04-01 | Retain | Required for monthly reporting |
| USER-002 | Tableau | Creator | Dashboard publishing access | Operations | Active | 2026-02-05 | 2026-04-01 | Retain | Requires creator access for dashboard updates |
| USER-003 | Qlik | Professional | Elevated analytics access | Commercial | Under Review | 2026-01-22 | 2026-04-01 | Review access need | Confirm ongoing requirement |
| USER-004 | Tableau | Viewer | Standard reporting access | HR | Removed | 2025-12-15 | 2026-04-01 | Licence recovered | User no longer requires access |

## Field Descriptions

| Field | Description |
|---|---|
| User ID | Dummy or anonymised user reference |
| Platform | Analytics platform, such as Qlik or Tableau |
| Licence Type | Type of licence assigned |
| Access Level | Summary of the user’s access level |
| Business Area | Team, department, or business function |
| Status | Active, under review, pending removal, or removed |
| Date Assigned | Date the licence was assigned |
| Last Reviewed | Date the access or licence was last reviewed |
| Review Outcome | Decision made during review |
| Notes | Non-sensitive context for tracking purposes |

## Status Values

| Status | Meaning |
|---|---|
| Active | User currently has a valid licence assignment |
| Under Review | Access or licence requirement is being checked |
| Pending Removal | User has been identified for access or licence removal |
| Removed | Access has been removed and the licence has been recovered |

## Review Outcomes

| Outcome | Meaning |
|---|---|
| Retain | User still requires the licence |
| Downgrade | User requires a lower licence type or access level |
| Remove | User no longer requires access |
| Licence recovered | Licence has been removed and made available |
| Review access need | Further confirmation is required |

## Licence Review Checklist

| Check | Completed |
|---|---|
| User still requires platform access | Yes / No |
| Licence type matches user need | Yes / No |
| User has not changed role or team | Yes / No |
| Leaver or inactive user access has been removed | Yes / No |
| Licence tracker has been updated | Yes / No |
| Review outcome has been recorded | Yes / No |

## Example Licence Review Flow

```text
Review licence tracker
        ↓
Identify active, inactive, or unnecessary assignments
        ↓
Validate ongoing access need
        ↓
Retain, downgrade, or remove licence
        ↓
Update licence tracker
        ↓
Record review outcome
```
