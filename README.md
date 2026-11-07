# Matte Releases

This public repository contains signed installers and update metadata for **Matte**, a local-first screenshot studio. Source code and issue tracking live in the private application repository.

## Install

macOS and Linux can install from the terminal:

```bash
curl -fsSL https://github.com/CyKrome-Nexus/Matte-Release/releases/latest/download/install.sh | bash
```

The macOS installer extracts the `.app.tar.gz` into `/Applications` and removes Gatekeeper quarantine attributes. The Linux installer installs the AppImage under `~/.local/share/Matte`, creates a desktop entry, and links `matte` into `~/.local/bin`.

## Downloads

Download the newest stable build from [Releases](https://github.com/CyKrome-Nexus/Matte-Release/releases/latest).

| Platform | Installer |
| --- | --- |
| macOS (Apple Silicon) | `.dmg` — `aarch64` |
| macOS (Intel) | `.dmg` — `x64` |
| Windows | `.msi` or `-setup.exe` |
| Linux | `.AppImage`, `.deb`, or `.rpm` |

On macOS, Matte needs Screen Recording permission to capture. Linux capture requires `gnome-screenshot`.

Installed copies verify every self-update against the signing key embedded in the application. This repository intentionally contains release assets only.
