# 🌊 RisingOS Version 5.0 Open Beta (Lyonesse)

## 🏛️ Introduction
- Evoking the lost grandeur of the mythical Lyonesse, this release represents a step into the extraordinary. With this version, we delve into new horizons, crafting new experience for everyone.

---

## 🔒 Security Updates
- **Android Security:** Stay protected with up-to-date security patches for August 2024.
---

## 💬 Highlights (RisingOS Exclusive Additions)
---

This update brings previous features from the previous releases with the following bug fixes and improvements:
- **Reported Issues:** 
  - Fixed crashed when launching Quick Tap open app list
  - Re-applied scrolling fix for three finger gestures
  - (OEM) Fixed doze preference theming under display settings [Legendleo90]
  - (OEM) Attempt to fix random camera crashes on some devices
  - Fixed extreme battery saver not showing on GAPPS builds
  - Resolved conflicts with strong integrity bypass modules e.g TrickyStore
  - Added workaround on broken heads-up notification on landscape (now shows island notification instead of nothing)
  - Fixed Lorn icon pack signal padding

- **Advanced:** 
  - Added option to create virtual RAM/swap using adb or root (adb shell ram_boost.sh <size_in_gb> e.g adb shell ram_boost.sh 2 - creates 2gb swap) 
    - Helpful for legacy devices and does not conflict with ZRAM. Needs to be applied after every reboot.

- **Bootanimation Styles:** 
  - Added option to change bootanimation

- **Black Theme Styles:** 
  - Added black theme styles with Berry black and true amoled dark as choices

- **Display Engine:** 
  - Added Triluminous Display mode
  - Retuned X-reality engine
  - Reworked previews

- **FaceUnlock:** 
  - Revamped face unlock indicator to island style

- **Freeform windows:** 
  - Improved freeform window resize animation
  - Fixed freeform minimized button not working
  - Fixed freeform buttons/bar colors

- **Island notification:** 
  - Added swipe to left/right to dismiss gesture

- **Lawnchair:** 
  - Updated lawnchair to 14.0.0-20240727 [Alvin Francis]

- **Ortus Launcher:** 
  - Implemented long press to search (for gestures only)

- **Power modes:**
  - Introducing device power modes - control cpu and memory based from profiles
  - Added QS tile

- **QuickSettings:**
  - Redesigned QS Data Usage UI

- **QS Widgets:**
  - Replaced tiles with connectivity tiles (wifi, bt, data, airplane mode)
  - Improved and updated layout
  - Added support for QS panel styles
  - Added QS Photo Widget

- **RAM Boost:**
  - Introducing ram boost feature - prioritize utilizing compressed memory (ZRAM) and swap space (if available) to improve overall performance.

- **Sound engine:**
  - Implemented Equal loudness contour logic

- **Spoofing:**
  - GameProps -> Per-app spoofing
  - Added option to directly update Play Integrity Fix properties
  - Added option to display currently set PIF properties

---

## 💬 Highlights (Cherry-Picked Additions)
- **Added BCR support:**
  - Added Basic call recording support [Chaitanyakm, James, Andrew Gunnerson]

- **Power modes:**
  - Implemented kernel tunings from KTweaks by [tytydraco](https://github.com/tytydraco/)
  
- **Security bypass features:**
  - Hide ADB and developer settings by [someone5678](https://github.com/someone5678/)
  - Hide Screen capture status from apps by [someone5678](https://github.com/someone5678/)
  - Storage Access Framework bypass by [rdxzv](https://github.com/rdxzv/)
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
- **LineageOS features and customizations:** LineageOS and crDroidAndroid Project
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


