# AI Usage Island

macOS 14+ 菜单栏／侧边停靠的 AI 用量与额度工具，支持 DeepSeek、智谱 CodingPlan 和 ChatGPT/Codex。

[![Latest release](https://img.shields.io/github/v/release/gReyWangP/AIUsageIsland-releases?label=latest&style=flat-square)](https://github.com/gReyWangP/AIUsageIsland-releases/releases/latest)
[![Platform](https://img.shields.io/badge/platform-macOS%2014%2B%20Apple%20Silicon-lightgrey?style=flat-square)](https://github.com/gReyWangP/AIUsageIsland#系统要求)
[![Source](https://img.shields.io/badge/source-AIUsageIsland-blue?style=flat-square)](https://github.com/gReyWangP/AIUsageIsland)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](https://github.com/gReyWangP/AIUsageIsland/blob/main/LICENSE)

**[下载最新版](https://github.com/gReyWangP/AIUsageIsland-releases/releases/latest)** · [源码仓库](https://github.com/gReyWangP/AIUsageIsland) · [更新说明](https://github.com/gReyWangP/AIUsageIsland/blob/main/CHANGELOG.md) · [问题反馈](https://github.com/gReyWangP/AIUsageIsland/issues)

此仓库只用于分发安装包、校验和与 Sparkle 更新 feed；应用源码、使用说明、隐私政策和许可证在公开源码仓库。

![侧边停靠与详情卡片](https://raw.githubusercontent.com/gReyWangP/AIUsageIsland/main/docs/screenshots/side-dock-card.jpg)
*界面预览 · 侧边停靠、双额度环与引出尖角详情卡片（演示数据）*

## 下载与安装

在本仓库 [Releases](https://github.com/gReyWangP/AIUsageIsland-releases/releases/latest) 下载最新 ZIP，解压得到 `AIUsageIsland.app`。先退出旧实例，再将应用放到“应用程序”目录后打开。

当前版本：2.0.3（build 82）。支持 macOS 14 及以上、Apple Silicon。

安装包采用临时签名，尚未完成 Developer ID 签名和 Apple 公证，macOS 可能阻止首次打开。首次接入应用内更新的版本需要手动安装一次，之后可在“设置 → 通用与支持 → 软件更新”中检查、下载并安装。自动检查默认关闭，可自行开启。

## 功能

- 三种显示形式：顶部灵动岛、悬浮状态栏、侧边停靠。
- 侧边停靠跟随账号页的显示选择，支持上下拖动、双额度弧与可调圆弧；悬停弹出带引出尖角的详情卡片。
- 支持 DeepSeek、智谱 CodingPlan、ChatGPT/Codex；多平台、多账号的额度／余额、重置时间、用量分析与历史记录。
- 用量分析按天堆叠展示多个平台与账号，各账号独立色块和明细。
- 本机提醒、Bark 公开重置动态推送；Sparkle 应用内更新，自动检查默认关闭。
- 切换外接屏时保持所选屏幕；设置页的屏幕列表随显示器插拔刷新。
- 账号凭据只保存在本机，没有遥测。

## 更新机制

应用通过 Sparkle 2.9.6 检查更新，feed 固定为 <https://raw.githubusercontent.com/gReyWangP/AIUsageIsland-releases/main/appcast.xml>；更新包使用 Ed25519 签名验证。此仓库的 appcast 保留最近 3 个版本。

## 反馈与许可

- 问题与建议：[源码仓库 Issues](https://github.com/gReyWangP/AIUsageIsland/issues)
- 安全漏洞：请通过 [GitHub Security Advisories](https://github.com/gReyWangP/AIUsageIsland/security/advisories/new) 私下报告，不要在公开 issue 中粘贴 token、Cookie 或账号信息。
- 代码采用 [MIT License](https://github.com/gReyWangP/AIUsageIsland/blob/main/LICENSE)；平台名称与 Logo 归各自权利人所有，仅用于识别。
- 第三方组件与许可证见 [THIRD_PARTY_NOTICES.md](https://github.com/gReyWangP/AIUsageIsland/blob/main/THIRD_PARTY_NOTICES.md)。

ChatGPT 账号展示 Codex 额度与官方日统计，不代表 ChatGPT 聊天用量。应用为独立第三方工具，与所列平台无隶属关系。
