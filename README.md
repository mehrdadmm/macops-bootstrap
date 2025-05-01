# macops-bootstrap

> A One-Step Bootstrap for Preparing Your macOS DevOps Environment. This guide outlines the essential steps to configure your macos DevOps environment efficiently.

Included:

* 🔧 1. Homebrew & Base Tools
* 🐳 2. Docker & Virtualization
* 🧰 3. DevOps Tools
* 💻 4. Code & IDEs
* 🧪 5. Testing & Automation
* 🔐 6. Security & Secrets
* 📦 7. Optional (but Recommended)
* 📁 8. Folder Structure (Best Practice)
      ```~/devops/
           ├── terraform/
           ├── ansible/
           ├── docker/
           ├── helm/
           ├── kubernetes/
           ├── projects/
           └── scripts/ ```

* ⚙️ 9. Performance Tips for M4 Chip
*     Use Activity Monitor to verify CPU architecture.
*     Consider running containers with platform=linux/arm64 to avoid translation.
*     Personal macos dotfiles optimized for DevOps and Zsh users on Apple Silicon (M1/M2/M3/M4).
*     Avoid Rosetta apps — use native ARM64 builds when possible.


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
