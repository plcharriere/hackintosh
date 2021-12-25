# Hackintosh

This repository contains my EFI folders and bootloaders configurations to boot macOS on my computers.

If you want to use them, don't forget to generate your own SMBIOS and update your config.plist files.

## Clone

To clone and download configurations, use the following command :

```git clone --recurse-submodules https://github.com/plcharriere/hackintosh.git```

# Models

## MSI Z97 Gaming 5

### Specifications :

- Motherboard : [MSI Z97 Gaming 5](https://msi.com/Motherboard/z97-gaming-5.html)
- CPU : [Intel Core i5-4690k](https://ark.intel.com/content/www/us/en/ark/products/80811/intel-core-i5-4690k-processor-6m-cache-up-to-3-90-ghz.html)
- GPU : Intel HD Graphics 4600

### Bios settings :

`Settings > Advanced > Integrated Graphics Configuration`

- Set `Initiate Graphic Adapter` to `IGD`
- Set `Integrated Graphics Shared Memory` to `64M`

`OC > CPU Features`

- Set `Intel VT-D Tech` to `Disabled`
- Set `CFG Lock` to `Disabled`

## Asus VivoBook 15 X510UF

### Specifications :

- CPU : [Intel Core i7-8550U](https://ark.intel.com/content/www/us/en/ark/products/122589/intel-core-i7-8550u-processor-8m-cache-up-to-4-00-ghz.html)
- GPU : Intel HD Graphics 620

## Lenovo ThinkPad T14s

### Specifications :

- CPU : [Intel Core i7-10610U](https://ark.intel.com/content/www/us/en/ark/products/201896/intel-core-i710610u-processor-8m-cache-up-to-4-90-ghz.html)
- GPU : Intel HD Graphics 620

### What's not working :

- HDMI Port
- Thunderbolt port
- Internal Microphone
- Card reader
- Fingerprint reader

## Credits

- [OpenCore Bootloader](https://github.com/acidanthera/OpenCorePkg)
- [Clover Bootloader](https://github.com/CloverHackyColor/CloverBootloader)
- [acidanthera](https://github.com/acidanthera) for OpenCore & Kexts
- [tctien342](https://github.com/tctien342/Asus-Vivobook-S510UA-Hackintosh) for Asus Patches & Kexts
- [Dortania](https://dortania.github.io/getting-started/) for everything