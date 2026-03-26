<p align="center">

<img src="https://img.shields.io/github/stars/MBSDEVOPS/manisinghrepo?style=for-the-badge" />
<img src="https://img.shields.io/github/forks/MBSDEVOPS/manisinghrepo?style=for-the-badge" />
<img src="https://img.shields.io/github/license/MBSDEVOPS/manisinghrepo?style=for-the-badge" />
<img src="https://img.shields.io/github/v/release/MBSDEVOPS/manisinghrepo?style=for-the-badge" />
<img src="https://img.shields.io/badge/Platform-Linux-blue?style=for-the-badge" />
<img src="https://img.shields.io/badge/Shell-Bash-green?style=for-the-badge" />

</p>
# 🚀 DevOps Projects – Mani Singh

Welcome to my DevOps repository showcasing cloud automation, DevOps tools, and real-world hands-on projects focused on modern cloud infrastructure and automation practices.

---
## 🎬 DevSetup CLI Demo

[View Demo](./demo.html)

## ⭐ Featured Project: DevSetup CLI Tool v1.0

**DevSetup** is a modular CLI-based DevOps automation tool that provisions a complete development environment on Linux or AWS EC2 using a single command.

It simplifies DevOps onboarding by allowing developers to quickly install, validate, and manage essential DevOps tools with optional selections and interactive setup.

---

## ⚡ Quick Installation

Install DevSetup globally:

```bash
curl -fsSL https://raw.githubusercontent.com/MBSDEVOPS/manisinghrepo/main/devsetup | bash

After installation:

devsetup --help
🎯 Project Purpose

This project demonstrates real DevOps engineering practices:

Infrastructure automation

CLI tool development

Environment provisioning

Idempotent automation

Linux system engineering

DevOps workflow optimization

🛠 Tech Stack
☁️ Platform

Linux (Amazon Linux / RHEL-based systems)

AWS EC2

⚙️ DevOps Tools Supported

Docker

AWS CLI

Terraform

Kubernetes (kubectl)

Node.js

Ansible

Docker Compose

✨ Features

🚀 One-click DevOps environment setup

🎛 Interactive installation mode

🔁 Idempotent automation (safe re-run)

🩺 Environment diagnostics (doctor)

📁 Auto workspace creation

🧹 Cleanup automation

🔄 Self update feature

📝 Logging system

🎨 Professional CLI output

Logs location:

~/.devsetup/logs/devsetup.log
💻 CLI Commands
Command	Description
devsetup install	Install DevOps tools
devsetup install --interactive	Interactive installation
devsetup doctor	Diagnose environment
devsetup cleanup	Remove directories
devsetup update	Update DevSetup
devsetup --help	Show help
devsetup --version	Show version
📦 Example Usage

Install Docker & Terraform:

devsetup install docker terraform

Interactive setup:

devsetup install --interactive

Run diagnostics:

devsetup doctor
🧱 Architecture Highlights

DevSetup follows real DevOps engineering design principles:

Modular CLI architecture

Self-installing automation tool

Idempotent installation logic

Environment validation workflows

Automated provisioning lifecycle

📂 Project Structure
devsetup        # CLI + installer script
README.md
👨‍💻 Author

Mani Singh
Aspiring Cloud & DevOps Engineer

GitHub: https://github.com/MBSDEVOPS

🚀 Future Enhancements

Cross-OS Support (Ubuntu/Debian)

Plugin Architecture

Kubernetes Local Cluster Setup

CI/CD Modules

Dev Environment Templates

⭐ If you find this project useful, please give it a Star!
