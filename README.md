<div align="center">

```text
╔════════════════════════════════════════════════════════════════════════════╗
║    ____  _____ _____ _____ _____ ____      ____    _    _     _            ║
║   | __ )| ____|_   _|_   _| ____|  _ \    / ___|  / \  | |   | |           ║
║   |  _ \|  _|   | |   | | |  _| | |_) |  | |     / _ \ | |   | |           ║
║   | |_) | |___  | |   | | | |___|  _ <   | |___ / ___ \| |___| |___        ║
║   |____/|_____| |_|   |_| |_____|_| \_\   \____/_/   \_\_____|_____|       ║
║     ____ _   _    _    ____ ___                                            ║
║    / ___| | | |  / \  |  _ \_ _|                                           ║
║   | |   | |_| | / _ \ | | | | |                                            ║
║   | |___|  _  |/ ___ \| |_| | |                                            ║
║    \____|_| |_/_/   \_\____/___|                                           ║
║                                                                            ║
╚════════════════════════════════════════════════════════════════════════════╝
```

# 🚀 BETTER CALL CHADI 🚀
### The Ultimate Cyberpunk SOC Dashboard & Pentesting Toolkit

[![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Flask](https://img.shields.io/badge/Flask-2.3.2-000000?style=for-the-badge&logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![Docker](https://img.shields.io/badge/Docker-Ready-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

<br/>

> **"Stop staring at terminal output. Start visualizing the battlefield."**

**Better Call Chadi** transforms your browser into a command center for Penetration Testing, Red Teaming, and Threat Intelligence. Built with a responsive **Cyberpunk** aesthetic, it combines powerful scanners, offensive engineering tools, and real-time 3D visualization into one unified platform.

[Features](#-features) • [Screenshots](#-screenshots) • [Installation](#-installation) • [Usage](#-usage)

</div>

---

## 🔥 Features

### 🛡️ 1. Advanced Scanner
Perform deep reconnaissance and vulnerability assessment.
- [x] **Web / API / Infra Scan**: Custom scopes.
- [x] **Vulnerability Profiles**: Quick, Stealth, SQLi, XSS, RCE hunting.
- [x] **Active Toolkit**: Subdomain Enumeration, Port Scanner, Tech Stack Detection.

### 🔬 2. Engineer Mode
Analyze artifacts and generate payloads.
- [x] **Binary Inspector**: Static analysis & YARA scanning.
- [x] **PCAP Analyzer**: Network traffic inspection with threat alerts.
- [x] **Wordlist Generator**: Create intelligent custom wordlists based on target patterns.

### 🕶️ 3. Behind the Wall (Red Team)
Offensive tools for the modern operator.
- [x] **Social Engineer**: High-fidelity phishing template generator with scenario support.
- [x] **Ghost Proxies**: Real-time proxy scraper & tester.
- [x] **Shadow Cloak**: Payload obfuscation techniques.

### 🌍 4. Global Intelligence (Live Map)
Visualize the cyber war in real-time.
- [x] **3D WebGL Globe**: Watch live attacks (SSH Brute Force, Malware Beacons) across the world.
- [x] **Active Threats**: Top malware families currently in the wild.
- [x] **Real-Time Feed**: Streaming event ticker with country flags.

---

## 📸 Screenshots

<div align="center">
  <table>
    <tr>
      <td align="center"><b>Dashboard</b><br><img src="screenshots/dash.png" width="200" alt="Dashboard"/></td>
      <td align="center"><b>Live Map</b><br><img src="screenshots/globe.png" width="200" alt="Live Map"/></td>
      <td align="center"><b>Engineer</b><br><img src="screenshots/engineer.png" width="200" alt="Engineer"/></td>
      <td align="center"><b>Red Team</b><br><img src="screenshots/wall.png" width="200" alt="Red Team"/></td>
    </tr>
  </table>
</div>

---

## 🚀 Installation

### Prerequisites
- [Docker](https://www.docker.com/) & [Docker Compose](https://docs.docker.com/compose/)

### Quick Start

```bash
# 1. Clone the repository
git clone https://github.com/chadi0x/better-call-chadi.git
cd better-call-chadi

# 2. Launch with Docker Compose
docker-compose up --build
```

> The application will be available at `http://localhost:3000`

---

## 🛠️ Usage

1.  **Scanner**: Enter a target domain (e.g., `example.com`), select a profile (e.g., `Full Recon`), and hit **SCAN**.
2.  **Engineer**: Drag & Drop a suspicious file (`.exe`, `.apk`, `.pcap`) to analyze metadata and strings.
3.  **Red Team**: Use the **Social Engineer** tab to generate a convincing phishing page for your engagement.
4.  **Intel**: switch to the **Live Map** tab to monitor global threat levels.

---

## 🛡️ Disclaimer

This project is for **educational purposes and authorized testing only**. 
The developers are not responsible for any misuse or damage caused by this software. 
**Do not use this tool on systems you do not own or have explicit permission to test.**

---

<div align="center">

Made with ❤️ and ☕ by **Chadi**

[![GitHub](https://img.shields.io/badge/GitHub-chadi0x-181717?style=social&logo=github)](https://github.com/chadi0x)
[![Twitter](https://img.shields.io/badge/Twitter-@chadi0x-1DA1F2?style=social&logo=twitter)](https://twitter.com/chadi0x)

</div>
