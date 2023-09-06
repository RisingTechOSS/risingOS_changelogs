# RisingOS Version 1.4 Final (Elysium) 🏞️

Notes: Final release/version bump for android 13 

Inspired by Elysium, the realm of perfect happiness and beauty, this final update brings fixes and improvements to enhance user experience with RisingOS.

## Table of Contents
- [Security 🔒](#-security)
- [RisingOS General Changes ⚙️](#️-risingos-general-changes)
- [Improvements 🛠️](#️-improvements)
- [Fixed 🐛](#-fixed)
- [Cherry-picked Features 🍒](#-cherry-picked-features)

---

## 🔒 Security
- **Android Security**: September 2023 security patches applied.
- **Safetynet Attestation**: Passes by default, Play protect protect certification status is certified.

---

## ⚙️ RisingOS General Changes

### 🛠️ Improvements

#### System
- Updated touch sound effect
- Added more fonts to override
- Updated Oneplus Sans font
- Optimized system binaries for performance and size: _Co-author: Andrzej Perczak, Yi Kong, John Galt_

#### Settings
- Minor UI improvements
    * new illustration for personalization preference
    * new maintainer name highlighting style

#### Volume Panel
- Sound feedback when changing volume through tap/drag
- Long-press per-app volume icon to launch active media app

#### Memory Usage Optimizations
- Optimized memory management
- Optimized resource handling

#### QS Header
- Transition and performance improvements

#### Stability
- Optimized QS Panel reinflation to prevent possible systemui crashes
- Remove unstable codec changes

#### Bluetooth
- Optimized bluetooth battery level scanning

---

## 🐛 Fixed
- **Fonts**: Fixed monospace overriden by sans-serif.
- **System Memory Leaks**: Various leaks fixed for enhanced system stability.
- **Crashes**: Resolved system ui crashes system manager game boost mode is enabled.
- **Keyguard**: Fixed adaptive charging indication showing even though it's disabled.
- **Display**: Fixed possible flickering caused by null surfacecontrol.
- **Authentication**: Fixed getting authentication ripple scrim getting stucked.
- **User Switching**: Fixed random crash when switching user.
- **Brightness Slider**: Fixed QS Panel brightness slider vibrating to automatic brightness adjustments.
- **Ortus Launcher**: Fixed recents apps touch issues and gestures getting stuck.

---

## 🍒 Cherry-picked Features
- **Improve Blur Handling**: _Author: nift4_
- **Fix Quickswitch with Gesture Pill Disabled**: _Author: nift4_
- **fix missing rotate suggestion in 2 button nav mode**: _Author: nift4_
- **Bluetooth Battery Level Enhancements**: _Authors: jhonboy121, Pranav Vashi_
- **Always finish the LightRevealScrim**: _Author: Chenyang Zhong_
- **Allow limiting AOD & ambient display refresh rate**: _Author: Ido Ben-Hur_
- **Navbar layouts settings**: _Author: Pranav Vashi_
