# MiNotes

这是小米便签的迭代工程

配置环境注意查看`app/build.gradle`，`gradle.properties`中的改动

第一次配置项目会先sync gradle设置，在`build.gradle`中添加`google()`以帮助下载

注意：`gradle/wrapper/gradle-wrapper.properties`和`build.gradle`中的dependencies中gradle需要版本一致

## 环境

* Android Studio 2022.3.1
* Android SDK Build-Tools 34
* Java JDK 17.0.4

## v0.0

`v0.0`是小米便签的初始版本，在上述环境中已经调试妥当

## v0.1

`v0.1`是小米便签的第一次更新

* 实现语音输入功能（调用科大讯飞语音包实现）
* 修复一些已知问题

## v0.2

`v0.2`是小米便签的第二次更新

* 实现朗读功能（Android原生）
* 修复一些已知问题

## v0.3

`v0.3`是小米便签的第三次更新

* 实现置顶功能
* 修复一些已知问题

