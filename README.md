# Dailybot for macOS

本仓库用于分发 Dailybot 的 macOS 安装包、更新说明和自动更新文件。源代码仓库保持私有，不在这里公开。

## 下载

首个固定签名公开版 [v0.20261113.0](https://github.com/lighters/Dailybot-Releases/releases/tag/v0.20261113.0) 已发布。
最新版本和更新说明见[发行页](https://github.com/lighters/Dailybot-Releases/releases/latest)。

[下载 Dailybot · Apple Silicon Mac](https://github.com/lighters/Dailybot-Releases/releases/latest/download/Dailybot-mac-arm64.dmg)

上面的固定地址始终下载最新安装包。当前提供 Apple Silicon（M 系列芯片）版本；Intel Mac 和 Windows 安装包尚未提供。

## 首次安装

1. 下载 DMG，打开后将 Dailybot 拖到“应用程序”。
2. 从“应用程序”打开 Dailybot。
3. 这是固定自签名、未经过 Apple 公证的应用。如果 macOS 阻止首次打开，先尝试打开一次，再到“系统设置 → 隐私与安全性”中选择“仍要打开”。
4. 在应用内配置自己的模型服务。安装包不包含任何人的模型账号、密钥或聊天数据。

## 应用内更新

应用启动时自动检查更新，此后每 6 小时检查一次。发现新版本后，在安装前征求确认。用户不需要 GitHub 账号或访问令牌。

更新会备份本机数据并保留上一版本，出现安装失败时尝试回退。临时签名的早期本机版需要手动安装首个固定签名版一次。

公开地址的匿名下载及本机安装已验证。应用内签名升级已在本机隔离环境、通过本机更新源跑通；
另一台 Mac 的首次安装和跨电脑升级尚未实测。
