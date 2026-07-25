Pine64 PinePhone u-boot binaries
===================

This directory contains Pine64 PinePhone u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://pine64.org/devices/pinephone/>

Source information
-------------
> *Last Update:* Sat Jul 25 01:57:48 PM CDT 2026

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot.bin u-boot-sunxi-with-spl.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Fri Jul 24 10:46:16 2026 -0600
  * **GIT Hash:** 574b1adad70a19d95c65e0f37f9c36d94fb5418f
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
  * **Toolchain version:** gcc version 16.1.0 (GCC) 
* **Build Commands:**
  * make pinephone_defconfig
  * ARCH=arm64 CROSS_COMPILE=aarch64-linux-gnu- make
