# Virtual POS printer


This repository provides a description of the supported commands for the RawBT virtual printer. 

**RawBT** is an android application. [GET IT ON Google Play](https://play.google.com/store/apps/details?id=ru.a402d.rawbtprinter).

_Requires version above 4.9_

## Why is it necessary
A virtual printer will be useful for you in the process of debugging printing forms.
Ready-made examples of .prn files and the results of their emulation are given in the prn and png directories.

![receipt](https://github.com/402d/Virtual_POS_printer/raw/master/png/receipt-with-logo.png)

## How use

Install app.

You can open and view .prn files on the device. Make it available over the network (Available choice of port number 9100,9102 - 9108) or bluetooth.

- [Overview PRN Viewer](doc/overview.md)
- [Use Virtual device for all supported app functions](doc/useforall.md)
- [Virtual Net printer](doc/netshare.md)
- [Virtual BT printer](doc/btshare.md)
- [Open .prn files](doc/files.md)
- [Configure virtual printer](doc/configure.md) 

### Support for common ESC/POS commands

ESC/POS is a page description language that is commonly used for receipt printing.

Currently, the application can detect most commands and emulate the behavior of the standard print mode.

- [List commands](commands.md)

### Capabilities

You may find  RawBT profile in /resources subfolder. 

 