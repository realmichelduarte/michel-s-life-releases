# Michel's Life — Windows Releases

Official Windows distribution channel for **Michel's Life**, an RPG-inspired productivity and life-management desktop app.

This repository intentionally contains **release binaries only**. The application source code is maintained separately in a private repository.

## Downloads

Use the **Releases** section to download the latest Windows build.

Each normal release can include:

- `MichelsLife-Setup-vX.Y.Z.exe` — recommended Windows installer
- `MichelsLife-vX.Y.Z.exe` — portable single-file build
- `MichelsLife-vX.Y.Z.exe.sha256` — SHA-256 checksum for the portable build
- `AppBundle.zip` — internal visual/application bundle used to bootstrap the next release
- `michels_life_icon.ico` — release icon asset

## Update channel

Michel's Life checks this public repository for newer official releases. Update downloads are verified against their published SHA-256 checksum before installation.

Before applying an update, Michel's Life creates a restore point of the current local state.

## Source code

Source code, build workflows and development history are not published in this repository.
