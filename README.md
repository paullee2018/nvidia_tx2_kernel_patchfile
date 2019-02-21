# Linux patch file for TX2 Kernel development
To be able to use the J21 serial port and enable spi

To use the patch file, copy the device_tree.patch to hardware folder and kernel.patch to kernel-4.4 folder. Apply the patch by typing in the terminal,

    patch -s -p0 < device_tree.patch

    or 

    patch -s -p0 < kernel.patch
