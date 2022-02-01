# JetBrainsRuntime-for-Linux-x64  
利用 Github Actions 每4个小时检查 [JetBrainsRuntime](https://github.com/JetBrains/JetBrainsRuntime) 是否有新的release（不包括pre-release），通过打[社区大佬的补丁](https://github.com/prehonor/myJetBrainsRuntime)进行改进并针对 Linux x64 平台提供[编译产物](https://github.com/ayanamist/JetBrainsRuntime-for-fcitx/releases)。  

## 说明  
解决在 Linux x64 操作系统环境下，使用 JetBrains 系 IDE 使用 fcitx 输入法候选框不跟随光标的问题。

使用方法：Ctrl+Shift+A 搜索 runtime 然后将 boot runtime 指向本产物

## 参考  
* [idea 中文输入法定位不准问题修复(fcitx框架输入法)](https://blog.csdn.net/u011166277/article/details/106287587)  
* [BUG解决之路-1 Linux下fcitx输入法候选框在IDEA等JetBrains系列IDE中不跟随光标（JetBrains Runtime版本：11.0.7）](https://blog.csdn.net/qq_41859728/article/details/109187748)  

