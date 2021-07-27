QEMU RISCV64 u-boot binaries
===================

This directory contains QEMU RISCV64 u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://www.qemu.org>

Source information
-------------
> *Last Update:* Tue Jul 27 10:35:06 AM CDT 2021

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Mon Jul 26 20:57:18 2021 -0400
  * **GIT Hash:** b70b9b07463db2f6937c7ea6d7fb5122feb7ba1b
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make qemu-riscv64_smode_defconfig
  * ARCH=riscv64 CROSS_COMPILE=riscv64-linux-gnu- make
