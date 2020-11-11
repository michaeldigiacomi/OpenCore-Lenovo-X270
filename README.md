# Lenovo-X270-Hackintosh-BigSur-OpenCore-0.6.3
This repo contains the files and scripts to install macOS on the Lenovo X270 family

![X270](Images/screen.png)

# Update History
- [x] macOS 11.0.1 Beta 3
- [x] macOS 11.0.1 RC 2

# Laptop's Hardware
- <b>Model</b>: Thinkpad X270
- <b>Bios</b>: 1.43
- <b>CPU</b>: Intel(R) Core(TM) i5-6300U CPU @ 2.40GHz
- <b>GPU</b>: Intel HD Graphics 520
- <b>RAM</b>: 16 GB 2400MHz DDR4
- <b>Screen</b>: 14" FHD (1920x1080) IPS
- <b>Wi-Fi</b>: DW-1820a
- <b>Camera</b>: 720p
- <b>Battery</b>: 6-cell 

# Bios settings

<b>Security</b>
- `Security Chip` **Disabled**
- `Memory Protection -> Execution Prevention` **Enabled**
- `Virtualization -> Intel Virtualization Technology` **Enabled**
- `Virtualization -> Intel VT-d Feature` **Enabled**
- `Anti-Theft -> Computrace -> Current Setting` **Disabled**
- `Secure Boot -> Secure Boot` **Disabled**
- `Intel SGX -> Intel SGX Control` **Disabled**
- `Device Guard` **Disabled**

<b>Startup</b>
- `UEFI/Legacy Boot` **UEFI Only**
- `CSM Support` **No**

# What's Working?
- [x] Intel HD 520 Graphics (incuding graphics acceleration)
- [x] CPU Power Management
- [x] Battery
- [x] All USB ports
- [x] HDMI port (including HDMI Audio)
- [x] Intel Ethernet port
- [x] Realtek Audio (including headphones jack)
- [x] Internal camera (including Facetime)
- [x] Trackpad (gestures work but not the trackpad click. tap to click works.)
- [x] Shutdown / Reboot 
- [x] Keyboard (incuding all fn Keys)
- [x] iMessage, FaceTime, App Store, iTunes Store (with valid smbios)
- [x] DRM support (iTunes Movies, Apple TV+, Amazon Prime and Netflix, and others)
- [x] SD Card Reader (v2.2 works but still a bit unstable)

# What's not working ⚠️
- [x] Sleep / Wake (lid sleep and lid wake)
- [x] Wi-Fi & Bluetooth (including Apple services)
- [x] Trackpoint and physical buttons
