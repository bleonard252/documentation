# dahliaOS on 64-efi

# Installation 

- dahliaOS supports a wide range of devices. This guide will tell you how to flash it on a USB and what hardware you need.

## Flash the ISO

There are two ISOs to choose from, **EFI** and **Legacy**.

- Most devices can only run the **EFI ISOs**, for older, **legacy devices** you can can check the instructions [here](x86_64-legacy.md).

1. Go to [releases](https://github.com/dahliaos/releases/releases/download/201215-x86_64/dahliaOS-201215-efi.zip) and download the zip file.
2. Then download [etcher](https://www.balena.io/etcher/) and flash the .zip file on a USB.
3. You're almost good to go, reboot your system and go in your UEFI and go to the **Boot** tab and select the USB.
4. Your system should boot into dahliaOS.

## Requirements

### Minimum requirements

- You need at least **512 MB of RAM** and a **64 bit** dual core processor with **Intel HD graphics**

### Recommended requirements

**2 GB of RAM** and **a 64 bit** quad core processor with **Intel HD graphics**

**Note: Nvidia graphics won't work well, use onboard graphics for the best result.**

## License

<a href="https://dahliaos.io?utm_source=docsifyjsdocs" target="_blank"><img src="https://github.com/dahliaos/brand/blob/master/Logo%20SVGs/dahliaOS%20logo%20with%20text%20(drop%20shadow).svg" width="300px"></a>

Copyright © The dahliaOS authors, contact@dahliaos.io

This project is licensed under the [Apache 2.0 license](../LICENSE)