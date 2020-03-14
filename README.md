# redmibook 14寸笔记本的黑苹果EFI

本人手里的redmibook，经过不断的折腾，终于算是把黑苹果几乎完美解决了。中间踩了不少坑也费了不少脑细胞，过程不表了太曲折。好歹成功了也算苍天不负有心人哈，这个过程中我发现网上关于这款本子的黑苹果EFI的几乎没有（隔壁也有同学提供EFI但我发现并不是很完美）于是我觉得把我搞的这个EFI贡献出来，如果你也正在折腾你的那台红米本子，可以拿我的去试试。祝你成功！

我的黑苹果系统是基于黑果小兵网站的：[macOS Catalina 10.15.2 19C57 正式版 with Clover 5100原版镜像[双EFI双平台版]](https://blog.daliansky.net/macOS-Catalina-10.15.2-19C57-Release-version-with-Clover-5100-original-image-Double-EFI-Version.html)，理论上讲应该最新的Catalina 10.15.3应该也是适用的。如果有系统安装方面的问题，可以多去黑果小兵上面多看看，或许就能找到你要的帮助。

关于这个有任何问题和帮助可以在issue里提出来，我会尽量帮助大家。

## 电脑配置 

先列一下这个电脑的配置，如果有类似配置的可以参考哈

|设备|型号|
|---|---|
|处理器|Inter（R）i7-8565U 1.80Ghz|
|内存|8Gb|
|显卡|1.Nvidia Geforce MX250 2.inter(R)UHD Graphics 620
|硬盘|SAMSUNG 512GB
|主板|TM814
|声卡|Realtek ALC256
|网卡|Intel Wireless-AC9462
|显示器|NCP:4a00 分辨率 1920x1080

##  完整度介绍

* 显卡：核显驱动正常（独显无解，这个神仙也没有办法）。
* HDMI：正常，但是不能4K输出。
* 声卡：正常。
* USB: 正常。
* 蓝牙：正常
* 电源管理：正常，可以显示剩余电量。
* 网络：暂时还是一直用有线网络使用，wifi网卡可以等我买到替换网卡再补充。
* 触控板：正常，并且可以多指操作。（在本子的F12上是触控板的开关，如果不起作用可以按一下F12试试）。
* 功能键：本机键盘的静音键、音量+、音量- 可用，其他不行。
* 睡眠唤醒：正常。
* 操作系统 & Clover ：使用的是黑果小兵的“macOS Catalina 10.15.2(19C57) Installer for Clover 5100 and WEPE”

![](https://home.superliunian.tech:8077/images/2020/03/14/be2dd8cb1c971cf32bfd1317103649fa.png  | width=655)

![Screen Shot 2020-03-13 at 8.15.11 P](https://home.superliunian.tech:8077/images/2020/03/14/6d1b6872329b66dbe339b827cbfb7191.png | width=655)

![Screen Shot 2020-03-13 at 8.26.32 P-w960](https://home.superliunian.tech:8077/images/2020/03/14/63434e4f2f07a7a53d73fadfd6e658bc.png)

![IMG_6264-w1512](https://home.superliunian.tech:8077/images/2020/03/14/ff4451e86a44d5fa169637475a1ee60b.jpg)


## 如何使用

把我这里提供的CLOVER目录下载下来，替换到你的EFI/CLOVER目录即可。（如果你搞过黑苹果，我说的这个你应该都懂的，具体方法我就不再废话了，哈哈）还有，操作前请做好备份！万一水土不服呢也好有个后悔药。

## 感谢

如果我的贡献帮助到你，并且让你心情愉悦了，那可不可以请我一个早餐的煎饼呢？那你开心我也会很开心的，哈哈。

![](https://home.superliunian.tech:8077/images/2020/03/14/9c423e6996ca9f4aad2d562e06dbab3a.jpg | width=621)
