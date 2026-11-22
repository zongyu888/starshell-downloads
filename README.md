# StarShell 桌面客户端 · 安装包下载

本仓库**只提供编译好的安装包，不含任何源代码**。
系统要求：Windows 10 / 11（x64）。安装包已内置运行所需服务，不需要另装 Java / Node / 数据库。

## 当前版本 v1.0.3

| 平台 | 下载 |
| --- | --- |
| GitHub | [StarShell-Setup-1.0.3-x64.exe（约 104 MB，单文件）](https://github.com/zongyu888/starshell-downloads/releases/download/v1.0.3/StarShell-Setup-1.0.3-x64.exe) |
| Gitee（国内备用） | [前往 Gitee 发行版](https://gitee.com/zongyu_xyz/starshell-downloads/releases/tag/v1.0.3)（单附件 100 MB 限制，安装包拆成两个分卷，附 `merge.bat`） |

SHA-256：`593b96d8ba274c9c253d2e8c89b65494a1bf0fdec24e10fb73f2090d3955ef40`

## 安装

1. 下载后双击 `StarShell-Setup-1.0.3-x64.exe`。
2. 出现 SmartScreen 时点「更多信息」→「仍要运行」。
3. 向导最后一步可勾选：创建桌面快捷方式（默认勾选）、开机自动启动、安装完成后立即启动。
4. 建议右键快捷方式 →「以管理员身份运行」。

Gitee 分卷下载：把 `.001`、`.002`、`merge.bat` 放到同一文件夹，双击 `merge.bat` 合并后再安装。

## 首次使用

打开后进入连接页，可登录云账号、使用本机离线模式，或填写自建服务端地址。
本机数据存放在 `%APPDATA%\StarShell\`。

## 安全说明

- 本仓库没有任何源码、配置密钥或服务器地址，只有安装程序和说明文档。
- 安装包内的密钥在首次安装时随机生成，不复用任何固定密钥。
