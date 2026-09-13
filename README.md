# 掌上酒馆 PocketTavern

Android 原生 SillyTavern 客户端 —— 直连你自己的 SillyTavern 服务端，无需浏览器。

> 本仓库仅用于**发布安装包与更新说明**，不含源码。
> 下载请前往 [Releases](https://github.com/wacilimonster-source/pockettavern/releases)。

## 特性

- **原生体验**：Flutter 原生界面，为手机竖屏与触控重新设计，不是套壳浏览器
- **直连服务端**：连接你自己的 SillyTavern 服务端（局域网/公网均可），聊天记录、角色卡、世界书与网页端互通
- **生成链路对齐**：提示词组装、世界书递归/预算/时效（sticky·cooldown）、正则脚本、宏系统、EJS 模板子集均对照 SillyTavern 源码逐项实现
- **卡片脚本兼容**：酒馆助手（JS-Slash-Runner）风格的消息内脚本、行动面板、变量桥接
- **本地能力**：输入草稿、变体（swipe）管理、作者注释、向量记忆（RAG）、前情摘要、聊天分支

## 下载

前往 [**Releases**](https://github.com/wacilimonster-source/pockettavern/releases) 下载最新版 `pocket_tavern_X.Y.Z.apk`。

- 国内网络可尝试镜像加速前缀（如 `https://ghfast.top/` 拼接完整下载地址）
- App 内「设置 → 检查更新」可自动检测新版本

## 常见问题

**Q：如何连接服务器？**
设置 → 顶部服务器卡片，填入 SillyTavern 服务端地址（如 `http://192.168.1.178:8000`）。

**Q：检查更新失败？**
多为网络问题，可尝试开关 VPN 后重试；或直接到 Releases 页面手动下载。

**Q：聊天记录存在哪里？**
聊天文件保存在 SillyTavern 服务端（与网页端同一份），本地仅存草稿、置顶、世界书加选等偏好。

## 免责声明

本项目为开源 SillyTavern 的第三方移动客户端，仅供学习与个人使用。应用内展示的全部内容由用户自行配置的角色卡与服务端决定，与本项目无关。

---

*掌上酒馆 PocketTavern · 源码未公开 · Releases 提供 APK 下载*
