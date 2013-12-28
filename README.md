Fat32lib
========

Portable FAT12/16/32 Library for Embedded Devices.

Check back within a week or two for code release.

Features:
---------

- Written in 100% portable C89 code (driver requires hardware abstraction library);
- Synchronous and asynchronous (non-blocking) IO;
- Buffered and unbuffered IO;
- Stream IO (for writting continuos streams of data);
- Extensible drive manager (can be extended to interface with other file systems);
- FAT12/16/32 drive formatting support;
- SPI driver for SD cards (for Microchip's dsPIC but should be easy to port);
- Driver supports any SD card size;
- Multi-threading support;
- Multiple volumes/partitions can be mounted at once;
- Automatic volume mounting (when SD card or other device is inserted);
- Long filenames support (ASCII only/can be disabled at compile-time);
- Several memory management options;
- Easy to use API;
- Released under GPL v3. Commercial licenses also available (contact frodriguez.developer@outlook.com for info).
