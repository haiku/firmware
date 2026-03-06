Libre ALL-H5-CC u-boot binaries
===================

This directory contains Libre ALL-H5-CC u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://libre.computer/products/boards/all-h3-cc/>

Source information
-------------
> *Last Update:* Fri Mar  6 09:23:16 CST 2026

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot.bin u-boot-sunxi-with-spl.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Wed Mar 4 14:25:30 2026 -0600
  * **GIT Hash:** b26cc03b7cecaabdb306c2f68eebde764161a545
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
  * **Toolchain version:** gcc version 15.1.0 (GCC) 
* **Build Commands:**
  * make libretech_all_h3_cc_h5_defconfig
  * ARCH=arm64 CROSS_COMPILE=aarch64-linux-gnu- make
