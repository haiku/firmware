# U-Boot Binaries

u-boot firmware binaries for various arm,arm64 devices.
These files are generally used by the [rune](https://github.com/haiku/rune) tool.

----------

> *Notice:* Licenses are **strictly** followed in this repository.
> Any binaries **must** have a documented source location if the license requires it.

Directories
-------------

* arm - ARMv7 firmwares and u-boot artifacts.
* arm64 - ARMv8 firmwares and u-boot artifacts.
* tools - Tools to compile u-boot sources and record commit info.
* docs - SoC Documentation

Build
-------------

To rebuild the u-boot sources:

* Place the architecture's cross compiler binaries into your PATH
* From the root, run ./tools/build &lt;arch&gt;
* manifest.json is updated by hand to reflect what is needed for each board.

Manifest Format
------------

```manifest.json``` defines each SOC and what files are required to make an SD card bootable.

* arch - Target architecture
* id - board identification (should match directory name)
* soc - Name of ARM SOC
* name - Pretty name of board
* files - Files to place on the initial FAT32 boot partition
  * If the file url begins with a number, this is the offset it gets written to the disk device at.
  * Example: 8192,https://github.com/blah.bin:
    * ```dd if=blah.bin of=/sdcard bs=1024 seek=8```

License
------------

[![GPLv2 License](https://img.shields.io/badge/license-GPL--2.0+-red.svg)](LICENSE)

This repository contains sources and binaries from u-boot which are licensed under GPLv2.
