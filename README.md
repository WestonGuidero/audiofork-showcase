<div align="center">

<img src="https://github.com/user-attachments/assets/906a25b3-2f79-4a07-b76d-725224cfa671" alt="AudioFork app screenshot" width="820" />

# AudioFork

**Version history, backup, and safe restore for your DAW.**

[west-audio.com/audiofork](https://west-audio.com/audiofork) · 14-day free trial · $99 one-time license

</div>

---

## What it is

AudioFork quietly keeps every save of your DAW project: Ableton, Reaper, FL Studio, Logic, and more. It shows exactly what changed between any two saves in plain English (tempo, tracks, devices, plugins, clips, mixer moves) and brings back any version in one click, without ever overwriting your current project file.

No exporting. No "Save As" discipline. No cloud lock-in. Just save like you always do, and AudioFork does the rest quietly from the system tray.

> Friends who code keep asking: "so this is basically Git, but for DAWs and audio?" Yep — and it goes back forever: every snapshot, every change, from any DAW.

## Features

| | |
|---|---|
| **Automatic snapshots** | Every save becomes a permanent version. No exporting, no manual discipline required. |
| **Semantic diff** | Tempo, tracks, devices, plugins, clips, mixer moves — see exactly what changed between any two saves, in plain English. |
| **Safe restore** | Bring any version back as a new timestamped copy. Your current project file is never touched. |
| **Storage that disappears** | Content-addressed and zstd-compressed. Identical saves cost zero bytes; a year of versions fits in a pocket of disk. |
| **Private by architecture** | Sessions never leave your machine — no telemetry, no cloud analysis. The only things that ever talk to a server are license activation and optional Cloud Backup. |
| **Label the keepers** | Name a version ("before label feedback," "the good bass take") and find it later by name, not by squinting at timestamps. |

## How it works

1. **Point it at your projects** — pick any DAW's projects folder. AudioFork scans what's there and starts watching from the system tray.
2. **Make music** — save like you always do. AudioFork captures each version in the background; your DAW never knows it's there.
3. **Travel back in time** — "what changed?" shows the story of your session. One click restores the version that had it.

## Tech stack

Built in **Rust** (core version-control engine and diffing), with a **TypeScript/JavaScript** desktop app shell and companion web tooling for license delivery and optional Cloud Backup.

## About this repository

AudioFork's product code is closed-source while it's an actively sold, paid application. This repository exists to walk through the product, architecture, and design decisions behind it.

- 🎧 Live product & purchase: **[west-audio.com/audiofork](https://west-audio.com/audiofork)**
- 🗂️ Development workflow / roadmap: see the **Projects** tab on this repo
- 👤 Built by **[Weston Guidero](https://github.com/WestonGuidero)** — [west-audio.com](https://west-audio.com) · [LinkedIn](https://linkedin.com/in/weston-guidero)
