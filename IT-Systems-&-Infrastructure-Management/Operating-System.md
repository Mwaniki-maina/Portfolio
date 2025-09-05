# 🖥️ Windows & Ubuntu OS Maintenance

This document outlines the routine maintenance, updates, and support tasks performed across **Windows** and **Ubuntu** operating systems in an enterprise environment. The goal was to ensure system stability, security, and performance for all endpoints under management.

---

## 🎯 Objectives

- Maintain and update Windows and Ubuntu systems for optimal performance
- Ensure security compliance through patching and configuration
- Provide technical support and troubleshooting for OS-related issues
- Automate routine tasks and streamline system administration

---

## 🛠️ Key Responsibilities

### 1. 🪟 Windows OS Maintenance

- Installed and configured Windows 10/11 across organizational devices
- Applied Windows updates and security patches via WSUS and manual rollout
- Managed system services, startup programs, and scheduled tasks
- Configured Group Policies for user restrictions, drive mappings, and desktop settings
- Performed disk cleanup, defragmentation, and registry optimization
- Resolved BSODs, driver conflicts, and application errors

### 2. 🐧 Ubuntu OS Maintenance

- Installed and configured Ubuntu LTS versions (18.04, 20.04, 22.04)
- Applied updates using `apt` and automated patching scripts
- Managed systemd services and cron jobs
- Configured firewall rules using `ufw` and monitored logs via `journalctl`
- Performed disk usage analysis and cleanup with tools like `ncdu` and `bleachbit`
- Resolved boot issues, package conflicts, and permission errors

### 3. 🔐 Security & Compliance

- Enabled automatic updates and configured update policies
- Installed and maintained antivirus/endpoint protection tools
- Enforced password policies and screen lock timers
- Configured full-disk encryption (BitLocker for Windows, LUKS for Ubuntu)
- Monitored system logs for suspicious activity

### 4. ⚙️ Automation & Scripting

- Created PowerShell scripts for Windows maintenance tasks
- Developed Bash scripts for Ubuntu updates and backups
- Scheduled automated backups and cleanup routines
- Logged maintenance activities and generated system health reports

---

## 📊 Impact Summary

| Task Area                  | Status       | Notes                          |
|---------------------------|--------------|--------------------------------|
| OS Updates & Patching     | ✅ Automated | Weekly schedule across all devices |
| Disk Cleanup & Optimization| ✅ Completed | Improved system performance    |
| Security Hardening        | ✅ Active    | Policies enforced on both OS types |
| User Support              | ✅ Ongoing   | Helpdesk and remote assistance |
| Backup & Recovery         | ✅ Configured| Local and cloud-based backups  |

---

## 📁 Repository Structure

```plaintext
├── windows/
│   └── powershell_scripts/
│   └── gpo_templates.md
├── ubuntu/
│   └── bash_scripts/
│   └── systemd_config.md
├── docs/
│   └── maintenance_checklist.md
│   └── update_schedule.pdf
├── reports/
│   └── system_health_summary.xlsx
