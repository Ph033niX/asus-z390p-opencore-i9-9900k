# asus-z390p-opencore-i9-9900k
Opencore Vanilla MacOS Catalina 10.15.6 Build EFI files for Hackintosh built on Asus Prime Z390 P &amp; Intel i9 9900K

# System Configuration
1. OpenCore version 0.5.9
2. MacOS Catalina 10.15.6
3. Processor: 3.6 GHz 8-Core Intel i9 9900K
4. Motherboard: Asus Prime Z390 P
5. Graphics: Intel UHD 630 & Nvidia 2080Ti (disabled via WhateverGreen) on an Acer 144hz monitor with full resolution & 144hz refresh rate

<strong>Note</strong>: Use the files for reference, make changes according to your requirements & then copy to EFI folder if you have the same motherboard & CPU configuration. It's generally not recommended to copy someone else's EFI folder as it is, as your system configuration might be a little different than mine, even if you've the same motherboard, CPU & GPU

# TO DO BEFORE COPYING FILES TO YOUR EFI DRIVE
1. <a href="https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html#prerequisites">Follow this guide</a> for initial setup & creating a bootable MacOS USB
2. Change SMBIOS, i.e "PlatformInfo", "MLB", "ROM", "SystemProductName", "SystemSerialNumber" &amp; "SystemUUID" using <a href="https://github.com/corpnewt/GenSMBIOS">GenSMBIOS</a>
3. If you have a supported AMD external GPU, remove <code>-wegnoegpu</code> from <code>boot-args</code> in config.plist
