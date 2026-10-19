# DramaBox Desktop Releases

Windows 桌面客户端的公共发行仓库，仅存放安装包、便携包、签名、更新清单和说明。应用源码与签名私钥保留本地。

## 下载

前往[最新发行版](https://github.com/sabermasterlc/dramabox-desktop-releases/releases/latest)，选择 Windows x64 的 setup.exe 安装包。便携 ZIP 可解压试用。

## 当前功能

0.10.0 支持输入完整剧名等待上线，不必填写未知的上线时间。运行期间定期搜索所选语言的 DramaBox 官网，确认上线后加入本机项目，并在通知中心保存未读消息。退出软件后暂停，重新打开补查。

## 应用内更新

每次启动立即检查 GitHub 稳定版，也可点击顶部“软件更新”或进入“设置与快捷键 → 软件更新”。下载和安装由用户决定，更新包必须通过固定公钥和版本绑定签名验证才可安装。安装会关闭软件，请先结束播放。

0.9.0 已有更新器，可在线更新；0.8.0 及更早版本需先手动安装新版。便携版若需在线安装更新，请先使用安装包。

## 附件

- setup.exe：Windows x64 安装包。
- windows-x64-portable.zip：便携程序及必要资源。
- windows-x64.exe：独立可执行文件；浏览器账号连接需配套资源。
- latest.json / setup.exe.sig：应用签名更新使用。
- PUBLIC-SHA256.json：公开附件校验值。

平台范围、已实现功能与尚未接通的手机端服务，请查看对应版本的 Release notes。
