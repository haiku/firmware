SiFive Unmatched u-boot binaries
===================

This directory contains SiFive Unmatched u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://www.sifive.com>

Source information
-------------
> *Last Update:* Thu Mar 17 03:14:16 PM CDT 2022

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot-spl.bin u-boot.itb
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Wed Mar 16 08:13:16 2022 -0400
  * **GIT Hash:** e7fb67df319cec410c20906bbf33936a6f7479b2
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
  * **Toolchain version:** gcc version 11.2.0 (GCC) 
* **Build Commands:**
  * make sifive_unmatched_defconfig
  * ARCH=riscv64 CROSS_COMPILE=riscv64-unknown-haiku- make
