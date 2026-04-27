# Secure Transfer Permission Matrix Template

## Purpose

This template demonstrates how secure transfer permissions can be tracked at a high level using dummy data.

It supports visibility of who has access to which transfer areas and helps reduce unnecessary access.

## Permission Matrix

| User ID | Business Area | Transfer Area | Access Level | Internal / External | Status | Last Reviewed | Review Outcome | Notes |
|---|---|---|---|---|---|---|---|---|
| USER-001 | Finance | Transfer Area A | Upload and Download | Internal | Active | 2026-04-01 | Retain | Required for monthly exchange |
| USER-002 | Operations | Transfer Area B | Download | Internal | Active | 2026-04-01 | Retain | Requires read-only transfer access |
| USER-003 | External Partner | Transfer Area C | Upload | External | Under Review | 2026-04-01 | Review access need | Confirm ongoing requirement |
| USER-004 | Finance | Transfer Area A | Upload and Download | Internal | Removed | 2026-04-01 | Access removed | User no longer requires access |

## Access Levels

| Access Level | Description |
|---|---|
| Upload | User can upload files to the transfer area |
| Download | User can download files from the transfer area |
| Upload and Download | User can upload and download files |
| Admin | User has elevated administration permissions |

## Review Checklist

| Check | Completed |
|---|---|
| User still requires access | Yes / No |
| Access level is appropriate | Yes / No |
| External access is still required | Yes / No |
| Temporary access has expired or been reviewed | Yes / No |
| Unnecessary access has been removed | Yes / No |
| Matrix has been updated | Yes / No |

## Confidentiality Note

This template is for portfolio use only and uses dummy data. Do not include real folder paths, usernames, email addresses, partner names, file names, transfer locations, or confidential platform details.
