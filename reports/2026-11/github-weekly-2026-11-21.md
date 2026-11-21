# GitHub 热门项目周报 — 最近一周

**时间窗口：** 2026-11-15 至 2026-11-21（GitHub Trending `since=weekly`）
**查证时间：** 2026-11-21 08:00 CST（Asia/Shanghai）
**口径说明：** 排名以 GitHub 官方 Trending 周榜展示顺序为准；本周增星数取自官方榜单页面本身（“X stars this week”），总星数取自 GitHub API 实时查询（2026-11-21 08:00 前后）与第三方汇总站快照（2026-11-21 04:41 北京时间）。官方榜单的展示顺序并不完全按增星数排序。

---

## 本周总览

这一周的主线是 **Agent 从“能干活”走向“让人放心地干活”，同时“技能”继续向垂直场景扩散**。

1. **人在回路（human-in-the-loop）登顶** — 全站第一 backnotprop/plannotator 是“让人在 Agent 循环里保持掌控”的工作区；Python 榜第五 andrewyng/openworker（吴恩达团队）把“审批、审计、沙箱”做成桌面 Agent 的默认架构；Tencent/LoopForge 也在交付流程里加了人工审批关卡。Agent 越能干，人越要看得住。
2. **“技能”继续垂直化** — 上周还是通用技能包，这周已经分化到具体工种：mvanhorn/last30days-skill（跨 Reddit/X/YouTube/HN 的调研技能）、tradermonty/claude-trading-skills（给散户投资者的交易技能）、kajisho5/ffmpeg-skill（本地视频剪辑技能）、coreyhaines31/marketingskills（营销技能）。技能正在从“Agent 的插件”变成“某个职业的工作流”。
3. **代码评审 Agent 进入大厂实战口径** — 阿里 alibaba/open-code-review（全站第四，总星 54,766）主打“阿里规模验证过的确定性流水线 + LLM Agent”；GoogleChrome/modern-web-guidance-src（全站第三）则是让编码 Agent 跟上最新 Web 最佳实践。评审与规范，成了 Agent 落地的下一道关。
4. **Agent 与前端的协议层出现** — ag-ui-protocol/ag-ui（Agent-User Interaction Protocol）、a2ui-project/a2ui（生成式 UI 框架）同周上榜：Agent 不再只输出文字，要直接往应用界面里“长”组件。
5. **中国团队项目集中冒头** — 阿里、腾讯、dream-num/univer、jeecgboot/JeecgBoot、DeanChensj/jiangshan-map（中国历史交互地图）同周在榜，覆盖代码评审、Agent 交付、办公套件、低代码与文化内容。
6. **老将继续在榜单边缘刷存在感** — jquery 回到 JS 榜第四，openjdk/jdk、SeleniumHQ/selenium 领跑 Java 榜；affaan-m/ECC 本周再涨 5,598 星，总星已达 307,847。Agent 浪潮里，老牌基础设施的星数基本盘依然很稳。

---

## 1. 全站总榜 Top 5

| # | 项目 | 语言 | 说明 |
|---|------|------|------|
| 1 | backnotprop/plannotator | TypeScript | 让人在 Agent 循环里保持掌控的工作区：塑形、决策、规划、批注、审代码，一键把反馈发给 Agent。本周新增约 3,468 星，总星 13,888 |
| 2 | google-labs-code/stitch-skills | TypeScript | 为 Stitch MCP 服务器设计的 Agent Skills 库，遵循 Agent Skills 开放标准，兼容 Antigravity、Gemini CLI、Claude Code、Cursor。本周新增约 1,829 星，总星 11,022 |
| 3 | GoogleChrome/modern-web-guidance-src | TypeScript | 让编码 Agent 跟上最新 Web 最佳实践。本周新增约 6,858 星，总星 9,522 |
| 4 | alibaba/open-code-review | Go | 阿里规模验证的代码评审工具：确定性流水线 + LLM Agent，精确到行的评论，内置多语言规则集（NPE、线程安全、XSS、SQL 注入）。本周新增约 4,492 星，总星 54,766 |
| 5 | mvanhorn/last30days-skill | Python | 跨 Reddit、X、YouTube、HN、Polymarket 与全网调研任意话题的 Agent 技能，输出有依据的总结。本周新增约 3,179 星，总星 71,431 |

紧随其后：dream-num/univer（本周 +7,248）、meta/astryx（本周 +4,977）、milind-soni/OpenMausBot（本周 +4,228）、ag-ui-protocol/ag-ui（本周 +3,455）、tradermonty/claude-trading-skills（本周 +3,385）、ChromeDevTools/chrome-devtools-mcp（本周 +3,229）、we-promise/sure（本周 +3,226）、kajisho5/ffmpeg-skill（本周 +2,998）。

项目链接：
- https://github.com/backnotprop/plannotator
- https://github.com/google-labs-code/stitch-skills
- https://github.com/GoogleChrome/modern-web-guidance-src
- https://github.com/alibaba/open-code-review
- https://github.com/mvanhorn/last30days-skill

---

## 2. Python / AI 与数据 Top 5

1. **mvanhorn/last30days-skill** — 跨 Reddit、X、YouTube、HN、Polymarket 与全网调研任意话题的 Agent 技能，输出有依据的总结。本周新增约 3,179 星
   https://github.com/mvanhorn/last30days-skill
2. **tradermonty/claude-trading-skills** — 给散户投资者的 Claude Code 交易技能：市场分析、技术图表、经济日历、选股器与交易策略开发。本周新增约 3,385 星
   https://github.com/tradermonty/claude-trading-skills
3. **kajisho5/ffmpeg-skill** — 给编码 Agent 的本地视频编辑器：42 个 FFmpeg 工具 + 机器可读契约 + MCP 服务器，剪辑、字幕、重构、响度与多平台导出，无云端、无 API Key。本周新增约 2,998 星
   https://github.com/kajisho5/ffmpeg-skill
4. **ZhuLinsen/daily_stock_analysis** — LLM 驱动的多市场股票智能分析系统：多源行情、实时新闻、决策看板与自动推送，支持零成本定时运行（连续第二周在榜）。本周新增约 2,595 星
   https://github.com/ZhuLinsen/daily_stock_analysis
5. **andrewyng/openworker** — 吴恩达团队的桌面 Agent：日常工作的 AI 协作者 + 构建 Agent 应用的 Harness SDK，审批、审计轨迹与沙箱是默认架构，自带模型、本地优先。本周新增约 460 星
   https://github.com/andrewyng/openworker

后面值得注意：anthropics/skills（本周 +4,235，连续第五周上榜）、elementalsouls/Claude-BugHunter（本周 +6,517，82 个猎 bug 技能 + 681 个已披露漏洞模式）、jingyaogong/minimind（两小时从 0 训出 64M 大模型，本周 +1,612）、zhouxiaoka/autoclip（AI 视频剪辑桌面工具，本周 +717）、FujiwaraChoki/supoclip（开源 OpusClip 替代品，本周 +711）、soxoj/maigret（按用户名从 6K 网站收集个人档案，本周 +548）。

---

## 3. TypeScript / 前端与 Agent 工具 Top 5

1. **backnotprop/plannotator** — 让人在 Agent 循环里保持掌控的工作区。本周新增约 3,468 星
   https://github.com/backnotprop/plannotator
2. **google-labs-code/stitch-skills** — 为 Stitch MCP 服务器设计的 Agent Skills 库。本周新增约 1,829 星
   https://github.com/google-labs-code/stitch-skills
3. **GoogleChrome/modern-web-guidance-src** — 让编码 Agent 跟上最新 Web 最佳实践。本周新增约 6,858 星
   https://github.com/GoogleChrome/modern-web-guidance-src
4. **ChromeDevTools/chrome-devtools-mcp** — 给编码 Agent 的 Chrome DevTools。本周新增约 3,229 星
   https://github.com/ChromeDevTools/chrome-devtools-mcp
5. **ag-ui-protocol/ag-ui** — Agent-User Interaction Protocol：把 Agent 带进前端应用。本周新增约 3,455 星
   https://github.com/ag-ui-protocol/ag-ui

后面值得注意：dream-num/univer（本周 +7,248，AI 办公套件 SDK）、meta/astryx（本周 +4,977，Agent-ready 开源设计系统）、milind-soni/OpenMausBot（本周 +4,228，连续第二周在榜）、openai/codex-security（本周 +2,150，连续第二周在榜）、CopilotKit/OpenBot（本周 +1,624）、QwenLM/qwen-code（终端里的开源 AI 编码 Agent，本周 +1,190）、lobehub/lobehub（本周 +751）、a2ui-project/a2ui（生成式 UI 框架，本周 +480）。

---

## 4. JavaScript Top 5

1. **Anil-matcha/Open-Generative-AI** — 无审查的开源 AI 视频平台替代品：800+ 模型免费生图生视频，自托管、MIT 协议（连续第二周登顶 JS 榜）。本周新增约 1,168 星
   https://github.com/Anil-matcha/Open-Generative-AI
2. **DeanChensj/jiangshan-map** — 江山时序 · 中国历史交互地图时间轴（403 BCE – Present），18 个朝代、198 个疆域快照、古今地名世系与诗词路线。本周新增约 2,960 星
   https://github.com/DeanChensj/jiangshan-map
3. **coreyhaines31/marketingskills** — 给 Claude Code 与 AI Agent 的营销技能：CRO、文案、SEO、数据分析与增长工程（连续第二周在榜）。本周新增约 1,572 星
   https://github.com/coreyhaines31/marketingskills
4. **jquery/jquery** — jQuery JavaScript 库，老牌项目回榜。本周新增约 523 星
   https://github.com/jquery/jquery
5. **affaan-m/ECC** — Agent harness 性能优化系统：技能、本能、记忆、安全与研究优先开发，覆盖 Claude Code、Codex、OpenCode、Cursor 等。本周新增约 5,598 星，总星 307,847
   https://github.com/affaan-m/ECC

后面值得注意：addyosmani/agent-skills（本周 +2,765，连续第二周在榜）、sveltejs/svelte（本周 +1,669）、louislam/uptime-kuma（本周 +1,146）、vercel-labs/agent-skills（Vercel 官方 Agent 技能合集，本周 +613）、GoogleChrome/lighthouse（本周 +115）。

---

## 5. Rust / 系统工具 Top 5

1. **vercel-labs/agent-browser** — 给 AI Agent 的浏览器自动化 CLI（连续第二周 Rust 榜第一）。本周新增约 2,691 星，总星 53,079
   https://github.com/vercel-labs/agent-browser
2. **block/buzz** — 蜂群思维通信平台。本周新增约 549 星，总星 37,630
   https://github.com/block/buzz
3. **ModernRelay/omnigraph** — 对象存储原生的图数据库，支持分支与类型化本体。本周新增约 1,094 星，总星 3,152
   https://github.com/ModernRelay/omnigraph
4. **martin-olivier/airgorah** — WiFi 安全审计软件。本周新增约 1,560 星，总星 6,737
   https://github.com/martin-olivier/airgorah
5. **crmne/zapfast** — Rust + egui 写的快速原生 WhatsApp 客户端。本周新增约 523 星，总星 4,819
   https://github.com/crmne/zapfast

后面值得注意：rustfs/rustfs（S3 兼容的高性能对象存储，本周 +310）、ViceVerse-cz/Serein（100% 原生 Rust Discord 客户端，本周 +215）。

---

## 6. Go / 云原生与 AI 服务 Top 5

1. **alibaba/open-code-review** — 阿里规模验证的代码评审工具。本周新增约 4,492 星
   https://github.com/alibaba/open-code-review
2. **getarcaneapp/arcane** — 面向所有人的现代 Docker 管理工具。本周新增约 1,820 星
   https://github.com/getarcaneapp/arcane
3. **agent-substrate/substrate** — Agent Substrate 核心系统。本周新增约 1,263 星
   https://github.com/agent-substrate/substrate
4. **runkids/skillshare** — 一条命令把技能、Agent、MCP、插件同步到所有 AI CLI 工具，方便团队共享。本周新增约 178 星
   https://github.com/runkids/skillshare
5. **Tencent/LoopForge** — 自托管的编码 Agent 交付工作流：用脚本与人工审批关卡编排 CodeBuddy、Codex 与 Claude Code。本周新增约 3,540 星，总星 5,271
   https://github.com/Tencent/LoopForge

后面值得注意：JuliusBrussee/caveman（本周 +2,279，连续第二周在榜）、docker/compose（本周 +641）、opensandbox-group/OpenSandbox（本周 +416，连续第二周在榜）、aquasecurity/trivy（本周 +289）、cli/cli（本周 +156）。

---

## 7. Java / Android 与逆向 Top 5

*按 GitHub Trending Java 周榜展示顺序；本周 Java 榜整体偏冷，前五多为周增星不足 200 的老牌项目*

1. **openjdk/jdk** — JDK 主线开发。本周新增约 34 星，总星 23,556
   https://github.com/openjdk/jdk
2. **jeecgboot/JeecgBoot** — 免费开源的 AI 低代码平台，AI 时代构建复杂业务系统的开源基座；AI Skills 一句话生成完整系统。本周新增约 95 星，总星 48,550
   https://github.com/jeecgboot/JeecgBoot
3. **SeleniumHQ/selenium** — 浏览器自动化框架与生态。本周新增约 27 星，总星 34,601
   https://github.com/SeleniumHQ/selenium
4. **jean-voila/FeurStagram** — 没有 Reels、信息流与广告的 Instagram：开源、可更新的 Android 版 Instagram 应用，保留私信与 Stories。本周新增约 154 星，总星 1,410
   https://github.com/jean-voila/FeurStagram
5. **TGX-Android/Telegram-X** — Telegram X 官方替代客户端（Android）。本周新增约 39 星，总星 6,223
   https://github.com/TGX-Android/Telegram-X

后面值得注意：termux/termux-app（本周 +560，本周 Java 榜实际增星最多）、elastic/elasticsearch（本周 +389）、TeamNewPipe/NewPipe（本周 +248）、MewX/light-novel-library_Wenku8_Android（本周 +151）、keycloak/keycloak（本周 +148）、LSPosed/LSPosed（本周 +125）。

---

## 值得 Xtop 亲自试的 4 个

结合你之前 Star 过的方向（AI/Agent 工具、本地模型、MCP）和你在做的项目：

1. **tradermonty/claude-trading-skills** — 交易技能包：市场分析、技术图表、经济日历、选股器与策略开发，和你的交易平台、加密货币晚间日报是同一条工作流，可以直接对照它的技能结构来组织你自己的行情分析流程
2. **andrewyng/openworker** — 吴恩达团队的桌面 Agent，“审批、审计、沙箱”默认架构；你的交易平台如果要加自动化提醒或自动执行，它的四级管控设计（硬底线、分级授权、审计轨迹、沙箱）是最值得抄的作业
3. **backnotprop/plannotator** — 本周全站第一的“人在 Agent 循环里”的工作区；你用 Agent 写交易平台代码时，用它做审代码、批注、发反馈的中枢，比在聊天框里来回贴代码更省上下文
4. **alibaba/open-code-review** — 确定性流水线 + LLM Agent 的代码评审，内置 NPE、线程安全、XSS、SQL 注入等规则集；跑一遍你的交易平台后端，看看它能抓出什么问题

---

## 数据来源

- GitHub Trending 官方周榜：https://github.com/trending?since=weekly 及各语言子榜（python / typescript / javascript / rust / go / java），查证于 2026-11-21 08:00 CST；本周增星数取自官方榜单页面本身
- 第三方汇总快照：gaojihao.github.io/github-hot/trending-weekly.html（更新于 2026-11-21 04:41 北京时间），用于交叉核对全站前 13 名的顺序与增星数
- 总星数来自 GitHub API 实时查询（2026-11-21 08:00 前后）；快照站的总星数与 API 实时数有微小出入（如 plannotator 快照 13,855，API 实时 13,888），以官方页面/API 为准
- 与上期（2026-11-14）对比：全站前五全部换新，仅 anthropics/skills、OpenMausBot、agent-browser、codex-security、daily_stock_analysis、marketingskills、agent-skills、caveman、OpenSandbox、termux、elasticsearch、NewPipe、keycloak 等少数项目连续在榜；主题从“Agent 运行环境 + Agent 安全”转向“人在回路的管控 + 技能垂直化 + 代码评审实战”，同时阿里、腾讯等中国团队项目集中冒头，Java 榜则整体偏冷

*说明：项目自述的性能数字（如 token 缩减、推理速度）均为项目方自家基准，未经第三方复现，导入前建议用自己的工作负载重测。*
