# Luke's dmenu

Extra stuff added to vanilla dmenu:

- reads Xresources (ergo pywal compatible)
- alpha patch, which importantly allows this build to be embedded in transparent st
- can view color characters like emoji (libxft-bgra is required for this reason)
- `-P` for password mode: hide user input
- `-r` to reject non-matching input
- dmenu options are mouse clickable

## Installation
```
git clone https://github.com/mgauz01/dmenu.git
cd dmenu
sudo make clean install
```
## How to use
```
./dmenu_run
```

## For Arch Linux users
You must have `libxft-bgra` installed until the libxft upstream is fixed.

After making any config changes that you want, but `make`, `sudo make install` it.
