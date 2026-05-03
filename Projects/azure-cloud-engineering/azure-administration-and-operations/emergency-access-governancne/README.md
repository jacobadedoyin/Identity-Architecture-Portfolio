# Emergency Access Governance Review

## Overview

This project documents a workplace-aligned review of emergency access, commonly known as break-glass account governance, within a Microsoft Entra ID environment.

The review focused on assessing whether emergency access arrangements were suitable, controlled, and aligned with security best practice.

No confidential organisational data is included. All evidence is sanitised, recreated, or summarised.

---

## Purpose

The purpose of this review was to assess the governance and control posture of emergency access accounts, including:

- Whether emergency access accounts were present and known
- Whether account ownership and contact details were appropriate
- Whether Conditional Access exclusions had been considered
- Whether monitoring or alerting existed for emergency account use
- Whether a secondary emergency access account was required
- Whether any governance gaps should be escalated for review

---

## Review Scope

The review considered the following areas:

| Area | Review Focus |
| :--- | :--- |
| Account presence | Confirm whether emergency access account arrangements were in place |
| Account contact details | Review whether the associated email/contact method was suitable |
| Conditional Access | Check whether emergency access accounts were excluded from relevant policies |
| Resilience | Assess whether a second emergency access account was required |
| Monitoring | Consider whether usage of emergency access accounts would be detected |
| Governance | Identify risks, gaps, and recommended next steps |

---

## Summary of Findings

| Finding | Outcome |
| :--- | :--- |
| Existing emergency access account reviewed | Completed |
| Email/contact address reviewed | No change required |
| Need for second emergency access account assessed | No immediate change approved |
| Independent email address identified as a gap | Flagged for review |
| Conditional Access exception not confirmed | Flagged for review |
| Secondary break-glass account not present | Flagged as a resilience consideration |
| Monitoring/alerting requirement considered | Recommended for follow-up |

---

## Key Risks Identified

### 1. No independent email address for emergency access

The review identified that the emergency access account did not have a fully independent contact method.

This was flagged because emergency access accounts should remain usable if normal corporate identity, email, or authentication systems are unavailable.

### 2. Conditional Access exception not clearly defined

The review identified that the emergency access account did not have a clearly documented Conditional Access exception.

This was flagged because emergency accounts may need to bypass certain policies during an outage, misconfiguration, or identity lockout scenario.

### 3. No secondary emergency access account

The review identified that only one emergency access account was in place.

This was flagged as a resilience consideration because relying on a single emergency access account can create a single point of failure.

---

## Actions Taken

- Completed an emergency access account review
- Checked whether existing details required immediate change
- Documented that no email address change was approved at the time
- Documented that no second break-glass account was approved at the time
- Flagged governance gaps for further review
- Recommended review of Conditional Access exclusions
- Recommended consideration of independent monitoring or alerting for emergency access usage

---

## Recommended Improvements

| Recommendation | Reason |
| :--- | :--- |
| Configure an independent email/contact method | Reduces dependency on normal corporate systems |
| Define and document Conditional Access exclusions | Ensures emergency access remains possible during policy failures |
| Consider a second break-glass account | Improves resilience and reduces single-account dependency |
| Implement sign-in monitoring and alerting | Ensures emergency access usage is visible and auditable |
| Review emergency access periodically | Keeps the control aligned with operational and security requirements |

---

## IAM / Security Relevance

This work demonstrates practical experience in:

- Emergency access governance
- Microsoft Entra ID administration
- Conditional Access review
- Privileged access risk identification
- Identity resilience planning
- Access control documentation
- Security gap reporting
- Operational IAM review processes

---

## Evidence Approach

Evidence for this project should be sanitised or recreated.

Suitable evidence includes:

- Redacted review checklist
- Dummy emergency access account review table
- Conditional Access exclusion diagram
- Sanitised risk register entry
- Example sign-in monitoring query
- High-level before/after governance summary
- Worklog entry showing review activity and outcome

No real user names, email addresses, tenant IDs, policy names, screenshots, or internal ticket references should be included.

---

## Example Worklog Entry

| Date | Area | Activity | Outcome | Evidence |
| :--- | :--- | :--- | :--- | :--- |
| YYYY-MM-DD | Emergency Access | Reviewed break-glass account configuration, contact details, Conditional Access considerations, and resilience requirements | No immediate account changes approved. Independent email, Conditional Access exception, and secondary account requirements were flagged for review | Sanitised review summary / recreated checklist |

---

## Confidentiality Note

This project is based on real-world Azure and Microsoft Entra administration experience, but all organisational details have been removed or recreated.

The purpose is to evidence the review process, risk awareness, and governance thinking without exposing confidential configuration or operational data.
