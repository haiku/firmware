OrangePi Zero2 u-boot binaries
===================

This directory contains OrangePi Zero2 u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <http://www.orangepi.org/html/hardWare/computerAndMicrocontrollers/details/Orange-Pi-Zero-2.html>

Source information
-------------
> *Last Update:* pią, 29 lis 2024, 23:55:12 CET

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot.bin u-boot-sunxi-with-spl.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Fri Nov 29 07:51:57 2024 -0600
  * **GIT Hash:** 20f641987f83c4679a1181d79a546a098f11f5ad
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
  * **Toolchain version:** gcc version 14.2.1 20240912 (Red Hat Cross 14.2.1-1) (GCC) 
* **Build Commands:**
  * make orangepi_zero2_defconfig
  * ARCH=arm64 CROSS_COMPILE=aarch64-linux-gnu- make
