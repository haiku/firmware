Libre ALL-H3-CC u-boot binaries
===================

This directory contains Libre ALL-H3-CC u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://libre.computer/products/boards/all-h3-cc/>

Source information
-------------
> *Last Update:* Thu 16 Jan 2020 08:16:53 PM CST

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot.bin u-boot-sunxi-with-spl.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Thu Jan 16 13:20:51 2020 -0500
  * **GIT Hash:** d7bb6aceb2e99a832efbb96f9bf480bf95602192
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make libretech_all_h3_cc_h3_defconfig
  * ARCH=arm CROSS_COMPILE=arm-none-eabi- make
