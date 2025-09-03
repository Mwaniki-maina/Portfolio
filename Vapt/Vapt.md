# 🔐 VAPT Project:   
This project documents a comprehensive Vulnerability Assessment and Penetration Testing (VAPT) exercise conducted using **Parrot OS** and **OWASP ZAP**. The targets were two web applications—one hosted on **Windows** and the other on **Linux**. The goal was to identify security flaws, assess risk levels, and provide actionable remediation steps.

---

## 🧰 Tools & Environment

- **Operating System**: Parrot OS (Security Edition)
- **Testing Tool**: OWASP ZAP (Zed Attack Proxy)
- **Targets**:
  - Windows-hosted web app (IIS + ASP.NET)
  - Linux-hosted web app (Apache + PHP)
- **Network Setup**: Local virtual lab using VirtualBox and NAT networking

---

## 🚀 Methodology

1. **Reconnaissance**
   - Identified open ports and services using `nmap`
   - Mapped application structure via ZAP spidering

2. **Active Scanning**
   - Performed automated vulnerability scans with ZAP
   - Manual testing for authentication flaws and input validation

3. **Report Generation**
   - Exported ZAP reports in HTML and XML formats
   - Summarized findings by severity and category

---

## 📊 Summary of Findings

| Vulnerability Type       | Windows Target | Linux Target | Severity |
|--------------------------|----------------|--------------|----------|
| X-Frame-Options Missing  | ✅              | ✅            | Low      |
| Cross-Site Scripting (XSS) | ✅            | ❌            | Medium   |
| Server Banner Disclosure | ✅              | ✅            | Low      |
| SQL Injection Potential  | ❌              | ✅            | High     |
| Insecure Cookies         | ✅              | ✅            | Medium   |

> ⚠️ **Critical Finding**: The Linux-hosted app was vulnerable to SQL Injection, allowing unauthorized access to backend data. Immediate patching and input sanitization were recommended.

---

## 📁 Report Files

- `zap_report_windows.html` – Full scan report for Windows target  
- `zap_report_linux.html` – Full scan report for Linux target  
- `summary_notes.md` – Manual notes and remediation suggestions

---

## ✅ Remediation Recommendations

- Implement input validation and sanitization across all forms  
- Configure secure HTTP headers (e.g., X-Frame-Options, Content-Security-Policy)  
- Disable server banner exposure in Apache and IIS  
- Use secure cookie flags (`HttpOnly`, `Secure`)  
- Patch vulnerable libraries and frameworks

---

## 📫 Contact

For questions or collaboration, feel free to reach out:

- **Email**: muhindi17@gmail.com  
- **LinkedIn**: [linkedin.com/in/stephen-m-maina](https://www.linkedin.com/in/stephen-m-maina)  
- **GitHub**: [github.com/Mwaniki-maina](https://github.com/Mwaniki-maina/Portfolio)

---

Thanks for checking out this project! 🕵️‍♂️
