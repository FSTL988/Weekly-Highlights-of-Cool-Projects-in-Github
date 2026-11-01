# Weekly Highlights

每周 GitHub 热门项目精选。来源是 GitHub Trending 官方周榜（`since=weekly`）及各语言子榜，按领域整理成清单；每周六早上 8 点更新一期，完整周报见 `reports/<日期>/`。

> 说明：这里是项目清单版 — 项目以链接形式收录，不把上游仓库的代码本体复制进来。点击项目名即可跳转到原仓库。

## 最新一期：2026-10-31（2026-10-25 至 2026-10-31）

- 完整周报：[reports/2026-10-31/github-weekly-2026-10-31.md](reports/2026-10-31/github-weekly-2026-10-31.md)

本周主线：关键词仍然是 Agent 技能（skills），但风向从“做更多技能”转向了“管好技能”和“让 Agent 更有品味”。
1. 技能安全与质量成为新焦点 — cloudflare/security-audit-skill 让 Agent 自己做多阶段安全审计；NVIDIA 的 SkillSpector 扫描技能里的提示注入与数据外泄。
2. 大厂亲自下场发技能 — Anthropic 的 knowledge-work-plugins、AWS 的 agent-toolkit-for-aws 上线；技能分发从社区自发变成官方标配。
3. Agent 开始讲“品味”和“审美” — pbakaus/impeccable 给 Agent 一套设计词汇，taste-skill 教 Agent 做界面、做艺术指导。

### 全站总榜 Top 5

| # | 项目 | 说明 |
|---|------|------|
| 1 | [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill) | 让编程 Agent 做多阶段安全审计，独立验证、机器可读 |
| 2 | [AgriciDaniel/claude-seo](https://github.com/AgriciDaniel/claude-seo) | Claude Code 通用 SEO 技能：26 个子技能 + 19 个子代理 |
| 3 | [pbakaus/impeccable](https://github.com/pbakaus/impeccable) | 给编码 Agent 的设计词汇，拦截 AI 味页面 |
| 4 | [obra/superpowers](https://github.com/obra/superpowers) | Agent 技能框架与软件开发方法论 |
| 5 | [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents) | 多智能体 LLM 金融交易框架 |

### Python / AI 与数据 Top 5

| # | 项目 | 说明 |
|---|------|------|
| 1 | [AgriciDaniel/claude-seo](https://github.com/AgriciDaniel/claude-seo) | Claude Code 通用 SEO 技能，26 个子技能 + 19 个子代理 |
| 2 | [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents) | 多智能体 LLM 金融交易框架 |
| 3 | [anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins) | Anthropic 官方插件库，面向 Claude Cowork 的知识工作者 |
| 4 | [anthropics/skills](https://github.com/anthropics/skills) | Anthropic 官方 Agent Skills 公共仓库 |
| 5 | [aws/agent-toolkit-for-aws](https://github.com/aws/agent-toolkit-for-aws) | AWS 官方 MCP 服务器、技能与插件 |

### TypeScript / 前端与 Agent 工具 Top 5

| # | 项目 | 说明 |
|---|------|------|
| 1 | [pingdotgg/t3code](https://github.com/pingdotgg/t3code) | T3 团队的编程 Agent 工具 |
| 2 | [ruvnet/ruflo](https://github.com/ruvnet/ruflo) | Agent 集群 harness |
| 3 | [gitroomhq/postiz-app](https://github.com/gitroomhq/postiz-app) | Agent 化社交媒体排期工具 |
| 4 | [anomalyco/opencode](https://github.com/anomalyco/opencode) | 开源编程 Agent |
| 5 | [google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli) | 把 Gemini 带进终端的开源 AI Agent |

### JavaScript Top 5

| # | 项目 | 说明 |
|---|------|------|
| 1 | [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill) | 让编程 Agent 做多阶段安全审计，独立验证、机器可读 |
| 2 | [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) | 给编码 Agent“品味”的技能：艺术指导、参考图、浏览器实测 |
| 3 | [affaan-m/ECC](https://github.com/affaan-m/ECC) | Agent harness 性能优化系统 |
| 4 | [hmjz100/LinkSwift](https://github.com/hmjz100/LinkSwift) | 网盘直链下载工具，支持八大网盘 |
| 5 | [citrolabs/ego-lite](https://github.com/citrolabs/ego-lite) | 给 AI Agent 的最快浏览器，共享已登录浏览器状态做自动化 |

### Rust / 系统工具 Top 5

| # | 项目 | 说明 |
|---|------|------|
| 1 | [pbakaus/impeccable](https://github.com/pbakaus/impeccable) | 给编码 Agent 的设计词汇 |
| 2 | [akitaonrails/ai-memory](https://github.com/akitaonrails/ai-memory) | 给编程 Agent CLI 做长期记忆，支持厂商间交接 |
| 3 | [agentgateway/agentgateway](https://github.com/agentgateway/agentgateway) | 下一代 Agentic Proxy，面向 AI Agent 与 MCP 服务器 |
| 4 | [pollen-robotics/microduck](https://github.com/pollen-robotics/microduck) | 微型双足鸭子机器人 |
| 5 | [macro-inc/macro](https://github.com/macro-inc/macro) | 统一工作空间：邮件、聊天、文档、任务、Agent、通话与 CRM |

### Go / 云原生与 AI 服务 Top 5

| # | 项目 | 说明 |
|---|------|------|
| 1 | [infiniflow/ragflow](https://github.com/infiniflow/ragflow) | 开源 RAG 引擎，RAG + Agent 的上下文层 |
| 2 | [slavakurilyak/awesome-ai-agents](https://github.com/slavakurilyak/awesome-ai-agents) | 300+ Agent AI 资源精选清单 |
| 3 | [multica-ai/multica](https://github.com/multica-ai/multica) | 让人类与 AI Agent 像一个团队协作，开源、可自托管 |
| 4 | [QuantumNous/new-api](https://github.com/QuantumNous/new-api) | 开源 AI 网关，兼容 OpenAI / Claude / Gemini API |
| 5 | [plandex-ai/plandex](https://github.com/plandex-ai/plandex) | 开源 AI 编程 Agent，面向大型项目与真实任务 |

### Java / Android 与逆向 Top 5

| # | 项目 | 说明 |
|---|------|------|
| 1 | [krahets/hello-algo](https://github.com/krahets/hello-algo) | 《Hello 算法》：动画图解的数据结构与算法教程 |
| 2 | [TheAlgorithms/Java](https://github.com/TheAlgorithms/Java) | Java 实现的全部经典算法 |
| 3 | [kksimp/Mac.apk](https://github.com/kksimp/Mac.apk) | 在 Apple Silicon Mac 上原生运行 Android 应用 |
| 4 | [HMCL-dev/HMCL](https://github.com/HMCL-dev/HMCL) | 多功能、跨平台的 Minecraft 启动器 |
| 5 | [DependencyTrack/dependency-track](https://github.com/DependencyTrack/dependency-track) | 智能组件分析平台，降低软件供应链风险 |

## 往期周报

| 日期 | 完整周报 |
|------|----------|
| 2026-10-31 | [reports/2026-10-31/github-weekly-2026-10-31.md](reports/2026-10-31/github-weekly-2026-10-31.md) |
| 2026-10-24 | [reports/2026-10-24/github-weekly-2026-10-24.md](reports/2026-10-24/github-weekly-2026-10-24.md) |

## 数据来源

- GitHub Trending 官方周榜：https://github.com/trending?since=weekly 及各语言子榜
- 排名以官方周榜展示顺序为准；星数/增星来自第三方汇总站快照，不同来源因抓取时间不同会有差异
- 项目自述的性能数字均为项目方自家基准，未经第三方复现
