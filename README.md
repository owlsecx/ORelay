# 🔄 ORelay

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux%20%2F%20Windows-informational?style=flat-square&logo=linux&logoColor=white&color=0a0c10"/>
  <img src="https://img.shields.io/badge/Category-ONetwork%20%2F%20Traffic%20Relay-cyan?style=flat-square"/>
  <img src="https://img.shields.io/badge/Dependencies-None%20(Tkinter%20stdlib)-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-Proprietary-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-v1.0-cyan?style=flat-square"/>
</p>

> **ORelay** is a powerful bidirectional TCP socket bridge and relay suite. It supports port forwarding, live traffic inspection with hex dump, multi-client mode, per-session statistics, and detailed session logging.

---

## 📌 Overview

ORelay acts as a TCP proxy/bridge between a local port and a remote host/port. It provides real-time visibility into all traffic with beautiful hex + ASCII inspection, byte counters, speed tracking, and full session history. Perfect for debugging, testing, pivoting, or redirecting network traffic.

---

## 🖥️ Modules / Features

- **Bidirectional TCP Relay** — socat-style transparent bridge
- **Multi-Client Listener** — support multiple simultaneous connections
- **Live Hex Dump & ASCII Inspector** — real-time packet viewing
- **Per-Session Statistics** — bytes in/out, duration, packet count
- **Session History** — timeline of all connections
- **Export Options** — TXT log and structured JSON reports
- **Dark OwlSec Theme** — clean, professional GUI interface

---

## 📊 Key Features

- Full bidirectional data relay with zero data loss
- Real-time traffic inspection (Hex + ASCII)
- Multi-client support (can handle multiple incoming connections)
- Live byte counters and session duration
- Automatic session logging and history
- Clean, modern GUI with dark theme
- Export logs and session data for analysis
- Connection status and speed monitoring

---

## ⚙️ Requirements

- **Linux or Windows**
- **Python with Tkinter** (usually pre-installed)
- **No additional dependencies** — runs as a standalone executable

---

## 🚀 Usage

```bash
./ORelay

📁 Output

Live Traffic Log — displayed in the GUI
Hex Inspector — detailed packet view
Session History — list of all past and active sessions
Export:
TXT export of the full traffic log
JSON export of all sessions with detailed statistics



📦 Part of OwlSec Toolkit
This tool is part of the OwlSec suite — a collection of 300+ security and privacy tools.
🔗 owlsec.org

©️ License
Proprietary — © Khaled S. Haddad
Tools are distributed as pre-built executables. Source code is proprietary.

AUTHORISED SECURITY TESTING & NETWORK DEBUGGING USE ONLY
