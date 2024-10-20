# 🌊 RisingOS Version 5.2.1 EOL (Lyonesse)

## 🏛️ Introduction
- Evoking the lost grandeur of the mythical Lyonesse, this release represents a step into the extraordinary. With this version, we delve into new horizons, crafting new experience for everyone.

---

## 🔒 Security Updates
- **Android Security:** Stay protected with up-to-date security patches for October 2024.
---

## 💬 Highlights (RisingOS Exclusive Additions)
---

This update brings previous features from the previous releases with the following bug fixes and improvements:
- **Reported Issues:** 
  - (5.1) Attempt to fix snapchat messaging delays 
  - (5.1) Fixed swipe gestures multi-touch issues
  - (5.1) Attempt to fix memory leaks caused by SystemUI theme reevaluations and SystemUI restarts
  - (5.1) Fixed custom QS Header not working (when selecting custom photo via google photos etc)
  - (5.1) Fixed swiped island notification blocking input
  - (5.1) Fixed weather widget redirect
  - (5.1) Improved multi-tasking by tuning low-memory killer daemon
  - (5.2) Fixed status bar notification count not working after a reboot
  - (5.2) Fixed QuickSettings brightness icon color when using certain icon packs
  - (5.2) Fixed SmartPower Off Automatically working right after the feature was enabled
  - (5.2) Fixed realme link sign-in crash
  - (5.2) Fixed status bar max notification not going above 4
  - (5.2.1) Fixed ortus launcher memory leaks caused by QuickSpace
  - (5.2.1) Attempt to prevent more possible memory leaks 

- **System-Wide:** 
  - (5.2) Optimized and fixed layout issues on tablets or high dpi devices (600dp+)
  - (5.2) Fixed Android System Intelligence crashes on devices with missing mms-sms provider (e.g tablets)
  - (5.2.1) Added option to directly modify max cached processes

- **Advanced:** 
  - Added option to create virtual RAM/swap using adb or root (adb shell ram_boost.sh <size_in_gb> e.g adb shell ram_boost.sh 2 - creates 2gb swap) 
    - Helpful for legacy devices and does not conflict with ZRAM. Needs to be applied after every reboot.

- **AOD Image:** 
  - (5.1) Improved animation and resource usage

- **Bootanimation Styles:** 
  - Added option to change bootanimation
  - Added an option to import custom bootanimation [by Alvin Francis](https://github.com/nivlafx/)
  - (5.1) Fixed bootanimation styles not working after upgrade

- **Black Theme Styles:** 
  - Added black theme styles with Berry black and true amoled dark as choices

- **Cache Cleaner Service:** 
  - (5.1) Introducing cache cleaner service

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

- **Healthy Charge:** 
  - (5.2.1) Implemented Charge hold/pause feature

- **Island notification:** 
  - Added swipe to left/right to dismiss gesture
  - (5.1) Fixed island showing when navigating youtube playback

- **Lawnchair:** 
  - Updated lawnchair to 14.0.0-20240727 [by Alvin Francis](https://github.com/nivlafx/)
  - (5.2.1) Updated to 14.0.0-20240913 [by donjohanliebert](https://github.com/donjohanliebert/)

- **Lockscreen Clocks:** 
  - (5.1) Fixed crashed when a specific font is applied [by Alvin Francis](https://github.com/nivlafx/)

- **Ortus Launcher:** 
  - Implemented long press to search (for gestures only) 

- **Personalizations:**
  - (5.1) Re-organized theming and toolbox settings

- **Power modes:**
  - Introducing device power modes - control cpu and memory based from profiles
  - Added QS tile
  - (5.1) Conservative mode: Increased bias to lower frequencies 
  - (5.2) Integrated power modes into memory management
  - (5.2.1) Game boost mode now prioritizes top-app and limits background processes

- **Pulse Gestures:** 
  - (5.2) Single/Double tap to pulse doze
  - (5.2) Pickup to pulse doze

- **QuickSettings:**
  - Redesigned QS Data Usage UI

- **QS Widgets:**
  - Replaced tiles with connectivity tiles (wifi, bt, data, airplane mode)
  - Improved and updated layout
  - Added support for QS panel styles
  - Added QS Photo Widget
  - Fixed paddings for different DPIs
  - (5.1) Added long press to open wifi settings for internet tile
  - (5.2) Fixed visual landscape issues on light mode
  - (5.2) Fixed widget missing when rotating devices to landscape
  - (5.2.1) Fixed media player control buttons positioning
  - (5.2.1) Fixed oversized player icon
  - (5.2.1) Fixed random crash caused by media player widget

- **RAM Boost:**
  - Introducing ram boost feature - prioritize utilizing compressed memory (ZRAM) and swap space (if available) to improve overall performance.
  - Improved virtual memory tunings for performance

- **Settings Styles:** 
  - (5.1) Added option to toggle device showcase
  - (5.2) Added toggle for dashboard greetings and user card
  - (5.2.1) Minor UI enhancements
  - (5.2.1) Added OOS legacy and colorful (OOS) styles

- **Smart 5G service:**
  - (5.1) Implemented Smart 5G service - Automatically switch between 5G and 4G to reduce battery consumption [by Adithya R](https://github.com/adithya2306/)
    - RisingOS Edit: added more functionalities

- **Smart Power-Off Service:** 
  - (5.1) Smart Power-Off Service - an automated power off service with smart delay mechanism
  - (5.2.1) Alarm is now optional

- **Sound engine:**
  - (5.2) Removed audio profiles, replaced by adjustable loudness gain/bass boost settings (Works with dolby and other sounds mods - Tested on Xiaomi Mi Pad 5 with Moto Dolby)
  - (5.2) Added surround level settings

- **Spoofing:**
  - GameProps -> Per-app spoofing
  - Added option to directly update Play Integrity Fix properties
  - Added option to display currently set PIF properties

- **Toolbox:**
  - Added backup/restore feature settings [by Alvin Francis](https://github.com/nivlafx/)
  - (5.1) Added upload and restore from google drive feature [by Alvin Francis](https://github.com/nivlafx/)

---

## 💬 Highlights (Cherry-Picked Additions)
- **Added BCR support:**
  - Added Basic call recording support [Chaitanyakm, James, Andrew Gunnerson]

- **GameSpace:**
  - Improved floating app selection support by [YiQiuYes](https://github.com/YiQiuYes/)

- **Power modes:**
  - Implemented kernel tunings from KTweaks by [tytydraco](https://github.com/tytydraco/)
  
- **Security bypass features:**
  - Hide ADB and developer settings by [someone5678](https://github.com/someone5678/)
  - Hide Screen capture status from apps by [someone5678](https://github.com/someone5678/)
  - Storage Access Framework bypass by [rdxzv](https://github.com/rdxzv/)
  
- **Bootloader Spoofing:**
  - Added option to spoof as locked bootloader when spoofing GMS [by chiteroman](https://github.com/chiteroman/)
  
- **RefreshRate control enhancements:**
  - (5.1) Improved dynamic refresh rate scheduler [by arter97](https://github.com/arter97/)
  
- **Added Conditional LTE_CA toggle:**
  - (5.1) Added toggle for LTE_CA enablement [by DarkJoker360](https://github.com/DarkJoker360/)
  
- **Sleep mode:**
  - Added sleep mode feature by [Anushek Prasal](https://github.com/SKULSHADY/)
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


