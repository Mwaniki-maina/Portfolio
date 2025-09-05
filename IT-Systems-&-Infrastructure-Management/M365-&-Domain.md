# 🧑‍💼 Microsoft 365 & Domain Systems Administration

This document outlines the configuration, management, and maintenance tasks performed in administering Microsoft 365 services and domain-connected machines within an enterprise environment. The goal was to ensure secure, efficient, and scalable IT operations across user accounts, devices, and services.

---

## 🎯 Objectives

- Manage Microsoft 365 services including Exchange, SharePoint, Teams, and OneDrive
- Administer domain-connected machines via Active Directory and Group Policy
- Implement security policies and compliance controls
- Provide seamless user access and device management across platforms

---

## 🛠️ Key Responsibilities

### 1. 📧 Microsoft 365 Administration

- Created and managed user accounts, groups, and licenses
- Configured email policies, shared mailboxes, and distribution lists
- Enabled Multi-Factor Authentication (MFA) and Conditional Access
- Managed SharePoint sites and OneDrive storage quotas
- Monitored service health and usage analytics via the Admin Center

### 2. 🖥️ Domain-Connected Machine Management

- Deployed and configured Windows domain controllers
- Joined client machines to the domain and applied Group Policies
- Managed Organizational Units (OUs) and security groups
- Automated login scripts and drive mappings
- Enforced password policies and account lockout thresholds

### 3. 🔐 Security & Compliance

- Implemented Data Loss Prevention (DLP) policies
- Configured Microsoft Defender for Endpoint and email filtering
- Audited user activity and login patterns
- Applied retention policies and mailbox archiving
- Ensured compliance with organizational and regulatory standards

### 4. 🧑‍💻 User Access & Device Management

- Managed access permissions across Microsoft 365 apps
- Provisioned devices using Intune and Endpoint Manager
- Applied device compliance policies and remote wipe capabilities
- Supported onboarding and offboarding workflows
- Resolved user login and synchronization issues

---

## 📊 Impact Summary

| Task Area                  | Status       | Notes                          |
|---------------------------|--------------|--------------------------------|
| User Account Management   | ✅ Completed | Automated via PowerShell       |
| Email System Configuration| ✅ Completed | Exchange Online & Shared Mailboxes |
| Device Enrollment         | ✅ Completed | Windows & Mobile Devices       |
| Security Policies         | ✅ Active    | MFA, DLP, Conditional Access   |
| Group Policy Deployment   | ✅ Completed | Applied to all domain clients  |

---

## 📁 Repository Structure

```plaintext
├── scripts/
│   └── user_provisioning.ps1
│   └── mailbox_audit.ps1
├── docs/
│   └── m365_admin_guide.md
│   └── domain_config_steps.md
├── reports/
│   └── compliance_audit_summary.pdf
│   └── device_inventory.xlsx
