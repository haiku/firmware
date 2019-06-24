Raspberry Pi 3 u-boot binaries
===================

This directory contains Raspberry Pi 3 u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://www.raspberrypi.org>

Source information
-------------
> *Last Update:* Mon 24 Jun 2019 02:27:46 PM CDT

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Sat Jun 15 13:03:00 2019 -0400
  * **GIT Hash:** 77f6e2dd0551d8a825bab391a1bd6b838874bcd4
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make rpi_3_32b_defconfig
  * ARCH=arm CROSS_COMPILE=arm-linux-gnu- make
