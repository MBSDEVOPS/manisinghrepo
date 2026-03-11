![Version](https://img.shields.io/badge/version-1.0.0-blue?style=for-the-badge)
![Platform](https://img.shields.io/badge/platform-Linux-green?style=for-the-badge)
![Language](https://img.shields.io/badge/language-Bash-yellow?style=for-the-badge)
![DevOps](https://img.shields.io/badge/category-DevOps%20Automation-purple?style=for-the-badge)
![CLI Tool](https://img.shields.io/badge/type-CLI%20Tool-orange?style=for-the-badge)
![Maintained](https://img.shields.io/badge/maintained-yes-brightgreen?style=for-the-badge)

# 🚀 DevOps Projects – Mani Singh

Welcome to my DevOps repository showcasing cloud automation, DevOps tools, and real-world hands-on projects focused on modern cloud infrastructure and automation practices.

---
## 🎬 Demo

[![asciicast](https://asciinema.org/a/J6sfAaLdDcAIFJbC.svg)](https://asciinema.org/a/J6sfAaLdDcAIFJbC)

## ⭐ Featured Project: DevSetup CLI Tool v1.0

**DevSetup** is a modular, CLI-based DevOps automation tool designed to provision a complete development environment on Linux systems using a single command.

It simplifies DevOps onboarding by allowing developers and engineers to quickly install, validate, and manage essential DevOps tools with optional selections and interactive setup.

---

# ⚡ Quick Installation (One Command)

Install DevSetup globally on any Linux machine:

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

⚙️ Supported DevOps Tools

Docker

AWS CLI

Terraform

Kubernetes (kubectl)

Node.js

Ansible

Docker Compose

🧠 Concepts Implemented

Bash Automation

Idempotent Configuration Management

System Diagnostics

Modular CLI Architecture

Automated Provisioning

✨ Features
🚀 One-Click DevOps Environment Setup

Provision DevOps tools instantly.

🎛 Modular Installation (Command Chaining)

Install only required tools:

devsetup install docker terraform kubectl
🔥 Idempotent Automation (Core DevOps Concept)

Detects existing installations

Skips reinstallations automatically

Safe to run multiple times

🩺 System Diagnostics — Doctor Command

Check environment health:

devsetup doctor

Example:

[✔] docker installed
[⚠] terraform missing
📁 Automated Directory Provisioning

Creates development workspace automatically:

~/projects/dev
~/projects/test
~/projects/scripts
🧹 Cleanup Automation
devsetup cleanup

Removes DevSetup environment safely.

🔄 Self Update Feature
devsetup update

Fetches latest version directly from GitHub.

🎨 Professional CLI Experience

Startup banner

Colored output indicators

Progress spinner

Clear status messages

📝 Logging System

Logs stored at:

~/.devsetup/logs/devsetup.log
💻 CLI Commands
Command	Description
devsetup install <tools>	Install DevOps tools
devsetup install --interactive	Interactive installation
devsetup doctor	Diagnose environment
devsetup cleanup	Remove directories
devsetup update	Update DevSetup
devsetup --help	Show help
devsetup --version	Show version
📦 Example Usage

Install Docker & Terraform:

devsetup install docker terraform

Run diagnostics:

devsetup doctor

Interactive setup:

devsetup install --interactive
🧱 Architecture Highlights

DevSetup follows real DevOps engineering design principles:

Modular CLI command structure

Self-installing automation tool

Idempotent installation logic

Environment validation workflows

Automated provisioning lifecycle

📂 Project Structure
devsetup        # CLI + installer script
README.md

The devsetup file works as both:

Installer

Global CLI application

👨‍💻 Author

Mani Singh
Aspiring Cloud & DevOps Engineer

GitHub Profile:
https://github.com/MBSDEVOPS

Repository:
https://github.com/MBSDEVOPS/manisinghrepo

🚀 Future Enhancements

Cross-OS Support (Ubuntu/Debian)

Plugin Architecture

Kubernetes Local Cluster Setup

CI/CD Modules

Dev Environment Templates

⭐ Why DevSetup?

Modern teams waste time configuring environments manually.

DevSetup enables:

✅ Faster onboarding
✅ Standardized environments
✅ Automated provisioning
✅ DevOps best practices

⭐ If you find this project useful, please consider giving it a Star ⭐ on GitHub!


---

## ✅ After Updating

Run:

```bash
git add README.md
git commit -m "Final README with full DevSetup features"
git push origin main
