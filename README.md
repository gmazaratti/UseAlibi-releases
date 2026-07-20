<div align="center">

<img src="assets/logo.png" width="120" alt="UseAlibi"/>

# UseAlibi

### Simulate your iPhone's GPS location over USB — a clean, native desktop app.

[![Latest release](https://img.shields.io/github/v/release/gmazaratti/UseAlibi-releases?label=download&color=d8528f)](https://github.com/gmazaratti/UseAlibi-releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/gmazaratti/UseAlibi-releases/total?color=d8528f)](https://github.com/gmazaratti/UseAlibi-releases/releases)
![Platform](https://img.shields.io/badge/platform-Windows-2a2c34)
![iOS](https://img.shields.io/badge/iOS-17%20and%20later-2a2c34)

**[⬇️  Download the latest release](https://github.com/gmazaratti/UseAlibi-releases/releases/latest)**

</div>

---

Drop yourself anywhere on a map, or plan a full multi-stop trip and *drive* it in
real time — with speed control, red lights, and realistic braking. UseAlibi is
built on **Apple's own developer location-simulation service**, so there's no
jailbreak and no modified apps: it's the same thing Xcode's *Debug → Simulate
Location* does, wrapped in a fast, native desktop app.

> **Intended use.** UseAlibi is developer / QA / privacy tooling for a device
> **you own and have unlocked and trusted over USB**. The simulated location only
> applies while the device is tethered. Don't use it to deceive people or
> services, defeat fraud / anti-cheat systems, or misrepresent your whereabouts
> to anyone relying on that data — and follow the terms of any app you point it
> at, plus your local laws.

## ✨ Features

- **Place mode** — click or search anywhere to set your location instantly, with
  an optional confirm step.
- **Trip mode** — chain a start → stops → destination, each a searchable field
  with its own dwell time. Routes snap to real roads and show a **live ETA**.
- **Realistic driving** — floor it on straightaways, brake before turns, pause at
  **red lights** — or just set a fixed speed from a walk to a highway.
- **Playback controls** — pause, change speed live, reverse, and one-tap **return
  to start**.
- **Draw or snap** — let routes follow the roads, or draw a straight path yourself.
- **Beautiful map** — dark themed, standard, or **satellite**, in 2D or tilted 3D
  with buildings; **saved places** drop pins you can jump back to.
- **Tracking mode** keeps your location centered as it moves, and a **pop-out
  miniplayer** stays on top so you can watch a trip from anywhere on screen.
- **Guided first-run setup** that checks each step for you, and **automatic
  update** notifications.

## ⬇️ Install

1. **[Download the latest `UseAlibi-Setup.exe`](https://github.com/gmazaratti/UseAlibi-releases/releases/latest)** and run it. Approve the admin prompt (the iOS 17+ tunnel needs it).
2. Install the free **Apple Devices** app from the Microsoft Store — the in-app
   setup guide links you straight to it. It provides the USB service the app needs.
3. On your iPhone: unlock, tap **Trust**, and turn on **Developer Mode** the first
   time. The setup guide walks you through each step and confirms when it's done.

Works with **iOS 17 and later** — including the newest **iOS 26**. It uses the
modern CoreDevice path that's shared across every current iOS version, so new
releases work without an update. Validated on iOS 18; Windows 10/11.

## 🧩 How it works

```
 Native window  ──►  local app  ──USB / lockdown──►  CoreDevice tunnel  ──►  iPhone
```

Everything runs locally on your machine and talks to the phone through the modern
iOS 17+ CoreDevice tunnel. **Your location never leaves your computer** — it goes
straight from the app to the tethered phone.

## 📄 License

UseAlibi is proprietary software. © 2026. All rights reserved. This repository
hosts the distributable binaries and the update manifest only; the source code is
maintained privately. The packaged app includes third-party open-source
components under their respective licenses.

<div align="center">

**[Releases](https://github.com/gmazaratti/UseAlibi-releases/releases)** · Made for iPhone on Windows

</div>
