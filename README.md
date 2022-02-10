# Lenovo-X270-Hackintosh-Monterey-OpenCore-0.7.6
This repo contains the files and scripts to install macOS on the Lenovo X270 20K5


![X270](Images/screen.png)

# Update History
- [x] macOS 12.1
- [x] macOS 12.2

# Laptop's Hardware
- <b>Model</b>: Thinkpad X270
- <b>CPU</b>: Intel(R) Core(TM) i5-6300U CPU @ 2.50GHz
- <b>GPU</b>: Intel HD Graphics 520
- <b>RAM</b>: 8 GB 2133MHz DDR4
- <b>Screen</b>: 12,4" (1366x768)
- <b>Wi-Fi</b>: AC-8260
- <b>Camera</b>: 720p
- <b>Battery</b>: 3-cell with inside battery 

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
- [x] Wi-Fi & Bluetooth (including Apple services)
- [x] iMessage, FaceTime, App Store, iTunes Store (with valid smbios)
- [x] DRM support (iTunes Movies, Apple TV+, Amazon Prime and Netflix, and others)
- [x] SD Card Reader (v2.2 works but still a bit unstable)
- [x] Sleep / Wake (lid sleep and lid wake) (works for me you can try for yourself)

# What's not working ⚠️
- [x] Everything looks perfect for now 

