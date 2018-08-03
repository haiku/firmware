Firmware binaries
===================

This repo contains u-boot and other firmware binaries for use
by Haiku and other operating systems.

----------

> *Notice:* Licenses are **strictly** followed in this repository.
> Any binaries **must** have a documented source location if the license requires it.

Directories
-------------

* arm - ARMv7 firmwares and u-boot artifacts.
* arm64 - ARMv8 firmwares and u-boot artifacts.

Build
-------------

To rebuild the u-boot sources:

* Place the architecture's cross compiler binaries into your PATH
* From the root, run ./tools/build &lt;arch&gt;
* manifest.json is updated by hand to reflect what is needed for each board.

License
------------

[![GPLv2 License](https://img.shields.io/badge/license-GPL--2.0+-red.svg)](LICENSE)

This repository contains sources and binaries from u-boot which are licensed under GPLv2.
