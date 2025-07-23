 # Dell Latitude 7390 2-in-1 Hackintosh Sonoma with OpenCore 1.0.5

<img width="1920" height="1080" alt="Screenshot 2025-07-23 at 23 21 03" src="https://github.com/user-attachments/assets/5b6753dc-dd55-4d7b-8aa2-961540bf73ec" />

-----

<img alt="Static Badge" src="https://img.shields.io/badge/1.0.5-opencore?style=flat&logoColor=grey&logoSize=auto&label=OpenCore&labelColor=grey&color=blue&link=https%3A%2F%2Fgithub.com%2Facidanthera%2FOpenCorePkg">



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
- HDMI (HDMI works but with purple tinge)
- Webcam
- Touchpad (touchpad buttons can only be used for 1 button purpose) 
- Touchscreen (works as a giant touchpad)
- Pen support (?) (i don't have any Wacom stylus so i'm not sure)
- Keyboard
- iMessage and Facetime works (but you have to add your own SMBIOS from [here](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/kaby-lake.html#platforminfo)
- Wifi and Bluetooth (Bluetooth were a bit picky to some devices)

## What Doesn't Work
- Woke from hibernate (closed lid)
- As PurpleCrumpet's said, the brightness keys (currently mapped to Function + S, Function + B) are not mapped to the arrow keys.
- Airdrop, Airplay,... (Airporttlwm kext doesn't support Airdrop and Airplay anyway)
