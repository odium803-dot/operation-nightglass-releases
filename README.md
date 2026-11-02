# Operation Nightglass

A tactical stealth game by Dead End Productions. The native closed beta includes **51 missions across eight chapters**.

## Current release: beta2.31 (build 11031)

[Release notes and downloads](https://github.com/odium803-dot/operation-nightglass-releases/releases/tag/v1.1.0-beta2.31)

- Windows: download the Windows portable ZIP, extract the entire folder, and launch Operation Nightglass.exe.
- Linux: download the Linux portable ZIP, extract it, and launch operation-nightglass. Keep its PCK beside the executable.
- Android: the test APK uses development signing; physical-device testing is pending.
- Source: a sanitized Godot 4.7.2 project snapshot is included in the source ZIP.

SHA256SUMS.txt provides package checksums. Native automatic installer updates are disabled; install from the release packages. The existing latest.json serves an older installer generation and is not the native beta download catalog.

## What changed

This release fixes the Chapter VI first-explosion shader stall and includes varied scenery, line-of-sight minimap contacts with faded last-seen markers, soldier-perspective binoculars, snow footprints, and rendering optimizations.

Both packaged resource sets passed checks that instantiate all 51 missions, and the Linux executable passed a headless boot check. These are not full human playthroughs or physical Windows/Android certification. See VALIDATION.txt and PACKAGE-CHECKS.txt in the release.

A measured one-minute mission 43 run averaged 60.002 FPS, with a worst frame of 22.92 ms. A steady minimum 60 FPS across the campaign is **not yet certified**.

Existing native save identity is preserved. Back up your saves before switching versions. This does not promise migration from the older browser game.

## Credits

Thomas Bennett • Thomas Olson  
Beta testing: Michael Bennett

Engine and asset acknowledgements ship with the game.
