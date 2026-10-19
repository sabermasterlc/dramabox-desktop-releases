<div align="center">

<img src="docs/images/dramabox-logo.png" width="88" alt="DramaBox 图标">

# DramaBox 短剧电脑版

### 在电脑上找剧、追剧，接着上次的进度看

剧场首页 · 沉浸播放 · 自动连播 · 竖屏小窗 · 收藏与续播 · 观影笔记 · 项目复盘

**[⬇ 下载 Windows 版](https://github.com/sabermasterlc/dramabox-desktop-releases/releases/download/v0.13.0/DramaBox_0.13.0_x64-setup.exe)** · **[🍎 下载 Mac 预览版](https://github.com/sabermasterlc/dramabox-desktop-releases/releases/tag/v0.13.0-macos-preview)** · **[查看全部版本](https://github.com/sabermasterlc/dramabox-desktop-releases/releases)**

Windows 10 / 11（64 位） · macOS 14+（Apple 芯片 / Intel 分别下载）

</div>

> macOS 首个预览版已通过云端编译和安装包校验，尚未完成真实 Mac 上的安装、播放和登录测试。当前只有临时签名，未完成 Apple Developer ID 签名和公证。

## 🖥️ 这个项目能做什么？

DramaBox 是一个面向电脑使用的非官方短剧客户端。打开软件就能浏览 DramaBox 片库，搜索想看的剧，切换到沉浸播放；需要兼顾其他事情时，也可以使用竖屏或置顶小窗。

除了看剧，还能保存本机收藏和观看进度、写观影笔记，整理自己的项目，以及查看作者发布的作品与公开指标记录。

## ✨ 主要功能

| 功能 | 现在可以做什么 |
| --- | --- |
| 🎬 剧场与沉浸播放 | 浏览推荐分区，从剧场进入沉浸模式，随时返回片库。 |
| 🔍 搜索与找剧 | 搜索联想、分页、最近搜索；按官网提供的分类和剧种标签筛选。 |
| 🌍 多语言片库 | 切换官网提供的 17 种内容语言；软件界面保持中文。 |
| ▶️ 播放与续播 | 分组选集、自动下一集、倍速、音量、全屏、播放进度保存；片源提供时可选择音轨与字幕。 |
| 🪟 桌面观影 | 竖屏模式、小窗、置顶、悬停隐藏、深色与浅色主题。Mac 窗口行为待实机确认。 |
| ❤️ 收藏与历史 | 本机保存；按登录账号分区，支持旧记录预览迁移、导入与导出。 |
| 🔔 预约与通知 | 按剧名预约上线、关注选集更新，在软件运行并联网时检查，结果进入本机通知中心。 |
| 📝 观影工具 | 保存整剧或分集笔记、整理选集清单，方便回看与复盘。选集清单不等于离线下载。 |
| 📁 项目与数据 | 分开管理“我的项目”和“作者项目”；同步作者发布的作品清单及公开指标，查看历史趋势。 |
| 🔄 Windows 更新 | 0.9.0 及以上安装版支持软件内检查更新、验签后安装。Mac 暂不提供自动更新。 |

**内容与账号范围：** 当前片库和播放来自 DramaBox 官网链路；能否播放以官网对当前章节返回的授权为准。其他平台、官方排行榜、手机端收藏/历史同步、远端评论与实际视频下载尚未接通。本机笔记、弹幕等记录不会自动同步给其他观众。

## 📸 界面预览

以下是本项目已有 Windows 版本的真实界面截图（0.7.0—0.11.0），用于展示布局与交互。界面细节可能随版本调整，不代表 Mac 已完成实机验证。

| 剧场首页 | 沉浸播放 |
| --- | --- |
| ![剧场首页](docs/screenshots/theater-home.png) | ![沉浸播放](docs/screenshots/immersive-playback.png) |

| 搜索与官网评分 | 观影笔记 |
| --- | --- |
| ![搜索结果与官网评分](docs/screenshots/search.png) | ![观影笔记](docs/screenshots/viewing-tools.png) |

截图中的海报、剧名与视频画面属于各自权利人，仅用于说明软件界面。

## 📥 下载与安装

| 电脑类型 | 下载 | 当前状态 |
| --- | --- | --- |
| Windows 10 / 11 · 64 位 | [Windows 安装包](https://github.com/sabermasterlc/dramabox-desktop-releases/releases/download/v0.13.0/DramaBox_0.13.0_x64-setup.exe) | 0.13.0 |
| Mac · Apple 芯片（M 系列） | [Apple 芯片 DMG](https://github.com/sabermasterlc/dramabox-desktop-releases/releases/download/v0.13.0-macos-preview/DramaBox_0.13.0_aarch64.dmg) | macOS 14+ · 预览版 |
| Mac · Intel 处理器 | [Intel DMG](https://github.com/sabermasterlc/dramabox-desktop-releases/releases/download/v0.13.0-macos-preview/DramaBox_0.13.0_x64.dmg) | macOS 14+ · 预览版 |

### Windows

1. 下载 `DramaBox_0.13.0_x64-setup.exe`，按安装向导完成安装。
2. 启动 DramaBox，按首次网络指南检查片库、封面和公开片源连接。
3. 以后在“设置与快捷键 → 软件更新”检查新版本。0.8.0 及更早版本需要先手动安装新版。

关闭主窗口会暂停视频并收起到托盘；需要彻底退出时，从托盘菜单选择“退出”。Windows 提供可选的 App 专用 Wi-Fi 通道，需要保持无线网络连接。

### macOS

1. 在“关于本机”查看芯片或处理器，下载对应 DMG。两个安装包分别用于 Apple 芯片和 Intel，不能互相替代。
2. 打开 DMG，将 DramaBox 拖入“应用程序”，再从“应用程序”启动。
3. 当前预览版未公证，首次启动可能被系统阻止。核对下载来源与附件校验值后，可参考 [Apple 的打开 App 说明](https://support.apple.com/zh-cn/102445)。如果系统报告损坏、恶意软件或其他错误，请保留完整提示并反馈。

Mac 版使用系统网络，未提供 Windows 专用 Wi-Fi 通道。Google 独立登录需要本机安装 Chrome 或 Edge。Mac 预览版需要手动下载后续版本。

## ❓ 常见问题

### 需要登录吗？会员集能直接看吗？

公开页面允许访问的片库和公开剧集可直接尝试。需要账号的章节仍受官网逐集授权限制；登录或显示会员身份不代表所有章节都已解锁。本项目不提供会员绕过或解锁服务。

### 收藏和历史会与手机同步吗？

目前保存在当前电脑，按账号独立分区。尚未与 DramaBox 手机端或其他电脑自动同步；更换电脑前可以导出本机记录。

### 为什么搜不到剧，或者视频无法加载？

先确认片库语言和网络连接，再使用软件中的连接检查。官网访问策略、内容地区、账号授权或片源状态都可能影响结果。Windows 的可选 Wi-Fi 通道与 Mac 的系统网络是不同的连接方式。

### 为什么项目数据和手机上看到的不一样？

项目记录来自官网公开的观看、追剧等字段，统计口径由官网决定，不能当作后台精确播放、收入或实时业务报表。缺失的数据保持缺失，不推算补齐。

### Mac 版测试到了哪一步？

Apple 芯片和 Intel 两个安装包均已通过云端编译、架构检查、临时签名校验及 DMG 完整性检查。云端 ARM Mac 上通过 194 项前端测试、25 项原生测试；另有 5 项需要特定环境的测试未运行。Intel 安装包由 ARM Mac 交叉编译。两类 Mac 的真实安装、播放、登录与长期运行仍待验证。

### 怎么反馈问题？

在 [Issues](https://github.com/sabermasterlc/dramabox-desktop-releases/issues) 中说明系统版本、芯片/处理器、软件版本、复现步骤与完整错误提示。截图请遮住账号、邮箱、配对码等私人信息。

## 📌 近期更新

- **macOS 0.13.0 预览版**：增加 Apple 芯片与 Intel DMG，适配独立账号会话存储，修复 Mac 浏览器连接关闭问题。
- **Windows 0.13.0**：作者项目后台采集与发布、本机账号记录隔离、关闭到托盘和首次网络指南。
- **Windows 0.12.0**：增加 App 专用 Wi-Fi 通道。

完整变更和各版验收范围见 [Releases](https://github.com/sabermasterlc/dramabox-desktop-releases/releases)。Mac 预览版单独发布，不替换 Windows 稳定更新清单。

## ⚠️ 项目说明

本项目是个人开发的非官方第三方客户端，与 DramaBox 官方无隶属关系。片库、剧集、商标及相关素材的权利归各自权利人所有，内容访问以官网授权和可用性为准。

本公开仓库用于发布安装包、说明、界面预览和作者项目数据；应用源码由私有仓库维护，发布凭据不随安装包提供。GitHub 自动生成的“Source code”压缩包仅包含本公开仓库文件，不是应用工程源码。

Windows 安装包内的 Mihomo 网络组件包含对应许可、说明与源码归档；Mac 安装包不包含该组件。

<details>
<summary>作者项目清单维护</summary>

作者作品清单发布在 [projects.json](./projects.json)，历史观测按月保存在 `project-history/`。普通用户可以在软件里同步阅读，无需重新下载安装包。个人项目和观影笔记默认保存在本机，不会自动提交到这个仓库。

维护清单时保留 `version: 1`、`updatedAt` 与 `projects` 结构，仅发布确有意公开的作品资料，不包含私人笔记、账号资料或配对码。

</details>

## ⭐ 支持与反馈

如果这个工具对你有帮助，欢迎点个 Star，也欢迎在 Issues 中留下具体问题和建议。
