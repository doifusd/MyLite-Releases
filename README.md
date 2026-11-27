<div align="center">

<img src="assets/icon.png" alt="MyLite Logo" width="128" height="128" />

# MyLite

**A lightweight, blazing-fast, and modern MySQL desktop client.**

[![Version](https://img.shields.io/badge/version-1.3.19-blue.svg)](https://github.com/doifusd/MyLite-Releases/releases/latest)
[![Platform](https://img.shields.io/badge/platform-macOS%20%7C%20Windows%20%7C%20Linux-lightgrey.svg)](https://github.com/doifusd/MyLite-Releases/releases/latest)
[![License](https://img.shields.io/badge/license-Freeware-green.svg)](#-license)

⚡ **Ultra Lightweight** • 🚀 **High Performance** • 🔒 **Secure Local Storage** • 💻 **Cross-Platform** • 🎨 **Native Experience**

</div>

---

## 📥 Downloads (v1.3.19)

Download the latest release directly from [GitHub Releases](https://github.com/doifusd/MyLite-Releases/releases/latest).

| Operating System | Architecture | Package Format | Download Link |
| :--- | :--- | :--- | :--- |
| **macOS** | Apple Silicon (M1/M2/M3/M4) | `.dmg` | [Download MyLite for macOS (Apple Silicon)](https://github.com/doifusd/MyLite-Releases/releases/download/v1.3.19/MyLite_1.3.19_aarch64.dmg) |
| **Windows** | Windows 10 / 11 (64-bit) | `.msi` | [Download MyLite for Windows (x64)](https://github.com/doifusd/MyLite-Releases/releases/download/v1.3.19/MyLite_1.3.19_x64_en-US.msi) |
| **Linux** | Ubuntu / Debian (64-bit) | `.deb` | [Download MyLite DEB](https://github.com/doifusd/MyLite-Releases/releases/download/v1.3.19/MyLite_1.3.19_amd64.deb) |
| **Linux** | Universal Linux | `.AppImage` | [Download MyLite AppImage](https://github.com/doifusd/MyLite-Releases/releases/download/v1.3.19/MyLite_1.3.19_amd64.AppImage) |

> 💡 All packages and archives can also be found on the [Releases Page](https://github.com/doifusd/MyLite-Releases/releases).

---

### ⚠️ macOS: "App is damaged and can't be opened" Notice

Since MyLite is distributed independently, macOS Gatekeeper may show a warning like *"MyLite is damaged and can't be opened"* on initial launch. This is standard behavior for non-notarized applications.

To allow MyLite to open:
1. Open **Terminal**.
2. Run the following command:
   ```bash
   xattr -cr /Applications/MyLite.app
   ```
3. Open MyLite normally from Applications or Launchpad.

---

## ✨ Key Features

- **🚀 High Performance & Low Memory Footprint**
  - Built with Rust and Tauri for ultra-fast startup and negligible RAM consumption compared to Electron alternatives.
- **🔌 Multi-Mode Connections**
  - Direct TCP connection with SSL/TLS support.
  - SSH tunneling with public-key / password authentication for secure remote server access.
  - Secure local credential storage.
- **📝 Intelligent SQL Editor**
  - Syntax highlighting and intelligent auto-completion for schema, tables, and columns.
  - Multi-tab query sessions with instant keyboard shortcuts (`Cmd/Ctrl + Enter` to run).
  - Query execution history and query favorites.
- **📊 Intuitive Schema & Table Management**
  - Database & table tree view with quick search.
  - Table context menu: Quick Query, Design Table, Show Data, Show DDL, Generate Go Struct, Create Index.
  - Fast table name copying directly from the context menu into queries.
- **📈 Efficient Data Grid**
  - High-performance virtualized result table for browsing large datasets smoothly.
  - Instant column sorting, filtering, and data export.

---

## 📞 Support & Feedback

If you encounter any issues, have questions, or wish to request features:

- 📧 Email: **doifusdsky@gmail.com**
- 🐛 Issues & Bug Reports: [Submit an Issue](https://github.com/doifusd/MyLite-Releases/issues)

---

## 📄 License

MyLite is provided free to use. All rights reserved.
