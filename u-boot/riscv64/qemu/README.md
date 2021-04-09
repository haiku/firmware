QEMU RISCV64 u-boot binaries
===================

This directory contains QEMU RISCV64 u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://www.qemu.org>

Source information
-------------
> *Last Update:* Fri Apr  9 06:21:12 PM CDT 2021

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Fri Apr 9 10:08:52 2021 -0400
  * **GIT Hash:** a1e95e3805eacca1162f6049dceb9b1d2726cbf5
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make qemu-riscv64_smode_defconfig
  * ARCH=riscv64 CROSS_COMPILE=riscv64-linux-gnu- make
