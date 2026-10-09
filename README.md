# easycliproxyapi-bin (AUR)

[![Auto Update AUR Package](https://github.com/moliyu/easycliproxyapi-bin/actions/workflows/update.yml/badge.svg)](https://github.com/moliyu/easycliproxyapi-bin/actions/workflows/update.yml)

This repository automatically maintains and synchronizes the Arch User Repository (AUR) package [easycliproxyapi-bin](https://aur.archlinux.org/packages/easycliproxyapi-bin) with the latest releases from [router-for-me/EasyCLIProxyAPI](https://github.com/router-for-me/EasyCLIProxyAPI).

## Features

- **Automated AUR Sync**: A GitHub Action checks for upstream releases every 3 hours and updates `PKGBUILD`, checksums, and `.SRCINFO` automatically.
- **In-App Update Friendly**: The launcher script `easycliproxyapi.sh` includes intelligent version comparison to prevent in-app portable updates from being downgraded.

## Manual Trigger

You can manually trigger the update workflow from the **Actions** tab in GitHub or using GitHub CLI:

```bash
gh workflow run update.yml --repo moliyu/easycliproxyapi-bin
```
