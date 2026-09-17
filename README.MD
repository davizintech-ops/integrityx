## integrityX

Kairo Integrity Engine — a lightweight Android integrity-management module for Magisk and KernelSU.

---

«Version: V0.5.0
Module ID: "playintegrityfix"»

---

## Overview

**integrityX** is a modular Android project focused on integrity-state based on play integrity fork

The project is designed to keep its footprint small while making the current environment easy to inspect

---

## Features

- Magisk and KernelSU oriented module layout
- Zygisk/environment detection
- SELinux status detection
- "/data/adb/pif.prop" presence and inspection
- Lightweight status WebUI
- Clear diagnostic output
- Shell-first architecture
- Kairo Integrity Engine branding

## Requirements

- Rooted Android device
- Magisk or KernelSU
- Android shell environment
- Zygisk when features requiring Zygisk are enabled

## Installation

1. Download the integrityX module ZIP.
2. Open Magisk or KernelSU.
3. Install the ZIP as a module.
4. Reboot when requested.
5. Open the integrityX WebUI, if available.

## Diagnostics

**integrityX can inspect**:

- Root/module environment
- Zygisk availability
- KernelSU/Magisk environment
- SELinux mode
- "/data/adb/pif.prop"
- Relevant Android build properties

integrityX reports what it detects; it does not guarantee a particular Play Integrity result.

# Configuration

**Project Structure**

```bash
integrityX/
├── module.prop
├── README.md
├── CHANGELOG.md
├── LICENSE
├── customize.sh
├── post-fs-data.sh
├── service.sh
├── uninstall.sh
```

## Important

**integrityX** is a **diagnostic and customization** project.

**Integrity** and **Play Integrity** behavior can change **depending** on:

- Android version
- Device firmware
- Google Play services
- Root implementation
- Module configuration
- Server-side changes

Therefore, a status reported by integrityX should not be treated as a permanent guarantee.

Credits

Project: integrityX
Engine: Kairo Integrity Engine
Author/Maintainer: Kyro

Special thanks to the Android modding community and everyone contributing to open-source Android development.

License

MIT License. See ""LICENSE"" (LICENSE).
