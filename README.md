# 🖥️ BinodOS 3.0 — Portfolio OS

> An interactive, OS-themed personal portfolio built entirely with **HTML · CSS · Vanilla JS** — no frameworks, no dependencies.

![BinodOS](https://img.shields.io/badge/BinodOS-v3.0-00ff88?style=for-the-badge&logo=linux&logoColor=black)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 🚀 Live Demo

🌐 [budhabinod.com.np](https://budhabinod.com.np)

---

## 📸 Features

### 🔐 Login Screen
- Animated avatar ring with conic gradient spin
- Clock & date display
- Password-protected login (`hint: binod`)
- Show/hide password toggle

### 🖥️ Desktop Environment
- **Window System** — fully draggable, resizable, minimizable, maximizable windows
- **Taskbar** — open app pills, system tray (WiFi, battery, clock)
- **Desktop Icons** — double-click to open apps; single-click to select
- **Context Menu** — right-click on desktop for quick actions
- **Spotlight Search** — `Ctrl/⌘ + K` to search all apps & commands
- **Calendar Popup** — click the clock in the taskbar
- **Lock Screen** — press the lock icon in the tray
- **Welcome Splash** — animated boot sequence on login

### 📦 Built-in Applications

| App | Description |
|-----|-------------|
| 🏠 **Home** | Hero intro with tech stack, stats, and quick links |
| 🧠 **About Me** | Education timeline, experience, achievements, contact |
| ⚡ **Skills** | Categorized skill bars (Languages, Frontend, Backend, AI/ML, Cloud) |
| 🚀 **Projects** | Cards for all major projects with tech tags and GitHub links |
| 🏆 **Certificates** | Grid of verified credentials (Kaggle, Google DeepMind) |
| 📡 **Connect** | Social links, contact info, resume access |
| ⌨️ **Terminal** | Fully functional bash-like terminal with 20+ commands |
| 🌤️ **Weather** | Simulated weather widget for Gandhinagar, Gujarat |
| 🍅 **Pomodoro** | SVG ring timer with Focus / Short Break / Long Break modes |
| 🧮 **Calculator** | Fully functional calculator with keyboard support |
| 📄 **Resume** | PDF viewer + download dialog |
| ⚙️ **Settings** | Appearance, wallpaper, typography, system info, keyboard shortcuts |

### 🎨 Settings & Customization
- **Accent Color Picker** — 8 preset accent colors
- **Wallpaper Themes** — Aurora, Sunset, Ocean, Forest, Nebula, Cyber, Crimson + custom image upload
- **Wallpaper Effects** — Blur, Brightness, Opacity sliders
- **Typography Settings** — Font family, weight, and color with live preview
- **Interface Toggles** — Scanlines, particle network, grid overlay, vignette
- Session-persistent settings via `sessionStorage`

### ⌨️ Terminal Commands

```
help        whoami      neofetch    ls
open <app>  cat about   cat contact social
gpa         date        pwd         uptime
weather     joke        cowsay      history
echo        matrix      clear       exit
```

---

## 🛠️ Tech Stack

- **HTML5** — semantic markup, single-file architecture
- **CSS3** — CSS variables, grid, flexbox, keyframe animations, backdrop-filter
- **Vanilla JavaScript** — zero frameworks, full window management system
- **Google Fonts** — JetBrains Mono, Syne, Space Grotesk, Playfair Display, Raleway, Fira Code, Outfit
- **Remix Icons** — icon library via CDN
- **Canvas API** — animated particle network background

---

## 📁 Project Structure

```
/
├── index.html              # Entire portfolio (single-file)
├── image.png               # Profile photo
├── BinodBudhaResume.pdf    # Resume for viewer/download
├── Kaggle_certificate.png  # Kaggle ML Certificate image
└── python.png              # Kaggle Python Certificate image
```

---

## ⚡ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/binod01nep/binotos.git
cd binotos
```

### 2. Add your assets

Place these files in the root directory:
- `image.png` — your profile photo
- `BinodBudhaResume.pdf` — your resume
- Certificate images (`Kaggle_certificate.png`, `python.png`)

### 3. Open in browser

```bash
# Option A: Open directly
open index.html

# Option B: Serve locally (recommended for PDF viewer)
npx serve .
# or
python3 -m http.server 8080
```

> **Note:** The PDF resume viewer requires a local server due to browser security restrictions on `file://` protocols.

### 4. Login

Password: **`binod`**

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl/⌘ + K` | Open Spotlight Search |
| `H` | Open Home |
| `T` | Open Terminal |
| `P` | Open Projects |
| `S` | Open Skills |
| `C` | Open Connect |
| `Esc` | Close Spotlight / Context Menu |
| `Double-click icon` | Open application |
| `↑ / ↓` (in Terminal) | Navigate command history |
| `Tab` (in Terminal) | Autocomplete command |

---

## 🧑‍💻 About the Developer

**Binod Budha**
MERN Stack Developer & CS Undergraduate @ PDEU (GPA: 9.17/10)
Gandhinagar, Gujarat, India

- 📧 bcb4314@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/binod-budha-7691773a1/)
- 🐙 [GitHub](https://github.com/binod01nep)
- 🏆 [LeetCode](https://leetcode.com/u/AmBiLax/)
- 🌐 [budhabinod.com.np](https://budhabinod.com.np)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">
  <sub>Built with ❤️ by Binod Budha · BinodOS v3.0</sub>
</div>
