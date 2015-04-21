# Linux Firmware Debug Kit (lfdk)

Fix for Ubuntu 14.04 (Kernel 3.13)


※Source:
* Old version <http://sourceforge.net/projects/lfdk/> , Kernel 2.6.36 remove [ioctl](https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/commit/?id=b19dd42faf413b4705d4adb38521e82d73fa4249 "Kernel 2.6.36"), reference from <http://blog.xuite.net/meloscheng/note/62155264> and <http://blog.chinaunix.net/uid-20543672-id-3015637.html> to fix lfdd/lfdd.c.
* New version <https://github.com/merckhung/lfdk1> , use unlocked_ioctl to replace ioctl in lfdd/lfdd.c.
  
※Reference:
* <https://github.com/acelan/lfdk> remove asm/system.h
* <https://github.com/DesmondWu/lfdk1>
* <https://github.com/fcwu/lfdk>
* <http://rickey-nctu.blogspot.tw/2013/07/linux-firmware-debug-kit-on-ubuntu.html>
