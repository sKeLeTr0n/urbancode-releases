# UrbanCode beta downloads

Official Windows and macOS installers for UrbanCode Agent Workspace. The application source is maintained separately.

The first public beta is being prepared. Installers will appear in [Releases](https://github.com/sKeLeTr0n/urbancode-releases/releases) after package verification.

## Install

- **Windows x64:** download the `.exe` installer. WebView2 is installed automatically if needed.
- **Mac with Apple Silicon:** download the `darwin-aarch64.dmg`.
- **Intel Mac:** download the `darwin-x86_64.dmg`.

For Mac, open the disk image and drag UrbanCode to Applications.

Before upgrading, save your work and close UrbanCode and its coding sessions. Install the newer version over the existing app; do not delete application data.

Every public beta includes SHA256 checksums, updater signatures, Windows code signing, and Apple notarization. Signing identifies the publisher; Windows may still show a reputation warning for a new app.

## Feedback and security

Use Issues for reproducible beta bugs. Do not post credentials, private source code, or sensitive logs. For security issues, use the repository's private vulnerability reporting feature.

The `channels/beta.json` feed identifies the current beta, including all three installer links. Releases are marked as prereleases; GitHub's `/releases/latest` is not used.
