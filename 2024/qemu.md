qemu-system-arm -M vexpress-a9 -m 1024 -kernel zImage -dtb vexpress-v2p-ca9.dtb -sd rootfs.img -append "console=ttyAMA0,115200 root=/dev/mmcblk0 rw" -nographic
