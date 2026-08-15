# GlowieXRiftbound

Private **update channel** for the GlowieXRiftbound desktop app.

This repository does **not** contain application source. GitHub Releases hold the install zips the in-app updater downloads.

## Asset names

| Platform | File |
|---|---|
| Windows | `RiftboundRaffle-windows.zip` |
| macOS Apple Silicon | `RiftboundRaffle-macos-arm64.zip` |
| macOS Intel | `RiftboundRaffle-macos-x64.zip` |

Publish from the app tree:

- Windows: `.\build\publish-github.ps1`
- macOS: `./build/publish-github.sh /path/to/RiftboundRaffle.app`

Tag format: `vMAJOR.MINOR.PATCH` matching `src/version.py`.
