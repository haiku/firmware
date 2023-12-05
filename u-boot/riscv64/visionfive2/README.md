StarFive VisionFive V2 u-boot binaries
===================

This directory contains StarFive VisionFive V2 u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://www.starfivetech.com/en/site/boards>

Source information
-------------
> *Last Update:* Tue Dec  5 12:54:32 PM CST 2023

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot-spl.bin u-boot.itb
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Mon Dec 4 13:46:56 2023 -0500
  * **GIT Hash:** 2f0282922b2c458eea7f85c500a948a587437b63
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
  * **Toolchain version:** gcc version 12.2.0 (GCC) 
* **Build Commands:**
  * make starfive_visionfive2_defconfig
  * ARCH=riscv64 CROSS_COMPILE=riscv64-linux-gnu- make
