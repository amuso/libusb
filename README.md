# libusb for Mac OS X
## Version 1.0.21

Read more at http://www.libusb.org.
For building rtl-sdr (and other software packages).

## Requirements

- Xcode command line tools

## Building

```
xcode-select --install
```

```
wget https://github.com/libusb/libusb/releases/download/v1.0.21/libusb-1.0.21.tar.bz2
tar -zxvpf libusb-1.0.21.tar.bz2
cd libusb-1.0.21
./configure
make
sudo make install
```
