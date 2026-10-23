# 专属总台 · 官方下载

Copyright © 2026 yhl. All rights reserved.

日历、每天安排、待办和 AI 管家。本仓库只提供桌面程序下载，源码私有。

## 下载

- [Mac · Apple 芯片（M 系列）](https://github.com/Tyler9169/exclusive-hub-downloads/releases/latest/download/ExclusiveHub-Mac-Apple.zip)
- [Mac · Intel 芯片](https://github.com/Tyler9169/exclusive-hub-downloads/releases/latest/download/ExclusiveHub-Mac-Intel.zip)
- [Windows · x64](https://github.com/Tyler9169/exclusive-hub-downloads/releases/latest/download/ExclusiveHub-Windows-x64.zip)

解压后双击 Mac 的“专属总台.app”或 Windows 的“专属总台.exe”，不需要安装 Python。启动后会在浏览器打开工作台；保留启动窗口，结束时点击“退出程序”。

## 第一次打开（免费方式）

无需安装 Python，也无需购买证书。未签名版本首次可能需要你手动确认；更新程序或系统策略变化后可能再次提示。

### Mac

1. 解压与你芯片匹配的 ZIP，把“专属总台.app”拖到“应用程序”，再双击打开。
2. 如果提示无法验证开发者或 Apple 无法检查恶意软件，先关闭提示，打开“系统设置 → 隐私与安全性”。
3. 找到本次被阻止的“专属总台”，点击“仍要打开”，按系统提示确认。
4. 系统保存该 App 的例外后，以后可直接双击打开。

[Apple 官方操作说明](https://support.apple.com/zh-cn/102445)。上述步骤仅适用于你确认来自本仓库且未被篡改的原版；“将损坏电脑”、恶意软件或文件损坏提示不适用。

### Windows

1. 完整解压 ZIP，将“专属总台.exe”放在固定文件夹，再双击打开。
2. 如果是“Windows 已保护你的电脑 / 无法识别的应用”提示，且已确认是本仓库原版，点击“更多信息 → 仍要运行”（如果系统提供此按钮）。
3. 进入后设置自己的本机密码，再按需填写自己的 API Key。

[微软关于首次运行提示的说明](https://learn.microsoft.com/en-us/windows/apps/package-and-deploy/publish-first-app)。如果没有“仍要运行”，可能受 Smart App Control 或单位设备策略限制，此方法不能保证打开；请保留提示内容以便定位。

这些步骤只由使用者对当前原版程序作确认，不需要终端命令、关闭杀毒软件或关闭系统整体安全检查。

首次打开，设置你自己的本机密码。需要 AI 时，在设置里填写你自己的 API Key。程序不附带作者的 API Key、登录密码或个人记录。密码和记录保存在使用者本机的加密文件中；密码无法找回，请妥善保管密码和备份。API 请求会将本次对话及所需记录发送给你选择的服务商。语音输入依赖浏览器支持，部分浏览器可能使用在线语音服务。

当前版本未做 Apple 公证或 Windows 代码签名，系统可能提示无法验证开发者。仅从本仓库下载原版，下载页附 SHA-256 校验文件。

Mac 本机数据目录：`~/Library/Application Support/ExclusiveHub`。Windows：`%LOCALAPPDATA%/ExclusiveHub`。软件文件与个人数据分开保存。
