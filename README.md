# Linux patch file 
Changes to kernel and device tree to enable spi port and J21 serial port for application development.

To use the patch file, copy the device_tree.patch to hardware folder and kernel.patch to kernel-4.4 folder. Apply the patch by typing in the terminal,

    patch -s -p0 < device_tree.patch

    or 

    patch -s -p0 < kernel.patch
