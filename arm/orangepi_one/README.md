OrangePi One u-boot binaries
===================

This directory contains OrangePi One u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <http://www.orangepi.org/orangepione>

Source information
-------------
> *Last Update:* Thu May 24 20:35:58 CDT 2018

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot-sunxi-with-spl.bin u-boot.img u-boot.bin sunxi-spl.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Thu May 24 09:54:25 2018 -0400
  * **GIT Hash:** 8730d012c9bd92d6412b3ef6e33b40c5df00f225
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make orangepi_one_defconfig
  * ARCH=arm CROSS_COMPILE=arm-none-eabi- make
