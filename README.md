# Clash Node Manager

Windows 上的 Clash/Mihomo 节点管理工具：节点质量评分、自动择优、白名单/黑名单、Codex 连接故障复查和托盘提醒。

[下载最新 Windows 安装包](https://github.com/Mag357num/clash-node-manager-releases/releases/latest)

## 安装与更新

需要现有 357Toolkits / Codex harness、Python、Node.js 22.13+、PowerShell 5.1 或 7，以及 Clash/Mihomo。本包用于已经接入该环境的 Windows 用户，不包含完整 harness。

下载正式 Release 中的 `ClashNodeManager-X.Y.Z-windows.zip`，解压，退出本软件的其他窗口和托盘，再运行 `Install.ps1`。程序位置为 `CODEX_HOME/tools/CodexRecovery/CodexRecovery.exe`。只复制 EXE 无法完成安装。

安装后在主窗口点击 **检查更新 → 下载并安装**。无需 GitHub 账号；需要网络可以访问 GitHub。更新会校验 SHA256、备份并替换程序与配套脚本，再重新打开界面。私人设置、节点名单、历史、后台暂停原因和切换预算保持原样。本地修改的程序文件会受到覆盖保护。

质量评分只提供网络参考，不能保证账号安全或服务地区资格。开启自动择优前请确认使用范围和检测说明。

## 仓库内容

本公开仓库只维护发布说明，Release 附件包含 EXE 和运行必需的 PowerShell/JavaScript 脚本及说明；不包含 C# 开发源码、测试、用户设置、订阅或账号。开发源码与历史保存在维护者的私有源码仓库。

GitHub Release 附件提供 SHA256；校验和同时保存于 `SHA256SUMS.txt`。初版安装包未做 Windows Authenticode 签名。
