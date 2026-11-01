# GitHub 热门项目周报 — 最近一周

**时间窗口：** 2026-10-25 至 2026-10-31（GitHub Trending `since=weekly`）
**查证时间：** 2026-10-31 07:58 CST（Asia/Shanghai）
**口径说明：** 排名以 GitHub 官方 Trending 周榜展示顺序为准；本周增星数引用第三方汇总站快照（2026-10-31 02:08 北京时间），不同汇总站因抓取时间不同，增星数会有差异。官方榜单的展示顺序并不完全按增星数排序。

---

## 本周总览

这一周的关键词仍然是 **Agent 技能（skills）**，但风向从“做更多技能”转向了“管好技能”和“让 Agent 更有品味”。

1. **技能安全与质量成为新焦点** — 全站第一的 cloudflare/security-audit-skill（一周 +14,320 星）让 Agent 自己做多阶段安全审计；NVIDIA 的 SkillSpector 专门扫描技能里的提示注入、恶意代码和数据外泄。技能装得越多，越需要有人检查技能本身。
2. **大厂亲自下场发技能** — Anthropic 为知识工作者推出 knowledge-work-plugins，AWS 推出官方 agent-toolkit-for-aws，Anthropic 的 skills 仓库继续上榜；技能分发从社区自发变成官方标配。
3. **Agent 开始讲“品味”和“审美”** — pbakaus/impeccable（一周 +9,713 星）给 Agent 一套设计词汇，taste-skill 和 jakubkrehel/skills 教 Agent 做界面、做艺术指导；AI 写的页面能不能看，开始有人认真管了。
4. **金融 Agent 热度回升** — TauricResearch/TradingAgents（一周 +5,557 星）重回全站前五，多智能体交易框架再次受到关注；同时 Rust 榜出现了 WiFi 信号感知、机器人小鸭等跨界项目。

---

## 1. 全站总榜 Top 5

| # | 项目 | 语言 | 说明 |
|---|------|------|------|
| 1 | cloudflare/security-audit-skill | JavaScript | 让编程 Agent 做多阶段安全审计，独立验证、机器可读的结果。本周新增约 14,320 星 |
| 2 | AgriciDaniel/claude-seo | Python | Claude Code 通用 SEO 技能：26 个子技能 + 19 个子代理，覆盖技术 SEO、E-E-A-T、schema、GEO/AEO 等。本周新增约 4,110 星 |
| 3 | pbakaus/impeccable | Rust | 给编码 Agent 的设计词汇：引导写出精致大胆的设计，评审时做 critique 和 audit，在 AI 味页面上线前拦截。本周新增约 9,713 星 |
| 4 | obra/superpowers | Shell | Agent 技能框架与软件开发方法论。本周新增约 4,894 星 |
| 5 | TauricResearch/TradingAgents | Python | 多智能体 LLM 金融交易框架。本周新增约 5,557 星 |

紧随其后：multica-ai/andrej-karpathy-skills（本周 +4,250）、Leonxlnx/taste-skill（本周 +4,359）、jakubkrehel/skills、pingdotgg/t3code、anthropics/knowledge-work-plugins、affaan-m/ECC（本周 +6,594）、anthropics/skills、ruvnet/ruflo。

项目链接：
- https://github.com/cloudflare/security-audit-skill
- https://github.com/AgriciDaniel/claude-seo
- https://github.com/pbakaus/impeccable
- https://github.com/obra/superpowers
- https://github.com/TauricResearch/TradingAgents

---

## 2. Python / AI 与数据 Top 5

1. **AgriciDaniel/claude-seo** — Claude Code 通用 SEO 技能，26 个子技能 + 19 个子代理
   https://github.com/AgriciDaniel/claude-seo
2. **TauricResearch/TradingAgents** — 多智能体 LLM 金融交易框架
   https://github.com/TauricResearch/TradingAgents
3. **anthropics/knowledge-work-plugins** — Anthropic 官方插件库，主要面向 Claude Cowork 的知识工作者
   https://github.com/anthropics/knowledge-work-plugins
4. **anthropics/skills** — Anthropic 官方 Agent Skills 公共仓库
   https://github.com/anthropics/skills
5. **aws/agent-toolkit-for-aws** — AWS 官方 MCP 服务器、技能与插件，帮助 AI Agent 在 AWS 上构建
   https://github.com/aws/agent-toolkit-for-aws

后面值得注意：higgsfield-ai/skills、NVIDIA/SkillSpector（扫描技能的安全风险）、sgl-project/sglang、debpalash/VoiceStudio、vllm-project/vllm、HKUDS/DeepTutor（终身个性化家教）。

---

## 3. TypeScript / 前端与 Agent 工具 Top 5

1. **pingdotgg/t3code** — T3 团队的编程 Agent 工具
   https://github.com/pingdotgg/t3code
2. **ruvnet/ruflo** — Agent 集群 harness（连续两周上榜）
   https://github.com/ruvnet/ruflo
3. **gitroomhq/postiz-app** — Agent 化社交媒体排期工具
   https://github.com/gitroomhq/postiz-app
4. **anomalyco/opencode** — 开源编程 Agent
   https://github.com/anomalyco/opencode
5. **google-gemini/gemini-cli** — 把 Gemini 带进终端的开源 AI Agent
   https://github.com/google-gemini/gemini-cli

后面值得注意：anthropics/sandbox-runtime（轻量进程沙箱）、heygen-com/hyperframes（写 HTML 生成视频）、JetBrains/thinkrail、microsoft/skill-recorder（把屏幕操作录成可复用技能）、langfuse/langfuse。

---

## 4. JavaScript Top 5

1. **cloudflare/security-audit-skill** — 让编程 Agent 做多阶段安全审计，独立验证、机器可读。本周新增约 14,320 星
   https://github.com/cloudflare/security-audit-skill
2. **Leonxlnx/taste-skill** — 给编码 Agent“品味”的技能：艺术指导、参考图、浏览器实测，拒绝通用 AI 页面
   https://github.com/Leonxlnx/taste-skill
3. **affaan-m/ECC** — Agent harness 性能优化系统：技能、本能、记忆、安全与研究优先开发
   https://github.com/affaan-m/ECC
4. **hmjz100/LinkSwift** — 网盘直链下载工具，支持百度网盘 / 阿里云盘 / 中国移动云盘 / 天翼云盘 / 迅雷云盘 / 夸克网盘 / UC网盘 / 123云盘八大网盘
   https://github.com/hmjz100/LinkSwift
5. **citrolabs/ego-lite** — 给 AI Agent 的最快浏览器：共享已登录的浏览器状态做浏览器自动化，零成本、零配置
   https://github.com/citrolabs/ego-lite

后面值得注意：OpenWhispr/openwhispr（本地语音转文字）、ulsklyc/yuvomi（自托管家庭计划器）、nodejs/node。

---

## 5. Rust / 系统工具 Top 5

1. **pbakaus/impeccable** — 给编码 Agent 的设计词汇。本周新增约 9,713 星
   https://github.com/pbakaus/impeccable
2. **akitaonrails/ai-memory** — 给编程 Agent CLI 做长期记忆，支持不同 Agent 厂商之间交接 handoff
   https://github.com/akitaonrails/ai-memory
3. **agentgateway/agentgateway** — 下一代 Agentic Proxy，面向 AI Agent 与 MCP 服务器
   https://github.com/agentgateway/agentgateway
4. **pollen-robotics/microduck** — 一只微型双足鸭子机器人 🦆
   https://github.com/pollen-robotics/microduck
5. **macro-inc/macro** — 统一工作空间：邮件、聊天、文档、任务、Agent、通话与 CRM，共享 AI 记忆
   https://github.com/macro-inc/macro

后面值得注意：xerj-org/xerj、ruvnet/RuView（用 WiFi 信号做实时空间感知与生命体征监测）、ZSeven-W/openpencil（AI 原生矢量设计工具）、NVIDIA/cuda-rust、rustdesk/rustdesk。

---

## 6. Go / 云原生与 AI 服务 Top 5

1. **infiniflow/ragflow** — 开源 RAG 引擎，把前沿 RAG 与 Agent 能力融合成 LLM 的上下文层
   https://github.com/infiniflow/ragflow
2. **slavakurilyak/awesome-ai-agents** — 300+ Agent AI 资源精选清单
   https://github.com/slavakurilyak/awesome-ai-agents
3. **multica-ai/multica** — 让人类与 AI Agent 像一个团队协作，开源、可自托管
   https://github.com/multica-ai/multica
4. **QuantumNous/new-api** — 开源 AI 网关：自托管 LLM 网关，兼容 OpenAI / Claude / Gemini API，带模型路由、访问控制与用量计费
   https://github.com/QuantumNous/new-api
5. **plandex-ai/plandex** — 开源 AI 编程 Agent，面向大型项目与真实任务
   https://github.com/plandex-ai/plandex

后面值得注意：router-for-me/CLIProxyAPI、grafana/loki、wailsapp/wails、chaitin/SafeLine、ollama/ollama、tailscale/tailscale、github/gh-aw（GitHub Agentic Workflows）。

---

## 7. Java / Android 与逆向 Top 5

*按 GitHub Trending Java 周榜展示顺序*

1. **krahets/hello-algo** — 《Hello 算法》：动画图解、一键运行的数据结构与算法教程，支持多语言与多语言代码实现
   https://github.com/krahets/hello-algo
2. **TheAlgorithms/Java** — Java 实现的全部经典算法
   https://github.com/TheAlgorithms/Java
3. **kksimp/Mac.apk** — 在 Apple Silicon Mac 上原生运行 Android 应用
   https://github.com/kksimp/Mac.apk
4. **HMCL-dev/HMCL** — 多功能、跨平台的 Minecraft 启动器（连续两周上榜）
   https://github.com/HMCL-dev/HMCL
5. **DependencyTrack/dependency-track** — 智能组件分析平台，识别并降低软件供应链风险
   https://github.com/DependencyTrack/dependency-track

后面值得注意：halo-dev/halo、alibaba/nacos、iBotPeaches/Apktool、spring-projects/spring-framework、elastic/elasticsearch、apache/flink、cryptomator/cryptomator。

---

## 值得 Xtop 亲自试的 4 个

结合你之前 Star 过的方向（AI/Agent 工具、本地模型、MCP）和你在做的项目：

1. **cloudflare/security-audit-skill** — 本周全站第一。让 Agent 自己做安全审计的思路可以直接用到你的 Pro Crypto 项目上，审计 API key 与数据库配置
2. **NVIDIA/SkillSpector** — 技能装得越多越要防投毒：扫描技能里的提示注入与数据外泄，装新技能前先过一遍
3. **pbakaus/impeccable** — 如果你让 Agent 写前端页面，这个设计词汇能直接提升成品观感，拦截“AI 味”
4. **anthropics/sandbox-runtime** — 轻量进程沙箱，不用容器就能给任意进程加文件系统与网络限制，适合把 Agent 的工具调用关进沙箱

---

## 数据来源

- GitHub Trending 官方周榜：https://github.com/trending?since=weekly 及各语言子榜（python / typescript / javascript / rust / go / java），查证于 2026-10-31 07:58 CST
- 第三方汇总快照：gaojihao.github.io/github-hot/trending-weekly.html（更新于 2026-10-31 02:08 北京时间）
- 与上期（2026-10-24）对比：全站榜单几乎全部换血，仅 ruflo、opencode、ECC、LinkSwift、ai-memory、xerj、ollama、HMCL、Apktool 等少数项目连续两周在榜；Agent 技能主题从上周延续至今，但焦点从“技能数量”转向“技能安全与质量”

*说明：项目自述的性能数字（如 token 缩减、推理速度）均为项目方自家基准，未经第三方复现，导入前建议用自己的工作负载重测。*
