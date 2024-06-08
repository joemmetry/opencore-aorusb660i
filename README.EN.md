# Intel B660I Chipset + Intel Alder Lake CPU OpenCore EFI

### [日本語](https://github.com/joemmetry/opencore-aorusb660i/blob/master/README.md)

EFI Folder for OpenCore Bootloader.
Created with the help of [OpenCore Vanilla Desktop Guide](https://khronokernel-2.gitbook.io/opencore-vanilla-desktop-guide/).

<img src="https://scontent.fmnl17-2.fna.fbcdn.net/v/t1.6435-9/206743122_10216513288344107_3539624459220602424_n.jpg?_nc_cat=109&_nc_rgb565=1&ccb=1-3&_nc_sid=0debeb&_nc_ohc=GIahA9UCavwAX-0qNjY&_nc_ht=scontent.fmnl17-2.fna&oh=26a8b3847e6d7f8eaf644a7e4826a00f&oe=60F11940"/>

### Features

- Support up to macOS 14.5
- GUI boot menu enabled
- Triple-boot (macOS, Windows, Ubuntu)
- Bootcamp works

### Software Versions

- macOS Sonoma 14.5 (23F79)
- Windows 11
- Ubuntu 24.04
- OpenCore 1.0.0

### System Components

| **Component**       | **Model**                                      |
| ------------------- | -----------------------------------------------|
| CPU                 | Intel Core i5 12400                            |
| Motherboard         | Gigabyte Aorus Pro DDR4 B660I                  |
| RAM                 | 48GB (32+16GB) Corsair Vengeance LPX @ 3600MHz |
| Audio               | Realtek ALC897 Codec                           |
| GPU                 | AMD Radeon RX 6600 XT 8GB                      |
| Wi-Fi and Bluetooth | Broadcom BCM94360CS2                           |
| Ethernet            | Intel Ethernet Controller i225-LM              |
| OS Disk (SSD)       | Western Digital Black SN850X 1TB               |

### Working

CPU, RAM, Fans, Cooling etc. ✔<br/>
Audio ✔<br/>
Ethernet ✔<br/>
Graphics ✔<br/>
HDMI ✔<br/>
Sleep/wake Function ✔<br/>
Power Management ✔<br/>
App Store ✔<br/>
iMessage ✔<br/>
iCloud ✔<br/>
FaceTime ✔<br/>
USB ✔<br/>
Bootloader ✔<br/>
HDMI Audio ✔<br/>
Volume Hotkeys ✔<br/>
Wi-Fi ✔<br/>
Bluetooth ✔<br/>
AirDrop ✔<br/>
HandOff ✔<br/>
Docker (only Docker machine works) ✔<br/>

### Not Working

Side Car ✗<br/>

### Quick Notes

1. Kernel extensions are not included in this repo. Go to [acidanthera](https://github.com/acidanthera) and other providers to download the latest versions.
2. There are some macOS functions that aren't working because of limited Apple support.
3. This repo is just for learning how to configure your own EFI, simply copying this and putting in the EFI partition will not make the system boot properly.

### Sources

- [OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)
- [AMD Vanilla OpenCore](https://github.com/AMD-OSX/AMD_Vanilla)
- [OpenCore EFI and Kexts](https://dortania.github.io/builds/)
