ASUS Tinker Board u-boot binaries
===================

This directory contains ASUS Tinker Board u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://www.asus.com/us/Single-Board-Computer/Tinker-Board/>

Source information
-------------
> *Last Update:* Thu 30 Apr 2020 08:52:47 PM CDT

This section tracks the u-boot revision within this repo.

* **Files:**  idbloader.img u-boot-dtb.img
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Thu Apr 30 15:11:06 2020 -0400
  * **GIT Hash:** 78021b63373de32335bd204471d6cb7c7e18bc52
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make tinker-rk3288_defconfig
  * ARCH=arm CROSS_COMPILE=arm-linux-gnu- make
