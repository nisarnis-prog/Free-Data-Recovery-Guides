# Free Data Recovery Guides

Two free educational guides by Nisar Muhammad for inspecting storage and recovering files after an accidental partition deletion.

1. [SystemRescue Linux beginner guide (PDF)](docs/Free_Data_Recovery_Beginners_Guide.pdf) walks through booting a rescue USB, identifying disks and partitions, and safely inspecting files.
2. [Recover files from a deleted partition (PDF)](docs/Free_Data_Recovery_Step_by_Step_Guide.pdf) shows how to find a lost partition with SystemRescue and TestDisk, preview its files, and copy them to a separate physical drive.

## Official downloads

- [SystemRescue](https://www.system-rescue.org/Download/)
- [Rufus](https://rufus.ie/)
- [TestDisk](https://www.cgsecurity.org/wiki/TestDisk_Download)

These guides were independently prepared by Nisar Muhammad. The linked tools are developed and distributed by their respective projects. This repository contains documentation only.

## Before you start

Stop using the affected drive. Verify the source, boot USB, and destination by model and size, and check serial numbers when disks look alike. Creating the boot USB erases the selected USB. Keep logs and recovered files on a separate physical drive.

New writes can overwrite recoverable data. SSD TRIM may make recovery impossible, and encrypted volumes can require the original recovery key. If a drive clicks, disconnects, or reports repeated read errors, stop scanning. For irreplaceable data, seek professional help or work from a verified disk image when one can be safely obtained.

See the [educational-use disclaimer](DISCLAIMER.md).
