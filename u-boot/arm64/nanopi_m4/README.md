NanoPi M4 u-boot binaries
===================

This directory contains NanoPi M4 u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <http://wiki.friendlyarm.com/wiki/index.php/NanoPi_M4>

Source information
-------------
> *Last Update:* Wed 18 Sep 2019 09:34:53 AM CDT

This section tracks the u-boot revision within this repo.

* **Files:**  idbloader.img u-boot.bin u-boot.img
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Mon Sep 16 13:13:45 2019 -0400
  * **GIT Hash:** a9fa70b7b7167487affc5d919e541872c99e814b
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make nanopi-m4-rk3399_defconfig
  * ARCH=arm64 CROSS_COMPILE=aarch64-linux-gnu- make
