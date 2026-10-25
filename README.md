# 🦉 OGrafanaX

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OScan-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **OGrafanaX** — Observability-Stack Configuration Auditor

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OGrafanaX — Observability-Stack Configuration Auditor. It provides stdlib INI (+ GF_* env) and YAML-lite parsers with line tracking. Built-in demo/self-test paths and severity gates help validate detections without touching production when those flags are used.

---

## ✨ Features

- Stdlib INI (+ GF_* env) and YAML-lite parsers with line tracking
- Grafana — default admin / secret_key, anonymous roles, sign-up, auth proxy, cookies, HSTS, embedding, CSP, unsigned plugins, Angular, proxy whitelist, snapshots, provisioning passwords, EOL + CVE-2021-43798 / CVE-2025-41
- Prometheus / Alertmanager — web.yml auth & TLS, admin / lifecycle flags, exposure, scrape / remote_write TLS & creds, webhooks
- Loki / Promtail — auth_enabled, tenancy, storage keys, clients
- Secrets masked everywhere; --root discovery; CWE/CVE/MITRE
- Export TXT / Markdown / JSON / CSV / SARIF 2.1.0

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OGrafanaX                                     # interactive menu
./OGrafanaX --scan -r /path/to/root
./OGrafanaX --demo
./OGrafanaX --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
