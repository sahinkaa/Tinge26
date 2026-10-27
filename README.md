# Tinge 26

Customize your notification badges with adaptive colors, text colors and borders.

An iOS 26 compatibility port of **Tinge 1.2.2 by P2KDev (@p2kdev)**, ported by **sahinkaa**. The original developer credit and settings icon are preserved.

## Download version 1.0

[Open the release and full change notes](https://github.com/sahinkaa/Tinge26/releases/tag/v1.0).

- **RootHide:** download `com.sahinkaa.tinge26_1.0_iphoneos-arm64e.deb` and install it directly, **without RootHide Patcher**.
- **Standard rootless:** download `com.sahinkaa.tinge26_1.0_iphoneos-arm64.deb`.
- Choose one package matching your jailbreak. Both are version **1.0**.

## Changes

- Adaptive badge backgrounds from SpringBoard-rendered app icons, including themed icons, with a bounded visual-layer fallback.
- Folder colors follow the eligible app with the highest numbered badge; badge numbers remain unchanged.
- Static backgrounds, text colors and border customization are preserved.
- Native settings and color picker with atomic saves and disk readback, including static border colors.
- Original settings icon, Respring as the only action row, balanced footer spacing and a tappable GitHub credit.
- Separate native RootHide and standard rootless builds.

## Tested configuration

**Tested only on iPhone 11 Pro Max, iOS 26.0.1, Dopamine 3 RootHide.**

This is user-reported testing of the working RootHide port. The final spacing/link polish still needs an on-device visual check. Standard rootless has not been device-tested by this project. Other devices, iOS versions and jailbreaks are untested.

## Install

1. Close Settings and keep a backup of your working package/settings.
2. Install the package matching your jailbreak. On RootHide, use the arm64e file directly, without Patcher.
3. Since the version remains 1.0, reinstall the local package or remove the previous copy without purging settings before installing. Remove the failed 1.0.0 first if it is still installed.
4. Allow replacement of the older Tinge/adaptive bridge/settings repair test packages if present.
5. Respring and reopen Settings → **Tinge 26**.

PreferenceLoader, a Substrate-compatible loader and libcolorpicker are required. RootHide also requires rootless-compat for the preserved legacy core.

## Source and attribution

Download **Tinge26_1.0_source.zip** from the release for the port implementation, tests, prebuilt core inputs and build instructions. Use **SHA256SUMS** to verify the assets. GitHub's automatic source archives contain the repository snapshot; use the dedicated source asset for the implementation.

Original Tinge/Test 3 implementation source was not supplied. The port source archive includes the unchanged core binaries as build inputs and does not claim to recreate their original source or assign them a new license.

Original Tinge: **P2KDev (@p2kdev)**. iOS 26 port: **sahinkaa**. The rendered-icon sampling approach was informed by [w1tu's ntfy](https://github.com/w1tu/ntfy); its MIT notice is retained in the port source archive.
