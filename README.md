# Ryzentosh
This repo contains EFI needed to boot into macOS Catalina on non-Apple hardware.  
The bootloader of choice is OpenCore 0.5.9.  
Configuration files were made by following the official OpenCore guide on [dortania.github.io](https://dortania.github.io/OpenCore-Install-Guide/).  

## Why is this useful?
If you are struggling to make your own config.plist or you are just lazy, this EFI folder could give you a headstart for the following hardware:  
* Ryzen 3600
* MSI B450 Tomahawk MAX
* XFX RADEON RX 580  

If you have the exact hardware no further configuration should be required because the OC folder already contains correct kexts, drivers and config.plist with applied kernel patch for Ryzen processor. Audio, Ethernet and other essential desktop pc things are working flawlessly.

## Note
There is a high chance that by the time you are reading this OpenCore was updated several times. If that is the case make sure to check the config.plist for deprecated options on [OpenCore Sanity Checker](https://opencore.slowgeek.com/) and adjust it with the tools provided in the offical guide.
