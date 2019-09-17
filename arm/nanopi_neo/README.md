NanoPi NEO u-boot binaries
===================

This directory contains NanoPi NEO u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <http://www.friendlyarm.net/products/nanopi-neo>

Source information
-------------
> *Last Update:* Mon 16 Sep 2019 09:26:37 PM CDT

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot-sunxi-with-spl.bin u-boot.img u-boot.bin idbloader.img sunxi-spl.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Sun Sep 15 21:14:26 2019 -0400
  * **GIT Hash:** a314ec1bfda3d0db0ce8ae02dde1b06650d82e7f
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make nanopi_neo_defconfig
  * ARCH=arm CROSS_COMPILE=arm-none-eabi- make
