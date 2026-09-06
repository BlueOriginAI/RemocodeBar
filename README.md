# Remocode Bar

Remocode Bar 正式安装包公开下载仓库。  
Public download repository for official Remocode Bar builds.

## 下载 / Download

请从 [Latest Release](https://github.com/BlueOriginAI/RemocodeBar/releases/latest) 下载 macOS DMG。  
Download the macOS DMG from the [Latest Release](https://github.com/BlueOriginAI/RemocodeBar/releases/latest).

## 自动更新 / Automatic updates

从 v2.9.2 开始，正式版使用此公开仓库的签名 latest.json 自动检查后续更新。v2.9.1 及更早版本需要先手动安装一次 v2.9.2 DMG。  
Starting with v2.9.2, formal builds use the signed latest.json in this repository for future automatic updates. v2.9.1 and earlier must install the v2.9.2 DMG manually once.

## 支付环境 / Billing environment

这里发布的正式包固定使用 Stripe 正式环境，提交订阅会产生真实扣款。  
Builds published here use Stripe Live mode. Completing checkout creates a real paid subscription.

## 当前平台 / Current platform

- macOS Apple Silicon (arm64)

## 签名说明 / Signing notice

Updater 更新包使用独立签名防篡改。当前应用和 DMG 仍为内部/ad-hoc 签名，尚未完成 Apple 公证，首次打开可能出现 Gatekeeper 提示。  
Updater archives are signed for integrity. The app and DMG remain ad-hoc signed and not Apple-notarized, so Gatekeeper may warn on first launch.

源代码在私有仓库中维护，本仓库仅用于发布正式安装包与更新元数据。  
Source is maintained privately; this repository distributes official binaries and updater metadata only.
