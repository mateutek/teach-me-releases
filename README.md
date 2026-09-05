# Teach Me releases

Teach Me is a desktop app that turns a folder into a self-paced course taught by an AI agent (Claude Code, Copilot CLI, opencode, or an API key). This repo only holds the built releases; the source lives in a private repo.

## Download

**[Latest release](https://github.com/mateutek/teach-me-releases/releases/latest)**

| Platform | File to download |
|---|---|
| macOS, Apple Silicon | `Teach-Me_<version>_aarch64.dmg` |
| macOS, Intel | `Teach-Me_<version>_x64.dmg` |
| Windows | `Teach-Me_<version>_x64-setup.exe` |

Once installed, the app updates itself.

The builds are signed for update verification but not notarized or Authenticode-signed. On first launch macOS shows an unverified-developer dialog: open it once, then allow it under System Settings > Privacy & Security > Open Anyway. If macOS calls the app damaged, run `xattr -cr "/Applications/Teach Me.app"` and open it again. Windows SmartScreen warns as well: More info, then Run anyway.

The `*.app.tar.gz`, `*.sig` and `latest.json` files on each release are consumed by the in-app updater.
