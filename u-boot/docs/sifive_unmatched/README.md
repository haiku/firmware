# SiFive Unmatched

The SiFive Unmatched is a board produced by SiFive:

* SoC: SiFive Freedom U740 SoC
* Memory: 16GB DDR4

## Bootable SD card

SiFive Unmatched is expecting an SD Card with a GPT partition table.

The SD card which ships with the SiFive HiFive unmatched is laid out as follows:

* GPT 1
  * Start Sector: 34
  * End Sector: 2081
  * GUID: 5b193300-fc78-40cd-8002-e86c45580b47 (HiFive Unleashed FSBL)
  * u-boot-spl.bin
* GPT 2
  * Start Sector: 2082
  * End Sector: +4M
  * GUID: 2e54b353-1271-4842-806f-e436d6af6985 (HiFive Unleashed BBL)
  * u-boot.itb

**The NixOS folks figured out a sgdisk command to setup the SD card:**
```
sgdisk -Z [block device]
sgdisk -g --clear --set-alignment=1 \
  --new=1:34:2081: --typecode=1:5b193300-fc78-40cd-8002-e86c45580b47 \
  --new=2:2082:10273: --typecode=2:2e54b353-1271-4842-806f-e436d6af6985 \
  --new=3:10274:75809: --typecode=3:ef00 \
  --new=4:75810:: --typecode=4:eb00 \
  [block device]
```

**Writing the bootloader to the SD card:**
```
# FSBL
dd if=u-boot-spl.bin of=/dev/mmcblk0p1 bs=4k oflag=direct

# SBL
dd if=u-boot.itb of=/dev/mmcblk0p2 bs=4k oflag=direct
```

**Writing Haiku's EFI bootloader to the SD card:**
* Make /dev/mmcblk0p3 FAT32
* mkdir /EFI/BOOT
* Copy haiku_loader.efi to /EFI/BOOT/BOOTRISCV64.EFI

**Writing Haiku's filesystem to the SD card:**
* ```dd if=haiku-minimum.mmc of=/dev/mmcblk0p4 bs=4k oflag=direct```
