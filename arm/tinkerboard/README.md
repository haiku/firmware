ASUS Tinker Board u-boot binaries
===================

This directory contains ASUS Tinker Board u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://www.asus.com/us/Single-Board-Computer/Tinker-Board/>

Source information
-------------
> *Last Update:* Sun 22 Sep 2019 04:17:36 PM CDT

This section tracks the u-boot revision within this repo.

* **Files:**  idbloader.img u-boot-dtb.img u-boot-spl-dtb.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Sat Sep 21 07:31:23 2019 -0400
  * **GIT Hash:** 390183b58179ddaf986422f4d9446c596660f7e0
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make tinker-rk3288_defconfig
  * ARCH=arm CROSS_COMPILE=arm-unknown-haiku- make
