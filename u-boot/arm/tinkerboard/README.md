ASUS Tinker Board u-boot binaries
===================

This directory contains ASUS Tinker Board u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://www.asus.com/us/Single-Board-Computer/Tinker-Board/>

Source information
-------------
> *Last Update:* Mon Dec 28 08:40:07 PM CST 2020

This section tracks the u-boot revision within this repo.

* **Files:**  idbloader.img u-boot-dtb.img
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Mon Dec 28 07:44:03 2020 -0500
  * **GIT Hash:** ab865a8ee5c1a069f72a171270c02c99ccda7bfa
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make tinker-rk3288_defconfig
  * ARCH=arm CROSS_COMPILE=arm-none-eabi- make
