NanoPi NEO 2 u-boot binaries
===================

This directory contains NanoPi NEO 2 u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <http://www.friendlyarm.net/products/nanopi-neo>

Source information
-------------
> *Last Update:* Mon 24 Jun 2019 02:05:15 PM CDT

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot-sunxi-with-spl.bin u-boot.bin u-boot.img sunxi-spl.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Sat Jun 15 13:03:00 2019 -0400
  * **GIT Hash:** 77f6e2dd0551d8a825bab391a1bd6b838874bcd4
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make nanopi_neo2_defconfig
  * ARCH=arm64 CROSS_COMPILE=arm64-aarch64-linux-gnu- make
