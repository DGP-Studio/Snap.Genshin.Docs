# 快速开始

## 最低系统要求
|要求|规格|
|-|-|
|**最低可运行系统版本**|Windows 7 SP1 - 6.1.0|
|**最低兼容系统版本**|**Windows 10 1903 - 10.0.18362.0**|
|推荐系统版本|Windows 11 21H1 - 10.0.22000.0|
|运行时|.NET Desktop Runtime 6.0.2|
|可选组件|WebView2 Runtime|

## 下载 Snap Genshin

- 你可以在 Snap Genshin 的 GitHub 仓库的 [发布页面](https://github.com/DGP-Studio/Snap.Genshin/releases) 下载名为 `Publish.zip` 的最新版程序
  - 连接有困难的用户亦可以通过 [镜像站](https://resource.snapgenshin.com/Publish.zip) 分流下载
  - 你可以从 [Snap Genshin资源中心](https://resource.snapgenshin.com) 下载所有和 Snap Genshin 相关的文件

## 启动 Snap Genshin

- 将下载的压缩包内容**完整解压**到你认为合适的目录进行解压缩
  - **请勿将 Snap Genshin 置于系统使用的目录下（如`C:\Windows`等，这些目录有特殊的权限管理）**
  - 同时其他的 Snap Genshin 主程序与 WebView2 无法写入的目录也不能用于存放本软件
- 启动为名`DGP.Genshin.exe`的主程序
  - 如果弹窗出现缺少`.NET`环境错误，可参阅 [.NET 环境缺失](./FAQ/dotNET-env.md)文档
- 此时，你应当已经可以看到程序界面

## 首次启动

在第一次成功打开程序后，在等待校验资源完整性时，你需要设置你的米游社Cookie，否则我们无法获取到你的帐号信息从而提供相应的功能。

- 点击`设置Cookie`按钮
- 点击自动获取下方的`在新窗口中登录`按钮
- 等待新窗口中的米游社加载完成后，在米游社中登录你的帐号
- 登录完成后，点击新窗口右上角的`继续`，如果`继续`按钮没有反应，说明你的账号尚未登录米哈游通行证，可以尝试在头像的下拉菜单中登录米哈游通行证再试
- 此时，你就完成了Snap Genshin的初始化设置了
