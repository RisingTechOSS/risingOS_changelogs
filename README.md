# RisingOS Version 1.3.1 (Damascus) 🌇

Inspired by the rich history of Damascus, one of the oldest cities in the Middle East, this update brings new features, improvements, and bug fixes to enhance your experience with RisingOS.

## 🔒 Security
- [Security] Android August ASB 2023
- [Security] Safetynet attestation passes by default

## ✨ RisingOS Additions
- [Feature] Introducing Custom QS Header Image
- [Feature] Exposed split app button for non-tablet devices
- [Feature] Added kill/force close system shortcut for accessibility
- [Feature] [Modified by RisingOS team] Expanded Pulse visualizer options (fixed and forward-ported) - Author: TikkiTikki
- [Feature] [Modified by RisingOS team] Enhanced gesture navbar length and radius handling  - Authors: spkal01, Terminator-j, jhonboy121

## ⚙️ RisingOS General Changes

### 🛠️ Improvements
- Revamped System Manager structure and initialization for efficiency and robustness
- Introduced system UI restart/system reboot prompt for customization requiring system reloading
- Enhanced overall system performance through optimizations
- Enabled toggle for Google camera spoof (Exclusive for Pixel devices only)
- Redesigned recent apps layout for a better app switching experience
- Applied material you colors to home screen folder background
- Adjusted Udfps icon scale based on device's resolution
- Refined immersive status bar-navigation hiding
- Removed small inverted back arrow when keyboard is active with Hide IME space feature enabled

### ✔️ Stability
- Removed faulty/blind-picked/experimental source changes in preparation for incoming Android U upstream
- Eliminated GameSpace notification modes that required system UI restart to take effect

## 🐛 Fixed
- Recents apps glitches when swiping task views
- GameSpace crashes with "device & app notification" access
- QS notifications hidden during danmaku notification mode
- Wallpaper app lag fixed (caused by Android 14 wallpaper picker UI)
- Crash with multiple package installer intent resolved
- Random crash when animating media player play/pause button
- Fixed app crashes when picking photos through Google Photos
- Wallpaper app not accessible for tablets

## ❗ Known Issues
- QS Panel Pulse visualizer sometimes out of position if turning screen off from QS panel (fixable by unlocking phone)
    - Investigation ongoing related to pulse code

## 🍒 Cherry-picked Features (Taken from other open-source Android projects)
- Less boring heads up option - Authors: ezio84, Pranav Vashi, DroidFreak32
- Option to disable clipboard overlay - Authors: Adithya R
- Toggle for floating rotation button - Authors: idoybh
