# 🔐 Identity & Access Governance Engineering
**Enterprise Identity, Access Control & Governance Design for Regulated Environments**

---

## 📌 Overview

This repository demonstrates practical implementation of **identity and access governance engineering principles** across enterprise cloud environments.

It focuses on designing and validating secure identity systems using:

- Microsoft Entra ID (Azure AD)
- Okta Identity Platform
- Role-Based Access Control (RBAC)
- Multi-Factor Authentication (MFA)
- Conditional Access policies
- Identity lifecycle management (Joiners, Movers, Leavers)

The work reflects real-world IAM engineering in **financial and regulated environments**, where identity is the primary security control plane.

---

## 🎯 Objectives

- Design and implement identity governance structures  
- Enforce least privilege access using RBAC  
- Secure authentication using MFA and Conditional Access  
- Manage identity lifecycle processes (JML model)  
- Demonstrate cross-platform identity management (Azure + Okta)  
- Provide implementation evidence of IAM controls in enterprise environments  

---

## 🏗️ Architecture Overview

This portfolio is structured around identity-centric security architecture:

- **Identity Provider Layer:** Microsoft Entra ID / Okta  
- **Authentication Layer:** MFA + Conditional Access  
- **Access Control Layer:** RBAC via security groups  
- **Governance Layer:** Access reviews, policies, audit logs  
- **Application Layer:** Enterprise data and business applications  

---

## 🔄 Identity Lifecycle (JML Model)

### Joiners
- Users provisioned in identity platform  
- Assigned to role-based security groups  
- Access granted automatically via RBAC  

### Movers
- Group membership updated based on role change  
- Previous permissions revoked  
- New access applied based on role  

### Leavers
- Accounts disabled immediately  
- Removed from all groups  
- Access fully revoked across all systems  

---

## 🔐 Access Control Model

Access is enforced through **group-based RBAC**, not direct user permissions.

| Role | Access Scope |
|------|-------------|
| Standard User | Application-level access |
| Analyst | Read access to datasets |
| Manager | Read/write access to reports |
| Admin | Full system administration (restricted) |
| External User | Limited, scoped access only |

---

## 🛡️ Security & Authentication Controls

### Multi-Factor Authentication (MFA)
- Enforced across all user accounts  
- Additional verification for privileged roles  
- Reduces risk of credential compromise  

---

### Conditional Access (Entra ID)

- Block legacy authentication  
- Require compliant devices  
- Restrict access based on location  
- Apply risk-based authentication policies  

---

## 📊 Governance & Compliance

### Access Reviews
- Periodic validation of user access  
- Removal of unnecessary privileges  
- Focus on privileged and external users  

### Auditing & Monitoring
- Authentication logs captured centrally  
- Access activity monitored for anomalies  
- Supports compliance and regulatory requirements  

---

## 🧠 Key Engineering Principles

- Identity is the primary security boundary  
- Least privilege by default  
- Centralised access governance  
- Zero Trust-aligned architecture  
- Scalable group-based access control  

---

## 🌐 Platform Coverage

This engineering layer spans:

- Microsoft Entra ID (Azure IAM)
- Okta Identity Platform
- Azure governance and security services
- Cloud-based access control systems

---

## 🚀 Outcome

This repository demonstrates a structured approach to identity and access governance engineering, combining:

- Identity lifecycle management  
- Secure authentication design  
- Role-based access control  
- Cross-platform IAM implementation  
- Governance and compliance enforcement  

It reflects real-world IAM engineering responsibilities in **financial services and regulated enterprise environments**.

---

## 🔮 Future Enhancements

- Privileged Identity Management (PIM) integration  
- Automated access provisioning workflows  
- GitOps-based IAM policy deployment  
- Advanced Conditional Access and risk engines  
- Integration with SIEM (Microsoft Sentinel / logging pipelines)  

---

*Maintained by Jacob Adedoyin*
