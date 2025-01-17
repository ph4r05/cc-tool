### cc-tool version 0.26+
cc-tool provides support for Texas Instruments CC Debugger

### Building from source, dependencies:
- Ubuntu: `libusb-1.0-0-dev libboost-all-dev autoconf libtool`
- Fedora: `boost-devel libusb1-devel`
- Mac OS 12.5, from ports: `autoconf automake libusb boost pkgconfig libtool`

Regenerate Autotools files first by running `./bootstrap` script.

### User guide:
`man cc-tool`

### Additional:
File `udev/90-cc-debugger.rules` cotains udev rules changing permissions 
for TI CC Debugger device and TI evolution boards so they can be used 
from non-privileged accounts. Copy it to `/etc/udev/rules.d`

### Support:
If you found a bug try to reproduce it with command line option `--log`.
