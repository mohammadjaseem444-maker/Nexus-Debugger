<div align="center">

<img src="https://img.shields.io/badge/Nexus-Debugger-7c3aed?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="Nexus Debugger" height="40"/>

# Nexus Debugger

**A VS Code-style AI-powered code debugger that runs entirely in your browser.**  
No installation. No backend. No data sent anywhere. Just open and debug.

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](LICENSE)
[![HTML](https://img.shields.io/badge/Built%20with-HTML%2FCSS%2FJS-orange?style=flat-square)](index.html)
[![Single File](https://img.shields.io/badge/Single%20File-75KB-blue?style=flat-square)](index.html)
[![No Backend](https://img.shields.io/badge/Backend-None-brightgreen?style=flat-square)]()
[![Open Source](https://img.shields.io/badge/Open-Source-purple?style=flat-square)]()

### [→ Try it Live](https://mohammadjaseem444-maker.github.io/Nexus-Debugger/) · [Report Bug](../../issues) · [Request Feature](../../issues)

</div>

---

## ✨ What is Nexus Debugger?

Nexus Debugger is a **free, open-source** code analysis tool that works like a mini VS Code — right inside your browser. Upload your files, get instant bug reports, fix them with one click or with AI assistance.

Built for students, indie developers, and anyone who needs a fast, offline-capable debugger without heavy IDEs.

---

## 🚀 Features

### 🔍 Smart Bug Detection
- **JavaScript** — Real AST parsing via Acorn.js (not just regex!)
- **HTML** — Missing viewport, charset, alt tags, security issues
- **CSS** — Duplicate properties, !important abuse, missing units
- **Python** — Bare except, mutable defaults, eval() warnings
- **JSON** — Syntax validation, Firebase rules exposure detection
- **Firebase** — Missing await, open rules, auth null-check, onSnapshot errors

### ⚡ Auto-Fix Engine
- One-click fixes: `var→let`, `==→===`, `!=→!==`, remove debugger, add `alt=""`, add `rel="noopener"`
- Surgical fixes — only changes what's broken, nothing else

### 🤖 AI Integration
- Works with **Gemini, OpenRouter, Groq, OpenAI**, or any custom API
- AI reads your code + detected issues and suggests precise fixes
- Apply AI fix with one tap — changes only the broken lines
- **Your API key stays on your device** — never sent to any server

### 📊 Health Score System
| Grade | Score | Meaning |
|-------|-------|---------|
| A+ | 95–100 | Production ready |
| A  | 85–94  | Very clean |
| B  | 75–84  | Minor issues |
| C  | 60–74  | Needs attention |
| D  | 45–59  | Many problems |
| F  | 0–44   | Critical issues |

### 🗂️ Multi-File Support
- Upload multiple files or entire folders at once
- Per-file health scores and issue tracking
- Edit code directly in the browser and re-scan instantly

---

## 📱 Screenshots

> *(Screenshots coming soon)*

---

## 🛠️ Usage

### Option 1 — Use Online *(Recommended)*
Open the live link: **[mohammadjaseem444-maker.github.io/Nexus-Debugger](https://mohammadjaseem444-maker.github.io/Nexus-Debugger/)**

### Option 2 — Use Offline
1. Download `index.html`
2. Open it in any browser
3. Done — no setup needed!

### Setting Up AI *(Optional)*
1. Click the ⚙️ settings icon in the AI tab
2. Choose your provider (Gemini, OpenRouter, Groq, etc.)
3. Paste your API key — saved locally on your device only
4. Ask AI to fix any issue directly from the console

**Free API options:**
- [Google Gemini](https://aistudio.google.com) — Free tier available
- [OpenRouter](https://openrouter.ai) — Many free models
- [Groq](https://console.groq.com) — Fast and free tier

---

## 🔒 Privacy

- **Zero telemetry** — No analytics, no tracking
- **No backend** — Everything runs in your browser
- **API keys** — Stored only in your browser's localStorage
- **Your code** — Never leaves your device

---

## 🌍 Supported Languages

| Language | Detection | Auto-Fix | Firebase Checks |
|----------|-----------|----------|-----------------|
| JavaScript | ✅ AST | ✅ | ✅ |
| TypeScript | ✅ | ✅ | ✅ |
| HTML | ✅ | ✅ | ✅ |
| CSS | ✅ | ✅ | ❌ |
| Python | ✅ | ❌ | ❌ |
| JSON | ✅ | ❌ | ✅ |
| JSX / TSX / Vue / Svelte | ✅ | ✅ | ✅ |

---

## 📁 Project Structure

```
Nexus-Debugger/
├── index.html    # The entire app — single file!
├── README.md
└── LICENSE
```

---

## 🤝 Contributing

Contributions are welcome! Single-file project — easy to get started.

1. Fork this repo
2. Edit `index.html` in any editor
3. Test in your browser
4. Submit a Pull Request

**Ideas for contribution:**
- Add more language analyzers (Go, Rust, PHP...)
- Add syntax highlighting in read mode
- Improve auto-fix rules
- Add more Firebase-specific checks

---

## 📄 License

MIT License — free to use, modify, and distribute.  
See [LICENSE](LICENSE) for details.

---

<div align="center">

Built with ❤️ by [Mohammad Jaseem](https://github.com/mohammadjaseem444-maker)

*Free forever. No ads. No tracking. Just code.*

⭐ **Star this repo if it helped you!**

</div>
