# One-Step Bootstrap for DevOps on macos

This guide presents a streamlined process for automating the installation of a comprehensive DevOps/development environment on macos.

Packages Included:

* 🔧 Homebrew & Base Tools
* 🐳 Docker & Virtualization
* 🧰 DevOps Tools
* 💻 Code & IDEs
* 🧪 Testing & Automation
* 🔐 Security & Secrets

* 📁 Folder Structure (Best Practice)
     ```
      ~/devops/
      ├── terraform/
      ├── ansible/
      ├── docker/
      ├── helm/
      ├── kubernetes/
      ├── projects/
      └── scripts/ 
     ```

* ⚙️ Performance Tips for M4 Chip
     1. Use Activity Monitor to verify CPU architecture.
     2. Consider running containers with platform=linux/arm64 to avoid translation.
     3. Personal macos dotfiles optimized for DevOps and Zsh users on Apple Silicon (M1/M2/M3/M4).
     4. Avoid Rosetta apps — use native ARM64 builds when possible.


## 📦 Included Configs

| File            | Purpose                                |
|-----------------|----------------------------------------|
| `.zshrc`        | ZSH shell configuration                |
| `.gitconfig`    | Git user settings & helpful aliases    |
| `.tool-versions`| Version control via `asdf`             |

## ⚙️ Installation

Clone and install:

```bash
git clone https://github.com/mehrdadmm/macops-bootstrap ~/.dotfiles
cd ~/.dotfiles
./install.sh
```
