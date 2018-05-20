Raspberry Pi 3 u-boot binaries
===================

This directory contains Raspberry Pi 3 u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://www.raspberrypi.org>

Source information
-------------
> *Last Update:* Fri Mar 16 09:23:08 CDT 2018

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Fri Mar 16 09:42:41 2018 -0400
  * **GIT Hash:** f274f265668d43948f041f88e7b50b9639769d56
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make rpi_3_32b_defconfig
  * ARCH=arm CROSS_COMPILE=arm-none-eabi- make
