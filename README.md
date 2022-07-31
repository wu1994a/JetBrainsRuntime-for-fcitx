# JetBrainsRuntime-for-Linux-x64  
手动触发，通过打[社区大佬的补丁](https://github.com/prehonor/myJetBrainsRuntime)进行改进并针对 Linux x64 平台提供[编译产物](https://github.com/ayanamist/JetBrainsRuntime-for-fcitx/releases)。

官方跟进issue链接： https://youtrack.jetbrains.com/issue/JBR-2460

TLDR：由于AWT完全缺乏相关代码实现，这块估计短时间内不会有官方实现，这个补丁其实也有很多问题，例如缩放下位置依然是不对的。

## 说明  
解决在 Linux x64 操作系统环境下，使用 JetBrains 系 IDE 使用 fcitx 输入法候选框不跟随光标的问题。

使用方法：Ctrl+Shift+A 搜索 runtime 然后将 boot runtime 指向本产物

## 参考  
* [idea 中文输入法定位不准问题修复(fcitx框架输入法)](https://blog.csdn.net/u011166277/article/details/106287587)  
* [BUG解决之路-1 Linux下fcitx输入法候选框在IDEA等JetBrains系列IDE中不跟随光标（JetBrains Runtime版本：11.0.7）](https://blog.csdn.net/qq_41859728/article/details/109187748)  
* [New branch naming policy in JBR repo](https://youtrack.jetbrains.com/issue/JBR-4375/New-branch-naming-policy-in-JBR-repo)