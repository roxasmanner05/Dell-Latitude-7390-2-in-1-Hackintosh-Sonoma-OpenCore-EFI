 # Dell Latitude 7390 2-in-1 Hackintosh Sequoia with OpenCore 1.0.5

<img width="1920" height="1080" alt="Screenshot 2025-07-25 at 23 39 21" src="https://github.com/user-attachments/assets/ef49e4ec-26ba-442f-aea1-912d0bb63ba3" />

-----


[![OpenCore](https://img.shields.io/badge/1.0.5-opencore?style=flat&logoColor=grey&logoSize=auto&label=OpenCore&labelColor=grey&color=blue)](https://github.com/acidanthera/OpenCorePkg/releases/tag/1.0.5)



Used almost all of the SSDTs from [PurpleCrumpet's project](https://github.com/PurpleCrumpets/Hackintosh-Dell-Latitude-7390-2-in-1-OpenCore-EFI) (except SSDT-PLUG) and a couple of kexts was updated for OpenCore ```1.0.5``` EFI, this project was for MacOS Sonoma ```14.7.6```.

<br>**My Laptop Specs and Configuration 💻**</br>
<details>

| Laptop              | Dell Latitude 7390 2-in-1                                                                                  |
|:-------------------|:----------------------------------------------------------------------------------------------------------|
| Processor          | Intel Core i5-8350U vPro (4C, 8T,  1.7GHz / 3.6GHz)               |                                             
| Graphics           | Integrated Intel UHD 620 Graphics                                                                        |
| Memory             | 16 GB LPDDR3 2133MHz Soldered                                                 |
| Display            | 13.3" FHD (1920x1080) WVA, Touchscreen with Wacom Pen Support                                                                      |
| Storage            | 256GB Intel SSD                                                                               |
| Wifi Card           | Intel Wifi AC8265 + Bluetooth 4.2                                        |
| Battery            | 60Whr Battery                     |
|Touchpad            | ELAN Touchpad    |
</details>

## What Works

- Sleep (sleep works only when the lid was open)
- MicroSD card reader
- All USB ports (i don't know about Thunderbolt 3 because i don't have any Thunderbolt device)
- HDMI
- Webcam
- Touchpad (touchpad buttons can only be used for 1 button purpose) 
- Touchscreen (works as a giant touchpad)
- Pen support (?) (i don't have any Wacom stylus so i'm not sure)
- Keyboard
- iMessage and Facetime works (but you have to add your own SMBIOS from [here](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/kaby-lake.html#platforminfo)
- Wifi and Bluetooth (Bluetooth were a bit picky to some devices)
- Apple Audio DRM (Apple Music)
- Brightness functions (Fn + Arrow up/down) thanks to [@superguyadi](https://github.com/superguyadi)'s [tips](https://github.com/PurpleCrumpets/Hackintosh-Dell-Latitude-7390-2-in-1-OpenCore-EFI/issues/3)
- Airdrop, Airplay (only 1 way) thanks to [@randomappleboi](https://github.com/randomappleboi)'s guide [here](https://github.com/randomappleboi/Native-Wifi-for-Hackintoshes-with-Intel-Wireless-cards-on-macOS-sequoia)

## What Doesn't Work
- Wake from hibernate (closed lid)
- Apple Video DRM (Apple TV+,...)
