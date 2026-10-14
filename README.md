# Surco releases

Public downloads and update feed for [Surco](https://getsurco.app/en), the open-source track organizer for DJs. The source code lives in [surco-app/surco](https://github.com/surco-app/surco).

También en español: [getsurco.app](https://getsurco.app/).

## Download

Get the [latest release](https://github.com/surco-app/surco-releases/releases/latest) and pick the file for your computer:

| System | File |
|---|---|
| macOS, Apple Silicon (M1 and later) | `Surco-<version>-arm64.dmg` |
| macOS, Intel | `Surco-<version>-x64.dmg` |
| Windows 10 or later | `Surco-<version>-Setup.exe` |

On macOS you can also install it with Homebrew:

```bash
brew install --cask surco-app/surco/surco
```

Surco updates itself, so you only need to download it once.

## Requirements

- macOS 13 Ventura or later. On macOS 12 Monterey, [Surco 1.2.3](https://github.com/surco-app/surco-releases/releases/tag/v1.2.3) is the last version that runs.
- Windows 10 or later, 64-bit.

## Signing

The macOS builds are signed and notarized by Apple, so they open without warnings.

The Windows installer is not signed yet. When you open it, Windows shows "Windows protected your PC". Click "More info" and then "Run anyway". Our [code signing policy](https://getsurco.app/en/code-signing) explains how releases are signed, who approves them and what data the app sends.

## Help

- [Guide](https://getsurco.app/en/guide) with every feature and screenshots
- [What's new](https://getsurco.app/en/changelog) in each release
- [Report a bug or ask for a feature](https://github.com/surco-app/surco/issues)
