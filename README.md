# OpenWrt 25.12.5 Build Guide for Banana Pi BPI-R4-8P

> **Release 1.1** • **OpenWrt 25.12.5** • **Linux Kernel 6.12.94**

A comprehensive and tested guide to building OpenWrt 25.12.5 from source for the Banana Pi BPI-R4-8P platform.

---

## Overview

This repository contains comprehensive documentation describing the complete build process of OpenWrt 25.12.5 for the Banana Pi BPI-R4-8P.

The guide is based on a fully validated build performed on real hardware equipped with the Banana Pi BPI-R4-NIC-BE14 (MediaTek MT7996) wireless module. It brings together all required steps into a single reference, from preparing the build environment to building the firmware, installing the appropriate BL2 bootloader for 8 GB RAM support, expanding the eMMC partition, and verifying the final installation.

Both **English** and **Russian** editions are included.

---

## Tested Environment

| Component | Specification |
|-----------|---------------|
| Board | Banana Pi BPI-R4-8P |
| SoC | MediaTek MT7988 |
| Memory | 8 GB LPDDR4 |
| Storage | eMMC |
| Wireless Module | Banana Pi BPI-R4-NIC-BE14 |
| Wireless Chipset | MediaTek MT7996 |
| OpenWrt Release | 25.12.5 |
| Linux Kernel | 6.12.94 |

---

## Guide Contents

The documentation covers:

- Preparing the build environment
- Downloading the OpenWrt source code
- Configuring the build system
- Obtaining the required BL2 bootloader image and MT7996 patch
- Building the firmware
- Verifying the build process
- Installing the appropriate BL2 bootloader for 8 GB RAM support
- Expanding the eMMC partition
- Post-installation verification
- Troubleshooting

---

## Repository Contents

| Path | Description |
|------|-------------|
| `docs/` | English and Russian editions of the guide (PDF and DOCX) |
| `README.md` | Project overview |
| `CHANGELOG.md` | Version history |

---

## External Resources

This guide references several external resources, including the BL2 bootloader image and the MT7996 transmit power patch.

To ensure you always use the latest available versions, please obtain these files from their respective official repositories, as referenced throughout the documentation.

---

## Author

**Andreas_Caliban**

GitHub Profile: https://github.com/AndreasCaliban

---

## Acknowledgements

This guide would not have been possible without the outstanding work of the following open-source projects and communities:

- **OpenWrt Project**  
  https://github.com/openwrt/openwrt

- **Banana Pi (BPI-SINOVOIP)**  
  https://github.com/BPI-SINOVOIP

- **ImmortalWrt Project**  
  https://github.com/immortalwrt/immortalwrt

- **Frank Wunderlich (frank-w)**  
  https://github.com/frank-w/u-boot

Their work made this guide possible.

---

## Feedback

If you find inaccurate information, have suggestions for improvement, or would like to contribute to the documentation, please feel free to open an Issue.

Feedback is always appreciated.

---

⭐ If this guide helped you, please consider giving this repository a star.
