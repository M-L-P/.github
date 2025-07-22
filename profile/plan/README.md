## 📅规划和进展🗺️

### rEFInd-theme-Yours, Yours-UEFI/LegacyBIOS
当前功能|进展中|未来规划
--|--|--
✔️安全启动开启下运行任意 .efi 程序（包括 Clover 和 OpenCore）；<br/>✔️适配大屏；<br/>✔️支持 LegacyBIOS；<br/>✔️横幅编辑器；<br/>|……|🗺️图形界面的安装兼设置程序；

### grub2-brunch
当前功能|进展中|未来规划
--|--|--
✔️安全启动开启下启动任意未签名的内核；<br/>✔️快捷键 f10 截屏；<br/>✔️图形界面选择.img 映像；<br/>✔️自定义的倒计时秒数；<br/>✔️支持 鼠标触控板；<br/>|🔜多国 键盘布局；<br/>🔜根据分辨率 自动缩放屏幕；<br/>🔜提供测试翻译的入口；<br/>|🗺️图形界面设置内核命令行参数；<br/>🗺️支持启动全盘安装的 chromeOS；

### grub2-fyde
当前功能|进展中|未来规划
--|--|--
✔️安全启动开启下启动任意未签名的内核；<br/>✔️切换 A/B 槽位；<br/>✔️快捷键 f10 截屏；<br/>✔️快捷键 f12 显示所有的启动菜单；<br/>✔️自定义的倒计时秒数；<br/>✔️支持 鼠标触控板；<br/>✔️多国 键盘布局；<br/>✔️根据分辨率 自动缩放屏幕；<br/>✔️定时切换 亮暗主题；<br/>✔️更新到 fydeOS v20；<br/>✔️隐藏彩蛋；<br/>✔️提供测试翻译的入口；<br/>✔️提供测试 KernelSU 的入口；<br/>✔️提供测试 APatch 的入口；<br/>|🔜启动本地硬盘上的安装映像【.img】；<br/>⚠️initrd 【virtual_usb.cpio】 有问题，<br/>暂时无法启动，需要完善源代码；<br/>⚠️KernelSU 需要使用 LKM 模式，<br/>  修补 `[FYDEOS-DUAL-BOOT]: /boot/dual_boot_ramfs.cpio`；<br/>⚠️APatch 需要用 x86_64 架构的 KernelPatch，<br/>  修补 `[FYDEOS-DUAL-BOOT]: /boot/vmlinuz-版本号`；|📅支持 KernelSU<br/>📅支持 APatch

### grub2-androidx86
当前功能|进展中|未来规划
--|--|--
✔️安全启动开启下启动任意未签名的内核；<br/>✔️快捷键 f10 截屏；<br/>✔️自定义的倒计时秒数；<br/>✔️支持 鼠标触控板；<br/>✔️图形界面设置内核命令行参数；<br/>✔️图形界面设置是否开启 initrd-magisk；<br/>✔️图形界面切换 userdata；<br/>|⚠️考虑到目前的 Android-x86 不稳定，<br/>⚠️考虑到 Android 16 官方自带桌面模式，<br/>⚠️索性停更，等 Android-x86 再发展一段时间然后看情况吧！<br/>|📅多国 键盘布局；<br/>📅根据分辨率 自动缩放屏幕；<br/>📅提供测试翻译的入口；<br/>📅启动本地硬盘上的虚拟光驱【.iso】；<br/>📅图形界面释放安装映像【.iso】，安装到本地；<br/>




