OrangePi One u-boot binaries
===================

This directory contains OrangePi One u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <http://www.orangepi.org/orangepione>

Source information
-------------
> *Last Update:* Mon Nov 20 17:49:46 CST 2017

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot-sunxi-with-spl.bin u-boot.img u-boot.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Mon Nov 20 11:46:08 2017 -0500
  * **GIT Hash:** 69d3226530a0bb4945644778b903c5b95d858e30
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make orangepi_one_defconfig
  * ARCH=arm CROSS_COMPILE=arm-unknown-haiku- make
