# Extended Graphics Options (EGO) — FM27

EGO extends the native Football Manager 27 graphics preferences with advanced graphics and performance controls. This repository contains **binary releases only**, not source code or game files.

## Installation

1. Exit Football Manager 27.
2. Install a compatible BepInEx IL2CPP loader if not already installed.
3. Download the ZIP from the [latest release](https://github.com/allcyber815/EGO-FM27/releases/latest) and extract it into the game directory.
4. Start FM normally. Read INSTALL.txt in the ZIP for migration and rollback instructions.

The first release is audited for Windows x64, FM 27.1.1+2511875 (Steam build 26797085) and BepInEx 6.0.0-be.793.

## Updates

The EGO updater checks once during BepInEx startup, before the main mod loads. It verifies the ECDSA P-256 signature of update.json, the DLL's exact size and SHA-256, and supported game/loader fingerprints. No periodic network checks during gameplay. The installed DLL stays unchanged when a check fails. Update options and rollback are available in EGO's Mod settings.

[Download releases](https://github.com/allcyber815/EGO-FM27/releases) · [Latest signed manifest](https://github.com/allcyber815/EGO-FM27/releases/latest/download/update.json)

EGO is an unofficial mod and is not affiliated with Sports Interactive or SEGA.
