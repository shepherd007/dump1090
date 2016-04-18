This repository is an attempt to bring back dump1090 to life in Windows system. It is based on existing implementation with a fewer modifications. The major difference is a replacement of pthreadVC2.dll with pthreads library.

After cloning repository you need to load submodule:
```
cd /dump1090/windows
git submodule add git://git.osmocom.org/rtl-sdr.git
```

**Supported compilators:**
- Visual C++ 2013

**Dependencies:**
- libpthread.dll
- libusb-1.0
- rtlsdr.dll


**More information:**
http://planeplotter.pbworks.com/w/page/79995023/Dump1090

Disabled features:
- --throttle
- --write-json 
