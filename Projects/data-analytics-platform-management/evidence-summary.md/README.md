# Data Analytics Platform Management

## Overview

This project demonstrates data analytics platform management responsibilities across Qlik and Tableau reporting environments.

The work focused on improving how analytics platform access, user lifecycle activity, licence usage, access reviews, support processes, and operational documentation were managed. The aim was to make platform administration more consistent, repeatable, easier to support, and easier to evidence.

## Platforms Covered

- Qlik
- Tableau

## Project Context

This work sat within application-level identity and access management because it involved managing the user access lifecycle across analytics platforms.

The work covered:

| Area | Description |
|---|---|
| Joiners | Setting up new users, assigning appropriate platform access, and following a repeatable onboarding process |
| Movers | Updating access when users changed role, team, reporting requirement, or access need |
| Leavers | Supporting user removal, licence clean-up, and offboarding to reduce stale access risk |
| Licence Management | Tracking licence allocation, visibility, recovery, and review activity |
| Access Reviews | Creating access review requirements and matrices to help stakeholders validate access |
| Platform Support | Improving support guidance and repeatable administration processes |

Although this was not Azure-native IAM, it supported access governance by making analytics platform access management more controlled, documented, and repeatable.

## My Role

I owned day-to-day platform management activity across Qlik and Tableau.

This included:

- Managing user access
- Supporting joiner, mover, and leaver activity
- Tracking licences
- Handling access requests
- Improving platform administration workflows
- Creating lifecycle process documentation
- Creating access review requirements
- Creating access review matrices for support teams and stakeholders
- Creating support guidance and process documentation
- Reducing reliance on informal process knowledge

## Areas Covered

| Area | Work Completed |
|---|---|
| Platform operations | Supported day-to-day administration across analytics platforms |
| Access management | Managed access requests and platform user changes |
| JML lifecycle support | Created lifecycle workflows for onboarding, access changes, and offboarding |
| Access review requirements | Defined review expectations and validation criteria for analytics platform access |
| Access review matrices | Created matrices to help stakeholders and support teams validate access needs |
| Licence management | Improved licence tracking, visibility, and recovery |
| Support process improvement | Made common platform tasks easier for support teams to follow |
| Documentation | Created reusable guidance, workflows, matrices, and templates |
| Access governance | Reduced stale access risk and improved process consistency |

## Key Improvements

This work improved analytics platform management by introducing clearer processes for:

- User onboarding
- Access changes
- User removal
- Licence recovery
- Access request handling
- Access review preparation
- Stakeholder access validation
- Platform support guidance
- Repeatable administration tasks
- Documented operating processes

## Governance and Control Improvements

The project improved control over analytics platform access by making lifecycle and review activity more structured.

Key improvements included:

| Control Area | Improvement |
|---|---|
| Joiner process | Created a more repeatable approach for setting up new platform users |
| Mover process | Improved how access changes were handled when roles, teams, or reporting needs changed |
| Leaver process | Supported user removal and licence recovery to reduce stale access risk |
| Licence tracking | Improved visibility of assigned, available, and recovered licences |
| Access reviews | Created review requirements to help validate whether access was still appropriate |
| Stakeholder validation | Created matrices to help stakeholders confirm access needs and ownership |
| Support consistency | Created guidance to reduce ambiguity for support teams |
| Evidence handling | Used sanitised templates and diagrams instead of confidential operational records |

## Evidence Pack

This project uses recreated and sanitised evidence only. Internal SOPs and real platform screenshots are not included.

Evidence is represented through:

| Evidence Item | Location | Purpose |
|---|---|---|
| JML workflow diagram | `diagrams/jml-workflow.md` | Shows the high-level joiner, mover, and leaver access process |
| Licence tracker template | `templates/licence-tracker-template.md` | Demonstrates how licence allocation, review, and recovery can be tracked |
| JML checklist template | `templates/jml-checklist-template.md` | Shows a repeatable structure for onboarding, access changes, and offboarding |
| Access request template | `templates/access-request-template.md` | Demonstrates controlled access request handling |
| Access review requirements template | `templates/access-review-requirements-template.md` | Shows how access review expectations and validation criteria can be documented |
| Stakeholder access matrix template | `templates/stakeholder-access-matrix-template.md` | Demonstrates how support teams and stakeholders can validate access ownership and requirements |
| Evidence summary | `evidence/evidence-summary.md` | Explains the sanitisation and evidence approach used for this project |

## Example JML Workflow

```text
Access request received
        ↓
Identify request type
        ↓
Joiner / Mover / Leaver
        ↓
Validate access requirement
        ↓
Apply platform access change
        ↓
Update licence tracking
        ↓
Confirm completion
        ↓
Record evidence / update support notes
