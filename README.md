<div align="center">

# OOD

**A sleek, modern, and smart OTA firmware downloader for OnePlus devices.**

[![Build and Release](https://github.com/dollbluesvanus0/OnePlus-OTA-Downloader/actions/workflows/release.yml/badge.svg)](https://github.com/dollbluesvanus0/OnePlus-OTA-Downloader/actions/workflows/release.yml)

</div>

---

## ✨ Features

- 🎨 **Premium Dark UI**: Built entirely with Jetpack Compose & Material Design 3, featuring a seamless, immersive dark mode experience.
- 📋 **Smart Clipboard Integration**: Automatically detects and reads supported firmware URLs from your clipboard the moment you open the app.
- ⚡ **Native Download Manager**: Reliable background downloads with real-time progress tracking and error handling.
- 📂 **Downloads History**: Built-in history manager to track, view, and safely delete downloaded firmware files from your device storage with a single tap.
- 🔍 **Smart Parsing**: Automatically extracts and formats firmware names (CPH, RMX, P-series) directly from the download URL. (idk if it works)

## 🚀 Installation

You can download the latest APK from the **[Releases](../../releases)** page, or from the GitHub Actions artifacts if you trigger a manual build.

1. Download the `app-debug.apk` file.
2. Open the file on your Android device.
3. Allow installation from unknown sources if prompted.

## 🛠️ Build from Source

To build the project locally, ensure you have Android Studio installed or the Android SDK with JDK 17.

```bash
# Clone the repository
git clone https://github.com/dollbluesvanus0/OnePlus-OTA-Downloader.git

# Navigate to the project directory
cd OnePlus-OTA-Downloader

# Build the debug APK
./gradlew assembleDebug
```
The compiled APK will be located at `app/build/outputs/apk/debug/app-debug.apk`.

## 📦 CI/CD Automation

This repository includes a fully configured **GitHub Actions** workflow for continuous integration.
- **Manual Builds**: Go to the **Actions** tab -> "Build APK and Release" -> "Run workflow". The compiled APK will be available in the **Artifacts** section at the bottom of the run page.
- **Automated Releases**: Create a new tag starting with `v` (e.g., `git tag v1.0.0`) and push it (`git push origin v1.0.0`). The workflow will automatically build and publish the APK to the GitHub Releases page.

## 📝 Built With

- **Kotlin** - First-class and official programming language for Android development.
- **Jetpack Compose** - Android’s modern toolkit for building native UI.
- **Material 3** - The latest version of Google's open-source design system.
- **Coroutines** - For asynchronous programming.

---
*Built with ❤️ for the Android community.*
