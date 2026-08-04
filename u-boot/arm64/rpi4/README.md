Raspberry Pi 4 u-boot binaries
===================

This directory contains Raspberry Pi 4 u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://www.raspberrypi.org>

Source information
-------------
> *Last Update:* Tue Aug  4 10:07:06 AM CDT 2026

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Fri Jul 31 08:55:30 2026 -0600
  * **GIT Hash:** baa64b2f892890f00a377eac4a3e685472bb56b5
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
  * **Toolchain version:** gcc version 16.1.0 (GCC) 
* **Build Commands:**
  * make rpi_4_defconfig
  * ARCH=arm64 CROSS_COMPILE=aarch64-linux-gnu- make
