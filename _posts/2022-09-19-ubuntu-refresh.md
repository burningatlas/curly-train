---
layout: post
title: Refresh - Ubuntu Ricing 
subtitle: removing the default GUI
tags: [playingwithOS]
odate: 19-09-2022
fdate: 19-09-2022
pdate: 19-09-2022
---
Felt the Default GUI for Ubuntu 22.04 was usual and boring. 

**Before**\
OS: Ubuntu 22.04 LTS\
DE: GNOME 40\
WM: Mutter\
DM: GDM

### GNOME 40 to MATE
So removed GNOME 40 and downloaded the MATE DE. Looked cool. Simple, explicit and Fast. But found out that MATE is GNOME 2, with no improvements over the DE. It is what it is. Tried looking at different ones. Like LXQt but it looks old and slow. Used Xfce in Kali and felt it's the best so far. Simple, Lean, Clean, Fast and consumes less resources.

**Intermediate**\
OS: Ubuntu 22.04 LTS\
DE: MATE\
WM: MATE\
DM: Light DM

### MATE to Xfce 
So downloaded Xfce DE for system. Since GNOME was removed, went ahead with Light Display Manager. This made it look good. But after removing MATE, had to install a new splash screen for Ubuntu and a new Display Manager using [plymouth](https://github.com/adi1090x/plymouth-themes). 

For a leaner better Display Manager, removed Light DM which had MATE theme to Ly. Terminal Style simple DM. When logging out, I do get some errors on Ly screen. But Booting ina nd out has no issues whatsoever.

**After**\
OS: Ubuntu 22.04 LTS\
DE: Xfce\
WM: Xfwm4\
DM: Ly

Transported Bindkeys (<10) for commonly used apps. \
For other apps, simple to use ROFI was downloaded with it's clear theme from [Eric Murphy](https://www.youtube.com/c/EricMurphyxyz).

The Xfce bar is simple and convenient. Riced it up! Looks sleeker than GNOME by a huge difference!