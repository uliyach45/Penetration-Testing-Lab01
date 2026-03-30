# Penetration-Testing-Lab01
Air University - Penetration Testing Lab 01
# 🛡️ Penetration Testing Lab 01 — Setting Up Your Virtual Lab


## 📋 Lab Overview

This repository contains the complete documentation, screenshots, and report for **Lab 01: Setting Up Your Virtual Lab** — the foundational lab for the Penetration Testing course.

---

## ✅ Tasks Completed

| Task | Description | Status |
|------|-------------|--------|
| Task 1 | Install VMware & Setup Kali Linux VM | ✔ Completed |
| Task 2 | Configure Network (Bridged Mode) & Test Connectivity | ✔ Completed |
| Task 3 | Install & Configure Nessus Vulnerability Scanner | ✔ Completed |
| Task 4 | Create Windows XP SP3 Target VM | ✔ Completed |
| Task 7 | Configure Static IP & Test VM-to-VM Connectivity | ✔ Completed |

---

## 🖥️ Lab Environment

| Component | Details |
|-----------|---------|
| **Attacker Machine** | Kali Linux (Latest) — IP: 192.168.17.128 |
| **Target Machine** | Windows XP SP3 — IP: 192.168.84.128 |
| **Vulnerability Scanner** | Nessus Essentials 10.11.2 |
| **Hypervisor** | VMware Workstation |
| **Network Mode** | Bridged Adapter |

---

## 📸 Screenshots

### Task 1 — Kali Linux Setup
| Screenshot | Description |
|------------|-------------|
| `Task1-KaliLogin.png` | Kali Linux login screen |
| `Task1-KaliDesktop.png` | Kali Linux desktop after login |

### Task 2 — Network Configuration
| Screenshot | Description |
|------------|-------------|
| `Task2-ifconfig.png` | ifconfig output showing IP address |
| `Task2-ping.png` | Successful ping to Google |

### Task 3 — Nessus Scanner
| Screenshot | Description |
|------------|-------------|
| `Task3-NessusLogin.png` | Nessus login screen |
| `Task3-NessusDashboard.png` | Nessus dashboard after login |

### Task 4 — Windows XP VM
| Screenshot | Description |
|------------|-------------|
| `Task6-XPDesktop.png` | Windows XP desktop after login |
| `Task6-FirewallOff.png` | Windows Firewall disabled |

### Task 7 — VM-to-VM Connectivity
| Screenshot | Description |
|------------|-------------|
| `Task7-PingXP.png` | Successful ping from Kali to Windows XP |

---

## 📄 Report

Full lab report with all screenshots and explanations:  
📥 [`Lab01_PenetrationTesting_Report.docx`](./Lab01_PenetrationTesting_Report.docx)

---

## 🔧 Tools Used

- **VMware Workstation** — Virtualization platform
- **Kali Linux** — Attacker/pentesting OS
- **Nessus Essentials** — Vulnerability scanner
- **Windows XP SP3** — Target machine
- **ifconfig / ping** — Network verification tools

---

## ⚠️ Disclaimer

> This lab is conducted in a **controlled virtual environment** for **educational purposes only**. All activities are performed on isolated VMs with no impact on real systems.
