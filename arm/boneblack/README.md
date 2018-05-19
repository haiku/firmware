BeagleBone Black u-boot binaries
===================

This directory contains BeagleBone Black u-boot binaries.
These binaries were compiled from the stock u-boot sources.

Hardware Information: <https://beagleboard.org/black>

Source information
-------------
> *Last Update:* Sat May 19 18:56:33 CDT 2018

This section tracks the u-boot revision within this repo.

* **Files:**  MLO u-boot.img u-boot.bin
  * **License:** GPLv2
  * **Source Code:** git://git.denx.de/u-boot.git
  * **Date:** Fri May 18 17:56:50 2018 -0400
  * **GIT Hash:** 855ff8e6dd58b01930d8b8b726e65310d546a0c9
* **Toolchain:** http://cgit.haiku-os.org/buildtools/
* **Build Commands:**
  * make am335x_boneblack_defconfig
  * ARCH=arm CROSS_COMPILE=arm-none-eabi- make

# Extra Config
CONFIG_PRELOAD="test -e mmc 0 uEnv.txt && fatload mmc 0 ${scriptaddr} uEnv.txt && env import -t ${scriptaddr} ${filesize} && run uenvcmd"
