OrangePi One u-boot binaries
===================

This directory contains OrangePi One u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <http://www.orangepi.org/orangepione>

Source information
-------------
> *Last Update:* Fri Mar 16 09:22:32 CDT 2018

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot-sunxi-with-spl.bin u-boot.img u-boot.bin sunxi-spl.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Fri Mar 16 09:42:41 2018 -0400
  * **GIT Hash:** f274f265668d43948f041f88e7b50b9639769d56
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make orangepi_one_defconfig
  * ARCH=arm CROSS_COMPILE=arm-none-eabi- make
