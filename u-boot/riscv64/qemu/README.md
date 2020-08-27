QEMU RISCV64 u-boot binaries
===================

This directory contains QEMU RISCV64 u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://www.qemu.org>

Source information
-------------
> *Last Update:* Thu 27 Aug 2020 08:31:15 AM CDT

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Wed Aug 26 17:30:22 2020 -0400
  * **GIT Hash:** f87c80ade3911f3d518036a28370fe44c85a95c7
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make qemu-riscv64_defconfig
  * ARCH=riscv64 CROSS_COMPILE=riscv64-unknown-haiku- make
