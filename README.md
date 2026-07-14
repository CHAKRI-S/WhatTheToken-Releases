# What The Token — Downloads

Official public downloads for **What The Token**.

> Know before you hit it.

## Latest macOS release

[What The Token 0.2.31 — macOS Unsigned Preview](https://github.com/CHAKRI-S/WhatTheToken-Releases/releases/tag/v0.2.31-macos-preview.1)

- [Download WhatTheToken-0.2.31.dmg](https://github.com/CHAKRI-S/WhatTheToken-Releases/releases/download/v0.2.31-macos-preview.1/WhatTheToken-0.2.31.dmg)
- [macOS SHA-256 checksum](https://github.com/CHAKRI-S/WhatTheToken-Releases/releases/download/v0.2.31-macos-preview.1/SHA256SUMS.macos)

Version 0.2.31 derives Codex labels from the real provider window, prevents a weekly reset from being paired with `5h`, and publishes an EdDSA-signed Mac-only Sparkle update.

This preview is not Apple Developer ID signed or notarized. Verify the checksum, then Control-click the installed app and choose **Open**. If macOS blocks it, use **System Settings → Privacy & Security → Open Anyway** only after verifying the checksum.

Version 0.2.30 and later contain the Mac-only Sparkle feed URL and matching public key. The signed feed can discover and download 0.2.31 automatically. Builds older than 0.2.30 use an obsolete feed and must be upgraded manually once.

## Latest Windows release

[What The Token v0.2.29-preview.1 — unsigned Windows installer preview](https://github.com/CHAKRI-S/WhatTheToken-Releases/releases/tag/v0.2.29-preview.1)

Windows builds, runtime testing and Windows release assets are maintained from Tik's Windows 11 environment.

## macOS update feed

- [appcast-macos.xml](https://raw.githubusercontent.com/CHAKRI-S/WhatTheToken-Releases/main/appcast-macos.xml)

The Mac update feed is separate from Windows releases. Signed production updates will additionally require Apple Developer ID signing and notarization.

The application source is maintained in a private repository. This repository contains only public release information and downloadable release assets.
