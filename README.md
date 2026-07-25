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

[What The Token v0.2.33-preview.27 — unsigned Windows preview](https://github.com/CHAKRI-S/WhatTheToken-Releases/releases/tag/v0.2.33-preview.27)

- [Download Setup for Windows x64](https://github.com/CHAKRI-S/WhatTheToken-Releases/releases/download/v0.2.33-preview.27/WhatTheTokenSetup-windows-x64.exe)
- [Download Setup for Windows ARM64](https://github.com/CHAKRI-S/WhatTheToken-Releases/releases/download/v0.2.33-preview.27/WhatTheTokenSetup-windows-arm64.exe)
- [Download portable update for Windows x64](https://github.com/CHAKRI-S/WhatTheToken-Releases/releases/download/v0.2.33-preview.27/WhatTheToken-windows-x64-portable.zip)
- [Download portable update for Windows ARM64](https://github.com/CHAKRI-S/WhatTheToken-Releases/releases/download/v0.2.33-preview.27/WhatTheToken-windows-arm64-portable.zip)
- [Windows SHA-256 checksums](https://github.com/CHAKRI-S/WhatTheToken-Releases/releases/download/v0.2.33-preview.27/SHA256SUMS.windows)

### What's new in v0.2.33-preview.27

- Restores the Claude reset countdown by using another provider-returned usage window when the primary 5-hour window has no reset timestamp.
- Keeps the correct usage-window label when the reset countdown falls back to the weekly window.
- Makes Donate, About and Refresh usage buttons the same size on the Windows dashboard.
- Makes Check for updates and Close buttons the same size in About, including DPI scaling and changing update-status text.

Installed Windows previews use the published static update feed and SHA-256 verified portable package. From v0.2.33-preview.26, open **About → Check for updates** to download v0.2.33-preview.27 and restart into the update.

This Windows preview is unsigned, so Microsoft Defender SmartScreen may show a warning. Verify the published SHA-256 checksum before running a manually downloaded installer.

Windows builds, runtime testing and Windows release assets are maintained from Tik's Windows 11 environment.

## macOS update feed

- [appcast-macos.xml](https://raw.githubusercontent.com/CHAKRI-S/WhatTheToken-Releases/main/appcast-macos.xml)

The Mac update feed is separate from Windows releases. Signed production updates will additionally require Apple Developer ID signing and notarization.

The application source is maintained in a private repository. This repository contains only public release information and downloadable release assets.
