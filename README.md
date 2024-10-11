# Kegworks
A wrapper project that's the successor to Wineskin\
This project supports *macOS 10.15.4* or later.

<br>

## Want to help support this project?
[![ko-fi](https://img.shields.io/badge/kofi-Donate-blue?style=for-the-badge&logo=ko-fi)](https://ko-fi.com/gcenx)
[![PayPal](https://img.shields.io/badge/PayPal-Donate-blue?style=for-the-badge&logo=paypal)](https://www.paypal.com/paypalme/gcenx)

<br>

> [!NOTE]
> How to install using [homebrew](https://brew.sh/)
> ```
> brew upgrade
> brew uninstall --force --zap wineskin
> brew install --cask --no-quarantine gcenx/wine/kegworks
> ```

<br>

> [!IMPORTANT]
> DirectX support
> - WineD3D (default) Supports DirectX 11 and below.
> - VKD3D (default) Limited DirectX 12 support.
> - D3DMetal (toggle) 64Bit DirectX 11 & 12 via Metal.
> - D9VK (winetricks) DirectX 9 via Vulkan.
> - DXVK (winetricks) DirectX 10 & 11 via Vulkan.

<br>

> [!CAUTION]
> My Antivirus says it's a VIRUS!!!\
> You need to contact your Antivirus/Anti-malware vendor to report these as false positives.\
> This started once wine moved to using *Mingw-gcc* to compile PE binaries.
> 
> __See the following examples:__
> - [CrossOver 19 and antivirus programs](https://www.codeweavers.com/support/forums/general/?t=27;msg=222870)
> - [Windows Defender detects Occamy.c trojan in steam proton 5.0 folder](https://github.com/ValveSoftware/Proton/issues/3593)

<br>

## Components that fall under LGPL-2.1 license
- `Kegworks Winery.app` (renamed/tweaked Wineskin Winery)
- `Wineskin.app` (tweaked)

<br>

## Components that don't fall under LGPG-2.1 license
_Kegworks Winery-2.0.3/Wineskin-3.0.6-1 or greater_
- `wineskinlauncher` (Kegworks in wineskin compatability mode)\
_Kegworks Winery & Wineskin.app are being used temporarily_

<br>

## Credits
- [VitorMM](https://github.com/vitor251093) for modernizing the [Wineskin Codebase](https://github.com/vitor251093/wineskin) & [ObjectiveC_Extension](https://github.com/vitor251093/ObjectiveC_Extension) & writting Kegworks-App from the ground up.
- [PaulTheTall](https://www.paulthetall.com/) for constant test data and finding bugs.
- doh123 for creating [Wineskin](https://web.archive.org/web/20141218081028/http://wineskin.urgesoftware.com/tiki-index.php).
- [thmrtz](https://github.com/thmrtnz) for the issue template, documentation and the wiki.
- [Gcenx](https://github.com/Gcenx) for maintaing the Wine Engines & upstream Winehq packages.
