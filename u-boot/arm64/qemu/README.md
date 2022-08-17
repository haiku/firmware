QEMU ARM64 u-boot binaries
===================

This directory contains QEMU ARM64 u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://www.qemu.org>

Source information
-------------
> *Last Update:* Wed Aug 17 07:03:00 PM CEST 2022

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Mon Jul 11 09:42:58 2022 -0400
  * **GIT Commit:** e092e3250270a1016c877da7bdd9384f14b1321e v2022.07
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
  * **Toolchain version:** gcc version 11.2.0 (GCC) 
* **Build Commands:**
  * make qemu_arm64_defconfig
  * ARCH=arm64 CROSS_COMPILE=aarch64-unknown-haiku- make
