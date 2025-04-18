StarFive VisionFive V2 u-boot binaries
===================

This directory contains StarFive VisionFive V2 u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://www.starfivetech.com/en/site/boards>

Source information
-------------
> *Last Update:* Thu Apr 17 08:18:40 PM CDT 2025

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot-spl.bin u-boot.itb
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Thu Apr 17 07:52:02 2025 -0600
  * **GIT Hash:** 278be62c052f3a5749c3c7a57bcd307b82dcdc2d
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
  * **Toolchain version:** gcc version 14.2.0 (GCC) 
* **Build Commands:**
  * make starfive_visionfive2_defconfig
  * ARCH=riscv64 CROSS_COMPILE=riscv64-linux-gnu- make
