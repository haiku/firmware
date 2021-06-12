SiFive Unmatched u-boot binaries
===================

This directory contains SiFive Unmatched u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://www.sifive.com>

Source information
-------------
> *Last Update:* Sat Jun 12 11:24:37 AM CDT 2021

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot-spl.bin u-boot.itb
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Thu Jun 10 13:27:14 2021 -0400
  * **GIT Hash:** cf066a20c3ec063d019a991cc32ba8ad95a39780
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make sifive_unmatched_defconfig
  * ARCH=riscv64 CROSS_COMPILE=riscv64-linux-gnu- make
