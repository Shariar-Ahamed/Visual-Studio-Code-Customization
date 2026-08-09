# 🚀 Apps & Companion Tools for VS Code Setup

This document lists all the essential development software, runtimes, terminal utilities, and productivity tools configured to work seamlessly alongside **Visual Studio Code**.

---

## ⚡ Quick One-Click Setup (Windows Package Manager - Winget)

You can install all essential tools in one go by running this command in **PowerShell (Run as Administrator)**:

```powershell
winget install --id Microsoft.VisualStudioCode -e ; `
winget install --id OpenJS.NodeJS.LTS -e ; `
winget install --id Git.Git -e ; `
winget install --id GitHub.cli -e ; `
winget install --id Microsoft.PowerShell -e ; `
winget install --id Microsoft.WindowsTerminal -e ; `
winget install --id Google.Chrome -e ; `
winget install --id Postman.Postman -e ; `
winget install --id Microsoft.PowerToys -e
```

---

## 🛠️ Core Runtimes & Version Control

These are the primary requirements to run, build, and version control modern web applications.

| Application | Category | Purpose / Role | Recommended Version | Download & Winget ID |
| :--- | :--- | :--- | :--- | :--- |
| **Google Antigravity** | AI IDE / Editor | Agentic AI-powered coding environment by Google DeepMind | Latest Preview / Stable | [Official Website](https://antigravity.google/) |
| **Visual Studio Code** | Code Editor | Primary code editor & IDE | Latest Stable (x64) | [Official Download](https://code.visualstudio.com/download#) <br> `Microsoft.VisualStudioCode` |
| **Node.js (LTS)** | JS Runtime | JavaScript/TypeScript runtime & npm ecosystem | v22.x LTS | [Official Download](https://nodejs.org/en/download/) <br> `OpenJS.NodeJS.LTS` |
| **Git for Windows** | Version Control | Source code versioning & Git Bash shell | v2.48+ | [Official Download](https://git-scm.com/downloads) <br> `Git.Git` |
| **GitHub CLI (`gh`)** | CLI Tool | Manage PRs, issues, and repos directly from terminal | Latest Stable | [Official Download](https://cli.github.com/) <br> `GitHub.cli` |
| **PowerShell 7 (x64)** | Modern Shell | High-performance cross-platform scripting shell | v7.5+ | [Official Download](https://github.com/PowerShell/PowerShell/releases) <br> `Microsoft.PowerShell` |

---

## 💻 Terminal & CLI Enhancements

Upgrade your command-line workflow with modern terminals and custom prompts.

| Tool | Type | Why It's Useful | Download Link |
| :--- | :--- | :--- | :--- |
| **Windows Terminal** | Terminal Emulator | Multi-tab, GPU-accelerated terminal with custom profiles | [Microsoft Store](https://aka.ms/terminal) |
| **Oh My Posh** | Prompt Engine | Beautiful git status, path, and node version in your prompt | [Official Site](https://ohmyposh.dev/) |
| **WSL 2 (Ubuntu)** | Linux Subsystem | Run a full native Linux environment inside Windows | [WSL Install Guide](https://learn.microsoft.com/en-us/windows/wsl/install) |

---

## 🌐 Browsers & Debugging

| Browser | Purpose | Key Feature for Developers | Download Link |
| :--- | :--- | :--- | :--- |
| **Google Chrome** | Primary Browser | Default testing, Chrome DevTools, React & Redux DevTools | [Official Download](https://www.google.com/chrome/) |
| **Firefox Developer Edition** | Secondary Browser | Advanced CSS Grid & Flexbox inspector | [Official Download](https://www.mozilla.org/firefox/developer/) |

---

## 🧪 API Testing & Database Tools

| Tool | Category | Purpose | Download Link |
| :--- | :--- | :--- | :--- |
| **Postman** | API Client | REST / GraphQL API testing, request mocking, and documentation | [Official Download](https://www.postman.com/downloads/) |
| **Docker Desktop** | Containerization | Run containerized databases (PostgreSQL, MongoDB, Redis) locally | [Official Download](https://www.docker.com/products/docker-desktop/) |
| **MongoDB Compass** | Database GUI | Visual exploration and query builder for MongoDB | [Official Download](https://www.mongodb.com/products/tools/compass) |

---

## ✒️ Developer Fonts (with Ligatures)

Coding fonts with programming ligatures make reading code faster and cleaner in VS Code.

| Font Name | Style | Features | Link |
| :--- | :--- | :--- | :--- |
| **Fira Code** | Monospace | Rich programming ligatures (`=>`, `===`, `!=`) | [Google Fonts](https://fonts.google.com/specimen/Fira+Code) |
| **JetBrains Mono** | Monospace | Clear letterforms designed specifically for developers | [JetBrains](https://www.jetbrains.com/lp/mono/) |
| **Cascadia Code** | Monospace | Microsoft's modern terminal & editor font with ligatures | [GitHub Releases](https://github.com/microsoft/cascadia-code/releases) |

---

## ⚡ Productivity Boosters

| Utility | Developer Benefit | Download Link |
| :--- | :--- | :--- |
| **Microsoft PowerToys** | Window tiling (FancyZones), Color Picker (`Win + Shift + C`), Screen Ruler | [Microsoft Store / GitHub](https://github.com/microsoft/PowerToys) |
| **Everything (Voidtools)** | Instantaneous local file search across entire drives | [Voidtools](https://www.voidtools.com/) |

---

## 🔍 Verification Commands

After installing the core tools, open your terminal (PowerShell 7 / Git Bash) and verify the setup:

```bash
# Check Node & NPM
node -v
npm -v

# Check Git & GitHub CLI
git --version
gh --version

# Check PowerShell version
$PSVersionTable.PSVersion
```

---

## 💡 Quick Tips for VS Code Integration

1. **Set Default Terminal**: Open Command Palette (`Ctrl + Shift + P`) → `Terminal: Select Default Profile` → Choose **PowerShell 7** or **Git Bash**.
2. **Enable Font Ligatures**: Ensure `"editor.fontLigatures": true` is present in your `settings.json`.
3. **GitHub CLI Login**: Run `gh auth login` in terminal to authenticate your GitHub account with SSH or HTTPS.
