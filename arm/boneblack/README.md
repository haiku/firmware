BeagleBone Black u-boot binaries
===================

This directory contains BeagleBone Black u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://beagleboard.org/black>

Source information
-------------
> *Last Update:* Sat 21 Sep 2019 02:20:35 PM CDT

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot.img MLO
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Fri Sep 20 17:43:33 2019 -0400
  * **GIT Hash:** d6c7309f561ac832c080e5ec07b0af9c8da319a8
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make am335x_evm_defconfig
  * ARCH=arm CROSS_COMPILE=arm-unknown-haiku- make
