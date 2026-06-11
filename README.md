# TenSeiBotHost

<p align="center">
  <img src="https://raw.githubusercontent.com/github/explore/main/topics/android/android.png" width="120" alt="Android"/>
</p>

<p align="center">
  Android application for hosting and running Telegram bots directly on your device using an embedded Python runtime.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-Android-2ea44f?style=for-the-badge">
  <img src="https://img.shields.io/badge/runtime-Python-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/status-active-black?style=for-the-badge">
</p>

---

## Overview

TenSeiBotHost is an Android application designed to host and execute Python-based Telegram bots directly from an Android device without requiring a separate VPS or Linux server.

The application includes:

- Embedded Python runtime support
- Foreground execution service
- Runtime bootstrap system
- Live process logging
- Automatic restart handling
- Persistent background execution

The project focuses on portability, lightweight execution, and running Telegram bots directly on-device.

---

## Features

- Run Telegram bots directly on Android
- Embedded Python runtime
- Foreground service execution
- Automatic boot startup support
- Live runtime console logs
- Background execution handling
- Lightweight UI
- Minimal resource usage
- APK-based deployment

---

## How It Works

1. Select your `app.py`
2. Select your `requirements.txt`
3. Press the `START` button
4. The application installs dependencies and launches the bot runtime automatically

Once started, the bot continues running in the background using Android foreground services.

The bot remains active until:
- the device shuts down
- internet connection is lost
- the app is force stopped
- battery restrictions terminate the process

---

## Installation

1. Download the latest APK from the Releases section
2. Install the APK on your Android device
3. Grant all required permissions
4. Disable battery optimization for stable background execution
5. Launch the app and configure your bot files

---

## Requirements

| Component | Requirement |
|---|---|
| Android Version | Android 8+ |
| Architecture | arm64-v8a |
| Permissions | Storage, Notifications, Internet |
| Internet | Required |

---

## Runtime Notes

Some Android OEMs aggressively terminate background services.

For proper execution:

- Disable battery optimization
- Allow auto-start permission
- Lock the app in recent tasks if supported by your ROM

---

## Screenshots

<p align="center">
  Add screenshots here
</p>

---

## Releases

Stable APK builds are available in the Releases section.

Naming format:

```text
TenSeiBotHost-v1.0.apk
