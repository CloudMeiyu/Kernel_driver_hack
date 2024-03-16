# Kernel_driver_hack
> Android/Linux Kernel driver read and write  memory.

##### ~~暂时无法读取bss段内存~~

##### ~~读取内存过长时会出现错误~~

使用相应型号的内核源码编译驱动文件

使用`insmod xxx`命令即可加载驱动

使用`rmmod xxx`命令即可卸载驱动

使用`dmesg`查看驱动日志

Google官方编译内核教程(只提供GKI内核编译)：`https://source.android.com/docs/setup/build/building-kernels?hl=zh-cn`

共创者  [Rogo](https://github.com/rogxo/kernel_hack)。以及主要测试以及机型适配提供： [LuMing](https://github.com/smm800)，感谢大佬的帮助:[小黑](https://github.com/GameCheatExpert)

请勿拿本项目用作非法用途或商用，本项目开源仅供学习交流，并且源码写的比较烂，还希望各位大佬提交fork优化本驱动模块
