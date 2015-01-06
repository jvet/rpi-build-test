jvet/rpi-build-test
==========

Linux kernel release 3.12.35+ with builtin IPv6 support for the Raspberry Pi.

Install
-------

```text
sudo REPO_URI=https://github.com/jvet/rpi-build-test rpi-update
```



Changelog
---------
No changes, first release.


Sources
-------
* [raspberrypi/tools](https://github.com/raspberrypi/tools/archive/8f58ab354eac2844c34aeb0e4f19bdb2c96ab99b.tar.gz)
* [raspberrypi/firmware](https://github.com/raspberrypi/firmware/archive/393dcc0e76f18f6ac1b67ba45d36058410670034.tar.gz)
* [raspberrypi/linux](https://github.com/raspberrypi/linux/archive/652b904db26e1f83216627381a106ba6998d024a.tar.gz)


Patches
--------
None

Kernel config
-------------
Default config: bcmrpi_defconfig



Changed:
```text
IPV6 m -> y
```


<p align="center">Built with <a href="https://github.com/notro/rpi-build/wiki">rpi-build</a></p>
