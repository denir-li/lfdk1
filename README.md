# Linux Firmware Debug Kit (lfdk)

Fix for Ubuntu 14.04 (Kernel 3.13), how to use:

1. sudo apt-get -y install libncurses5-dev
2. make
3. sudo insmod bin/lfdd_drv.ko
4. sudo bin/lfdk


## Source:
* Old version - <http://sourceforge.net/projects/lfdk/> ,  [ioctl](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/commit/?id=b19dd42faf413b4705d4adb38521e82d73fa4249 "Kernel 2.6.36") was removed in Kernel 2.6.36, reference from <http://blog.xuite.net/meloscheng/note/62155264> and <http://blog.chinaunix.net/uid-20543672-id-3015637.html> to fix lfdd/lfdd.c.
* New version - <https://github.com/merckhung/lfdk1> , use unlocked_ioctl to replace ioctl in lfdd/lfdd.c.


## Reference:
* <https://github.com/acelan/lfdk> : [asm/system.h](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/commit/?id=f05e798ad4c09255f590f5b2c00a7ca6c172f983 "Kernel 3.4") was removed in Kernel 3.4
* <https://github.com/DesmondWu/lfdk1>
* <https://github.com/fcwu/lfdk>
* <http://rickey-nctu.blogspot.tw/2013/07/linux-firmware-debug-kit-on-ubuntu.html>
