# Thorn & Reason Launcher

An optional home for Tessera, Consona, Lirensa, Versena, and Noema. Install apps, open existing copies, and choose which updates to install. Each app also works independently.

Download the appropriate installer from [Releases](https://github.com/Thorn-and-Reason/Launcher-releases/releases). The launcher also checks for its own updates through **Launcher updates**.

## Current beta: 0.1.1-beta.9

- [Apple Silicon Mac installer](https://github.com/Thorn-and-Reason/Launcher-releases/releases/download/v0.1.1-beta.9/Launcher_0.1.1-beta.9_darwin-aarch64.dmg)
- [Intel Mac installer](https://github.com/Thorn-and-Reason/Launcher-releases/releases/download/v0.1.1-beta.9/Launcher_0.1.1-beta.9_darwin-x86_64.dmg)
- [Windows ARM64 installer](https://github.com/Thorn-and-Reason/Launcher-releases/releases/download/v0.1.1-beta.9/Launcher_0.1.1-beta.9_windows-aarch64.exe)
- [Windows x64 installer](https://github.com/Thorn-and-Reason/Launcher-releases/releases/download/v0.1.1-beta.9/Launcher_0.1.1-beta.9_windows-x86_64.exe)
- [Linux x64 AppImage](https://github.com/Thorn-and-Reason/Launcher-releases/releases/download/v0.1.1-beta.9/Launcher_0.1.1-beta.9_linux-x86_64.AppImage)

On Linux, this version launches managed apps without requiring a FUSE mount and installs their menu icons. To start the Launcher itself without FUSE, allow the downloaded AppImage to execute and run `APPIMAGE_EXTRACT_AND_RUN=1 ./Launcher_0.1.1-beta.9_linux-x86_64.AppImage`. Temporary storage and the download location must allow execution. Physical Fedora hardware and SELinux acceptance remain unverified.

The native Windows ARM64 Launcher selects and validates ARM64 app packages. Existing x64 app installations need to be switched to ARM64 separately before this Launcher can manage them. Save work, close the apps, and preserve their data when switching architecture.

[Release notes](https://github.com/Thorn-and-Reason/Launcher-releases/releases/tag/v0.1.1-beta.9) · [Checksums](https://github.com/Thorn-and-Reason/Launcher-releases/releases/download/v0.1.1-beta.9/SHA256SUMS.txt)

These are early beta builds. Mac builds use local ad-hoc signing and are not notarised; Windows builds do not have Authenticode signatures. Updater packages have separate cryptographic signatures, which the launcher verifies before installation. Physical Windows and Linux acceptance testing remains outstanding.

This repository contains public installers, checksums, the public update-verification key, and update metadata. Application source and private signing keys are not published here.

Copyright © 2026 Thorn & Reason.
