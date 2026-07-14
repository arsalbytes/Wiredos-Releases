<div align="center">
  <img src="frontend/src/assets/images/icon.png" width="120" alt="Wiredos Logo" />
  <h1>Wiredos</h1>
  <p><strong>The ultimate, lightning-fast iOS to PC file transfer and backup utility.</strong></p>
</div>

<hr />

## 🚀 Overview

**Wiredos** (formerly i-to-pc) is a modern, native Windows application built to seamlessly bridge the gap between your iPhone and your PC. Without requiring iTunes or any third-party app installations on your iOS device, Wiredos allows you to effortlessly view, manage, and back up your photos, videos, and albums.

Built with **Wails (Go + React + TypeScript)**, it offers a blazing fast backend with a beautiful, frameless, and fully responsive frontend.

## ✨ Key Features

- **📱 No App Required on Phone:** Connect your iPhone via USB and access your media instantly. No companion apps needed.
- **🖼️ Smart Media Gallery:** Browse your photos and videos with high-quality generated thumbnails directly on your PC before transferring.
- **📦 1-Click Full Backup:** Automatically scans your iPhone albums and backs up everything with a single click.
- **🎨 Beautiful UI & Theming:** Enjoy a stunning, frameless design with built-in Light and Dark modes.
- **⚡ Native Performance:** Powered by Golang for system-level USB interactions (via go-ios) ensuring maximum transfer speeds.
- **🔄 Auto Updates:** Built-in OTA updater that automatically checks GitHub releases to keep you on the latest version.

## 🛠️ Technology Stack

- **Backend:** Go (Golang), Wails v2, SQLite
- **Frontend:** React 18, TypeScript, Tailwind CSS, Lucide Icons
- **iOS Protocol:** go-ios (Reverse engineered AFC and lockdown protocols)

## 📦 Installation

1. Download the latest `Wiredos.exe` from the [Releases](https://github.com/arsalbytes/Wiredos/releases) page.
2. Run the executable.
3. Connect your iPhone via USB (make sure to tap "Trust This Computer" on your phone if prompted).
4. Start transferring!

## 💻 Development

To run the project in development mode:

```bash
# Install dependencies
go mod tidy
cd frontend && npm install

# Run Wails Dev Server
wails dev
```

To build for production:

```bash
wails build
```

## 📝 License
Created by [Arsal Bytes](https://arsalbytes.com/). All rights reserved.
