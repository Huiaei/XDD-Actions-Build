# XDD-BUILD

## 使用说明

1. 克隆源项目的代码到自己知道的地方
2. 打开[Release](https://github.com/Huiaei/XDD-BUILD/releases)，按照你的平台运行环境选择下载并重命名为`xdd`
3. 移动`xdd`到外面代码克隆位置的根目录，通常哪里有`main.go`文件

* 由于是外部编译结果，**不保证其编译结果的可用性**。
* 如果你的部署环境中没有`go`语言环境，则无法自动更新编译`xdd`，相应的功能也失效。
* 如果需要立即编译请点击右上角的 **Star** ，当 **Star** 后过 1-2 秒， Action 将会开始编译，大约过 5 分钟左右，编译结果会上传到 [Release](https://github.com/Huiaei/XDD-BUILD/releases)

## 更改日志

### 20211209 

[764763903a/xdd-plus](https://github.com/764763903a/xdd-plus)项目已经自带编译，推荐直接使用原厂库编译

### 20210913 更改编译对象
 
这是个使用 Github Action 的编译项目。

**编译对象**为 [764763903a/xdd-plus](https://github.com/764763903a/xdd-plus) ；

编译结果将会上传到 [Release](https://github.com/Huiaei/XDD-BUILD/releases) 中，Release 格式名为 **XDD-PLUS-[时间]**；

#### V4面板

[764763903a/xdd-plus](https://github.com/764763903a/xdd-plus)项目说明中表示支持V4面板，但自动化编译未对其修改项进行适配。

如果对源仓库中的修改的确有需要，请按照原仓库说明更改相应文件。
个人推荐方式为Fork原仓库，按照说明进行相应的修改；复制本项目的自动化编译配置文件，修改第31行
```yml
      - name: 获取仓库代码
        run: |
          git clone https://github.com/764763903a/xdd-plus.git /home/runner/work/xdd/
```
将其克隆仓库`https://github.com/764763903a/xdd-plus.git`修改为自己修改好的仓库地址。

----

### 20210901

**已经失效，cdle/xdd 原仓库已经删库了。** 另寻其他项目吧。

这是个使用 Github Action 的编译项目。

**编译对象**为 [cdle/xdd](https://github.com/cdle/xdd) ；

编译结果将会上传到 [Release](https://github.com/Huiaei/XDD-BUILD/releases) 中，Release 格式名为 **[时间]**；
