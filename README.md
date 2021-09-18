# XDD-BUILD

## 20210913 更改编译对象
 
这是个使用 Github Action 的编译项目。

编译对象为 [764763903a/xdd-plus](https://github.com/764763903a/xdd-plus) ；

编译结果将会上传到 [Release](https://github.com/Huiaei/XDD-BUILD/releases) 中，Release 格式名为 **XDD-PLUS-[时间]**；

**不保证其编译结果的可用性**。

如果需要立即编译请点击右上角的 **Star** ，当 **Star** 后过 1-2 秒， Action 将会开始编译，大约过 5 分钟左右，编译结果会上传到 [Release](https://github.com/Huiaei/XDD-BUILD/releases)

### V4面板

[764763903a/xdd-plus](https://github.com/764763903a/xdd-plus)支持V4面板，自动化编译没有添加自动按照原仓库进行修改编译。

如果需要V4面板，可以Fork原仓库，按照原仓库的描述自行更改，之后在Fork修改后的库中添加 Github Action 的流程配置文件。

流程配置文件可以参考[本项目](https://github.com/Huiaei/XDD-BUILD/blob/main/.github/workflows/BUILD.yml)，自行添加到action中并修改第31行 git clone 的目标仓库。

----

## 20210901

**已经失效，cdle/xdd 原仓库已经删库了。** 另寻其他项目吧。

这是个使用 Github Action 的编译项目。

编译对象为 [cdle/xdd](https://github.com/cdle/xdd) ；

编译结果将会上传到 [Release](https://github.com/Huiaei/XDD-BUILD/releases) 中，Release 格式名为 **[时间]**；

**不保证其编译结果的可用性**。

如果需要立即编译请点击右上角的 **Star** ，当 **Star** 后过 1-2 秒， Action 将会开始编译，大约过 5 分钟左右，编译结果会上传到 [Release](https://github.com/Huiaei/XDD-BUILD/releases) 。
