# Remocode Bar

Remocode Bar 正式安装包公开下载仓库。  
Public download repository for official Remocode Bar builds.

## 下载 / Download

[下载 macOS Apple Silicon（arm64）](https://github.com/BlueOriginAI/RemocodeBar/releases/latest/download/Remocode-Bar-v2.10.13-macos-arm64.dmg) / [Download Apple Silicon (arm64)](https://github.com/BlueOriginAI/RemocodeBar/releases/latest/download/Remocode-Bar-v2.10.13-macos-arm64.dmg)
[下载 macOS Intel（x86_64）](https://github.com/BlueOriginAI/RemocodeBar/releases/latest/download/Remocode-Bar-v2.10.13-macos-x86_64.dmg) / [Download Intel (x86_64)](https://github.com/BlueOriginAI/RemocodeBar/releases/latest/download/Remocode-Bar-v2.10.13-macos-x86_64.dmg)

请选择与 Mac 架构匹配的安装包；v2.10.5 及更早版本仍提供 Universal DMG。
Choose the installer matching your Mac; v2.10.5 and earlier remain available as Universal DMGs.

## 自动更新 / Automatic updates

正式版发现新版本后，可在更新弹窗中点击安装，应用会自动下载、校验签名、安装并重启。v2.9.1 及更早版本请先手动安装与设备架构匹配的安装包。
When a new version is available, click Install in the update dialog to download, verify, install, and restart automatically. Users on v2.9.1 or earlier should first install the latest architecture-specific DMG for their Mac.

## 支付环境 / Billing environment

这里发布的正式包固定使用 Stripe 正式环境，提交订阅会产生真实扣款。  
Builds published here use Stripe Live mode. Completing checkout creates a real paid subscription.

## 当前平台 / Current platform

- macOS Apple Silicon（arm64）与 Intel（x86_64）独立安装包

## 签名说明 / Signing notice

当前新版本使用 Developer ID Application 签名，DMG 经过 Apple 公证并附带公证票据；Updater 更新包另有独立签名，用于校验更新完整性。旧版内部/ad-hoc 安装包保持历史状态。

Current releases use Developer ID Application signing and Apple-notarized DMGs with stapled tickets. Updater archives carry a separate integrity signature. Historical ad-hoc releases remain unchanged.

源代码在私有仓库中维护，本仓库仅用于发布正式安装包与更新元数据。  
Source is maintained privately; this repository distributes official binaries and updater metadata only.

## ChatGPT-web

macOS 13+ 可通过 Chrome 配套扩展向 ChatGPT 网页咨询问题，再将回答返回 Codex / Claude Code。API 反代与 ChatGPT-web 共用一份 Bar 有效订阅；用户需自行提供 ChatGPT 账号及网页额度。

当前 Chrome 网上应用店版本尚未发布。请在 Bar 的 ChatGPT-web 页点击“准备 / 启动服务”，展开“首次安装扩展”，按其中显示的目录手动加载扩展。随后检查登录与模型、完成测试并启用 MCP。

On macOS 13+, the companion Chrome extension lets Codex / Claude Code consult your ChatGPT web session. API proxy and ChatGPT-web share one active Bar subscription; your ChatGPT account and web allowance are separate. Chrome Web Store distribution is pending. Use the first-install instructions and extension folder in Bar's ChatGPT-web page, then verify the model and enable MCP.

[隐私政策 / Privacy](https://remocode.cc/products/remocode-bar/privacy) · [支持 / Support](https://remocode.cc/products/remocode-bar/support)
