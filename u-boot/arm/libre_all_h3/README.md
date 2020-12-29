Libre ALL-H3-CC u-boot binaries
===================

This directory contains Libre ALL-H3-CC u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://libre.computer/products/boards/all-h3-cc/>

Source information
-------------
> *Last Update:* Mon Dec 28 08:35:52 PM CST 2020

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot.bin u-boot-sunxi-with-spl.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Mon Dec 28 07:44:03 2020 -0500
  * **GIT Hash:** ab865a8ee5c1a069f72a171270c02c99ccda7bfa
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make libretech_all_h3_cc_h3_defconfig
  * ARCH=arm CROSS_COMPILE=arm-none-eabi- make
