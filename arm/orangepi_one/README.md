OrangePi One u-boot binaries
===================

This directory contains OrangePi One u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <http://www.orangepi.org/orangepione>

Source information
-------------
> *Last Update:* Fri Nov 17 09:02:06 CST 2017

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot-sunxi-with-spl.bin u-boot.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Thu Nov 16 09:32:04 2017 -0500
  * **GIT Hash:** ebca2083d3689c77c7d1365f1e6862b55abef8a2
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make orangepi_one_defconfig
  * ARCH=arm CROSS_COMPILE=arm-unknown-haiku- make
