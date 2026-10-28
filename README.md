# Pocket LFM — Android Releases

This PUBLIC repository distributes **signed Android APKs only** for Pocket LFM. The app's source code and development history remain in a separate private repository.

## Downloads

When the first stable release is published, it will appear under [Releases](https://github.com/danieleforte92/pocketlfm-releases/releases). Each release will contain:

- `PocketLFM.apk` — production-signed Android APK
- `update.json` — version metadata and file checksum for the in-app Update Manager
- `SHA256SUMS` — download integrity checksum
- release notes

**No stable APK is available until signing is configured and the first release is approved.** Never upload keystores, passwords, private repository tokens, proprietary model files, or source archives here.

## Installation and updates

The stable app is a separate Android package (`dev.pocketlfm.stable`) from existing experimental/debug builds. Keep the old debug app installed while verifying Stable, so its private GGUF and data are preserved. Once Stable is installed, updates signed with the same release key can retain app data.

Pocket LFM performs AI inference locally; only user-requested release checks/downloads use the network. APK installation requires Android user confirmation.
