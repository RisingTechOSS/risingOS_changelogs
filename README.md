# RisingOS Version 1.3.1 (Damascus) 🌇

Inspired by the rich history of Damascus, one of the oldest cities in the Middle East, this update brings new features, improvements, and bug fixes to enhance your experience with RisingOS.

## 🔒 Security
- [Security] Android August ASB 2023
- [Security] Safetynet attestation passes by default

## ✨ RisingOS Additions
- [Feature] Introducing Custom QS Header Image
- [Feature] Exposed split app button for non-tablet devices
- [Feature] Added kill/force close system shortcut for accessibility
- [Feature] [Modified by RisingOS team] Expanded Pulse visualizer options (fixed and forward-ported) - Co-Author: TikkiTikki
- [Feature] [Modified by RisingOS team] Enhanced gesture navbar length and radius handling  - Co-Authors: spkal01, Terminator-j, jhonboy121

## ⚙️ RisingOS General Changes

### 🛠️ Improvements
- Revamped System Manager structure and initialization for efficiency and robustness
- Introduced system UI restart/system reboot prompt for customizations that requires system reloading
- Optional toggle for Google camera spoof (Exclusive for Pixel devices only)
- Redesigned recent apps layout for a better app switching experience
- Applied material you colors to home screen folder background
- Adjusted Udfps icon scale based on device's resolution
- Refined immersive status bar-navigation hiding
- Small inverted back arrow when keyboard is active is now hidden when Hide IME space feature is enabled
- Performance enhancements for better user experience
  - Optimized binaries and libraries for performance by tweaking link time optimization flags
  - Moved weather updates to background to avoid any potential performance regressions
  - Enabled and improved pro-active kills for devices with modern kernels that supports LRU/PSI
  - Optimized storage manager service for a more faster lookup - improving system startup times
  - Moved freezer and compaction thread to background for memory/performance improvements
  - Implemented service rescheduler API - a service mechanism that delays non-persistant background apps
  - Improved refresh rate scheduler algorithm - reworked refresh rate selection for smoother transition with low-high refresh rate - Co-Author: arter97
  - Faster and smoother animations app-launcher transition by disabling blur effect when performing app launch/exit and improving animation transition scale

### ✔️ Stability
- Removed faulty/blind-picked/experimental source changes in preparation for incoming Android U upstream
- Removed GameSpace notification modes that required system UI restart to take effect

## 🐛 Fixed
- Recents apps glitches when swiping task views
- GameSpace crashes with "device & app notification" access
- QS notification were hidden when danmaku notification mode is active
- Wallpaper app lag fixed (caused by Android 14 wallpaper picker UI)
- Crash when multiple package installer intents were received when installing apps through apps/third party providers
- Random crash when animating media player play/pause button
- Fixed app crashes when picking photos through Google Photos
- Wallpaper app not accessible for tablets

## 🍒 Cherry-picked Features (Taken from other open-source Android projects)
- Less boring heads up option - Authors: ezio84, Pranav Vashi, DroidFreak32
- Option to disable clipboard overlay - Author: Adithya R
- Toggle for floating rotation button - Author: idoybh
