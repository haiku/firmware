Libre ALL-H5-CC u-boot binaries
===================

This directory contains Libre ALL-H5-CC u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://libre.computer/products/boards/all-h3-cc/>

Source information
-------------
> *Last Update:* Mon Sep 30 17:52:53 UTC 2019

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot.bin u-boot-sunxi-with-spl.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Mon Sep 30 07:21:38 2019 -0400
  * **GIT Hash:** 023ff4b88dcec5faa3f9b841bae4d3d232b58ce2
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make libretech_all_h3_cc_h5_defconfig
  * ARCH=arm CROSS_COMPILE=arm-unknown-haiku- make
