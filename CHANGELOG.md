### 最近更新

## 5.3.0 (2019-09-19)

1. 替换 apk reader 以避免某些环境读取 apk 版本号报错的问题

## 5.2.9 (2019-09-18)

1. 添加 proguard 混淆规则以解决开启混淆后闪退的问题

## 5.2.8

1. 解决某些情形下 Android 调用 switchVersion 不能重启的问题

## 5.2.7

1. 改进 windows 端打更新包的兼容性（部分 windows 机器上会产生空 ppk 文件）

## 5.2.4

1. 支持 RN 0.61 的 hermes（路径变化）
2. iOS 端使用第三方的 SSZipArchive 以减少重名冲突

## 5.2.2

1. 修复一处导致 iOS 回滚的问题

## 5.2.1

1. 检测如果开启了 hermes，则自动编译为 hermes 字节码格式

## 5.2.0

1. 添加 typescript 声明
2. 支持 cocoapods

## 5.1.9

1. 重写 bundle 命令以提升版本兼容性
2. 改进命令行的输出样式

## 5.1.8

1. 服务器迁移到 https
2. android 支持 64 位

## 5.1.6

解决 Android 热更新后部分图片丢失问题：

同一个项目中放置了多个完全相同的文件，在 5.1.0 至 5.1.5 之间的版本中，更新后有时会出现其中的部分无法显示。此问题在 5.1.6 版本修复。

修复此问题涉及原生部分，需要重新打包。