# Enterprise MFA Implementation & Identity Governance

This project documents the technical implementation and governance approach used to enforce **Multi-Factor Authentication (MFA)** for access to **Qlik Sense solutions** supporting clinical data services at **IQVIA**.

The implementation was designed to strengthen access control around environments handling sensitive patient data, with a focus on secure authentication, identity governance, and operational standardisation within a regulated healthcare context.

---

## ⚠️ Data Protection & Privacy Disclaimer

To protect enterprise systems, internal processes, and sensitive healthcare-related workflows, specific configuration details, platform settings, server names, access paths, and implementation-sensitive instructions have been redacted.

This documentation focuses on the **technical delivery approach**, **governance model**, and **operational controls** applied during the rollout, rather than disclosing privileged internal detail.

---

## 🎯 Project Overview

The objective of this project was to enforce MFA for access to Qlik Sense solutions used in the delivery of clinical data services, improving authentication assurance for systems handling sensitive patient data.

### Role
**Technical Implementation Lead**

### Focus Areas
- MFA enforcement for protected solution access
- Identity governance and access control alignment
- Integration with Joiner-Mover-Leaver (JML) processes
- Technical SOPs and operational standardisation
- Support model design for secure onboarding and access maintenance

### Environment
**Proprietary secure access platform / Qlik Sense / Enterprise clinical data environment**

---

## 🛠️ Implementation Focus

### Authentication Enforcement
Led the technical implementation of MFA controls to ensure that access to protected Qlik Sense solutions required stronger authentication before user entry was permitted.

### Access Governance
Aligned MFA enforcement with access governance processes to support secure, role-appropriate access to clinical data solutions.

### Identity Lifecycle Integration
Integrated MFA-related processes into the **Joiner-Mover-Leaver (JML)** lifecycle so that secure access requirements were applied during onboarding, maintained through role changes, and removed appropriately when access was no longer required.

### Operational Standardisation
Authored technical SOPs, troubleshooting frameworks, and user guidance to support a consistent support model and reduce avoidable manual intervention.

### Access Control Support
Supported the broader access control framework around protected solution access, helping ensure that authentication requirements aligned with operational and security expectations.

---

## 🔐 Security Context

This implementation supported stronger authentication controls for access to solutions handling sensitive patient data, where access assurance, governance, and operational consistency were critical.

The project was therefore not only a technical rollout, but also a governance and control exercise designed to strengthen the security posture around access to clinical data services.

---

## 📌 Key Contributions

- Led the technical implementation of MFA enforcement for Qlik Sense solution access
- Supported secure access controls for clinical data solutions handling sensitive patient information
- Integrated MFA processes into the Joiner-Mover-Leaver (JML) lifecycle
- Authored SOPs, support documentation, and troubleshooting guidance
- Helped standardise operational access workflows
- Contributed to a more controlled and security-aligned access model

---

## 🧭 Access Flow Summary

```mermaid
graph LR
    A[User Requests Access] --> B[User Identity Validated]
    B --> C[MFA Requirement Enforced]
    C --> D[Access to Qlik Sense Evaluated]
    D --> E[Secure Access Granted]
