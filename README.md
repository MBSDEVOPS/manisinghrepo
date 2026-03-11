🚀 DevOps Projects – Mani Singh

Welcome to my DevOps repository showcasing cloud automation, DevOps tools, and real-world hands-on projects.

⭐ Featured Project: DevSetup CLI Tool v1.0

DevSetup is a modular, CLI-based DevOps automation tool that provisions a complete development environment on AWS EC2 (or local Linux system) with a single command.
It supports optional installs, interactive menus, environment validation, and cleanup functionality — making setup fast, flexible, and beginner-friendly.

🛠 Tech Stack

Cloud & Infra: AWS, EC2

DevOps Tools: Docker, Docker Compose, Terraform, kubectl, Node.js, Ansible

Platform: Linux

Version Control: Git

⚙️ Features

One-click DevOps environment setup

Install tools optionally: Docker, AWS CLI, Terraform, kubectl, Node.js, Ansible, Docker Compose, Kubernetes cluster

Interactive menu for tool selection

Environment validation command

Cleanup functionality

Logging to file for troubleshooting (~/.devsetup/logs/devsetup.log)

Skip OS updates or upgrade only outdated tools

Modular CLI architecture

💻 CLI Commands
Command	Description
devsetup install [options]	Install selected DevOps tools
devsetup install --interactive	Interactive menu to choose tools
devsetup validate	Validate installed tools and show versions
devsetup cleanup	Remove DevSetup temporary directories
devsetup --version	Show DevSetup CLI version
devsetup --help	Show usage and available commands

Optional flags for install command:
--docker --aws --terraform --kubectl --node --ansible --docker-compose --k8s-cluster --all --skip-update

🎯 Purpose

This project demonstrates practical DevOps skills including:

Cloud environment provisioning

Automation scripting

CLI tool development

Infrastructure tooling setup

Optional advanced modules for developers

👨‍💻 Author

Mani Singh
Aspiring Cloud & DevOps Engineer

GitHub: https://github.com/MBSDEVOPS
