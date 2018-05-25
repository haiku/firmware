ASUS Tinker Board u-boot binaries
===================

This directory contains ASUS Tinker Board u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://www.asus.com/us/Single-Board-Computer/Tinker-Board/>

Source information
-------------
> *Last Update:* Thu May 24 20:37:10 CDT 2018

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot.img u-boot.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Thu May 24 09:54:25 2018 -0400
  * **GIT Hash:** 8730d012c9bd92d6412b3ef6e33b40c5df00f225
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make tinker-rk3288_defconfig
  * ARCH=arm CROSS_COMPILE=arm-none-eabi- make