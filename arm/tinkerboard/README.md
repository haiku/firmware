ASUS Tinker Board u-boot binaries
===================

This directory contains ASUS Tinker Board u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://www.asus.com/us/Single-Board-Computer/Tinker-Board/>

Source information
-------------
> *Last Update:* Sat 21 Sep 2019 02:19:47 PM CDT

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot.bin u-boot-spl-dtb.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Fri Sep 20 17:43:33 2019 -0400
  * **GIT Hash:** d6c7309f561ac832c080e5ec07b0af9c8da319a8
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make tinker-rk3288_defconfig
  * ARCH=arm CROSS_COMPILE=arm-unknown-haiku- make
