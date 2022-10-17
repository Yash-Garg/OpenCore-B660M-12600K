# Hackintosh OpenCore + Intel Alder Lake Core i5-12600K + MSI PRO B660M-A DDR4 + GeForce GT 710 / GT 1030

---

| Bootloader | Version | Boot Mode |  SMBIOS   |  macOS  | Version |
| :--------: | :-----: | :-------: | :-------: | :-----: | :-----: |
|  OpenCore  |  0.8.5  |   UEFI    | MacPro7,1 | Big Sur, Monterey |  11.7, 12.6   |

---

![About Mac - Monterey](https://user-images.githubusercontent.com/33605526/196194312-2933f0f1-bb36-486e-8d46-c8d5a5c61a7c.png)

![About Mac - Big Sur](https://user-images.githubusercontent.com/33605526/196044494-014608e1-1bc7-4066-83ef-147f4f136819.png)

![CPU Benchmark](https://user-images.githubusercontent.com/33605526/196029372-58923acb-a3c3-42b9-ba35-1c1c60ee9568.png)

## Specifications:

- 12th Gen Intel Alder Lake Core i5 - 12600K
- MSI PRO B660M-A DDR4
  - Audio Realtek [ALC897](https://github.com/acidanthera/AppleALC/wiki/Supported-codecs) `alcid=11`
  - Realtek Gaming 2.5GbE Family Controller
- NVIDIA GeForce GT 710 **(currently using as it's natively supported on Big Sur)**
- NVIDIA GeForce GT 1030 **(revert [043b44](https://github.com/Yash-Garg/OpenCore-B660M-12600K/commit/043b4400f6ddc1516d042cb8f3a7ff76529b3adb) and install [webdrivers](https://elitemacx86.com/threads/how-to-enable-nvidia-webdrivers-on-macos-big-sur-and-monterey.926/))**
- Samsung SSD 970 EVO Plus 500GB **(Windows)**
- WD Passport 500GB External HDD **(macOS)**
- 2 x Seagate 1TB Barracuda 7200RPM HDD
- Lenovo 300 FHD Webcam
- MSI G241V Gaming Monitor 75Hz
- Corsair 4000D Black Case

## What's Working:

- [x] Ethernet
- [x] Audio In/Out **(Motherboard and Front Panel)**
- [x] All USB Ports
- [x] GPU with Metal Support
- [x] Sleep/Wake/Restart/Shut Down **(works with TPM enabled)**
- [x] USB Devices **(Webcam, Keyboard, Mouse, etc.)**
- [x] Secure Boot **(Follow [this guide](https://github.com/perez987/OpenCore-and-UEFI-Secure-Boot), won't work with webdrivers)**
- [ ] Type C Port
- [ ] Display Ports **(couldn't check)**
- [ ] DRM **(won't work on my GPU)**

## Credits:

- [OpenCore Dortania](https://dortania.github.io/OpenCore-Install-Guide/)

- [OpenCore Alder Lake (12th-Gen Intel) Hackintosh Guidance](https://www.reddit.com/r/hackintosh/comments/sp1zgv/opencore_alder_lake_12thgen_intel_hackintosh/)

- [OpenCore-Install-Guide by alyxferrari](https://github.com/alyxferrari/OpenCore-Install-Guide/blob/alderlake/config.plist/alder-lake.md)
