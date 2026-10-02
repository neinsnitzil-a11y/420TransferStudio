# 🚀 420 Transfer Studio v9.10.6 — All-in-One Download & Network Toolkit

**420 Transfer Studio** is a Windows desktop application that brings torrent downloading, Telegram media management, web scraping, Tor networking, archive compression, and remote PC connectivity together in one interface.

Built around a customizable command-center design, Studio provides a unified workspace for managing downloads, exploring websites, handling archives, and accessing remote systems.

## ✨ Features

### 🧲 Torrent & Magnet Downloader
- Support for magnet links and `.torrent` files.
- Powered by the aria2 download engine.
- Download management and engine diagnostics.

### 📱 Telegram Downloader
- Integrated Telegram workspace.
- Channel and media download tools.
- Download management within the main application.

### 🌐 Advanced Web Spider
- Automated website crawling and link extraction.
- Chromium-powered page rendering.
- JavaScript-aware website discovery.
- Configurable crawling limits and robots.txt handling.

### 🧅 Tor Workspace
- Tor Expert Bundle integration.
- Start and stop Tor directly from Studio.
- Tor-routed page reading and link crawling.
- Experimental interactive Chromium-based browser.
- Support for accessing `.onion` addresses through Tor.

### 🗜️ .420 Compression & Archive Tools
- Custom `.420` archive format.
- File compression and extraction.
- Additional archive-format utilities.

### 🖥️ Remote PC Manager
- Save remote computer connection profiles.
- Configure hostnames, IP addresses, and RDP ports.
- Launch authenticated Windows Remote Desktop sessions.
- Connection diagnostics.

### 🔄 GitHub Update Manager
- Check a configured GitHub repository for new releases.
- Download available installers.
- Verify updates using SHA-256 checksums.
- Launch an update installer after user confirmation.

### 🎨 Customizable Interface
- Dark command-center layout.
- Multiple appearance themes.
- Custom application and installer icon support.

## 🛠️ What's New in v9.10.6

This release focuses on improving the Windows installer build process.

- **Manual Tor Expert Bundle selection:** Supply an existing `.tar.gz` archive instead of relying on automatic downloads.
- **Restricted-network support:** Useful for environments where direct downloads are blocked or unreliable.
- **Download progress indicators:** Display transfer size, speed, percentage, and ETA when available.
- **Improved aria2 packaging:** Validate the torrent engine before building.
- **Tor archive validation:** Reject incomplete or corrupted bundles.
- **Windows installer integration:** Package the application and its dependencies into a distributable setup executable.
- **Custom icon support:** Apply your selected icon to the application and installer.

## 📦 Installation

1. Download the Windows setup executable from the **Assets** section below.
2. Run the installer.
3. Follow the installation wizard.
4. Launch **420 Transfer Studio** from your desktop or Start Menu.

**Requirements:** Windows 10/11, 64-bit. Internet access is required for online features. Some functionality requires external accounts, accessible services, or additional configuration.

## ⚠️ Important Notes

The embedded Tor browser is experimental and does not provide the same privacy protections as the official Tor Browser. CAPTCHA challenges may require manual interaction. Remote PC management uses Windows Remote Desktop and requires authorized access to the destination computer.

Features involving external services depend on network availability and service compatibility.

---

**420 Transfer Studio — One workspace. Multiple tools. Full control.**

*Version 9.10.6 | Windows Desktop Release*
