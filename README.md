# ⛰️ RisingOS Version 4.2 (Kailash)

## 🏛️ Introduction
- Inspired by the sacred majesty of Mount Kailash, this version embodies our ongoing journey of transformation.

---

## 🔒 Security Updates
- **Android Security:** Stay protected with up-to-date security patches for July 2024.
---

## 💬 Highlights (RisingOS Exclusive Additions)
---

This update brings previous features from the previous releases with the following bug fixes and improvements:

- **Reported issues :**
  - (4.1) Fixed random reboot when changing screen off animation
  - (4.1) Fixed flickering on some devices
  - (4.1) Fixed some telephony crashes on qcom devices
  - (4.1) Fixed FrameTracker leaks and logspam (cjh1249131356)
  - (4.1) Freeform/multi-tasking fixes and improvements
  - (4.2) Attempt to fix telephony failures on exynos/qcom devices
  - (4.2) Fixed reported GameSpace crash
  - (4.2) Fixed three finger swipe gestures scrolling when performing gesture
  
- **System-wide:**
  - Resolved memory leaks 
  - Retuned max cached processes limit based on device ram size
  - Optimized and improved rendering performance
  - Resolved crash when less boring headsup is active
  - Fixed RCS and integrity spoofing - credits to sir Alvin and chiteroman
  - Marked SMS premium code 8080 as free in Poland
  - Fixed wifi soft ap band not being applied
  - Optimized bitmap shaders
  - Fixed crash when using dismissing split screen pair
  - (4.1) Optimize file reading operations
  - (4.1) Optimize and improve font style overriding
  - (4.1) Android runtime improvements to reduce janks
  - (4.1) Fixed shared memory and FileUtils memory leaks
  - (4.1) Fixed systemui crash when casting device to another display 
  - (4.2) Minor swap performance enhancements
  - (4.2) Resolved regressions that causes QS janks
  - (4.2) Attempt to reduce audio/media CPU usage 

- **Bluetooth:**
  - Fixed an issue where the volume of Bluetooth devices is set to minimum after connecting.

- **Bootanimation:**
  - New awesome bootanimation created by sir Ayan

- **Charging animation:**
  - Fixed charging animation being too dark

- **Dark Theme:**
  - Retuned shade colors

- **Depth Wallpaper:**
  - Improved and fixed ui glitches

- **Display:**
  - Introducing Reality display engine 
    - Introducing vivid mode and x-reality display 

- **GameSpace:**
  - Fixed multiple issues
  - Introducing Quick Start Apps feature - launch apps in multi-window mode while gaming/watching videos

- **GameProps:**
  - (4.2) Introducing JSON-based game device spoofing - Spoof any game without restrictions

- **Gesures:**
  - (4.2) Introducing Three finger long press gestures

- **Haptics:**
  - Refined volume slider haptics
  - Added options to disable/reduce vibration intensity of QS fling vibration
  - (4.2) Refined brightness slider haptics

- **Hide IME Space:**
  - Fixed feature not working

- **Lockscreen AOD image:**
  - (4.2) Added option to show custom AOD image on top of custom clock

- **Lockscreen Clocks:**
  - Added Google clocks back
  - Optimized custom lockscreen clock styles loading
  - Reduced resource usage
  - Custom clocks fonts are now changeable (Except for clocks with specific design pattern)
  - Added weather support for center clock/IDE/OOS styles
  - Fixed aesthetic clock style reported charging mAh
  - Added and reworked clock font/style picker
  - (4.1) Thicker clock for centered clock style
  - (4.2) Fixed crash when upgrading from old version (if user is using a removed clock style)
  - (4.2) Added burn-in protection

- **Lockscreen Media art:**
  - Introducing lockscreen media art feature

- **Lockscreen Widgets:**
  - Optimized resource usage
  - Fix preference loading

- **Ortus Launcher:**
  - Fixed swipe up gestures leading to screen freezing
  - Revamped themed icons colors

- **Pixel framework:**
  - Resolved booting failures on legacy pixel devices

- **Play Integrity:**
  - (4.2) Added support to load custom PIF.json for play integrity spoofing

- **Pocket Mode:**
  - (4.2) Pocket mode is now disabled when device enters Always on Display
  - (4.2) Pocket mode now blocks shake/swipe gestures and biometrics

- **QuickSettings:**
  - (4.0) Fixed QS styles notification background not being rounded
  - (4.1) Introducing QS Widgets - shortcuts and widgets on top of QS tiles
  - (4.1) Minor UI changes/improvements
    - A11 Style: Fixed A11 QS panel paddings on notch devices
    - A11 Style: Increased QS tiles vertical margin
    - Moved brightness icon to the start of the slider
  - (4.2) Added option to modify QS panel row count
  - (4.2) Fixed oversized QS widgets
  - (4.2) Attempt to fix QS signal icon bug
  - (4.2) Minor QS animation enhancements

- **QuickSwitch:**
  - Added Lawnchair support big thanks to ashoss, elpaablo, and sir alvin

- **Settings:**
  - Introducing new revamped 4.0 user interface

- **Sound engine:**
  - Improved adaptive sound engine loudness, reverb, and compression handling
  - (4.2) retuned music profile bass, reverb and loudness

- **Wallpapers:**
  - (4.1) Added CMF Phone 1 wallpapers
  - (4.2) Added Kailash Edition wallpapers

- **Wifi Standard:**
  - Fixed crashes and high power usage

---

## 💬 Highlights (Cherry-Picked Additions)
- **Desktop Mode:**
  - (4.1) Implemented Desktop mode feature [by LibreMobileOS Project](https://github.com/LMODroid/)

- **Reported Issues:**
  - (4.1) Fixed booting issues for Pixel 8 Series [credits to ionutgherman](https://github.com/ionutgherman/)
---

## 👴 Deprecated Features (Removed Features)

- **Nothing Launcher:**
  - Deprecated as of QPR2 update

---

## 🙌 All Features currently shipped with respective Authors and Contributors
Below is a detailed compilation of all features incorporated into the current release, accompanied by the acknowledgments of the original authors and contributors of the listed features.

**Disclaimer:** The risingOS team may have made partial modifications to these features. However, it is essential to note that we do not assert or will NEVER assert ownership to any of these features, nor do we claim any part of them as our own. All copyrights and credits belong to their respective authors and contributors.

Your understanding and appreciation for the creativity and efforts of the original contributors are highly valued. We extend our outmost gratitude and appreciation to all the people listed below for their contributions and efforts to the development of these features 🙏

---
- **LineageOS features and customizations:** LineageOS Project
- **Adaptive Playback:** Jyotiraditya, Stylogey
- **Ai Assistant Shortcut:** Credits to Mishaal Rahman
- **Always on Display schedule:** idoybh
- **Always on Display on Charge:** darkobas, jhonboy121, idoybh, Pranav Vashi (Fixes and Improvements)
- **AppLock:** jhonboy121, Pranav Vashi (Forward Port and fixes)
- **Brightness Slider Customizations:** Alberto97, Michael Bestas, Luca Stefani, Alexander Westphal, qjohn, maxwen, Pranav Vashi, idoybh, timjosten
- **Battery Bar:** cphelps76, Pranav Vashi (Fixes)
- **Battery Customizations:** althafvly, Pranav Vashi, Myself5, TheStrix, ezio84, 703joko, R15Hi, spezi77, StarkDroid, Dr Disagree
- **Colored Status Bar Icons:** Dil3mm4, spkal101, Pranav Vashi (Fixes and Improvements)
- **Disable Data Indicator:** varund7726
- **Edge Light:** jhonboy121, Stallix (Forward Port), Pranav Vashi (Fixes and Improvements)
- **GameSpace:** Nauval Rizky
- **Hide Power Menu on QS:** jhonboy121
- **Island Notification:** Dil3mm4 (author of reticker feature), Pranav Vashi and someone5678 (fixes and improvements)
- **Less Boring Headsup:** ezio84, Rushab Shah, Pranav Vashi
- **Music Ticker:** ezio84, Pranav Vashi (Forward Port)
- **Noisy Notifications:** ezio84
- **Lockscreen Charging Info:** beanstown106
- **LockScreen Clocks:** Afterlife Project (703joko)
- **Lockscreen Media Art:** beanstown106
- **Monet Customizations:** idoybh, Pranav Vashi
- **Notification Count:** Steve Kondik, jhonboy121, Pranav Vashi (Fixes)
- **Omnijaws Weather Client:** Maxwen, Pranav Vashi
- **QuickSettings Tile Animations:** Nico60, PacMM79
- **QuickSettings Header Image:** Idc/ancientOS
- **QuickSettings Styles and Customizations:** IacobIonut01, SamarV-121, Tim Zimmermann, cjh1249131356, timjosten, StarkDroid, Dr Disagree, elluzion, rdx420
- **Screen Off Animations:** Kshitij Gupta, Pranav Vashi (Forward Port),
- **Shape and Icon Pack Themes:** SagarMakhar, Pranav Vashi (Improvements), Dr Disagree (Iconify Icon Packs)
- **Status Bar Clock Customizations:** Luca Stefani, Hendrik Hagendorn, LuK1337, Michael W, Volodymyr Zhdanov, kxxt, bellegarde-c, Pranav Vashi
- **Status Bar Clock Chip:** StarkDroid
- **Status Bar Logo:** Pranav Vashi, Shevt, LorDClockaN, varund7726
- **System Haptics:** Blaster4385, Pranav Vashi, someone5678
- **Smart Pixels:** Sergii Pylypenko, Anay Wadhera, Pranav Vashi, frap129
- **Screenshot Sound:** Ashwin R C
- **Swipe to Screenshot:** ghbhaha, jhenrique09
- **Pulse Visualizer:** bigrushdog (Randall), Pranav Vashi (Forward Port)
- **UDFPS Animations:** SagarMakhar, Dhina17, AnnierinBliss, Pranav Vashi
- **Volume Steps:** Meticulus
- **Volume Styles:** Dr Disagree (iconify volume style packs).

---


