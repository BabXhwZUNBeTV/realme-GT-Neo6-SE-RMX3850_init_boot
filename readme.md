KernelSU LKM 模式修补过的 init_boot.img 文件。适用于 RMX3850 14.0.1.608(CN01) 获取 root 。

使用方式:先根据官方说明解锁 Bootloader , 重启到 fastboot 模式，fastboot flash init_boot RMX3850_kernelsu_patched_20240708_151112.img

fastboot 模式下刷入 release 里面下载的文件 RMX3850_kernelsu_patched_20240708_151112.img 的命令：fastboot flash init_boot RMX3850_kernelsu_patched_20240708_151112.img 
你也可以将 RMX3850_kernelsu_patched_20240708_151112.img 文件改名 inti_boot.img 也行,刷入的命令就是： fastboot flash init_boot inti_boot.img

你还可以自行参照这个 https://kernelsu.org/zh_CN/guide/installation.html#lkm-安装 链接的教程自己修补刷入。
