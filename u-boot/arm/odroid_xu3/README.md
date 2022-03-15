ODROID XU3/XU4/HC1/HC2 u-boot binaries
===================

This directory contains ODROID XU3/XU4/HC1/HC2 u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://odroid.com>

Source information
-------------
> *Last Update:* Tue Mar 15 09:04:26 AM CDT 2022

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot-dtb.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Mon Mar 14 22:54:53 2022 -0400
  * **GIT Hash:** 4dc9b1771b152838ddfc4ae86a0ab9fd53ea16f7
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make odroid-xu3_defconfig
  * ARCH=arm CROSS_COMPILE=arm-none-eabi- make
