# ⛰️ RisingOS Version 4.0 (Kailash)

## 🏛️ Introduction
- Inspired by the sacred majesty of Mount Kailash, this version embodies our ongoing journey of transformation.

---

## 🔒 Security Updates
- **Android Security:** Stay protected with up-to-date security patches for July 2024.
---

## 💬 Highlights (RisingOS Exclusive Additions)

- For previous changelogs from our initial beta release, please refer to [Beta Release Changelog](https://github.com/RisingTechOSS/risingOS_changelogs/tree/32f1bc41a6a0b7c263b157c68dacd08ce4e768c8).
- For previous changelogs from 2.0-2.2 release, please refer to [2.0 Series Release Changelog](https://github.com/RisingTechOSS/risingOS_changelogs/tree/ebdf909aff26a0bfe4c0c669b34bdf333ba4e3c9).
- For previous changelogs from 3.0 release, please refer to [3.0 Series Release Changelog](https://github.com/RisingTechOSS/risingOS_changelogs/tree/032e1bd176f9b3f29d14470b2424fcf22baa0619).
---

This update brings previous features from the previous releases with the following improvements:

- **Framework:**
  - Resolved memory leaks 
  - Retuned max cached processes limit based on device ram size
  - Optimized and improved rendering performance
  - Resolved crash when less boring headsup is active
  - Improved audio effects handling
  - Fixed RCS and integrity spoofing - credits to sir Alvin and chiteroman
  - Marked SMS premium code 8080 as free in Poland
  - Fixed wifi soft ap band not being applied
  - Optimized bitmap shaders
  
- **Adaptive sound engine:**
  - Improved adaptive sound engine loudness, reverb, and compression handling

- **Bluetooth:**
  - Fixed an issue where the volume of Bluetooth devices is set to minimum after connecting.

- **Bootanimation:**
  - New awesome bootanimation created by sir Ayan

- **Charging animation:**
  - Fixed charging animation being too dark

- **Dark Theme:**
  - Retuned shade colors

- **GameSpace:**
  - Fixed multiple issues

- **Depth Wallpaper:**
  - Improved and fixed ui glitches

- **Game Space:**
  - Introducing Quick Start Apps feature - launch apps in multi-window mode while gaming/watching videos

- **Hide IME Space:**
  - Fixed feature not working

- **Lockscreen Clocks:**
  - Added Google clocks back
  - Optimized custom lockscreen clock styles loading
  - Reduced resource usage
  - Custom clocks fonts are now changeable (Except for clocks with specific design pattern)
  - Added weather support for center clock/IDE/OOS styles
  - Fixed aesthetic clock style reported charging mAh
  - Added and reworked clock font/style picker

- **Lockscreen Media art:**
  - Introducing lockscreen media art feature

- **Lockscreen Widgets:**
  - Optimized resource usage
  - Fix preference loading

- **Display:**
  - Introducing Reality display engine 
    - Introducing vivid mode and x-reality display 

- **Haptics:**
  - Refined volume slider haptics
  - Added options to disable/reduce vibration intensity of QS fling vibration

- **Ortus Launcher:**
  - Fixed swipe up gestures leading to screen freezing
  - Revamped themed icons colors

- **Pixel framework:**
  - Resolved booting failures on legacy pixel devices

- **QS Styles:**
  - Fixed QS styles notification background not being rounded

- **QuickSettings:**
  - Optimize QS album art cover scaling

- **Settings:**
  - Introducing new revamped 4.0 user interface

- **Wifi Standard:**
  - Fixed crashes and high power usage

---

## 👴 Deprecated Features (Removed Features)

- **Nothing Launcher:**
  - Deprecated as of QPR2 update

- **RisingUI Beta QuickSettings:**
  - Removed and will be re-introduced as Quicksettings Styles in upcoming releases. - Completely removed, references were lost after a pc format.

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


