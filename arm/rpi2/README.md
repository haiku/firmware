Raspberry Pi 2 u-boot binaries
===================

This directory contains Raspberry Pi 2 u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Source information
-------------
> *Last Update:* Thu Nov 16 19:31:47 CST 2017

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Mon Nov 13 20:08:06 2017 -0500
  * **GIT Hash:** c253573f3e269fd9a24ee6684d87dd91106018a5
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make rpi_2_defconfig
  * ARCH=arm CROSS_COMPILE=arm-unknown-haiku- make
