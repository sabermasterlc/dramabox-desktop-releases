# DramaBox Desktop Releases

Windows 桌面客户端的公开发行仓库，仅存放安装包、便携包、签名更新清单及发行说明。应用工程源码与更新签名私钥保留本地。

## 下载

前往 [最新发行版](https://github.com/sabermasterlc/dramabox-desktop-releases/releases/latest)，选择 Windows x64 的 setup.exe 安装包。便携 ZIP 可直接解压试用。

## 应用内更新

0.9.0 是首个包含在线更新器的版本。0.8.0 和更早版本需要先手动安装一次0.9.0或更新版本。

此后软件启动时检查 GitHub 稳定版，也可在「设置与快捷键 → 软件更新」手动检查。用户选择下载后，软件验证包签名和对应版本，验证通过才允许「安装并重启」。安装时会关闭软件，请先结束播放。

便携运行不是原位置自动覆盖升级；需要在线安装更新时，请先安装安装包。

## 附件

- setup.exe：Windows x64 安装包。
- windows-x64-portable.zip：便携程序及必要资源。
- windows-x64.exe：独立可执行文件；备用浏览器连接需要便携包内资源。
- latest.json / setup.exe.sig：应用内签名更新使用，不需手动打开。
- PUBLIC-SHA256.json：公开附件哈希。

各版本已实现功能、服务接入边界和平台范围请查看对应 Release notes。未验证的手机端服务不会因页面入口存在而视为已接通。
