QEMU x86_64 u-boot binaries
===================

This directory contains QEMU x86_64 u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://www.qemu.org>

Source information
-------------
> *Last Update:* Sat Dec 26 08:48:38 PM CST 2020

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot.img
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Tue Dec 22 08:18:21 2020 -0500
  * **GIT Hash:** fbc326244ce6fb3bd42353f343a511b512b8e710
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make qemu-x86_64_defconfig
  * ARCH=x86_64 CROSS_COMPILE=-- make
