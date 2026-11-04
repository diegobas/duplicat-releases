<p align="center">
  <img src="https://duplicat.app/icon-256.png" width="88" alt="Duplicat">
</p>

<h1 align="center">Duplicat</h1>

<p align="center">Your iPhone, in a Mac window — and your mouse in it.</p>

<p align="center">
  <a href="https://duplicat.app">duplicat.app</a> ·
  <a href="https://github.com/diegobas/duplicat-releases/releases/latest">Download</a> ·
  <a href="https://duplicat.app/how-to">Setup guide</a> ·
  <a href="https://duplicat.app/es">Español</a>
</p>

Duplicat mirrors an iPhone screen on a Mac over AirPlay and sends mouse clicks, typing and swipes
back through Apple's developer tunnel. Nothing is installed on the phone, and there is no account:
no Apple ID, no sign-in, no server in the middle.

- **Mirroring is free** — no time limit, no watermark, no sign-up.
- **Control is €4.99 once** — clicks become real taps, typing goes in as text, dragging swipes.
  One payment, not a subscription.
- Screenshots at the phone's own resolution, and QuickTime recordings, are part of the free mirror.
- Works offline: the licence is a signed key checked on your Mac, not an activation server.

## Requirements

| | |
|---|---|
| Mac | macOS 14 (Sonoma) or later, Apple silicon |
| iPhone | iOS 17 or later for control; older phones mirror fine |
| Network | Both devices on the same Wi-Fi, Bluetooth on |

For control, iOS needs **Developer Mode** switched on once — Settings → Privacy & Security →
Developer Mode, then a restart and a second confirmation. That is Apple's rule for synthetic
touches, not Duplicat's; the [setup guide](https://duplicat.app/how-to) walks through it, and so
does the [Spanish guide](https://duplicat.app/es/como-usar).

## Install

1. Download `Duplicat-0.1.1-macOS-arm64.zip` from the
   [latest release](https://github.com/diegobas/duplicat-releases/releases/latest) and drag
   `Duplicat.app` into Applications.
2. Open it once. The app is signed outside the App Store, so macOS is cautious the first time:
   **System Settings → Privacy & Security → Open Anyway**.
3. Press Start in Duplicat, then choose **Duplicat** in iPhone Control Center → Screen Mirroring.

## What it does not do

No audio. DRM video (Netflix, the Apple TV app) shows a black frame, because AirPlay receivers are
not licensed to decrypt it. The phone has to stay unlocked while you mirror. One finger only —
pinch-to-zoom is not wired up yet.

## Licence

€4.99 once, for the Macs you use. Bought at [duplicat.app](https://duplicat.app/#buy); the key
arrives by email and is verified offline. Lost it? [Recover it](https://duplicat.app/recover).

## Why this repository

Builds only. This is where the download lives, so the store page has a stable URL to point at and
each build has a permanent, checksummable home.
