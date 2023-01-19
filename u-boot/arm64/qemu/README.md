QEMU ARM64 u-boot binaries
===================

This directory contains QEMU ARM64 u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://www.qemu.org>

Source information
-------------
> *Last Update:* Thu Jan 19 11:33:34 AM CST 2023

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Thu Jan 19 09:41:54 2023 -0500
  * **GIT Hash:** 7aec35be4b5fa7aabc0ece03dc8825495d86a1be
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
  * **Toolchain version:** gcc version 11.3.0 (GCC) 
* **Build Commands:**
  * make qemu_arm64_defconfig
  * ARCH=arm64 CROSS_COMPILE=aarch64-unknown-haiku- make
