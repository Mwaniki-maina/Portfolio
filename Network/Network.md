# 🧩 IT Infrastructure Audit Project

This project documents a comprehensive audit conducted across multiple organizations to evaluate their IT infrastructure, focusing on network setup, server architecture, data protection mechanisms, application landscape, email systems, access control, and endpoint security. The goal was to assess operational efficiency, identify vulnerabilities, and recommend improvements aligned with best practices.

---

## 🛰️ 1. Network Assessment

### ✅ Scope
- **Network Setup & Topology**: Reviewed LAN/WAN architecture, switch/router configurations, and segmentation
- **Bandwidth & Utilization**: Measured throughput and peak usage using tools like NetFlow and SolarWinds
- **Security Methods**:
  - Firewalls (hardware/software)
  - VLAN isolation
  - Intrusion Detection/Prevention Systems (IDS/IPS)
- **Implementation Techniques**:
  - ACLs on routers/switches
  - VPN for remote access
  - Regular firmware updates and patching

---

## 🖥️ 2. Server Infrastructure

### ✅ Findings
- **Number of Servers**: Ranged from 3 to 25 per organization
- **Server Roles**:
  - Domain Controllers
  - File & Print Servers
  - Application Servers
  - Database Servers
- **Location**:
  - **On-Premise**: Majority of legacy systems
  - **Cloud**: Azure and AWS used for scalability and redundancy

---

## 💾 3. Backup & Data Storage

### ✅ Backup Systems
- **Solutions Used**:
  - Veeam
  - Acronis
  - Windows Server Backup
- **Storage Mediums**:
  - NAS devices
  - External HDDs
  - Cloud storage (AWS S3, Azure Blob)
- **Frequency**:
  - Daily incremental + weekly full backups
- **Retention Policies**:
  - 30–90 days depending on compliance needs

---

## 🧩 4. Application Landscape

### ✅ Common Applications
- ERP systems (SAP, Odoo)
- HR & Payroll software
- Inventory management tools
- Custom-built web apps
- Productivity suites (Microsoft 365, Google Workspace)

---

## 📧 5. Email Systems

### ✅ Email Infrastructure
- **Platforms Used**:
  - Microsoft Exchange (on-prem/cloud)
  - Google Workspace
- **Number of Email Addresses**:
  - Ranged from 50 to 500+ per organization
- **Security Features**:
  - SPF, DKIM, DMARC
  - Email filtering and anti-phishing tools

---

## 🔐 6. Access Control Systems

### ✅ Mechanisms in Place
- Role-Based Access Control (RBAC)
- Active Directory Group Policies
- Biometric and RFID-based physical access
- MFA for critical systems
- Audit logs and access reviews conducted quarterly

---

## 🛡️ 7. Endpoint & Security Systems

### ✅ Security Measures
- **Endpoint Protection**:
  - Antivirus/EDR solutions (e.g., Bitdefender, CrowdStrike)
  - Regular updates (weekly or automated)
- **Mobile Device Management (MDM)**:
  - Implemented in 60% of audited organizations
  - Tools used: Microsoft Intune, ManageEngine
- **Other Controls**:
  - Patch management systems
  - Device encryption
  - USB port restrictions
  - Security awareness training

---

## 📊 Summary & Recommendations

| Area                     | Status Summary         | Recommendation                          |
|--------------------------|------------------------|------------------------------------------|
| Network Security         | Generally strong       | Improve segmentation and IDS coverage    |
| Server Management        | Mixed cloud adoption   | Migrate legacy systems to hybrid cloud   |
| Backup Systems           | Mostly compliant       | Test restore procedures regularly        |
| Email Security           | Adequate               | Enforce MFA and phishing simulations     |
| Endpoint Protection      | Inconsistent updates   | Automate patching and expand MDM usage   |

---

## 📫 Contact

For further details, collaboration, or consulting inquiries:

- **Email**: your.email@example.com  
- **GitHub**: [github.com/yourusername](https://github.com/yourusername)  
- **LinkedIn**: [linkedin.com/in/yourprofile](https://linkedin.com/in/yourprofile)

---

> “A secure and efficient IT environment starts with visibility. This audit was a step toward smarter infrastructure decisions.”

