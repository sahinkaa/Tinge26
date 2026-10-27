# Tinge 26

Customize your notification badges with adaptive colors, text colors and borders.

An iOS 26 compatibility port of **Tinge 1.2.2 by P2KDev (@p2kdev)**, ported by **sahinkaa**. The original developer credit and settings icon are preserved.

## Download 1.0

[Download Tinge 26 1.0 and read the release notes](https://github.com/sahinkaa/Tinge26/releases/tag/v1.0).

- **RootHide:** `com.sahinkaa.tinge26_1.0_iphoneos-arm64e.deb` — install directly, **without Patcher**.
- **Standard rootless:** `com.sahinkaa.tinge26_1.0_iphoneos-arm64.deb`.
- Both packages are version **1.0**. Choose the one matching your jailbreak.

## Features

- Adaptive colors from SpringBoard-rendered app icons, including themed icons.
- Folder badge colors follow the eligible app with the highest badge count; numbers remain unchanged.
- Safe animated badge updates as notifications arrive or counts change.
- Static backgrounds, text colors and border customization.
- Native settings and color picker with verified saves.
- Original settings icon, Respring as the only action row, balanced spacing and a tappable GitHub credit.
- Separate native RootHide and standard rootless builds.

## Compatibility

**Confirmed working only on iPhone 11 Pro Max, iOS 26.0.1, Dopamine 3 RootHide.**

On-device compatibility for the standard rootless variant and for other devices, iOS versions or jailbreaks has not been confirmed.

## Install

1. Close Settings and keep a backup of your current preferences.
2. Install the package matching your jailbreak. On RootHide, use the **iphoneos-arm64e** file directly, without Patcher.
3. Allow replacement of another Tinge installation if present, preserving settings if desired.
4. Respring and open **Settings → Tinge 26**.

PreferenceLoader, a Substrate-compatible loader and libcolorpicker are required. RootHide also requires rootless-compat for the preserved original core. Keep both **Tinge** and **ZZTingeAdaptiveBridge** enabled for SpringBoard.

Some folders may need to be opened once before their highest-badged app's color becomes available.

## Source and credits

Download **Tinge26_1.0_source.zip** from the release for the port implementation, prebuilt core inputs and build instructions. Use **SHA256SUMS** to verify the assets. GitHub's automatic source archives contain the repository snapshot; use the dedicated source asset for the implementation.

Original implementation source was not supplied. The archive includes the unchanged compatibility core as prebuilt binaries and does not assign it a new license.

Original Tinge: **P2KDev (@p2kdev)**. iOS 26 port: **sahinkaa**. The rendered-icon sampling approach was informed by [w1tu's ntfy](https://github.com/w1tu/ntfy); its MIT notice is retained in the source archive.
