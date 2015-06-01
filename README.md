# Linux Firmware Debug Kit (lfdk)

Fork to fix for Ubuntu 14.04 (Kernel 3.13), how to use:

1. sudo apt-get -y install libncurses5-dev
2. make
3. sudo insmod bin/lfdd_drv.ko
4. sudo bin/lfdk

If you have any questions, please feel free to contact me by E-Mail - Denir Li (<denir.li@gmail.com>).


## Source:
* v0.1.0 - <http://sourceforge.net/projects/lfdk/> ,  [ioctl](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/commit/?id=b19dd42faf413b4705d4adb38521e82d73fa4249 "Kernel 2.6.36") was removed in Kernel 2.6.36, reference from <http://blog.xuite.net/meloscheng/note/62155264> and <http://blog.chinaunix.net/uid-20543672-id-3015637.html> to fix lfdd/lfdd.c.
* v2.0.0 - <https://github.com/merckhung/lfdk1> , use unlocked_ioctl to replace ioctl in lfdd/lfdd.c and added new features.
* Firmware Debug Kit (FDK) - <https://github.com/merckhung/fdk> , it's Network Client-Server architecture and exchanging network packets with each other. <https://sites.google.com/site/merckhung/Home/firmwaredebugkit>

PS. The original author: Merck Hung (<merckhung@gmail.com>). This software is licensed under the terms of the **GNU General Public License version 2**, as published by the Free Software Foundation, and may be copied, distributed, and modified under those terms.

## Reference:
* <https://github.com/acelan/lfdk> : [asm/system.h](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/commit/?id=f05e798ad4c09255f590f5b2c00a7ca6c172f983 "Kernel 3.4") was removed in Kernel 3.4
* <https://github.com/DesmondWu/lfdk1>
* <https://github.com/fcwu/lfdk>
* <http://rickey-nctu.blogspot.tw/2013/07/linux-firmware-debug-kit-on-ubuntu.html>
