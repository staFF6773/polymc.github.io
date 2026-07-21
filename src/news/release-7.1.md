---
title: PolyMC 7.1 has been released
description: Fixes CurseForge after July 16th
date: 2026-07-14
release_version: 7.1
minimum_macos_version: 11.0.0
legacy_macos_minimum_version: 10.14.0
mac_signature: EJyVXloxbcKsTt4c+2gLH4nTRA6MSRMlqeZ3CgYDPqW3bxIL8HcqmqDamkJ2vp6hMUvljz1Ph6l7gvrTzDlZDQ==
legacy_mac_signature: 2u6ocBsA16GbD8pPQ/LFS7YmKJoToV2CXxCp3g2Hfdu4ytx2cf4HYzhIvT/h6fwUZ18jmujrOG4Iokb0u/5oCA==
tags:
  - release
---

This is just to fix support for CurseForge after July 16th... <sup><sub>god i hate curseforge</sup></sub>

## Notice
Linux builds are now exclusively AppImage. The prebuilt binaries are useless. Also Removed Qt 5 builds from Linux

## What's Changed

- Fix compiling for Qt 6.9.0 (Nice) and QTBUG-135800 workaround by [@Kaydax](https://github.com/Kaydax) in [#1693](https://github.com/PolyMC/PolyMC/pull/1693), [#1703](https://github.com/PolyMC/PolyMC/pull/1703)
- Skip empty and non-executable Java paths when probing by [@byte-chan](https://github.com/byte-chan) in [#1696](https://github.com/PolyMC/PolyMC/pull/1696)
- Windows on ARM support: architecture detection, workflow matrix, NSIS fixes by [@crueter](https://github.com/crueter) and [@Kaydax](https://github.com/Kaydax) in [#1743](https://github.com/PolyMC/PolyMC/pull/1743)
- Fix GitHub workflow: Ubuntu 22.04, CMake, ccache-action by [@Kaydax](https://github.com/Kaydax) in [#1705](https://github.com/PolyMC/PolyMC/pull/1705)
- macOS CI: update to macOS 15, fix macos-legacy by [@Kaydax](https://github.com/Kaydax) in [#1731](https://github.com/PolyMC/PolyMC/pull/1731)
- nix: add JDK 25, migrate from deprecated xorg namespace by [@rusty-tendrils](https://github.com/rusty-tendrils) in [#1755](https://github.com/PolyMC/PolyMC/pull/1755)
- CMake: add USE_CCACHE option by [@crueter](https://github.com/crueter) in [#1744](https://github.com/PolyMC/PolyMC/pull/1744)
- Refactor workflows: extensible scripts, quick-sharun, new action structure by [@crueter](https://github.com/crueter) in [#1746](https://github.com/PolyMC/PolyMC/pull/1746)
- CI: move CodeQL to separate job, add versioned artifacts by [@crueter](https://github.com/crueter) in [#1747](https://github.com/PolyMC/PolyMC/pull/1747)
- CI: add aarch64 AppImage, remove Quazip-qt5 by [@crueter](https://github.com/crueter) in [#1751](https://github.com/PolyMC/PolyMC/pull/1751)
- Add patchelf to deps.sh by [@Samueru-sama](https://github.com/Samueru-sama) in [#1765](https://github.com/PolyMC/PolyMC/pull/1765)
- mangohud: update to shim DLL by [@hustlerone](https://github.com/hustlerone) in [#1729](https://github.com/PolyMC/PolyMC/pull/1729)

## New Contributors

- [@byte-chan](https://github.com/byte-chan) made their first contribution in [#1696](https://github.com/PolyMC/PolyMC/pull/1696)
- [@rusty-tendrils](https://github.com/rusty-tendrils) made their first contribution in [#1755](https://github.com/PolyMC/PolyMC/pull/1755)
- [@Samueru-sama](https://github.com/Samueru-sama) made their first contribution in [#1765](https://github.com/PolyMC/PolyMC/pull/1765)

**Full Changelog**: https://github.com/PolyMC/PolyMC/compare/7.0...7.1

You can [grab the latest download here](/download) for your respective platform.