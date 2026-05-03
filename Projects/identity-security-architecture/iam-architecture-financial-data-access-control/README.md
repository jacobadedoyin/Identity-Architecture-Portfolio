# Secure Financial Data Access Architecture

## Overview

This project is a concept architecture for securing access to sensitive financial data platforms in a regulated environment.

The design focuses on identity and access management, role-based access control, Conditional Access, least privilege, auditability, and access governance.

This project is included as a portfolio architecture exercise to demonstrate how identity controls can be designed around sensitive data access.

## Project Type

Concept architecture / portfolio design exercise.

This is a recreated architecture model used to demonstrate IAM, RBAC, Conditional Access, access reviews, and secure data access design. It does not include confidential organisational architecture, live tenant configuration, real user data, or internal system details.

## Architecture Focus

The architecture is centred around Microsoft Entra ID as the identity provider and control point for access to sensitive financial data platforms.

The design covers:

- Internal and external identity access
- Strong authentication using MFA
- Conditional Access policy enforcement
- Group-based role assignment
- Role-based access control
- Least privilege access design
- Joiner, mover, and leaver lifecycle considerations
- Access reviews and governance
- Audit logging and monitoring

## Architecture Diagram

![Secure Financial Data Access Architecture](./images/architecture-diagram.png)

## Design Objectives

| Objective | Description |
|---|---|
| Centralise identity | Use Microsoft Entra ID as the central identity control plane |
| Enforce strong authentication | Require MFA for access to sensitive data platforms |
| Apply Conditional Access | Evaluate access based on signals such as user, device, location, and risk |
| Use RBAC | Assign access through roles and groups rather than direct user permissions |
| Support least privilege | Ensure users only receive access required for their role |
| Support JML processes | Consider how access is created, changed, and removed across the user lifecycle |
| Improve auditability | Ensure access activity can be logged, reviewed, and evidenced |
| Support access reviews | Enable periodic validation of access to sensitive data platforms |

## Access Flow

```text
User signs in
        ↓
Microsoft Entra ID authenticates user
        ↓
Conditional Access policies evaluate request
        ↓
MFA is enforced where required
        ↓
User group membership is checked
        ↓
RBAC role determines access scope
        ↓
Financial data platform access is granted or denied
        ↓
Activity is logged for audit and review
```
