# 🚀 DevSetupX — Enterprise DevOps Bootstrap CLI

![Version](https://img.shields.io/badge/version-1.0.1-blue?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)
![Platforms](https://img.shields.io/badge/platform-Linux%20%7C%20macOS-lightgrey?style=for-the-badge)

🔥 **Your ultimate DevOps bootstrap CLI for enterprise environments!**


██████╗ ███████╗██╗ ██╗███████╗███████╗████████╗██╗ ██╗██████╗ ██╗ ██╗
██╔══██╗██╔════╝██║ ██║██╔════╝██╔════╝╚══██╔══╝██║ ██║██╔══██╗╚██╗██╔╝
██║ ██║█████╗ ██║ ██║███████╗█████╗ ██║ ██║ ██║██████╔╝ ╚███╔╝
██║ ██║██╔══╝ ╚██╗ ██╔╝╚════██║██╔══╝ ██║ ██║ ██║██╔═══╝ ██╔██╗
██████╔╝███████╗ ╚████╔╝ ███████║███████╗ ██║ ╚██████╔╝██║ ██╔╝ ██╗
╚═════╝ ╚══════╝ ╚═══╝ ╚══════╝╚══════╝ ╚═╝ ╚═════╝ ╚═╝ ╚═╝ ╚═╝


### 👤 Creator
**Manibhushan Singh** — Enterprise DevOps Engineer & Automation Enthusiast  

---

## 💡 Features

- 🎨 Original ASCII banner style  
- 🌈 Colored professional output  
- 🤖 Interactive & Automation modes (`--interactive`, `--auto`)  
- ⚙ Enterprise Ansible setup  
- 🐳 Docker + Docker Compose  
- ☸ Kubernetes (kubectl)  
- 🌍 AWS CLI  
- 📦 Terraform  
- 🟢 Node.js + npm  
- 🔴 OpenShift CLI  
- ✅ Stability improvements  
- ☁ Correct cloud detection (AWS / Azure / GCP / Local)  
- 💫 Dry-run simulation (`--dry-run`)  
- 🔄 Idempotent installs  
- ⏳ Tiny spinner/progress indicator for professional feel  

---

## ⚡ Quick Install / Update

Run this one-liner to **install or update DevSetupX**:

```bash
curl -fsSL https://raw.githubusercontent.com/MBSDEVOPS/manisinghrepo/main/devsetupx | sudo tee /usr/local/bin/devsetupx >/dev/null && sudo chmod +x /usr/local/bin/devsetupx && echo "✔ DevSetupX installed/updated successfully"

🏃 Usage
1️⃣ Interactive Mode

Ask yes/no for each tool:

devsetupx --interactive

2️⃣ Automation Mode

Install a single tool:

devsetupx --auto docker       # Docker only
devsetupx --auto terraform    # Terraform only

Install all tools automatically:

devsetupx --auto all

3️⃣ Dry-Run Mode

Simulate installation without making changes:

devsetupx --dry-run all

4️⃣ Optional Alias
Make it shorter to run:

echo 'alias dsx="devsetupx"' >> ~/.bashrc
source ~/.bashrc
dsx --interactive

🌐 Supported Platforms
Linux (Debian/Ubuntu, RHEL/CentOS, Fedora, Amazon Linux)
macOS (brew)
Windows (via WSL)

🛠️ Example Workflow
# Install or update DevSetupX
curl -fsSL https://raw.githubusercontent.com/MBSDEVOPS/manisinghrepo/main/devsetupx | sudo tee /usr/local/bin/devsetupx >/dev/null && sudo chmod +x /usr/local/bin/devsetupx

# Interactive install
devsetupx --interactive

# Automation install
devsetupx --auto all

# Dry-run simulation
devsetupx --dry-run all

📜 License

MIT License — free to use, modify, and distribute.
