An adaptive badge background responsiveness update for **Tinge 26**.

### What changed

- Reuse cached icon colors when a new badge appears.
- Preserve the same icon's sampled color through badge count changes.
- Retry unavailable icon pixels early with a bounded recovery sequence.
- Keep valid background paint visible while the same icon's appearance refreshes.
- Reject stale callbacks after view reuse or a folder's highest-count app changes.

Static badge backgrounds, text colors, borders, highest-count folder coloring and safe animated badge updates are preserved. No additional runtime hook targets, recurring timers or background services were added.

### Compatibility and installation

**Tested for several days on iPhone 11 Pro Max running iOS 26.0.1 with Dopamine 3 RootHide, with no problems reported.** Other devices, iOS versions and the standard rootless variant have not been confirmed on-device.

- **Native RootHide:** `com.sahinkaa.tinge26_1.0.1_iphoneos-arm64e.deb`. Install directly without RootHide Patcher.
- **Rootless:** `com.sahinkaa.tinge26_1.0.1_iphoneos-arm64.deb`.

Upgrade the existing installation and respring once. Saved preferences are preserved. Keep both **Tinge** and **ZZTingeAdaptiveBridge** enabled for SpringBoard.

An icon must have usable rendered pixels before its color can be sampled. An unrendered folder member may still require opening its folder once.

### Credits and source

Original Tinge by **P2KDev (@p2kdev)**. iOS 26 port and maintenance by **sahinkaa**. The rendered-icon approach was informed by [w1tu's ntfy](https://github.com/w1tu/ntfy), whose MIT notice is retained.

The dedicated `Tinge26_1.0.1_source.zip` includes the port source, build instructions and unchanged prebuilt original compatibility core. Original implementation source was not supplied. Use this archive for the implementation; GitHub's automatic source archives contain the repository documentation. SHA-256 checksums are included.
