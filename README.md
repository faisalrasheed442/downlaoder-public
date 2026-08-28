# Downloader Pro — Free Multi-Connection Download Manager (Windows, Linux)

**Downloader Pro** is a fast, free desktop **download manager** built around one
promise: **downloads that never die.** Pause it, close the app, reboot, come back
tomorrow — it picks up exactly where it left off.

Two engines live under one managed queue:

| Engine | What it does |
|---|---|
| **Segmented HTTP downloader** | Splits a file across up to **32 parallel connections** for maximum throughput |
| **Video & audio grabber** | Pulls clean MP4s from video sites across the web, with quality selection |

One list, one set of controls, whatever the source.

---

## Key features

- **Rock-solid pause / resume** — works for *every* engine, including **resume
  after closing the app**. Segments are journaled to an atomic `.meta` sidecar,
  so a restart continues from the exact byte it stopped at.
- **A real queue** — a max-simultaneous-downloads limit, per-download scheduled
  start times, and priorities that behave predictably.
- **Categories** — finished files are auto-classified (Video, Music, Documents,
  Programs, Compressed) and optionally sorted into matching folders.
- **Clipboard capture** — copy a link anywhere and Downloader Pro offers to grab
  it instantly.
- **Drag files straight out** — drop a finished download onto a player, an editor
  or another folder. Files are always copied, never moved.
- **Stays out of your way** — lives in the system tray with desktop
  notifications, and bootstraps its own FFmpeg and dependencies on first run.
  Nothing to configure.
- **Free, with nothing held back** — no ads inside the app, no account, no paid
  tier, no telemetry.

---

## Download & install

Everything is on the **[Releases](../../releases)** page.

| Download | Platform |
|---|---|
| `DownloaderProSetup.exe` | **Windows** — run the installer |
| `DownloaderPro-x86_64.AppImage` | **Linux** (x86_64) — `chmod +x` it, then run it |

> **macOS:** there is no current `.dmg` build. The macOS build is paused, not
> cancelled — when it returns it will appear on the Releases page like any other
> asset. Said plainly here so nobody downloads the repo hoping to find one.

---

## Step 2 (optional): the browser extension

`extension.zip` on the Releases page adds a "send to Downloader Pro" action to
your browser, so links go straight into the queue instead of through the
clipboard.

> ⚠️ **The extension requires the Downloader Pro desktop app.** It is a companion
> to the app, never a replacement for it. On its own it does nothing — install
> the desktop app first, then add the extension if you want it.

---

## FAQ

**What does it cost?**
Nothing. It is free, and it stays free.

**Does it need an account?**
No. There is no sign-up, no login and no licence key.

**Does it phone home?**
No telemetry and no analytics. It reaches the internet to download what you
asked it to download, and to fetch FFmpeg on first run.

**Will it resume a download after I close the app?**
Yes — that is the headline feature. Progress is journaled to disk as it goes,
so closing the app, or losing power, costs you the current segment at worst.

**Which sites does the video grabber work with?**
Video sites across the web, with quality selection. Use it responsibly and
download only content you are licensed to download.

**Is it open source?**
This repository publishes the builds. The application source is not currently
published here.

---

## Support this project

Downloader Pro is built by one person, in the evenings. The running costs are a
server, a domain and a lot of those evenings.

If it saved you time, you can chip in:

### ❤️ [patreon.com/zylio](https://www.patreon.com/zylio)

**Nothing is locked behind it.** Every feature stays available to everyone,
whether or not anybody ever contributes. There will not be a supporters-only
build.

---

**Keywords:** download manager, free download manager, multi-connection
downloader, segmented downloading, parallel downloads, resume downloads, pause
and resume, download accelerator, video downloader, audio downloader, download
queue, download scheduler, clipboard link capture, Windows download manager,
Linux download manager, AppImage, no ads, no telemetry, free software.

---

Built by **[zylio](https://zylio.net)** — an independent software studio building
fast, honest tools for power users and gamers.

**Product page:** [zylio.net/software/downloader-pro](https://zylio.net/software/downloader-pro)

© 2026 zylio. All rights reserved.
