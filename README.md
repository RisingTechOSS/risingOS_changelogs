# RisingOS Version 1.4 Final (Elysium) 🏞️

**Note**: This is the final release/version bump for Android 13.

Inspired by Elysium, the realm of perfect happiness and beauty, this update brings a series of fixes and improvements to enhance the user experience on RisingOS.

## Table of Contents
- [Security 🔒](#-security)
- [RisingOS General Changes ⚙️](#️-risingos-general-changes)
- [Improvements 🛠️](#️-improvements)
- [Fixed 🐛](#-fixed)
- [Cherry-picked Features 🍒](#-cherry-picked-features)

---

## 🔒 Security
- **Android Security**: Security patches for September 2023 have been applied.
- **Safetynet Attestation**: Passes by default. Play Protect certification status is certified.

---

## ⚙️ RisingOS General Changes

### 🛠️ Improvements

#### System
- Updated the touch sound effect.
- Introduced more fonts for overriding.
- Updated the Oneplus Sans font.
- Optimized system binaries for performance and size. 
  _Co-authors: Andrzej Perczak, Yi Kong, John Galt_
- Weather updates moved to the background to reduce resource usage.
- Improved multitasking performance
- Improved multi-window/freeform support
    - improved freeform handling
    - added freeform shorcut when long pressing app icon from drawer/hotseat
- Added keylayout for DualSense Edge/Xbox wireless controller

#### Settings
- Minor UI improvements:
    * New illustration for personalization preference.
    * New maintainer name highlighting style.

#### Volume Panel
- Sound feedback provided when changing volume via tap/drag.
- Long-press the per-app volume icon to launch the active media app.

#### Memory Usage Optimizations
- Improved memory management.
- Enhanced resource handling.

#### Stability
- Optimized QS Panel reinflation to prevent potential System UI crashes.
- Removed unstable codec changes.

#### Bluetooth
- Optimized Bluetooth battery level scanning.

---

## 🐛 Fixes
- **Fonts**: Resolved an issue where monospace was overridden by sans-serif.
- **System Memory Leaks**: Addressed various memory leaks to enhance system stability.
- **Crashes**: 
    - Resolved System UI crashes when the system manager game boost mode is active.
    - Fixed Android service library crash.
    - Resolved Google services crashes.
    - Resolve BaseBundle crashes
- **Keyguard**: Fixed the issue of adaptive charging indication appearing even when disabled.
- **Display**: Rectified possible flickering caused by a null surface control.
- **Authentication**: Fixed the authentication ripple scrim getting stuck.
- **User Switching**: Resolved a random crash occurring during user switching.
- **Brightness Slider**: Fixed the QS Panel brightness slider vibrating due to automatic brightness adjustments.
- **Ortus Launcher**: Rectified issues with recent apps touch and gestures getting stuck.
- **Adaptive Charging**: Fixed adaptive charging activating on daytime.
- **Firewall**: Fixed the firewall's internet/data access switch malfunction.
- **Desktop Mode**: Fixed Desktop mode pc settings crash.
- **Desktop Mode**: Fixed app drawer search bar layout.
- **Security Patch**: September build version is now reported to most apps e.g safetynet apps etc (without breaking cts).

---

## 🍒 Cherry-picked Features
- **Improved Blur Handling**: _Author: nift4_
- **Fixed Quickswitch with Gesture Pill Disabled**: _Author: nift4_
- **Rectified Missing Rotate Suggestion in 2-Button Nav Mode**: _Author: nift4_
- **Bluetooth Battery Level Enhancements**: _Authors: jhonboy121, Pranav Vashi_
- **Ensured Completion of the LightRevealScrim**: _Author: Chenyang Zhong_
- **Allowed Limiting AOD & Ambient Display Refresh Rate**: _Author: Ido Ben-Hur_
- **Navbar Layouts Settings**: _Author: Pranav Vashi_
