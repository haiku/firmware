SiFive Unmatched u-boot binaries
===================

This directory contains SiFive Unmatched u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://www.sifive.com>

Source information
-------------
> *Last Update:* Sat Nov  6 08:16:29 PM CDT 2021

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot-spl.bin u-boot.itb
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Fri Nov 5 15:38:46 2021 -0400
  * **GIT Hash:** 52207514ba419a69a8105d16997b025f966c8879
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make sifive_unmatched_defconfig
  * ARCH=riscv64 CROSS_COMPILE=riscv64-linux-gnu- make
