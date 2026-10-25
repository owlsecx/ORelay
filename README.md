# 🦉 ORelay

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-ONetwork-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0-cyan?style=flat-square"/>
</p>

> **ORelay** — TCP Socket Bridge & Relay Suite ║

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

ORelay is a TCP socket bridge and relay suite. It provides a bidirectional TCP relay with port forwarding, multi-client and single-shot modes, and IPv4/IPv6 dual-stack support. It includes live traffic inspection, session logging and protocol detection.

---

## ✨ Features

- Bidirectional TCP relay (socat-style) with a configurable bind address and port
- Multi-client listener and single-shot modes with IPv4/IPv6 dual-stack support
- Live packet hex/ASCII inspection with regex and keyword filtering
- Per-session byte counters and a live bandwidth (BPS) meter with throttling
- Session log export in TXT, JSON, PCAP-lite and CSV formats
- Protocol detection (HTTP, SSH, TLS, FTP, MySQL, Redis and more) with auto-reconnect

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./ORelay
./ORelay --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
