Change name to init_boot.img then flash it

KernelSU LKM 模式修补过的 init_boot.img 文件。适用于 RMX3850 14.0.1.608(CN01) 获取 root 。

使用方式:先根据官方说明解锁 Bootloader , 重启到 fastboot 模式，fastboot flash init_boot RMX3850_kernelsu_patched_20240708_151112.img

或者你也可以自行参照这个 链接的教程自己修补刷入。

