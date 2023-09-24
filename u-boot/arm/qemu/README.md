QEMU ARM u-boot binaries
===================

This directory contains QEMU ARM u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://www.qemu.org>

Source information
-------------
> *Last Update:* Fri Mar  3 05:49:48 PM CET 2023

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Mon Jan 9 11:07:33 2023 -0500
  * **GIT Commit:** 62e2ad1ceafbfdf2c44d3dc1b6efc81e768a96b9 v2023.01
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
  * **Toolchain version:** gcc version 11.3.0 (GCC) 
* **Build Commands:**
  * make qemu_arm_defconfig
  * ARCH=arm CROSS_COMPILE=arm-unknown-haiku- make
