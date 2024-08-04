# X570 Gigabyte Aorus Master - MacOS Ventura

![MacOS System](https://github.com/radueduard97/Aorus-X570-Master-Ventura-Hackintosh/blob/master/SCR-20240805-bnlk.png)

## What is this?

This repository contains working EFI for motherboard X570 Gigabyte Aorus Master paired with Ryzen 5800x3D and RX6900XT in order to boot MacOS Ventura with working Wi-FI  & Bluetooth and hardware acceleration.

## Components

| **Component** | **Product Name** |
|----|----|
| Motherboard | Gigabyte X570 Aorus Master |
| CPU | Ryzen 7 5800x3D |
| RAM | 65GB (4x16) Corsair RGB PRO  |
| GPU | Sapphire Nitro + 6900XT |
| SSD1 | ADA S70 Blade ( MacOS) |
| SSD2 | Samsung 970 Evo + ( Windows) |
| PSU | 1200W Platinum |
| BT/WI-FI | Fenvi T919 (MacOS) / Intel AX 201 ( Windows ) |
| Ethernet 1 | Realtek 2.5Gb (integrated in the motherboard) |
| Ethernet 2 | Intel 1GB (integrated in the motherboard) |


## What does work?

* IServices ( IMessages & Facetime )
* Bluetooth
* Wi-FI
* Hardware Acceleration
* Both ethernet adapters are working
* Sound 
* Almost everything ….

## What does not work?

* Sidecar

## Important notes

* I do not recommend using this specific EFI, you should always build one yourself for your specific components.
* If you plan to grab this, make sure you fill in the Platform Info section in the `config.plist` file.
* I do not recommend trying to boot Sonoma with this one as Wi-Fi and Bluetooth won't work even if you do have a Fenvi card in your PC.
* You can make Wi-FI work in Sonoma using `Airportltlwm.kext`. I haven't managed tough to get the integrated bluetooth working in Sonoma, you could get a cheat ASUS BT400 card and it should work.


**Make sure to always refer the guide in <https://dortania.github.io/OpenCore-Install-Guide/>.**

