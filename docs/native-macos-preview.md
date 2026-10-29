# DRAVO · 原生 Mac 新界面开发预览 0.1.0

> 当前 DRAVO Mac 下载请使用 [1.1.5 DMG](https://github.com/sabermasterlc/dramabox-desktop-releases/releases/download/v1.1.5-macos-preview/DRAVO_1.1.5_aarch64.dmg)，支持 macOS 14+、Apple M 芯片。本页保留独立开发或历史记录。

这次开放下载此前完成云编译的 **SwiftUI / Liquid Glass 原生 Mac 新界面开发包**。它是 DRAVO 项目下独立推进的 Mac 原生重建，不等同 Windows 1.1.0 的完整功能迁移。

## 下载与系统要求

- **Apple M 系列芯片，macOS 26 或更新版本。** 不适用于 Intel Mac 或 macOS 14/15。
- 下载 `DramaBox-Native-macOS-arm64-dev.zip`，解压得到 `DramaBox Native.app`，拖到“应用程序”后打开。
- 已编译包内仍显示 **DramaBox Native 0.1.0**，使用独立标识 `com.dramabox.desktop.native`。本次发布保留原始包体和签名；不会自动迁移旧 Tauri Mac 版记录。
- 使用 ad-hoc 开发签名，未取得 Apple Developer ID 签名或公证。若系统阻止启动，请保留完整提示并反馈。

## 本阶段已实现

- SwiftUI 原生分栏导航、工具栏、搜索、设置、菜单与窗口控件。
- 系统 Liquid Glass 材质与原生玻璃控件。
- DramaBox 公开片库分页、搜索、语言选择、作品详情与公开可播放选集。
- AVKit / AVPlayer 原生播放控制；仅接受官网明确提供的逐集授权地址。
- 独立本机收藏、主题、语言和自动播放设置。

## 尚未迁移

账号与会员读取、AI 字幕安装/识别/翻译、作者与个人项目管理、完整历史续播、推荐轮播、榜单、预约通知、共享弹幕、小窗和软件更新仍待迁移。Windows 1.1.0 的新增多平台片库未在此包接入。

## 验证到了哪一步

2026-10-27 的 Mac 云构建通过：原生编译、4 项解析测试、ad-hoc 签名结构检查；已核对 ZIP CRC、ARM64、最低系统版本与独立应用标识。

后续附加启动检查因 GitHub Mac runner 容量不足而未执行，不能算应用启动通过或失败。真实 Mac 上的启动、视觉交互、联网与视频播放仍待验证。这是一份开发预览包。

## 发布与源码

公开附件仅提供已编译应用 ZIP、使用说明、结构核验记录和校验值。**应用工程源码继续保留在私有仓库，不随本次发布公开。**

GitHub 自动生成的 “Source code (zip/tar.gz)” 仅打包这个公开发行仓库中的说明、图片和已公开项目数据，不包含 Mac Swift 工程或 Windows 应用工程。

本预览不会替换 Windows 1.1.0 的最新正式版标记与自动更新清单。旧的 macOS 14+ Tauri 0.16.0 历史预览版继续单独保留。

反馈请提供芯片、macOS 版本、操作步骤和完整错误提示；截图请遮住私人信息。

[回到项目首页](../README.md) · [下载与校验附件](https://github.com/sabermasterlc/dramabox-desktop-releases/releases/tag/v0.1.0-macos-native-preview)
