# Wineskin
This project supports *macOS 10.15.4* and later.

<br>

## Want to help support this project?
[![ko-fi](https://img.shields.io/badge/kofi-Donate-blue?style=for-the-badge&logo=ko-fi)](https://ko-fi.com/gcenx)
[![PayPal](https://img.shields.io/badge/PayPal-Donate-blue?style=for-the-badge&logo=paypal)](https://www.paypal.com/paypalme/gcenx)

<br>

## How to install using [homebrew](https://brew.sh/)
```
brew install --cask --no-quarantine gcenx/wine/wineskin
```

<br>

## DirectX support

__WineD3D (default)__\
Supports DirectX 11 and below.
- OpenGL backend is used for DirectX 9 and below
- Vulkan backend is used for DirectX 10 & 11  
_When Enabled D3DMetal when takes over 64Bit DirectX 11 & DirectX 12_

__VKD3D (default)__\
Limited DirectX 12 support.\
__Requires WineCX23.x or later Engines__

__D3DMetal (toggle)__\
Supports 64Bit DirectX 11 & 12 via Metal.\
Since "Game porting toolkit" 1.0 beta 4 Apple now allows redistribution for none commercial uses.\
You can view  Apple's documentation [here](https://github.com/Gcenx/WineskinServer/tree/master/D3DMetal).\
__Requires an Apple Silicon mac running macOS Sonoma__

__D9VK__\
Supports DirectX 9 via Vulkan.

__DXVK__\
Supports DirectX 10 & 11 via Vulkan.\
_D3DMetal is forced when Enabled_

<br>

## Hackintosh Support?
__AMD__ based systems are not supported due to being unable to run 32Bit code on macOS.  
__Intel__ based systems should work without issue.

<br>

# FAQ
### My Antivirus says it's a VIRUS!!!
You need to contact your Antivirus/Anti-malware vendor to report these as false positives.\
This started once wine moved to using *Mingw-gcc* to compile PE binaries.

__See the following examples:__
- [CrossOver 19 and antivirus programs](https://www.codeweavers.com/support/forums/general/?t=27;msg=222870)
- [Windows Defender detects Occamy.c trojan in steam proton 5.0 folder](https://github.com/ValveSoftware/Proton/issues/3593)

<br>

## License for listed components
- `Wineskin Winery.app`
- `Wineskin.app`
- `wineskinaluncher`\
These keep the same as the original material LGPL2.1

<br>

## Want to contribute Wineskin
You can find the current sources [here](https://github.com/The-Wineskin-Project/wineskin-source)

## Credits
- [VitorMM](https://github.com/vitor251093) for modernizing the [Wineskin Codebase](https://github.com/vitor251093/wineskin) & [ObjectiveC_Extension](https://github.com/vitor251093/ObjectiveC_Extension).
- [PaulTheTall](https://www.paulthetall.com/) for constant test data and finding bugs.
- doh123 for creating [Wineskin](https://web.archive.org/web/20141218081028/http://wineskin.urgesoftware.com/tiki-index.php).
- [thmrtz](https://github.com/thmrtnz) for the issue template, documentation and the wiki.
