Raspberry Pi 2 u-boot binaries
===================

This directory contains Raspberry Pi 2 u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://www.raspberrypi.org>

Source information
-------------
> *Last Update:* Mon Nov 20 17:48:35 CST 2017

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Mon Nov 20 11:46:08 2017 -0500
  * **GIT Hash:** 69d3226530a0bb4945644778b903c5b95d858e30
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make rpi_2_defconfig
  * ARCH=arm CROSS_COMPILE=arm-unknown-haiku- make
