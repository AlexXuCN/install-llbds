# install-llbds

用 GitHub Actions 安装[LiteLoaderBDS](https://github.com/LiteLDev/LiteLoaderBDS)

## 为什么？

如果你使用*nix系统，因为某些原因无法用wine运行`PeEditor.exe`且没有Windows电脑，可以考虑滥用一下ghactions（
或者只是懒得下各种东西....?

## 如何使用？

* [fork](https://github.com/AlexXuCN/install-llbds/fork)此项目
* 启用Actions
* 更改`VERSION`文件中的`BDS_VER`和`LL_VER`至你要安装的对应版本并提交更改
* 去Actions里等候一会，下载artifact

## 注意

为了节省上传附件的时间，成品先经过7z压缩，即下载下来的压缩包有2层（悲）
