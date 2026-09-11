# Yappr — releases

Downloads and update manifests for **Yappr**, push-to-talk dictation for macOS.

This repository holds no source code. It exists so that downloads and automatic
updates have a public home.

**Download the latest version:**

https://github.com/noanborel-dev/yappr-releases/releases/latest/download/Yappr-arm64.dmg

That link always serves the most recent release.

Each release carries three files:

| File | What it is for |
|---|---|
| `Yappr-arm64.dmg` | Installing Yappr for the first time |
| `Yappr-<version>-arm64-mac.zip` | Automatic updates — fetched by the app, not by you |
| `latest-mac.yml` | The manifest the updater reads to notice a new version exists |

Apple Silicon only. Every build is signed and notarized by Apple.
