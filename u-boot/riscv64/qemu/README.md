QEMU RISCV64 u-boot binaries
===================

This directory contains QEMU RISCV64 u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://www.qemu.org>

Source information
-------------
> *Last Update:* Sat Nov  6 08:15:43 PM CDT 2021

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Fri Nov 5 15:38:46 2021 -0400
  * **GIT Hash:** 52207514ba419a69a8105d16997b025f966c8879
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make qemu-riscv64_smode_defconfig
  * ARCH=riscv64 CROSS_COMPILE=riscv64-linux-gnu- make
