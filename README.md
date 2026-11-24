# 🎥 Videon — Multi-Platform Social Video & Audio Studio

**Videon** is a fast, modern desktop application for downloading, trimming, and editing video and audio from **YouTube, TikTok/Douyin, Facebook/Reels, Instagram, X/Twitter, Threads, SoundCloud, Bilibili, Vimeo, Reddit, Pinterest**, and 1,000+ other sites. Built on **Tauri v2 + Rust**, Videon runs natively across **Windows, macOS, and Linux** with bundled `yt-dlp` and `ffmpeg` engines.

---

## ✨ Key Features in v3.0.2

- **🎯 Precision Carbon & Safety-Orange UI (`taste-skill`):** Clean 92%+ matte carbon neutral canvas (`#090a0c` / `#111317` / `#16191e`), hairline `1px` borders, unified corner radii (`12/10/8/6px`), natural sentence-case typography, tabular numerals (`tabular-nums`), and a single safety-orange accent (`#ff5518`) — with red (`#ef4444`) strictly reserved for delete/cancel/error actions.
- **🔔 Live Active-Download Notifications:** Real-time active download counter badges at the top-right of **Recent Downloads** and **Downloads Manager**, plus live queue status pills and progress bars.
- **📦 Instant Batch & Playlist Recognition:** Paste a single link, multi-line/space/comma link lists, bare URLs, or full YouTube/Social Playlists for automatic background extraction (with YouTube playlist normalization, Mix loop protection, cookie-lock fallback, and collision-free atomic job IDs).
- **🎬 Frame-Accurate Multi-Hour Quick Editor:** Adaptive NLE timeline ruler (`1s` up to `12h` major intervals) that prevents label crowding on 3h–12h+ videos, sticky track headers with up to `3200%` horizontal zoom, container `start_offset` & fractional duration sync, zero-offset range handles, and `-ss` pre-input + `-avoid_negative_ts make_zero` frame-accurate cuts.
- **⚡ Fast Stream Copy (Instant Original Quality):** Automatically skips unnecessary `ffmpeg` re-encoding when downloading full videos in compatible H.264/MP4 streams with `+faststart` indexing.
- **🌐 Multi-Social Platform Support & 100% Bilingual UI:** Supports YouTube, TikTok/Douyin, Facebook/Reels, Instagram, X/Twitter, Threads, SoundCloud, Bilibili, Vimeo, Reddit, Twitch, and 1,000+ sites with complete **Vietnamese (`vi`)** and **English (`en`)** localization.
- **🔐 Cookie & Anti-Bot Bypass:** Built-in support for browser cookies (`Chrome`, `Edge`, `Brave`, `Firefox`, `Opera`, `Safari`) or custom `cookies.txt` files plus 1-click `yt-dlp` engine auto-update.

---

## 🚀 Installation Guide

Visit the **[Releases](https://github.com/yorupngg-creator/Videon/releases)** page of this repository to download the latest installer for your operating system:

### 1. Windows (`.exe` / `.msi`)
- Download the setup executable (`.exe` or `.msi`).
- Double-click the installer to install and launch **Videon**.

### 2. macOS (`.dmg`)
- Download the `.dmg` file and drag **Videon** into your **Applications** folder.
- **First-time Opening Note:** If macOS displays an unsigned app prompt, right-click (or `Control` + click) **Videon** in *Applications* and select **Open**, or allow it under **System Settings > Privacy & Security > Open Anyway**.

### 3. Linux (`.AppImage` / `.deb`)
- Download the `.AppImage` (make executable with `chmod +x` and run) or install the `.deb` package (`sudo dpkg -i videon_*.deb`).

---

## ☕️ Support the Developer
If Videon helps your workflow, consider supporting the developer:
👉 **[Ko-fi.com/ravenavi](https://ko-fi.com/ravenavi)**

---

## 📄 License
This project is licensed under the GPL-3.0 License.
