# GitHub 热门项目周报 — 最近一周

**时间窗口：** 2026-11-08 至 2026-11-14（GitHub Trending `since=weekly`）
**查证时间：** 2026-11-14 08:00 CST（Asia/Shanghai）
**口径说明：** 排名以 GitHub 官方 Trending 周榜展示顺序为准；本周增星数引用第三方汇总站快照（2026-11-14 03:57 北京时间），不同汇总站因抓取时间不同，增星数会有差异。官方榜单的展示顺序并不完全按增星数排序。

---

## 本周总览

这一周的主线是 **Agent 工具从“技能包”走向“运行环境”，同时老牌工具意外回春**。

1. **“技能”仍是分发主流，但开始分化** — anthropics/skills 连续第四周稳居全站前列，mattpocock/skills、addyosmani/agent-skills、google/skills 同周上榜；“技能”已经成了 Agent 能力的默认封装格式，竞争点从“有没有技能”变成“技能质量和安全”。
2. **Agent 的手和眼落到桌面与浏览器** — vercel-labs/agent-browser（Rust 榜第一、全站第四）与 agent-desktop 同周上榜，给 Agent 配浏览器自动化和电脑操作能力；milind-soni/OpenMausBot（全站第三）则是开源 Grok Bot 替代品，自带虚拟机供 Bot 使用。
3. **老项目回春** — 全站第一是 2018 年的老牌 OSINT 工具 sherlock-project/sherlock（按用户名全网找社交账号），总星已破 11 万；google-deepmind/mujoco（物理仿真器）也重回全站前十。经典工具借着 Agent 浪潮被重新发现。
4. **Agent 安全成为新赛道** — openai/codex-security（TypeScript 榜第三）、NVIDIA/SkillSpector（扫描 Agent 技能里的提示注入与供应链风险）同周上榜；cloudflare/security-audit-skill 本周再涨 10,700 星，连续四周登顶 JS 榜。技能装得越多，越要有人验货。
5. **金融 AI 持续冒头** — ZhuLinsen/daily_stock_analysis（LLM 驱动的多市场股票分析，零成本定时运行）冲进全站第六、Python 榜第四；NVIDIA/auto-ontology（给数据建语义图谱推理层）Python 榜第五。
6. **基础设施老将继续回流** — Go 榜第一是 prometheus，cli/cli、etcd、trivy 同周在榜；Java 榜则是 TheAlgorithms/Java、elasticsearch、NewPipe、floci 等老面孔。Agent 新贵和底层基建各占半壁江山。

---

## 1. 全站总榜 Top 5

| # | 项目 | 语言 | 说明 |
|---|------|------|------|
| 1 | sherlock-project/sherlock | Python | 按用户名全网追踪社交账号的老牌 OSINT 工具，总星 111,117（GitHub API，2026-11-14） |
| 2 | anthropics/skills | Python | Anthropic 官方 Agent Skills 公共仓库（连续四周上榜）。本周新增约 6,055 星 |
| 3 | milind-soni/OpenMausBot | TypeScript | 开源 Grok Bot 替代品，自带虚拟机供 Bot 使用。本周新增约 9,104 星 |
| 4 | vercel-labs/agent-browser | Rust | 给 AI Agent 的浏览器自动化 CLI。本周新增约 4,601 星 |
| 5 | google/elephant-goldfish-model | Python | 用 Agent 设计与评审软件的开源插件。本周新增约 5,555 星 |

紧随其后：ZhuLinsen/daily_stock_analysis（本周 +3,569）、NVIDIA/auto-ontology（本周 +5,802）、google-deepmind/mujoco（本周 +1,671）、mattpocock/skills（本周 +8,731）、addyosmani/agent-skills（本周 +3,199）、cloudflare/security-audit-skill（本周 +10,700）、zed-industries/zed（本周 +2,339）、vercel-labs/agent-desktop（本周 +6,414）。

> 注：sherlock 的本周增星数未在第三方快照中显示，故只列总星数；快照站的总星数与 GitHub API 实时数有微小出入（如 agent-browser 快照 50,656，API 实时 50,709），以官方页面为准。

项目链接：
- https://github.com/sherlock-project/sherlock
- https://github.com/anthropics/skills
- https://github.com/milind-soni/OpenMausBot
- https://github.com/vercel-labs/agent-browser
- https://github.com/google/elephant-goldfish-model

---

## 2. Python / AI 与数据 Top 5

1. **sherlock-project/sherlock** — 按用户名全网找社交账号的 OSINT 工具
   https://github.com/sherlock-project/sherlock
2. **anthropics/skills** — Anthropic 官方 Agent Skills 公共仓库（连续四周上榜）
   https://github.com/anthropics/skills
3. **google/elephant-goldfish-model** — 用 Agent 设计与评审软件的开源插件。本周新增约 5,555 星
   https://github.com/google/elephant-goldfish-model
4. **ZhuLinsen/daily_stock_analysis** — LLM 驱动的多市场股票智能分析系统：多源行情、实时新闻、决策看板与自动推送，支持零成本定时运行。本周新增约 3,569 星
   https://github.com/ZhuLinsen/daily_stock_analysis
5. **NVIDIA/auto-ontology** — 为数据构建语义图谱推理层：确定性查询生成、更好的上下文检索、LLM 与 Agent 工作流可解释性更强。本周新增约 5,802 星
   https://github.com/NVIDIA/auto-ontology

后面值得注意：anthropics/claude-quickstarts（Claude API 快速上手项目集）、google/skills（Google 产品 Agent 技能）、homeassistant-ai/ha-mcp（用 Claude/ChatGPT 配置和自动化 Home Assistant）、harry0703/MoneyPrinterTurbo（AI 一键生成短视频）、bradautomates/claude-video（让 Claude 能“看”视频）、D4Vinci/Scrapling（高性能爬取框架）、NVIDIA/SkillSpector（扫描 Agent 技能的安全风险）。

---

## 3. TypeScript / 前端与 Agent 工具 Top 5

1. **milind-soni/OpenMausBot** — 开源 Grok Bot 替代品，自带虚拟机供 Bot 使用。本周新增约 9,104 星
   https://github.com/milind-soni/OpenMausBot
2. **lobehub/lobehub** — 把超级 Agent 接进已有的聊天工具，让它们自行接活、每周变强。本周新增约 1,186 星
   https://github.com/lobehub/lobehub
3. **openai/codex-security** — OpenAI 的 Codex 安全 CLI 与 TypeScript SDK：发现、验证并修复安全漏洞
   https://github.com/openai/codex-security
4. **CopilotKit/OpenBot** — 开源 AI 同事：每个 AI 同事配一台自己的电脑（浏览器、文件），动作事前决策、事后记录
   https://github.com/CopilotKit/OpenBot
5. **immich-app/immich** — 高性能自托管照片与视频管理方案
   https://github.com/immich-app/immich

后面值得注意：can1357/oh-my-pi（把 IDE 接进编码 Agent）、every-app/open-seo（开源 Semrush/Ahrefs 替代品）、ranxianglei/billion-context（单会话十亿级 Token 的上下文压缩插件）、backnotprop/plannotator（让人在 Agent 循环里保持掌控的工作区）、getpaseo/paseo（桌面+手机编排多个编码 Agent）、meta/astryx（Agent-ready 的开源设计系统）、nightly-labs/openbot（本地优先的持久 AI 队友桌面工作区）、pingdotgg/t3code。

---

## 4. JavaScript Top 5

1. **addyosmani/agent-skills** — 给 AI 编码 Agent 的生产级工程技能。本周新增约 3,199 星
   https://github.com/addyosmani/agent-skills
2. **cloudflare/security-audit-skill** — 让编程 Agent 做多阶段安全审计，独立验证、机器可读的结果（连续四周登顶 JS 榜）。本周新增约 10,700 星
   https://github.com/cloudflare/security-audit-skill
3. **coreyhaines31/marketingskills** — Claude Code 与 AI Agent 的营销技能：CRO、文案、SEO、数据分析与增长工程
   https://github.com/coreyhaines31/marketingskills
4. **ConardLi/garden-skills** — 开源 Skills 合集：网页设计、知识检索、图像生成等
   https://github.com/ConardLi/garden-skills
5. **Anil-matcha/Open-Generative-AI** — 无审查的开源 AI 视频平台替代品：600+ 模型免费生图生视频，自托管、MIT 协议
   https://github.com/Anil-matcha/Open-Generative-AI

后面值得注意：Yu9191/wloc（改 Apple 网络定位返回坐标，配合 Surge/Quantumult X 等）、Leonxlnx/taste-skill（给编码 Agent“品味”的技能）。

---

## 5. Rust / 系统工具 Top 5

1. **vercel-labs/agent-browser** — 给 AI Agent 的浏览器自动化 CLI。本周新增约 4,601 星
   https://github.com/vercel-labs/agent-browser
2. **zed-industries/zed** — 高性能多人代码编辑器，Atom 与 Tree-sitter 原班人马出品。本周新增约 2,339 星
   https://github.com/zed-industries/zed
3. **vercel-labs/agent-desktop** — 给 AI Agent 的电脑操作 CLI。本周新增约 6,414 星
   https://github.com/vercel-labs/agent-desktop
4. **herdrdev/herdr** — “你的编码 Agent 住的运行时”
   https://github.com/herdrdev/herdr
5. **ruvnet/RuView** — 用普通 WiFi 信号做实时空间感知、生命体征监测与存在检测，全程无摄像头
   https://github.com/ruvnet/RuView

后面值得注意：astral-sh/ruff（极速 Python linter/格式化器）、longbridge/gpui-kit（基于 GPUI 的 Rust GUI 组件）、rustdesk/rustdesk（开源远程桌面）、max-sixty/worktrunk（并行 AI Agent 的 Git worktree 管理）、tokio-rs/topcoat（Web 应用全家桶框架）、openai/codex（终端轻量编码 Agent）。

---

## 6. Go / 云原生与 AI 服务 Top 5

1. **prometheus/prometheus** — Prometheus 监控系统与时序数据库
   https://github.com/prometheus/prometheus
2. **multica-ai/multica** — 让人类与 AI Agent 像一个团队协作，开源、可自托管（连续三周上榜）
   https://github.com/multica-ai/multica
3. **opensandbox-group/OpenSandbox** — 面向 AI Agent 的安全、快速、可扩展沙箱运行时
   https://github.com/opensandbox-group/OpenSandbox
4. **cli/cli** — GitHub 官方命令行工具
   https://github.com/cli/cli
5. **dsx-ai-factory/nvke** — NVIDIA Kubernetes Engine：裸机 GPU Kubernetes 的管理面
   https://github.com/dsx-ai-factory/nvke

后面值得注意：JuliusBrussee/caveman（用“穴居人说话”给编码 Agent 省 65% Token 的技能+代理）、trufflesecurity/trufflehog（找泄漏的凭证）、henrygd/beszel（轻量服务器监控）、router-for-me/CLIProxyAPI（把多个 Agent CLI 包装成兼容 API）、gitleaks/gitleaks、etcd-io/etcd、aquasecurity/trivy、agent-substrate/substrate。

---

## 7. Java / Android 与逆向 Top 5

*按 GitHub Trending Java 周榜展示顺序*

1. **TheAlgorithms/Java** — Java 实现的全部经典算法。本周新增约 493 星
   https://github.com/TheAlgorithms/Java
2. **elastic/elasticsearch** — 免费开源的分布式 RESTful 搜索引擎。本周新增约 220 星
   https://github.com/elastic/elasticsearch
3. **TeamNewPipe/NewPipe** — 轻量自由的 Android 流媒体前端。本周新增约 217 星
   https://github.com/TeamNewPipe/NewPipe
4. **floci-io/floci** — 轻量免费的 AWS 本地模拟器替代品。本周新增约 1,417 星
   https://github.com/floci-io/floci
5. **agentscope-ai/agentscope-java** — 构建分布式、生产级、长期运行的 Agent
   https://github.com/agentscope-ai/agentscope-java

后面值得注意：yuliskov/SmartTube（Android TV 播放器）、keycloak/keycloak（身份与访问管理）、termux/termux-app（Android 终端模拟器，本周 +583）、halo-dev/halo（开源建站工具）、spring-projects/spring-boot。

---

## 值得 Xtop 亲自试的 4 个

结合你之前 Star 过的方向（AI/Agent 工具、本地模型、MCP）和你在做的项目：

1. **vercel-labs/agent-browser** — 给 Agent 配浏览器自动化 CLI，和你做的交易平台、行情抓取思路直接相关；配合 agent-desktop 一起看，Agent“动手操作电脑”这条线正在成型
2. **ZhuLinsen/daily_stock_analysis** — LLM 多市场股票分析 + 零成本定时运行，和你的加密货币晚间日报、交易平台是同一类需求，可以对照它的多源行情与推送设计
3. **sherlock-project/sherlock** — 全站第一的老牌 OSINT 工具，单文件逻辑清晰，适合当作“一个小工具怎么做到 11 万星”的代码学习样本
4. **NVIDIA/SkillSpector** — 扫描 Agent 技能里的提示注入与供应链风险；你装了不少 Claude Code/OpenCode 技能，装之前先扫一遍是个好习惯

---

## 数据来源

- GitHub Trending 官方周榜：https://github.com/trending?since=weekly 及各语言子榜（python / typescript / javascript / rust / go / java），查证于 2026-11-14 08:00 CST
- 第三方汇总快照：gaojihao.github.io/github-hot/trending-weekly.html（更新于 2026-11-14 03:57 北京时间）
- sherlock 总星数 111,117 来自 GitHub API（2026-11-14 实时查询）；其本周增星数未在快照中显示，故未列出
- 与上期（2026-11-07）对比：全站榜单再次大换血，仅 anthropics/skills、OpenMausBot、agent-browser、zed、floci 等少数项目连续在榜；主题从“Agent 记忆与协作”转向“Agent 运行环境（浏览器/桌面/沙箱）+ Agent 安全”，同时 sherlock、mujoco 等老牌项目回春，Go/Java 榜基础设施老将继续占优

*说明：项目自述的性能数字（如 token 缩减、推理速度）均为项目方自家基准，未经第三方复现，导入前建议用自己的工作负载重测。*
