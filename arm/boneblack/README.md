BeagleBone Black u-boot binaries
===================

This directory contains BeagleBone Black u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Source information
-------------
> *Last Update:* Thu Nov 16 19:22:00 CST 2017

This section tracks the u-boot revision within this repo.

* **Files:**  MLO u-boot.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Fri Oct 20 13:07:13 2017 -0500
  * **GIT Hash:** 098ffa1f97520a8cfc947d00dca1beb46d0c2311
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make am335x_boneblack_defconfig
  * ARCH=arm CROSS_COMPILE=arm-unknown-haiku- make
