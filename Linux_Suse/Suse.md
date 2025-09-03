# 🖥️ SUSE Linux Server Configuration Project

This project outlines the configuration and deployment of three SUSE Linux Enterprise servers, each serving a distinct role within an organization's IT infrastructure. The servers were set up to provide centralized authentication, secure file sharing, and reliable email communication.

---

## 🧭 Project Overview

- **Operating System**: SUSE Linux Enterprise Server (SLES)
- **Server Roles**:
  1. Active Directory Server
  2. File Server
  3. Mail Server

---

## 🛠️ Server Configurations

### 1. 🧑‍💼 Active Directory Server

- **Purpose**: Centralized user authentication and domain management
- **Tools Used**:
  - Samba (configured as an AD Domain Controller)
  - Kerberos
  - Winbind
- **Key Tasks**:
  - Installed and configured Samba in AD DC mode
  - Set up Kerberos realm and DNS entries
  - Created organizational units and user accounts
  - Integrated Windows clients for domain login

### 2. 📁 File Server

- **Purpose**: Secure file sharing across departments
- **Tools Used**:
  - Samba (for SMB/CIFS shares)
  - NFS (for Linux clients)
  - ACLs and quota management
- **Key Tasks**:
  - Created shared directories with department-level access
  - Configured Samba shares with authentication
  - Enabled disk quotas and auditing
  - Mounted shares on client machines (Windows/Linux)

### 3. 📧 Mail Server

- **Purpose**: Internal and external email communication
- **Tools Used**:
  - Postfix (SMTP)
  - Dovecot (IMAP/POP3)
  - SpamAssassin & ClamAV (security)
  - Roundcube (webmail interface)
- **Key Tasks**:
  - Configured Postfix with TLS encryption and relay restrictions
  - Set up Dovecot for mailbox access
  - Integrated spam filtering and antivirus scanning
  - Deployed Roundcube for browser-based email access

---

## 🔐 Security Measures

- Enabled firewall rules for each service
- Configured fail2ban for brute-force protection
- Applied regular updates and patches
- Enforced strong password policies and user access controls

---

## 📊 Deployment Summary

| Server Role         | IP Address     | Location       | Status     |
|---------------------|----------------|----------------|------------|
| Active Directory    | 192.168.1.10   | Data Center A  | ✅ Online  |
| File Server         | 192.168.1.20   | Data Center A  | ✅ Online  |
| Mail Server         | 192.168.1.30   | Data Center A  | ✅ Online  |

---

## 📁 Repository Contents

```plaintext
├── ad_server/
│   └── samba_ad_config.md
├── file_server/
│   └── smb_nfs_setup.md
├── mail_server/
│   └── postfix_dovecot_config.md
├── docs/
│   └── deployment_guide.pdf
│   └── security_hardening.md
