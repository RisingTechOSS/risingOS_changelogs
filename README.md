# 🕒 RisingOS Version 3.0 (Janus)

## 🏛️ Introduction
- Embracing the spirit of Janus, the Roman deity of new beginnings, this marks the dawn of a new era.

---

## 🔒 Security Updates
- **Android Security:** Stay protected with up-to-date security patches for May 2024.
---

## 💬 Highlights (RisingOS Exclusive Additions)

- For previous changelogs from our initial beta release, please refer to [Beta Release Changelog](https://github.com/RisingTechOSS/risingOS_changelogs/tree/32f1bc41a6a0b7c263b157c68dacd08ce4e768c8).
- For previous changelogs from 2.0-2.2 release, please refer to [2.0 Series Release Changelog](https://github.com/RisingTechOSS/risingOS_changelogs/tree/ebdf909aff26a0bfe4c0c669b34bdf333ba4e3c9).
---

This update brings previous features from the 2.0 releases with the following improvements:

- **Framework:**
  - Optimized low memory killer daemon (05/06/24)
  - Silenced spammy debugging messages that causes battery drain (05/06/24)
  - Resolved system haptics vibration issues  (05/11/24)
  - Resolved memory performance regressions (05/11/24)
  - Reduced max allowed background processes (05/11/24)
  
- **Audio Effects [BETA]:**
  - Added Sound Engine QS tile and lockscreen widget toggle (05/06/24)

- **Boost Framework:**
  - Resolved power regressions (05/12/24)

- **Dark Theme:**
  - Introducing True Amoled Dark mode - Optimized AMOLED like dark mode (05/09/24)

- **Depth Wallpaper:**
  - Introducing Depth Wallpaper feature [credits to Siavash](https://github.com/siavash79) (05/06/24)

- **GameSpace:**
  - Fixed FPS meter (05/09/24)

- **Healthy Charge:**
  - Introducing Healthy Charge Service (05/09/24) - Get healthy battery charging reminders

- **LockScreen Charging Info:**
  - Fixed crashes on some devices when lockscreen info is enabled while charging 05/12/24)

- **LockScreen Widgets [BETA]:**
  - Fixed scaling on high dpi devices (05/06/24)
  - Reintroducing IOS inspired clock widget as a lockscreen widget (05/11/24)

- **Ortus Launcher:**
  - Fixed Free memory calculation (05/06/24)
  - Restored homescreen popup legacy order (05/06/24)
  - Updated search bar colors (05/06/24)
  - Added force kill option to system shortcut (05/06/24)

- **QuickSettings:**
  - Fixed QuickSettings light theme color and background colors (05/11/24)
  - Revamped landscape quick settings (Enabled Split Shade QuickSettings) (05/12/24)

- **Settings:**
  - Added Hidden SSID, Hotspot client manager and AP band controls changes authored by [cjybyjk](https://github.com/cjybyjk/), forward ported by risingOS team (05/06/24)

- **Shake Gestures:**
  - Fixed an issue were devices vibrates when devices shakes (05/12/24)

- **UDFPS animations/icons:**
  - Fixed an issue where UDFPS animation gets stucked after unlocking device (05/06/24)

- **Volume Panel:**
  - Fixed Volume panel slider lag/delay issues (05/11/24)

---

## 👴 Deprecated Features (Removed Features)

- **Columbus/Elmyra:**
  - Removed due to deprecated dependencies and will be re-introduced once we learn how to regenerate the new java libraries.

- **LockScreen Album Art Filter:**
  - Deprecated as of [QPR2](https://github.com/crdroidandroid/android_frameworks_base/commit/8f922ec2cb649b99b07a90836584702c4f22e0a9). - we will add this back no matter what happens

- **Nothing Launcher:**
  - Deprecated as of QPR2 update

- **RisingUI Beta QuickSettings:**
  - Removed and will be re-introduced as Quicksettings Styles in upcoming releases. - PENDING: difficulty to implement back is high

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


