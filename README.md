# EFI_B550M-E_5600G
an OpenCore EFI for ASUS B550M-E-WIFI Motherboard with AMD Ryzen 5 5600G Processor + Radeon RX580 Graphics Card.

Specification
Motherboard : ASUS B550M-E-WIFI
CPU : AMD Ryzen 5 5600G with Radeon Graphics
RAM : Kingston DDR4 3200MHz 16GB
Storage : Kingston SNV2S1000G 1TB SSD
dGPU : AMD Radeon RX580 8GB
Wifi/BT : Intel® WI-Fi6 AX200 160MHz
Ethernet : Realtek RTL8111 Gigabit Ethernet
Boot Mode : UEFI
Bootloader : OpenCore 0.9.5
OS : macOS Monterey 12.7 + Windows 10 Enterprise

Whats Work?
QE/CI Graphics of RX580 + DRM 
(actually,at first I did not plug in this GPU in and it still normally booted but the system graphic shows GPU dram only 7MB, So I insert RX580 in and everything works like a charming)
CPU Power Management
Sleep/Wake
Shutdown and Restart
All USB Ports
Ethernet
Wifi
Bluetooth
HDMI
Audio 
Etc
What's not work?
Airdrop did not response as intel wirelessc card is not supoorted, if you need this function then replace it with BCM943602CS or BCM94360CS 

Tutorial
From Zero Tutorial : https://dortania.github.io/OpenCore-Install-Guide/
Creating the USB Installer : https://dortania.github.io/OpenCore-Install-Guide/installer-guide/
Generating SMBIOS : https://github.com/corpnewt/GenSMBIOS
USB Fixes : https://dortania.github.io/OpenCore-Post-Install/usb/ and https://github.com/usbtoolbox/tool
Tutorial on "USB Fixes" related to the UTBMap.kext and SSDT-SLEEP.aml files. Please pay close attention to the guidelines that have been provided.

I spent times to make this stuff work normally through the internet searching so hope this repository could help you as well.
All kinds of errors and kernel panics, beyond my responsibility.

![Screen Shot 2023-10-04 at 18 19 34](https://github.com/by6et/EFI_B550M-E_5600G/assets/32999706/7aa7160f-fa02-48a4-8319-74ba87002cfc)


