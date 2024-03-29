# Opencore Configuration for Ryzen 7 5700g, MSI MAG B550 Tomahawk, RX6600XT

<div align="center">

  [![GitHub release (latest by date)](https://img.shields.io/github/v/release/Lenochxd/Hackintosh-r7-5700g-msiB550-rx6600xt.svg?style=flat)](https://github.com/Lenochxd/Hackintosh-r7-5700g-msiB550-rx6600xt/releases)
  [![GitHub downloads](https://img.shields.io/github/downloads/Lenochxd/Hackintosh-r7-5700g-msiB550-rx6600xt/total.svg?style=flat)](https://github.com/Lenochxd/Hackintosh-r7-5700g-msiB550-rx6600xt/releases)
  [![GitHub stars](https://img.shields.io/github/stars/Lenochxd/Hackintosh-r7-5700g-msiB550-rx6600xt.svg?style=flat)](https://github.com/Lenochxd/Hackintosh-r7-5700g-msiB550-rx6600xt/stargazers)
  [![GitHub issues](https://img.shields.io/github/issues/Lenochxd/Hackintosh-r7-5700g-msiB550-rx6600xt.svg?style=flat)](https://github.com/Lenochxd/Hackintosh-r7-5700g-msiB550-rx6600xt/issues)
  [![Discord](https://img.shields.io/discord/391919052563546112?style=flat&logo=Discord&logoColor=fff&label=Discord&color=5e6ae8&link=https%3A%2F%2Fdiscord.gg%2FtUPsYHAGfm)](https://discord.gg/tUPsYHAGfm)
</div>

This repository contains the necessary EFI folder for running macOS on this system configuration. Please be aware that this configuration is currently optimized for use with sonoma 14.3.1, and is still a work in progress.


**IMPORTANT: Please ensure that you change the serial numbers in config.plist to avoid conflicts. You can easily change the serial numbers using        [Opencore Configurator](https://mackie100projects.altervista.org/download-opencore-configurator/).**

## System Specifications
- Processor: Ryzen 7 5700G
- Memory: 16GB DDR4 RAM @ 2667MHz
- Storage: 
  - 128GB EMTEC SATA NVME (Primary Drive)
  - 3TB HDD
- Motherboard: MSI MAG B550 Tomahawk
- Graphics Card: XFX RX6600XT

## Compatibility
| macOS Version | Compatibility |
|---------------|---------------|
| 14.3 and earlier | ✅             |
| 14.4            | ❌             |

## Features
| Component                        | Compatibility |
|----------------------------------|---------------|
| Audio                            | ✅             |
| USB                              | ✅             |
| GPU Acceleration and GPU Encoding| ✅             |
| Ethernet                         | ✅             |
| SATA and NVMe drives             | ✅             |

**Note:** There might be a known issue with the audio driver causing Discord to crash when joining a voice chat (discord fault). In such cases, consider using the [Vesktop Client](https://github.com/Vencord/Vesktop) as an alternative.


## Installation Guide
To install, simply drag and drop the EFI folder onto the root of your EFI partition and let the magic happen! Depending on your specific hardware configuration, you may need to adjust some kexts.

**REMINDER: Make sure to CHANGE THE SERIAL NUMBERS in config.plist to avoid conflicts with existing serials. The current serial number is already in use.**
