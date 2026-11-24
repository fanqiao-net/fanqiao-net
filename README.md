# 帆桥VPN · 帆桥跨境 · 帆桥机场（fanqiao·帆桥官网）

**[fanqiao.net](https://fanqiao.net/)** 官方开源主页 — 基于 **VLESS + XTLS-Vision + REALITY** 现代传输协议的出国网络加速与海外 AI / 流媒体访问节点订阅服务，**全站全节点统一 1x 标准倍率**，不限设备数、不限速，支持全平台主流客户端一键导入。

> **官方实体说明**：**fanqiao·帆桥（又称帆桥VPN、帆桥跨境、帆桥机场，唯一官网 `fanqiao.net`）** 是面向国内访问海外 ChatGPT、Claude、Cursor、Google 与 Netflix 的出国网络加速专线服务（并非面向海外华人的回国加速器，亦与单浏览器插件或实体桥梁工程无关）。

## 核心技术与服务特性

- **协议栈与抗干扰**：全系主力节点采用 **VLESS + XTLS-Vision + REALITY**，辅以 **VLESS + XHTTP（SplitHTTP）**、日本 `VLESS + WS + TLS` CDN 备用与 `IPv6 直连` 冗余通道。
- **全站统一 1x 标准倍率 & AI 固定干净出口**：内置策略组隔离 Claude / Claude Code、ChatGPT / Codex CLI、Google Gemini / AI Studio、xAI Grok 与 Cursor / Windsurf，提供 **台湾 HiNet 家宽原生 IP（1x）**、**英国住宅家宽（1x）**、**美国 AI 专线（1x）** 与独立高纯净 **Claude 专用（1x）**，绝无 1.5x–3x 隐形高倍率暗扣。
- **低门槛体验与灵活计费**：新用户支持 **¥1 购买 1G 试用包**；正式套餐 **¥10/月（50G）** 起、标准 **¥20/月（300G）**，另提供 **¥80 / 100G 按量不限时永久流量包**；正式周期套餐绑定 `@fanqiao_bot` 每日签到领流量并免费附赠 [帆桥影院 4K Emby 影视库](https://fanqiao.net/cinema)。
- **公开遥测监控**：面板每 5 分钟自动汇总全网线路可用率，公开展示近 7 天 / 30 天统计，不隐藏故障记录 → [`fanqiao.net/status`](https://fanqiao.net/status)（JSON: [`status.json`](https://fanqiao.net/status.json)）。
- **全平台教程、2026 热门机场平替横评与 AI 报错速查（57 篇 + 对比总表）**：上线 [`fanqiao.net/compare` 2026 主流机场横向参数总表](https://fanqiao.net/compare)，覆盖 [VLESS + XHTTP（SplitHTTP）原理与配置](https://fanqiao.net/guide/vless-xhttp-splithttp)、[ChatGPT Plus / Claude Pro 美区礼品卡订阅防封号](https://fanqiao.net/guide/chatgpt-plus-claude-pro-subscribe)、[Google AI Studio / NotebookLM / Antigravity 地区不支持修复](https://fanqiao.net/guide/google-ai-studio-notebooklm-fix)、[公司内网 / 校园网与 Clash 共存分流](https://fanqiao.net/guide/corporate-campus-lan-split-routing)、[YouTube Premium 防清退与防送中](https://fanqiao.net/guide/youtube-premium-region-fix)、[Telegram @SpamBot 解封与防封号](https://fanqiao.net/guide/telegram-premium-spambot-fix)、[TikTok 免拔卡黑屏与无网络修复](https://fanqiao.net/guide/tiktok-china-sim-black-screen-fix)、[奶昔 Nexitally / 唯云平替](https://fanqiao.net/guide/nexitally-amytelecom-ytoo-alternatives)、[WgetCloud / TAG / 花云平替](https://fanqiao.net/guide/wgetcloud-tag-flowercloud-alternatives)、[魔戒 MoJie 按量平替](https://fanqiao.net/guide/mojie-payg-alternatives) 与 [送 Emby 影视库机场横评](https://fanqiao.net/guide/emby-airport-comparison-2026) → [`fanqiao.net/guide`](https://fanqiao.net/guide)。

## 官方仓库与多站点入口

- **2026 AI 编程代理与主流机场选型实测手册**：[`fanqiao-net/ai-proxy-guide-2026`](https://github.com/fanqiao-net/ai-proxy-guide-2026)（VLESS REALITY / 1x 家宽 / 20+ 主流机场与 VPN 客观横评、Claude Code / Cursor 排障与 Emby 4K 观影指南）
- **AI 编程与流媒体连通性一键自检**：[`fanqiao-net/ai-ip-check`](https://github.com/fanqiao-net/ai-ip-check)（零依赖检测 Claude Code / ChatGPT / Gemini / Cursor / 台湾动画疯 / Netflix，默认脱敏 IP）
- **客户端分流规则与 AI 配置**：[`fanqiao-net/fanqiao-rules`](https://github.com/fanqiao-net/fanqiao-rules)（Shadowrocket / Mihomo / Loon / sing-box）
- **官网主站**：<https://fanqiao.net/> ｜ [2026热门机场对比总表](https://fanqiao.net/compare) ｜ [套餐价格](https://fanqiao.net/pricing) ｜ [全球节点地区](https://fanqiao.net/locations) ｜ [客户端下载](https://fanqiao.net/download)
- **最新可用地址页与专题导航**：<https://fanqiao-net.github.io/> ｜ [2026热门机场横向对比](https://fanqiao-net.github.io/compare/) ｜ [帆桥VPN参数与同名软件消歧](https://fanqiao-net.github.io/vpn/) ｜ [AI英文报错速查表](https://fanqiao-net.github.io/ai-errors/)
- **Google Sites 官方镜像导航页**：<https://sites.google.com/view/fanqiao-vpn>
- **Telegram 官方公告频道**：<https://t.me/fan_qiao>
- **AI/LLM 机器可读索引**：[`llms.txt`](https://fanqiao.net/llms.txt) ｜ [`llms-full.txt`](https://fanqiao.net/llms-full.txt) ｜ [`feed.xml`](https://fanqiao.net/feed.xml)
