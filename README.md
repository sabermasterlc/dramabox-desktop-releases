<div align="center">

<img src="docs/images/dravo-icon.png" width="64" alt="DRAVO 软件图标">

<img src="docs/images/dravo-banner.svg" width="100%" alt="DRAVO · More Stories. One Screen.">

### 把好故事，放到你的电脑上。

全平台剧场 · 自动检测连接 · AI 字幕翻译 · 共享弹幕 · 收藏续播

[![Windows 1.1.7](https://img.shields.io/badge/Windows-1.1.7-27DCCB?style=flat-square&labelColor=171B29)](https://github.com/sabermasterlc/dramabox-desktop-releases/releases/tag/v1.1.7)
[![macOS 1.1.5](https://img.shields.io/badge/macOS-1.1.5_Preview-AF8CFF?style=flat-square&labelColor=171B29)](https://github.com/sabermasterlc/dramabox-desktop-releases/releases/tag/v1.1.5-macos-preview)

**[⬇ 下载 Windows 安装版](https://github.com/sabermasterlc/dramabox-desktop-releases/releases/download/v1.1.7/DRAVO_1.1.7_x64-setup.exe)**　｜　**[🍎 下载 Mac 1.1.5](https://github.com/sabermasterlc/dramabox-desktop-releases/releases/download/v1.1.5-macos-preview/DRAVO_1.1.5_aarch64.dmg)**

Windows 10 / 11 · macOS 14+，Apple M 系列芯片

[功能一览](#看剧也可以更顺手) · [平台支持](#平台支持) · [安装与升级](#安装与升级) · [反馈问题](https://github.com/sabermasterlc/dramabox-desktop-releases/issues)

</div>

---

## 从 DramaBox 开始，找到下一部想看的剧

![DramaBox 平台剧场首页：大幅推荐、海报片库和桌面导航](docs/screenshots/theater-home.png)

*DramaBox 平台的真实 Windows 界面截图，拍摄于更名前的 0.15.2 版本，用于展示剧场布局。当前软件名为 DRAVO；平台海报与作品资料归各自权利人所有。*

打开片库，挑一部剧，在电脑上接着看。需要兼顾其他事情时，切到置顶小窗；下次回来，从上次的进度继续。原 DramaBox 桌面客户端现已更名为 **DRAVO**，沿用原有应用标识和本机数据目录。

## 看剧，也可以更顺手

| 功能 | 你可以这样用 |
| --- | --- |
| **AI 字幕翻译** | 使用片源字幕、导入 SRT / VTT，或在支持的片源中听音识别；选择本地模型或在线 API 转译，调整双语样式、保存和导出字幕。[字幕指南](docs/ai-subtitles.md) |
| **剧场与沉浸播放** | 海报找剧、快捷选集、倍速、全屏、竖屏与置顶小窗，把浏览和观看放在一个界面里。 |
| **共享弹幕** | 边看边分享感受；共享弹幕使用独立社区服务，不与内容平台或手机 App 弹幕互通。 |
| **多平台切换** | 在「剧场」统一查看已接入平台和类目，输入剧名搜索并查看来源；各平台的搜索范围、播放和账号权益分别处理。 |
| **收藏与续播** | 跨平台统一查看本机收藏，保留来源、历史和观看进度，支持记录导入与导出。 |
| **项目与观影笔记** | 分开管理个人项目和作者项目，记录选集、观影笔记及有来源的公开指标。[项目指南](docs/project-data.md) |

<details>
<summary><b>看看 AI 字幕与播放界面</b></summary>

| AI 字幕设置 | 沉浸播放 |
| --- | --- |
| ![AI 字幕设置](docs/screenshots/ai-subtitles.png) | ![沉浸播放](docs/screenshots/immersive-playback.png) |

*以上为功能参考截图；字幕样式演示使用示例字幕，当前效果以实际版本和片源为准。*

</details>

## 安装与升级

| 系统 | 下载 | 使用要求 |
| --- | --- | --- |
| **Windows 1.1.7 · x64** | **[下载安装包](https://github.com/sabermasterlc/dramabox-desktop-releases/releases/download/v1.1.7/DRAVO_1.1.7_x64-setup.exe)** | Windows 10 / 11，使用系统 WebView2；AI 组件按需准备 |
| **Mac 1.1.5 · 预览版** | **[下载 DMG](https://github.com/sabermasterlc/dramabox-desktop-releases/releases/download/v1.1.5-macos-preview/DRAVO_1.1.5_aarch64.dmg)** | macOS 14+、Apple M 系列芯片；本次修复顶栏居中与窄小窗布局 |

**Windows：** 下载并安装后，首次按玻璃向导选择平台并自动检测连接，完成后会记住设置。已开启 VPN 时先检测系统网络；需要时可填写本机 HTTP 代理端口。原安装版可在「设置与快捷键 → 软件更新」检查新版本；下载后会校验更新签名，再由你选择安装。0.8.0 及更早版本需先手动安装新版。

**Mac：** 退出旧应用，将 DMG 内的 `DRAVO.app` 拖到“应用程序”；更新时替换原应用即可，保留原有本机数据目录。Mac 预览版使用 DMG 手动更新，采用临时签名，尚未完成 Apple 公证。[Mac 升级说明](https://github.com/sabermasterlc/dramabox-desktop-releases/releases/download/v1.1.5-macos-preview/Mac-README.txt)

本地 AI 首次需下载约 3.1 GB 组件，并至少预留 12 GB 空间。模型启用前请阅读并接受其使用条款。Windows 系统字幕与 Windows 画面 OCR 不适用于 Mac。

Windows 关闭窗口时可选择收起到托盘或退出，支持记住选择；也可在「设置 → 窗口与关闭」更改默认行为。网络出口与官网访问策略可能影响片库和播放，软件不会替你开启 VPN 或更改系统代理。

## 平台支持

各平台的接入深度不同。以下是当前共享版本的适配范围；新平台的账号、会员及付费权益仍待接入，免费集数以官网实时返回为准。

| 平台 | 片库与资料 | 播放范围 |
| --- | --- | --- |
| <img src="docs/images/platforms/dramabox.png" width="22" alt=""> **DramaBox** | 保留现有片库、搜索与详情 | 通过现有播放链，按官网逐集授权 |
| <img src="docs/images/platforms/hongguo.png" width="22" alt=""> **红果短剧** | 中文首页、真人剧 / 漫剧 / AI 剧分类分页、资料与选集 | 官网明确开放的免费集，逐集重新核验 |
| <img src="docs/images/platforms/reelshort.png" width="22" alt=""> **ReelShort** | 公开英文片库 | 已适配的公开免费集 |
| <img src="docs/images/platforms/goodshort.png" width="22" alt=""> **GoodShort** | 公开英文片库、作品资料与选集 | 已适配的公开免费集 |
| <img src="docs/images/platforms/shortmax.png" width="22" alt=""> **ShortMax** | 英文分类、真实分页、资料与选集 | 官网公开免费集 |
| <img src="docs/images/platforms/netshort.png" width="22" alt=""> **NetShort** | 英文首页片库、资料与选集 | 官网公开免费集 |
| <img src="docs/images/platforms/vigloo.png" width="22" alt=""> **Vigloo** | 英文分类、游标翻页、资料与单季目录 | 无 DRM 且明确免费的章节 |
| <img src="docs/images/platforms/moboreels.png" width="22" alt=""> **MoboReels** | 英文分类分页、官网搜索、资料与选集 | 官网公开免费集 |
| <img src="docs/images/platforms/shortime.png" width="22" alt=""> **Shortime** | 待接入 | 暂不开放切换 |
| <img src="docs/images/platforms/pinedrama.png" width="22" alt=""> **PineDrama** | 待接入 | 暂不开放切换 |

红果、ShortMax、Vigloo 的搜索筛选当前官网片库页，可翻页继续查找；MoboReels 读取官网搜索前 100 张结果卡片并去重；NetShort 暂限官网首页推荐。红果、ShortMax、MoboReels、Vigloo 暂不支持直接从视频识别对白，可以导入已有字幕。云同步和实际视频下载尚未开放。

## 使用前想知道的几件事

**已有记录还能用吗？** DRAVO 沿用原应用标识和本机数据目录；新旧名称的应用请避免同时运行。收藏与观看记录主要保存在本机，换设备前可导出备份。

**付费剧集能直接看吗？** 播放始终按平台对当前章节的授权执行。各平台的账号、会员与逐集播放权限相互独立。

**Mac 应该下哪一份？** 上方的 **DRAVO 1.1.5 DMG**。它延续原 Tauri Mac 客户端，支持 macOS 14+ 与 Apple M 芯片；旧 SwiftUI 0.1.0 属于另一条开发预览，不能代替此安装包。

**验证到什么程度？** Windows 1.1.7 的前端和原生测试、签名及部分公开片源检查已完成；Mac 1.1.5 的云端构建、原生测试、DMG 校验和 AI 安装 / CPU / Metal 受控样本检查通过。真实设备的旧版迁移、全片库播放、会员流程及长期稳定性仍需实际使用验证。

问题反馈请附系统与软件版本、平台、网络方式、剧名 / 集号、操作步骤及提示，并遮住账号和配对码等私人信息：[提交问题](https://github.com/sabermasterlc/dramabox-desktop-releases/issues)。

<details>
<summary><b>版本记录与开发资料</b></summary>

- [Windows 1.1.7 更新说明](https://github.com/sabermasterlc/dramabox-desktop-releases/releases/tag/v1.1.7)
- [Mac 1.1.5 顶栏修复](https://github.com/sabermasterlc/dramabox-desktop-releases/releases/tag/v1.1.5-macos-preview)
- [独立 SwiftUI 原生界面开发记录](docs/native-macos-preview.md)
- [更名前的介绍与历史记录](docs/legacy-dramabox.md)
- [全部发行版](https://github.com/sabermasterlc/dramabox-desktop-releases/releases)

</details>

---

这是个人开发的非官方第三方客户端，与各内容平台无隶属关系。内容、商标与素材归各自权利人所有，访问以平台授权和可用性为准。

本仓库仅提供软件发行、使用说明、界面预览及已公开的作者项目数据。应用工程源码和发布凭据不在此公开；GitHub 自动生成的 “Source code” 压缩包不是应用工程源码。Windows 网络组件随包提供许可与对应源码归档。

[作者项目清单](projects.json) · [反馈与建议](https://github.com/sabermasterlc/dramabox-desktop-releases/issues)

