# 🧪 Windows Server Virtual Lab Configuration

This project documents the setup and configuration of a virtual lab environment using **Windows Server**, designed to simulate enterprise-level infrastructure services. The lab includes the deployment of **Active Directory Domain Services (AD DS)**, **DNS**, **DHCP**, and **Group Policy**, providing a hands-on platform for testing, learning, and administrative practice.

---

## 🎯 Objectives

- Create a virtualized Windows Server environment for infrastructure simulation
- Implement core network services: AD DS, DNS, DHCP
- Configure Group Policies for centralized management
- Enable domain-joined client machines for testing and validation

---

## 🛠️ Lab Environment

- **Platform**: VirtualBox / VMware Workstation
- **Operating System**: Windows Server 2019 / 2022
- **Client Machines**: Windows 10 / 11 (domain-joined)
- **Network Mode**: Internal Network / NAT

---

## ⚙️ Services Configured

### 1. 🧑‍💼 Active Directory Domain Services (AD DS)
- Installed AD DS role and promoted server to Domain Controller
- Created domain: `lab.local`
- Added Organizational Units (OUs) for departments
- Created user accounts and security groups

### 2. 🌐 DNS (Domain Name System)
- Configured DNS role during AD DS setup
- Verified forward and reverse lookup zones
- Ensured proper name resolution for domain clients

### 3. 📡 DHCP (Dynamic Host Configuration Protocol)
- Installed DHCP role and authorized server
- Created scope: `192.168.10.0/24`
- Configured lease duration, reservations, and exclusions
- Integrated DHCP with DNS for dynamic updates

### 4. 🛡️ Group Policy
- Created and linked GPOs to OUs
- Policies applied:
  - Password complexity and expiration
  - Desktop wallpaper and login message
  - Software restriction policies
  - Drive mapping and printer deployment

---

## 🧪 Testing & Validation

- Joined client machines to `lab.local` domain
- Verified DHCP lease assignment and DNS resolution
- Confirmed GPO application using `gpresult` and `RSOP`
- Tested user login, group membership, and access control

---

## 📫 Contact

For technical support, collaboration, or future upgrades:

- **Email**: muhindi17@gmail.com  
- **LinkedIn**: [linkedin.com/in/stephen-m-maina](https://www.linkedin.com/in/stephen-m-maina)  
- **GitHub**: [github.com/Mwaniki-maina](https://github.com/Mwaniki-maina/Portfolio)
- [Go back](/readme.md)