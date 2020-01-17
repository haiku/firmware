ASUS Tinker Board u-boot binaries
===================

This directory contains ASUS Tinker Board u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://www.asus.com/us/Single-Board-Computer/Tinker-Board/>

Source information
-------------
> *Last Update:* Thu 16 Jan 2020 08:12:59 PM CST

This section tracks the u-boot revision within this repo.

* **Files:**  idbloader.img u-boot-dtb.img
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Thu Jan 16 13:20:51 2020 -0500
  * **GIT Hash:** d7bb6aceb2e99a832efbb96f9bf480bf95602192
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make tinker-rk3288_defconfig
  * ARCH=arm CROSS_COMPILE=arm-none-eabi- make
