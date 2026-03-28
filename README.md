# iam-implementation-lab

# 🔐 IAM Implementation Lab (Entra ID + Okta + SailPoint Basics)

## 📌 Project Overview
This project demonstrates a complete Identity and Access Management (IAM) implementation using:

- Microsoft Entra ID (Azure AD)
- Okta (SSO & MFA)
- IAM Lifecycle Management (Joiner-Mover-Leaver)
- Basic Identity Governance concepts (SailPoint)

---

## 🎯 Objectives
- Implement secure authentication (MFA)
- Enforce Conditional Access policies
- Enable Single Sign-On (SSO)
- Simulate real-world IAM lifecycle

---

## 🏗️ Architecture Diagram

![IAM Architecture](./assets/architecture.png)

---

## 🧰 Tools & Technologies
- Microsoft Entra ID
- Okta Developer Tenant
- SAML / OAuth 2.0
- Microsoft 365 Admin Center

---

## 🔑 Key Implementations

### 1. Microsoft Entra ID Configuration
- Created users and groups
- Configured Multi-Factor Authentication (MFA)
- Implemented Conditional Access Policies:
  - Block access from risky locations
  - Require MFA for admins
- Enabled Self-Service Password Reset (SSPR)

---

### 2. Okta SSO Integration
- Created Okta tenant
- Integrated applications using SAML
- Configured:
  - SSO login
  - MFA policies
- Assigned users to applications

---

### 3. IAM Lifecycle Management
Simulated Joiner-Mover-Leaver process:

- Joiner:
  - New user creation
  - License + app assignment
- Mover:
  - Role change → Access updated
- Leaver:
  - Account disabled
  - Access revoked

---

### 4. Governance (SailPoint Concepts)
- Access request flow
- Approval workflow
- Access certification basics

---

## 📸 Screenshots

| Feature | Screenshot |
|--------|-----------|
| MFA Setup | ![](./assets/mfa.png) |
| Conditional Access | ![](./assets/ca-policy.png) |
| Okta SSO | ![](./assets/okta-sso.png) |

---

## 🧪 Real-World Scenarios Covered
- Securing admin accounts with MFA
- Restricting login based on location
- Implementing SSO across applications
- Managing user lifecycle securely

---

## 📈 Skills Demonstrated
- Identity & Access Management (IAM)
- Microsoft Entra ID Administration
- Okta SSO Integration
- Security Best Practices (Zero Trust)
- Access Control & Governance

---

## 💼 Use Case
This project simulates how organizations manage identities securely across multiple platforms.

---

## 🚀 Author
**Sohel Sayyad**  
IAM Engineer (Aspiring)  

LinkedIn: (Add your link)  
