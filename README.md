<h2 align="center">Visual Studio Code Customization</h2>

<p align="center">
  <img src="https://i.postimg.cc/GpLHgXzr/visual-studio.png" alt="Visual Studio Code Customization">
</p>

<p align="center">
  A curated, high-productivity <b>VS Code</b> setup optimized for Frontend Development, React, UI/UX design, and Computer Science coursework.
  This repository contains customized <b>settings</b>, <b>extensions</b>, <b>keybindings</b>, and a step-by-step <b>setup guide</b> to quickly replicate this environment on any machine.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Visual%20Studio-Code-007ACC?style=for-the-badge&logo=visualstudiocode" alt="VS Code">
  <img src="https://img.shields.io/badge/Customization-Setup-black?style=for-the-badge" alt="Customization">
  <img src="https://img.shields.io/badge/Extensions-Collection-success?style=for-the-badge" alt="Extensions">
  <img src="https://img.shields.io/badge/Productivity-Workspace-blueviolet?style=for-the-badge" alt="Productivity">
</p>

<p align="center">
  <img src="https://img.shields.io/github/license/Shariar-Ahamed/Visual-Studio-Code-Customization" alt="License">
  <img src="https://img.shields.io/github/repo-size/Shariar-Ahamed/Visual-Studio-Code-Customization" alt="Repo Size">
  <img src="https://img.shields.io/github/last-commit/Shariar-Ahamed/Visual-Studio-Code-Customization" alt="Last Commit">
  <img src="https://img.shields.io/github/stars/Shariar-Ahamed/Visual-Studio-Code-Customization?style=social" alt="Stars">
  <img src="https://img.shields.io/github/forks/Shariar-Ahamed/Visual-Studio-Code-Customization?style=social" alt="Forks">
</p>

<p align="center">
  <a href="https://wakatime.com/badge/user/c7433bc5-6f12-4c97-baea-430790fa608c/project/5e9e6bc6-6021-4cd5-b96b-6dbf0c1037fd">
    <img src="https://wakatime.com/badge/user/c7433bc5-6f12-4c97-baea-430790fa608c/project/5e9e6bc6-6021-4cd5-b96b-6dbf0c1037fd.svg" alt="WakaTime">
  </a>
</p>

---

## 📂 Repository Structure

```bash
Visual-Studio-Code-Customization/
│ 
├── 📁 extensions/
│   ├── 📝 extensions-list.md            # Complete list of extensions with shortcuts & features
│   └── 📕 VS Code update extension.pdf   # Printable extension update reference
│ 
├── 📁 keyboard-shortcuts/
│   ├── 📝 README.md                     # Shortcut guide & documentation
│   ├── 📕 01-keyboard-shortcuts-windows.pdf
│   ├── 📕 02-keyboard-shortcuts-linux.pdf
│   └── 📕 03-keyboard-shortcuts-macos.pdf
│ 
├── 📁 settings/
│   ├── ⚙️ settings.min.json              # Minimal, fast settings for daily frontend development
│   ├── ⚙️ settings.json                  # Full advanced configuration with customized UI
│   └── ⚙️ keybindings.json              # Custom keybindings & shortcuts
│ 
├── 📁 setup-guide/
│   ├── 📝 setup.md                      # ⚡ 5-Step Quick Restore Guide
│   └── 📝 apps-used-for-vscode.md       # 🚀 Required apps, fonts, and Winget install script
│ 
└── 📝 README.md                         # Main repository overview
```

---

## ✨ Key Features

- 🎯 **Clean & Distraction-Free UI**: Minimap disabled, clean breadcrumbs, smooth cursor animations.
- ⚡ **Frontend & React Optimized**: Prettier-based formatting on save, HTML/CSS/Tailwind autocomplete, React snippets.
- 🎨 **Aesthetic Dark Themes**: Dracula Official, Andromeda, Catppuccin, Night Owl with Material Icon Theme.
- 🤖 **AI-Enhanced Coding**: Integrated with GitHub Copilot, Copilot Chat, and Gemini Code Assist.
- ⌨️ **Custom Productivity Keybindings**: Fast one-key shortcuts for Live Server, Prettier formatting, and Quokka.js.
- ✒️ **Font Ligatures Support**: Pre-configured for Fira Code, JetBrains Mono, and Operator Mono.

---

## ⚡ Quick 5-Step Setup

Restore this entire setup in less than 2 minutes:

1. **Install Prerequisites**: Follow the [Apps & Tools Guide](https://github.com/Shariar-Ahamed/Visual-Studio-Code-Customization/blob/main/setup-guide/apps-used-for-vscode.md).
2. **Open Settings (JSON)**: In VS Code, press `Ctrl + Shift + P` → `Preferences: Open User Settings (JSON)`.
3. **Apply Settings**: Paste configuration from [settings.min.json](https://github.com/Shariar-Ahamed/Visual-Studio-Code-Customization/blob/main/settings/settings.min.json) or [settings.json](https://github.com/Shariar-Ahamed/Visual-Studio-Code-Customization/blob/main/settings/settings.json).
4. **Install Extensions**: Browse and install from [extensions-list.md](https://github.com/Shariar-Ahamed/Visual-Studio-Code-Customization/blob/main/extensions/extensions-list.md).
5. **Restart & Reload**: Press `Ctrl + Shift + P` → `Developer: Reload Window`.

👉 **Read the full step-by-step guide**: **[setup-guide/setup.md](https://github.com/Shariar-Ahamed/Visual-Studio-Code-Customization/blob/main/setup-guide/setup.md)**

---

## 🛠️ Minimal Settings (`settings.min.json`)

A clean, fast configuration for everyday frontend work:

```json
{
  "editor.fontFamily": "Fira Code, Consolas, 'Courier New', monospace",
  "editor.fontLigatures": true,
  "editor.fontSize": 17,

  "editor.minimap.enabled": false,
  "breadcrumbs.enabled": false,
  "editor.guides.bracketPairs": true,
  "editor.bracketPairColorization.independentColorPoolPerBracketType": true,

  "editor.cursorStyle": "line",
  "editor.cursorBlinking": "expand",
  "editor.cursorSmoothCaretAnimation": "on",

  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",

  "editor.renderWhitespace": "selection",
  "files.autoSave": "afterDelay",

  "workbench.colorTheme": "Dracula Theme",
  "workbench.iconTheme": "material-icon-theme",

  "git.autofetch": true,
  "explorer.confirmDelete": false,

  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  }
}
```

*For the complete configuration with UI color customizations, see [settings/settings.json](https://github.com/Shariar-Ahamed/Visual-Studio-Code-Customization/blob/main/settings/settings.json).*

---

## 🔌 Curated Extensions Collection

All extensions are categorized with default trigger keys and descriptions in **[extensions/extensions-list.md](https://github.com/Shariar-Ahamed/Visual-Studio-Code-Customization/blob/main/extensions/extensions-list.md)**:

| Category | Highlights | Full Guide |
| :--- | :--- | :--- |
| 🌐 **Frontend Essentials** | Live Server, Live Sass, Prettier, ESLint, Tailwind CSS IntelliSense, CSS Peek | [View List](https://github.com/Shariar-Ahamed/Visual-Studio-Code-Customization/blob/main/extensions/extensions-list.md#frontend-essentials) |
| ⚛️ **React & JavaScript** | ES7+ React/Redux Snippets, Simple React Snippets, JS ES6 Snippets, React Refactor | [View List](https://github.com/Shariar-Ahamed/Visual-Studio-Code-Customization/blob/main/extensions/extensions-list.md#react--javascript) |
| 🤖 **AI Coding Assistants** | GitHub Copilot, Copilot Chat, Gemini Code Assist, Codex, BLACKBOXAI | [View List](https://github.com/Shariar-Ahamed/Visual-Studio-Code-Customization/blob/main/extensions/extensions-list.md#ai-coding-assistants) |
| 🎨 **UI Themes & Aesthetics** | Dracula Official, Material Icons, Error Lens, indent-rainbow, CodeSnap | [View List](https://github.com/Shariar-Ahamed/Visual-Studio-Code-Customization/blob/main/extensions/extensions-list.md#ui--ux--visual-tools) |
| ⚙️ **Productivity & Git** | GitLens, Git Graph, Todo Tree, WakaTime, Path & npm Intellisense | [View List](https://github.com/Shariar-Ahamed/Visual-Studio-Code-Customization/blob/main/extensions/extensions-list.md#productivity--workflow) |
| 🧪 **Execution & Debugging** | Quokka.js, Code Runner, CodeLLDB, Postman | [View List](https://github.com/Shariar-Ahamed/Visual-Studio-Code-Customization/blob/main/extensions/extensions-list.md#code-execution--debugging) |
| 💻 **Languages & Data Science** | C/C++, CMake Tools, Python, Jupyter Notebooks, Draw.io | [View List](https://github.com/Shariar-Ahamed/Visual-Studio-Code-Customization/blob/main/extensions/extensions-list.md#c--c--system-programming) |

---

## ⌨️ Custom Keybindings (`keybindings.json`)

Custom shortcuts configured for fast access:

| Command | Custom Keybinding | Default Shortcut | Action |
| :--- | :--- | :--- | :--- |
| **Format Document** | `Numpad /` | `Shift + Alt + F` | Prettier force format |
| **Live Server Toggle** | `Numpad *` | `Alt + L Alt + O` | Start / Stop Live Server |
| **Live Emmet Toggle** | `Numpad -` | `Ctrl + K Ctrl + L` | Toggle live Emmet preview |
| **Mobile Preview** | `Home` | `Ctrl + Shift + P` | Show mobile & tablet simulator |
| **Quokka.js Scratchpad** | `Delete` | `Ctrl + Alt + J` | Evaluate JavaScript in current file |
| **WakaTime Dashboard** | `ScrollLock` | Status bar | Open WakaTime metrics |

*For standard VS Code shortcut PDFs (Windows, Mac, Linux), visit the **[keyboard-shortcuts/](https://github.com/Shariar-Ahamed/Visual-Studio-Code-Customization/tree/main/keyboard-shortcuts)** directory.*

---

## 🚀 Apps & Companion Tools

Essential software configured alongside VS Code. Full setup and Winget one-liner: **[setup-guide/apps-used-for-vscode.md](https://github.com/Shariar-Ahamed/Visual-Studio-Code-Customization/blob/main/setup-guide/apps-used-for-vscode.md)**

| Application | Category | Download Link |
| :--- | :--- | :--- |
| **Google Antigravity** | AI IDE / Editor | [Official Website](https://antigravity.google/) |
| **Visual Studio Code** | Code Editor | [Official Download](https://code.visualstudio.com/download#) |
| **Node.js (LTS)** | JavaScript Runtime | [Official Download](https://nodejs.org/en/download/) |
| **Git for Windows** | Version Control | [Official Download](https://git-scm.com/downloads) |
| **GitHub CLI (`gh`)** | CLI Tool | [Official Download](https://cli.github.com/) |
| **PowerShell 7 (x64)** | Modern Shell | [Official Download](https://github.com/PowerShell/PowerShell/releases) |
| **Windows Terminal** | Terminal Emulator | [Microsoft Store](https://aka.ms/terminal) |
| **Google Chrome** | Browser & DevTools | [Official Download](https://www.google.com/chrome/) |
| **Postman** | API Client | [Official Download](https://www.postman.com/downloads/) |

---

## 🎨 Themes & Fonts

### Themes
- 🧛 **Dracula Theme Official** *(Default)*
- 🌌 **Andromeda**
- 🦉 **Night Owl**
- 🟣 **Shades of Purple**
- 🌆 **SynthWave '84**
- 🍃 **Ayu (Theme)**
- 🌸 **Catppuccin for VSCode**

### Developer Fonts
- **[Fira Code](https://fonts.google.com/specimen/Fira+Code)** (Recommended with ligatures)
- **[JetBrains Mono](https://www.jetbrains.com/lp/mono/)**
- **[Operator Mono](https://www.typography.com/fonts/operator/styles)**

---

## 🧑‍💻 Author & Maintainer

- **Shariar Ahamed** — [@Shariar-Ahamed](https://github.com/Shariar-Ahamed/)

---

## 🌐 Connect With Me

<p align="center">
  <a href="https://github.com/Shariar-Ahamed/"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
  <a href="https://www.linkedin.com/in/shariarahamed/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://facebook.com/Shahriar.TheBrownCat/"><img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook"></a>
  <a href="https://twitter.com/ShariarAlways/"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter"></a>
  <a href="https://instagram.com/shahriar_thebrowncat/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"></a>
</p>
