<p align="center"><img src="assets/apphub.png" width="112" height="112" alt="AppHub icon"></p>

# AppHub

A desktop library for finding GitHub projects, downloading releases, and cloning repositories.

This is AppHub's official public repository for downloads and release notes.

## Downloads

AppHub 0.2.0 is being prepared for Mac, Windows, and Linux. No public installer has been published yet.

Approved downloads will appear on the [Releases page](https://github.com/DestroyerMob/AppHub/releases). Choose a DMG for Apple Silicon or Intel Macs (macOS 13+), the Windows x64 installer, or the Linux x64 AppImage. Linux builds target Ubuntu 22.04 or newer and need an unlocked desktop keyring for sign-in.

The Windows installer and Linux AppImage are also used for in-app updates. Mac `.app.tar.gz` files and `latest.json` support the updater; use a DMG for a first Mac installation. Checksums cover every download. AppHub 0.1.1 users need one manual upgrade to 0.2.0 before in-app updates are available.

## What AppHub does

- Search GitHub repositories and browse projects with published releases as apps.
- Download release files or source archives and clone repositories without installing Git.
- Access public, private, and organisation repositories available to your GitHub account.
- Track transfers and customise theme, accent colour, density, and sidebar layout.
- Check for verified AppHub updates in Settings, with optional automatic checks.

Choose **Connect GitHub** in the app, sign in on GitHub, enter the displayed one-time code, and approve access. Users do not need to register an OAuth App or enter a client ID.

GitHub's repository permission includes write access. AppHub uses it to browse, download, and clone; it does not offer repository editing. Organisation approval and SSO restrictions still apply.

## Account data

AppHub connects directly to GitHub. Credentials are stored in macOS Keychain, Windows Credential Manager, or Linux Secret Service. Preferences and transfer history stay on your computer.

## Feedback

Report problems or suggest features through [Issues](https://github.com/DestroyerMob/AppHub/issues). Include the app version, operating system, architecture, and steps to reproduce. Keep access tokens, private repository contents, and personal information out of public reports.

AppHub was previously named Harbor. Application source is maintained separately from this download repository.
