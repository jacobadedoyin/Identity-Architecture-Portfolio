# Enterprise IAM Design for Financial Data Access & Governance

## Overview
This project presents a conceptual Identity and Access Management (IAM) architecture designed to secure access to sensitive financial data within a regulated environment.

The design focuses on enforcing strong authentication, controlling access to critical systems, and aligning identity processes with governance and compliance requirements. It reflects real-world IAM challenges such as managing internal and external users, securing access to data platforms, and maintaining auditability.

---

## Objectives
- Design a secure IAM architecture for financial data access  
- Enforce strong authentication using Multi-Factor Authentication (MFA)  
- Implement role-based access control (RBAC) aligned to least privilege  
- Support identity lifecycle management (joiners, movers, leavers)  
- Enable access governance through reviews and auditing  
- Align with regulatory and data security requirements  

---

## Architecture Overview
The solution is centred around Microsoft Entra ID as the primary identity provider, supporting authentication and access control for enterprise applications and data platforms.

### Key Components:
- Identity Provider: Microsoft Entra ID  
- Authentication: MFA with policy-based controls  
- Applications: Enterprise data and analytics platforms  
- User Types: Internal users and external users (third parties / partners)  
- Access Model: Role-based access control (RBAC) via groups  

---

## Identity & Access Model

### Role-Based Access Control (RBAC)
Access is assigned based on business roles and responsibilities, ensuring:
- Least privilege access  
- Separation of duties  
- Scalable permission management  

### Identity Lifecycle (JML)
- **Joiners:** Provisioned with appropriate role-based access  
- **Movers:** Access updated based on role or department changes  
- **Leavers:** Immediate deprovisioning to remove access  

---

## Authentication & Security Controls

### Multi-Factor Authentication (MFA)
- Enforced for all users accessing sensitive systems  
- Additional controls for privileged or high-risk access  

### Conditional Access (Conceptual)
- Location-based access restrictions  
- Device compliance requirements  
- Risk-based authentication policies  

---

## Access Governance

### Access Reviews
- Periodic validation of user permissions  
- Removal of unnecessary or excessive access  

### Auditing & Monitoring
- Logging of authentication and access activity  
- Monitoring for suspicious or high-risk behaviour  
- Support for audit and compliance reporting  

---

## Use Case Scenario
This design models a financial organisation where users require secure access to sensitive data platforms used for reporting and analysis.

The architecture ensures:
- Secure access for internal and external users  
- Controlled exposure of financial data  
- Strong governance over permissions and identity lifecycle  

---

## Key Design Principles
- Security-first approach aligned to Zero Trust concepts  
- Clear separation of identity, authentication, and access layers  
- Scalable and maintainable access model  
- Auditability and compliance for regulated environments  

---

## Future Enhancements
- Integration with Privileged Identity Management (PIM)  
- Automated provisioning and workflow-based access requests  
- Advanced Conditional Access and risk-based policies  
- Integration with enterprise access governance platforms  

---

## Summary
This project demonstrates a practical IAM architecture for securing access to financial data systems, combining identity lifecycle management, strong authentication, and access governance controls.

It reflects real-world IAM design considerations relevant to enterprise and regulated environments.
