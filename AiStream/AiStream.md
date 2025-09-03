 # 📡 AI Media Hub for TVET Schools

This project documents the development and deployment of a **Content Sharing Device (Media Hub)** designed to stream AI educational content to **TVET institutions** across the country. The Media Hub enables both **offline and cloud-synced content delivery**, ensuring accessibility in areas with limited or no internet connectivity.

---

## 🎯 Project Purpose

To provide scalable, offline-accessible AI learning resources to students and instructors in TVET schools, using a locally hosted Media Hub that supports mobile and desktop access across various network configurations.

---

## 🧰 Technology Stack

- **Operating System**: Linux (Debian-based)
- **Configuration Tool**: Mobaxterm (SSH, SCP, terminal access)
- **Content Management**: CAdmin App (offline upload & AWS sync)
- **Cloud Integration**: AWS S3 for centralized content updates
- **Access Methods**:
  - 📱 Android APK (offline playback after download)
  - 🌐 Browser-based access via Wi-Fi or LAN

---

## 🛠️ Key Features

- 🔄 **Offline & Online Sync**  
  Content is uploaded manually via the **CAdmin App** or synced from **AWS S3** using scheduled scripts.

- 🧑‍💻 **Admin Configuration**  
  Admins use **Mobaxterm** to:
  - Configure network settings
  - Manage sync scripts
  - Monitor logs and system health

- 📲 **Dual Access Modes**  
  - **APK**: Android users can download content and access it offline from anywhere  
  - **Browser**: Accessible via Wi-Fi or LAN on mobile and desktop devices

- 📡 **Local Broadcasting**  
  The Media Hub creates its own Wi-Fi network, allowing users to connect without internet access.

- 🌐 **LAN Distribution**  
  For wider coverage, the Media Hub connects to existing LAN infrastructure and distributes content via switches and access points.

---

## 🧪 Implementation Workflow

### 1. Content Upload
- Admins use **CAdmin App** to upload content offline via USB or local network
- Alternatively, content is synced from **AWS S3** using cron jobs or manual triggers

### 2. Device Configuration
- Accessed via **Mobaxterm** for:
  - Network setup (Wi-Fi hotspot or LAN)
  - Firewall and access control
  - Sync script management

### 3. User Access
- **Mobile Users**:
  - Connect to Media Hub Wi-Fi or LAN
  - Use APK to browse and download content
  - Access downloaded content offline from anywhere

- **Desktop Users**:
  - Connect via browser using local IP or hostname
  - Stream or download content directly

---

## 📊 Deployment Impact

| Metric                     | Value              |
|---------------------------|--------------------|
| Schools Deployed          | 50+                |
| Students Reached          | 10,000+            |
| AI Modules Delivered      | 150+               |
| Offline Sync Frequency    | Weekly             |
| Instructor Satisfaction   | 95% (Survey)       |

---

## 📁 Repository Structure

```plaintext
├── setup/
│   └── mobaxterm_config.md
├── sync/
│   └── aws_sync_script.sh
├── apk/
│   └── ai_mediahub.apk
├── content/
│   └── sample_modules/
├── docs/
│   └── deployment_guide.md
│   └── user_manual.pdf

