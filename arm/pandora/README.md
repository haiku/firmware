Pandora Handheld u-boot binaries
===================

This directory contains Pandora Handheld u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://pyra-handheld.com>

Source information
-------------
> *Last Update:* Wed 18 Sep 2019 09:29:47 AM CDT

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot.img u-boot.bin idbloader.img
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Mon Sep 16 13:13:45 2019 -0400
  * **GIT Hash:** a9fa70b7b7167487affc5d919e541872c99e814b
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make omap3_pandora_defconfig
  * ARCH=arm CROSS_COMPILE=arm-unknown-haiku- make
