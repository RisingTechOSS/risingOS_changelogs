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
- **Android August ASB 2023**: Updated security patches.
- **Safetynet Attestation**: Passes by default for enhanced app compatibility and trust.

---

## ⚙️ RisingOS General Changes

### 🛠️ Improvements

#### Memory Usage Optimizations
- Optimized memory management
- Optimized resource handling

#### QS Header
- Transition and performance improvements

#### SystemUI Stability
- Optimized QS Panel reinflation to prevent possible systemui crashes

#### Bluetooth
- Optimized bluetooth battery level scanning

---

## 🐛 Fixed
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
