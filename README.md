# OpenWrt 25.12.5 Build Guide for Banana Pi BPI-R4-8P

> **Release 1.1** • **OpenWrt 25.12.5** • **Linux Kernel 6.12.94**

A comprehensive and tested guide to building OpenWrt 25.12.5 from source for the Banana Pi BPI-R4-8P platform.

---

## Overview

This repository contains comprehensive documentation describing the complete build process of OpenWrt 25.12.5 for the Banana Pi BPI-R4-8P platform.

The guide is based on a fully validated build performed on real hardware equipped with the Banana Pi BPI-R4-NIC-BE14 (MediaTek MT7996) wireless module. It combines all required steps into a single reference, from preparing the build environment to flashing the firmware and verifying the final installation.

Both **English** and **Russian** editions are included.

---

## Tested Hardware

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
- Applying the MT7996 transmit power patch
- Building the firmware
- Verifying the build process
- Installing the BL2 bootloader for 8 GB RAM support
- Expanding the eMMC partition
- Post-installation verification
- Troubleshooting

---

## Repository Contents

| Path | Description |
|------|-------------|
| `docs/` | English and Russian documentation (PDF and DOCX) |
| `patches/` | MT7996 transmit power patch used during the build |
| `README.md` | Project overview |
| `CHANGELOG.md` | Version history |
| `LICENSE` | Documentation license |

---

## Compatibility

The guide has been verified using:

- Banana Pi BPI-R4-8P
- Banana Pi BPI-R4-NIC-BE14 (MediaTek MT7996)
- OpenWrt 25.12.5
- Linux Kernel 6.12.94

Future OpenWrt releases may require minor adjustments.

---

## Author

**Andreas_Caliban**

GitHub Profile: https://github.com/AndreasCaliban

---

## License

The documentation in this repository may be freely shared and adapted with appropriate attribution to the original author.

---

## Acknowledgements

Special thanks to:

- OpenWrt Project
- Banana Pi Team
- ImmortalWrt developers

for their outstanding work and continuous contributions to the open-source community.

---

## Feedback

If you find inaccurate information, have suggestions for improvement, or would like to contribute to the documentation, please feel free to open an Issue.

Feedback is always appreciated.

---

⭐ If this guide helped you, please consider giving this repository a star.
