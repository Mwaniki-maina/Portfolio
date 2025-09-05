# 🔐 Microsoft 365 User Access Management

This document outlines the configuration and administration of **user access controls** within a Microsoft 365 environment. The goal was to ensure secure, role-based access to organizational resources while maintaining compliance and operational efficiency.

---

## 🎯 Objectives

- Manage user identities and access permissions across Microsoft 365 services
- Implement security policies to protect sensitive data
- Streamline onboarding and offboarding processes
- Monitor and audit user activity for compliance

---

## 🛠️ Key Responsibilities

### 1. 👤 User Account Management

- Created and managed user accounts via Microsoft 365 Admin Center and Azure AD
- Assigned licenses based on role and department
- Configured user profiles, aliases, and mailbox settings
- Automated provisioning using PowerShell scripts

### 2. 🧑‍🤝‍🧑 Role-Based Access Control (RBAC)

- Defined roles and access levels for departments (e.g., HR, Finance, IT)
- Applied permissions to SharePoint sites, Teams channels, and OneDrive folders
- Managed group memberships and dynamic groups in Azure AD

### 3. 🔐 Security Policies

- Enabled Multi-Factor Authentication (MFA) for all users
- Configured Conditional Access policies based on location and device compliance
- Applied Data Loss Prevention (DLP) rules to sensitive content
- Enforced password policies and account lockout thresholds

### 4. 🔄 Onboarding & Offboarding

- Streamlined onboarding with automated license assignment and group enrollment
- Offboarded users by disabling accounts, revoking access, and archiving mailboxes
- Transferred ownership of shared resources and reassigned permissions

### 5. 📊 Monitoring & Auditing

- Reviewed sign-in logs and access reports via Microsoft 365 Security & Compliance Center
- Monitored risky sign-ins and device compliance status
- Generated audit logs for mailbox access, file sharing, and admin actions

---

## 📁 Repository Structure

```plaintext
├── scripts/
│   └── user_provisioning.ps1
│   └── offboarding_cleanup.ps1
├── policies/
│   └── conditional_access.md
│   └── mfa_enforcement_guide.md
├── reports/
│   └── access_audit_summary.pdf
│   └── license_usage.xlsx
├── docs/
│   └── onboarding_checklist.md
│   └── user_access_flowchart.png
