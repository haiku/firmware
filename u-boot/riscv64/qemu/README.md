QEMU RISCV64 u-boot binaries
===================

This directory contains QEMU RISCV64 u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://www.qemu.org>

Source information
-------------
> *Last Update:* Fri Aug 13 08:28:30 AM CDT 2021

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Fri Aug 13 08:37:47 2021 -0400
  * **GIT Hash:** 85ccbf666e549f0b06c29d565b9e4fdd87cf6600
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make qemu-riscv64_smode_defconfig
  * ARCH=riscv64 CROSS_COMPILE=riscv64-linux-gnu- make
