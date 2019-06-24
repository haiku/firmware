ASUS Tinker Board u-boot binaries
===================

This directory contains ASUS Tinker Board u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://www.asus.com/us/Single-Board-Computer/Tinker-Board/>

Source information
-------------
> *Last Update:* Mon 24 Jun 2019 02:24:22 PM CDT

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot.img u-boot.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Sat Jun 15 13:03:00 2019 -0400
  * **GIT Hash:** 77f6e2dd0551d8a825bab391a1bd6b838874bcd4
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make tinker-rk3288_defconfig
  * ARCH=arm CROSS_COMPILE=arm-linux-gnu- make
