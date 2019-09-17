Raspberry Pi 2 u-boot binaries
===================

This directory contains Raspberry Pi 2 u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://www.raspberrypi.org>

Source information
-------------
> *Last Update:* Mon 16 Sep 2019 09:28:31 PM CDT

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot.bin idbloader.img
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Sun Sep 15 21:14:26 2019 -0400
  * **GIT Hash:** a314ec1bfda3d0db0ce8ae02dde1b06650d82e7f
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make rpi_2_defconfig
  * ARCH=arm CROSS_COMPILE=arm-none-eabi- make
