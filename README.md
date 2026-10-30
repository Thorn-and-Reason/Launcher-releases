# Thorn & Reason Launcher

An optional home for Tessera, Consona, Lirensa, and Versena. Install apps, open existing copies, and choose which updates to install. Each app also works independently.

Download the appropriate installer from [Releases](https://github.com/Thorn-and-Reason/Launcher-releases/releases). The launcher also checks for its own updates through **Launcher updates**.

## Current beta: 0.1.1-beta.5

- [Apple Silicon Mac installer](https://github.com/Thorn-and-Reason/Launcher-releases/releases/download/v0.1.1-beta.5/Launcher_0.1.1-beta.5_darwin-aarch64.dmg)
- [Intel Mac installer](https://github.com/Thorn-and-Reason/Launcher-releases/releases/download/v0.1.1-beta.5/Launcher_0.1.1-beta.5_darwin-x86_64.dmg)
- [Windows ARM64 installer](https://github.com/Thorn-and-Reason/Launcher-releases/releases/download/v0.1.1-beta.5/Launcher_0.1.1-beta.5_windows-aarch64.exe)
- [Windows x64 installer](https://github.com/Thorn-and-Reason/Launcher-releases/releases/download/v0.1.1-beta.5/Launcher_0.1.1-beta.5_windows-x86_64.exe)
- [Linux x64 AppImage](https://github.com/Thorn-and-Reason/Launcher-releases/releases/download/v0.1.1-beta.5/Launcher_0.1.1-beta.5_linux-x86_64.AppImage)

The native Windows ARM64 Launcher selects and validates ARM64 app packages. Existing x64 app installations need to be switched to ARM64 separately before this Launcher can manage them. Save work, close the apps, and preserve their data when switching architecture.

[Release notes](https://github.com/Thorn-and-Reason/Launcher-releases/releases/tag/v0.1.1-beta.5) · [Updater checksums](https://github.com/Thorn-and-Reason/Launcher-releases/releases/download/v0.1.1-beta.5/SHA256SUMS) · [Mac installer checksums](https://github.com/Thorn-and-Reason/Launcher-releases/releases/download/v0.1.1-beta.5/INSTALLER-SHA256SUMS)

These are early beta builds. Mac builds use local ad-hoc signing and are not notarised; Windows builds do not have Authenticode signatures. Updater packages have separate cryptographic signatures, which the launcher verifies before installation. Physical Windows and Linux acceptance testing remains outstanding.

This repository contains public installers, checksums, the public update-verification key, and update metadata. Application source and private signing keys are not published here.

Copyright © 2026 Thorn & Reason.
