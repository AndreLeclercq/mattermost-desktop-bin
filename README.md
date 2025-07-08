# mattermost-desktop-bin

AUR package for Mattermost Desktop (precompiled binary) with automated updates.

## Installation

```bash
# Using an AUR helper (e.g., paru)
paru -S mattermost-desktop-bin

# Or manually
git clone https://aur.archlinux.org/mattermost-desktop-bin.git
cd mattermost-desktop-bin
makepkg -si
```

## Features

- Precompiled binary (no Electron dependency needed)
- Automated daily version checks
- Auto-updates to AUR when new releases are available

## Package Info

- **Source**: Official Mattermost Desktop releases
- **License**: Apache-2.0
- **Architecture**: x86_64 only
- **Upstream**: https://github.com/mattermost/desktop

## Automation

This repository automatically:
1. Checks for new Mattermost Desktop releases daily
2. Updates the PKGBUILD with new version and SHA256
3. Pushes updates to the AUR

No manual intervention required for version updates.

## Links

- [AUR Package](https://aur.archlinux.org/packages/mattermost-desktop-bin)
- [Mattermost Desktop](https://github.com/mattermost/desktop)
- [Official Website](https://mattermost.com/)
