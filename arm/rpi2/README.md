Raspberry Pi 2 u-boot binaries
===================

This directory contains Raspberry Pi 2 u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://www.raspberrypi.org>

Source information
-------------
> *Last Update:* Fri Nov 17 09:00:55 CST 2017

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Thu Nov 16 09:32:04 2017 -0500
  * **GIT Hash:** ebca2083d3689c77c7d1365f1e6862b55abef8a2
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make rpi_2_defconfig
  * ARCH=arm CROSS_COMPILE=arm-unknown-haiku- make
