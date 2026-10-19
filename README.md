# DramaBox

[下载最新版 Windows 安装包](https://github.com/sabermasterlc/dramabox-desktop-releases/releases/latest)

每个版本只保留安装包和 latest.json 两项附件。用户下载“Windows 安装包”即可；更新清单供软件读取，无需手动下载。0.9.0及以上可在软件顶部点击“软件更新”。

## 项目

- 我的项目：用户自行新增、导入或从剧集加入，保存在本机，不会上传到本仓库。
- 作者项目：作者在仓库根目录维护 [projects.json](./projects.json)，软件启动时及运行中每15分钟同步，也可手动更新。初始清单为空，没有预置示例作品。

维护者可以编辑 projects.json 来发布作者作品，无需重新打包软件。清单使用 version:1、updatedAt 和 projects 数组；作品使用已上线剧集的官方链接。请只发布有意公开的作品资料，不要包含个人笔记、账户资料或令牌。

## 观影工具

本机观影笔记与选集清单。未接通的手机端服务不作为正式功能入口展示。

本仓库仅包含发行说明与项目数据，应用源码和签名私钥保留本地。GitHub自动生成的Source code链接只是打包本仓库的说明和项目数据。
