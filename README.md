# VIF Patched Kernel Packages

Go to releases, download and install the kernel version you like. There are three patched kernels, its headers and libc-dev packages uploaded as zip. Install the kernel using `dpkg-i <filename>`. Then reboot and select the newly installed kernel from the boot menu. All three kernel packages when installed, will make a timestamped backup copy of /lib/firmware/regulatory.db and /lib/firmware/regulatory.db.p7s and copy the upstream version of the two files.
