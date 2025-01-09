SiFive Unmatched u-boot binaries
===================

This directory contains SiFive Unmatched u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://www.sifive.com>

Source information
-------------
> *Last Update:* Wed Jan  8 07:42:14 PM CST 2025

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot-spl.bin u-boot.itb
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Wed Jan 8 14:19:22 2025 -0600
  * **GIT Hash:** 3bfd12008bef1a8353e7ceaca2cb06cf388527ed
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
  * **Toolchain version:** gcc version 13.3.0 (GCC) 
* **Build Commands:**
  * make sifive_unmatched_defconfig
  * ARCH=riscv64 CROSS_COMPILE=riscv64-unknown-haiku- make
