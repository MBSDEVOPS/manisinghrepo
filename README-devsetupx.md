🚀 DevSetupX — Enterprise DevOps Bootstrap CLI

![Version](https://img.shields.io/badge/version-v1.0.1-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Shell](https://img.shields.io/badge/shell-bash-orange)

---

## 🎯 Overview

**DevSetupX** is an enterprise-grade DevOps automation CLI that provides
zero-configuration environment setup using intelligent system detection.

It automatically detects:

- Operating System
- Architecture
- Package Manager
- Cloud Provider
- Container Environment

and prepares a ready-to-use DevOps environment.

---

## ⭐ Key Features

### 🧭 Enterprise CLI Design
- Clean command router
- Single-file production CLI
- Safe output handling
- Colored terminal UI

---

### ⚙️ Installation Modes
- Interactive mode
- Automation mode
- Idempotent installs


devsetupx --interactive
devsetupx install


---

### 🖥️ System Intelligence
- OS detection
- Architecture detection (amd64 / arm64)
- Package manager auto detection

---

### ☁️ Cloud Auto Detection

DevSetupX automatically detects:

| Cloud | Action |
|---|---|
| AWS | AWS CLI profile setup |
| Azure | AZ environment ready |
| GCP | gcloud preparation |
| Local | Generic setup |

⭐ **Auto Cloud Profile Switching**
No manual configuration required.

---

### 📦 Container Awareness
Detects:
- Docker containers
- Virtual machines
- Bare-metal hosts

---

### 🔌 Plugin System

Extend DevSetupX without modifying core code.

Location:


~/.devsetupx/plugins/


Example:


plugins/
└── terraform.sh


---

### 🩺 Health & Diagnostics


devsetupx detect
devsetupx doctor


- Environment inspection
- Dependency validation
- Setup recommendations

---

### 🔄 Self Update


devsetupx update


Pulls latest version directly from GitHub.

---

## 📦 Installation

### Quick Install

```bash
curl -fsSL https://raw.githubusercontent.com/MBSDEVOPS/manisinghrepo/main/devsetupx -o devsetupx
chmod +x devsetupx
./devsetupx --interactive
Global Install
sudo mv devsetupx /usr/local/bin/
devsetupx --help
🧪 Commands
Command	Description
detect	Show environment info
doctor	Health check
install	Automated setup
update	Self update
clean	Cleanup cache
--interactive	Guided setup
🏗 Architecture

DevSetupX follows enterprise DevOps platform patterns:

Zero-config onboarding
Cloud-aware automation
Plugin extensibility
Idempotent operations
Single-file deployment

📌 Version
DevSetupX v1.0.1
Enterprise Stable Release

📜 License

MIT License — see LICENSE

👨‍💻 Author

Manibhushan Singh
DevOps Engineer — Platform Automation

GitHub: https://github.com/MBSDEVOPS

⭐ Vision

DevSetupX aims to become the kubectl for DevOps environment setup.
