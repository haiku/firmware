ASUS Tinker Board u-boot binaries
===================

This directory contains ASUS Tinker Board u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://www.asus.com/us/Single-Board-Computer/Tinker-Board/>

Source information
-------------
> *Last Update:* Sat May 19 18:58:41 CDT 2018

This section tracks the u-boot revision within this repo.

* **Files:**  u-boot.img u-boot.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Fri May 18 17:56:50 2018 -0400
  * **GIT Hash:** 855ff8e6dd58b01930d8b8b726e65310d546a0c9
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make tinker-rk3288_defconfig
  * ARCH=arm CROSS_COMPILE=arm-none-eabi- make

# Extra Config
CONFIG_PRELOAD="test -e mmc 0 uEnv.txt && fatload mmc 0 ${scriptaddr} uEnv.txt && env import -t ${scriptaddr} ${filesize} && run uenvcmd"
