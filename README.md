# android-x86-arm-enable

安卓x86的arm兼容文件

## 如何在android x86中手动安装Arm Native Bridge

文件下载地址：<https://github.com/SGNight/Arm-NativeBridge?tab=readme-ov-file>

下载所需的.sfs文件。

将文件houdini.sfs重命名为houdini7_y.sfs

将houdini7_y.sfs文件复制到/data/arm/文件夹

如果你想运行arm64应用程序，对z系列也要这样做。

按alt+f1打开终端并运行命令enable_nativebridge。

如果你没有收到任何错误消息，那么你已经成功地在系统上激活了ARM Native Bridge。

按alt+f7返回GUI并下载任何游戏/应用程序来测试libhoudini。

## xyz含义

houdini_7_x = (x86 arm translation)

houdini_7_y = (x86_64 arm translation)

houdini_7_z = (x86_64 arm64 translation)

## 版本对应

Houdini_6 series = android 6.0

Houdini_7 series = android 7.0

Houdini_8 series = android 8.0

Houdini_9 series = android 9.0
