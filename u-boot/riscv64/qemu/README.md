QEMU RISCV64 u-boot binaries
===================

This directory contains QEMU RISCV64 u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://www.qemu.org>

Source information
-------------
> *Last Update:* Sun Apr  6 10:55:04 AM CDT 2025

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Fri Apr 4 09:02:37 2025 -0600
  * **GIT Hash:** 848f7ffc64aa7c4cc2229095812625c12343c8c1
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
  * **Toolchain version:** gcc version 14.2.0 (GCC) 
* **Build Commands:**
  * make qemu-riscv64_smode_defconfig
  * ARCH=riscv64 CROSS_COMPILE=riscv64-linux-gnu- make
