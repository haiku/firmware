BeagleBone Black u-boot binaries
===================

This repo contains BeagleBone Black u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Source information
-------------
> *Last Update:* 10/20/2017

This section tracks the u-boot revision within this repo.

* **Files:** u-boot.img u-boot.bin MLO
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Thu Oct 19 11:19:38 2017 -0400
  * **GIT Hash:** 0def58f7fd26a237bb08cfbd58ec53372b1ad06b
* **Known Issues:** None at this time.
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make am335x_boneblack_defconfig
  * ARCH=arm CROSS_COMPILE=arm-unknown-haiku- make
