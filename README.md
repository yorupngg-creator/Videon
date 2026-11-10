# 🎥 Videon — Multi-Platform Social Video & Audio Studio

**Videon** is a fast, modern desktop application for downloading, trimming, and editing video and audio from **YouTube, TikTok/Douyin, Facebook/Reels, Instagram, X/Twitter, Threads, SoundCloud, Bilibili, Vimeo, Reddit, Pinterest**, and 1,000+ other sites. Built on **Tauri v2 + Rust**, Videon runs natively across **Windows, macOS, and Linux** with bundled `yt-dlp` and `ffmpeg` engines.

---

## ✨ Key Features in v2.1.4

- **📌 Collapsible Studio Sidebar & UI Refinements:** Smooth 1-click collapsible left navigation dock (`196px` ↔ `58px` icon mode) with persistent state, compact in-card structured timecode pickers (`HH:MM:SS`) without overflow, and strict tab content isolation.
- **🎨 AnimeClips Studio UI Overhaul:** Re-engineered dark interface inspired by `animeclips.online` with Matte Carbon/Obsidian surfaces (`#08080b` / `#0d0d12`), tactile SVG film-grain noise texture (`feTurbulence`), and top ambient cinema glow.
- **📐 100% Full-Height 2-Stage Studio Layout:** Completely eliminated empty bottom gap space with a sleek Left Vertical Studio Sidebar (app logo, vertical navigation capsule, bottom-anchored batch & settings) paired with a responsive 2-stage workspace (Left: Cinema Video Monitor + Trim & Download Deck; Right: Scene Chapters List + Live Recent Downloads Queue).
- **🔤 Studio Typography Suite:** Integrated Google Fonts **Space Grotesk** (geometric display titles, navigation & buttons), **Plus Jakarta Sans** (clean modern UI body), and **JetBrains Mono** (technical badges, timecodes, resolution & file size tags).
- **🌐 Multi-Social Platform Support:** Paste links from YouTube (Videos, Shorts, Playlists), TikTok/Douyin, Facebook/Reels, Instagram, X/Twitter, Threads, SoundCloud, Bilibili, Vimeo, Reddit, Pinterest, Twitch, and more — with automatic platform detection and vertical (`9:16`) / horizontal (`16:9`) resolution recognition up to 4K (`2160p`).
- **⚡ Fast Stream Copy (Instant Original Quality):** Automatically skips unnecessary `ffmpeg` re-encoding when downloading full videos in compatible H.264/MP4 streams, preserving 100% original bitrate and completing in seconds.
- **📦 Batch & Playlist Downloader:** Queue multiple video/audio links or entire playlists at once with selective item picking.
- **🔐 Cookie & Anti-Bot Bypass:** Built-in support for browser cookies (`Chrome`, `Edge`, `Brave`, `Firefox`, `Opera`, `Safari`) or custom `cookies.txt` files to download age-restricted, member-only, or login-protected social media posts, plus 1-click `yt-dlp` engine auto-update.
- **✂️ Smart Trimming & Chapters:** Precisely trim video/audio ranges before downloading or batch-download individual video **Chapters**.
- **🎬 Quick Studio Editor:** Built-in timeline editor with instant trim, toggleable Watermark Logo (`V2`) and Background Music (`A2`) overlay tracks, audio mixing, and `MP4` / `MKV` / `MOV ProRes` / `MP3` export.
- **📂 Upgraded Downloads Manager:** Real-time download speed (`MB/s`), `ETA`, file size, platform & quality badges, instant search, category filter pills, and in-app media preview.
- **🔴 Red-Only Destructive Actions:** Minimalist monochrome design preserving Apple Red strictly for Delete/Trash, Clear, and Error states. Full **Vietnamese (`vi`)** and **English (`en`)** localization.

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
