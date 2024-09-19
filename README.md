# Kirara-Release

>该应用为私有应用，下载了也无法使用，需要申请使用资格

## 关于各个变体
在各个Release，你会看到诸如```x86_64```、```x86```、```arm64```、```arm```、```universal```等字眼，这些是为不同的ABI平台而打包的apk变体，每个APK在功能上是没有区别的

下面是选择指南，具体要以你设备的CPU为准，不懂可以自行Google自己的机子新号或者CPU获得相关信息。
- 比较新的实体机一般用```arm64```，除了部分非常老的机子依然是```arm```
- 虚拟机理论上什么都可以用，但为了得到更好的性能最好选择```x86_64```，32位请选择```x86```
- 如果实在是什么都不懂，可以直接选择```universal```，里面包含所有ABI平台的so，系统自动适配，但缺点显而易见：占用会大很多
