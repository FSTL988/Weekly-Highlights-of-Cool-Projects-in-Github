# GitHub 热门项目周报 — 最近一周

**时间窗口：** 2026-11-01 至 2026-11-07（GitHub Trending `since=weekly`）
**查证时间：** 2026-11-07 08:00 CST（Asia/Shanghai）
**口径说明：** 排名以 GitHub 官方 Trending 周榜展示顺序为准；本周增星数引用第三方汇总站快照（2026-11-07 03:38 北京时间），不同汇总站因抓取时间不同，增星数会有差异。官方榜单的展示顺序并不完全按增星数排序。

---

## 本周总览

这一周的主线从“技能”转向了 **Agent 的记忆与协作基础设施**。

1. **Agent 记忆成为新瓶颈** — 全站第一的 thedotmack/claude-mem（一周 +9,318 星）做跨会话持久上下文：把 Agent 每次会话做的事压缩后注入未来会话。max-sixty/worktrunk（Rust 榜第一）用 Git worktree 让多个 Agent 并行干活不打架，herdrdev/herdr 则想做“Agent 住的运行时”。技能装完了，下一步是让 Agent 记得住、配合得上。
2. **Agent 开始接管整条生产线** — Donchitos/Claude-Code-Game-Studios（全站第二）把 Claude Code 变成游戏开发工作室：49 个 Agent、72 个工作流技能，按真实工作室层级分工；calesthio/OpenMontage 则是开源的 Agent 视频制作系统，12 条制作管线、700+ 技能文件。Agent 从“写代码”走向“跑完整项目”。
3. **反 AI 味设计连续三周在榜** — Nutlope/hallmark（全站第五）、pbakaus/impeccable、Leonxlnx/taste-skill 三个设计品味项目同时霸榜，AI 生成内容的“审美税”正在变成正式的基础设施。
4. **基础设施老将回潮** — Go 榜前五几乎全是 moby、gitea、argo-cd、docker/compose 等云原生老牌项目，Java 榜也是 keycloak、elasticsearch、cryptomator、StarRocks；与 Agent 新贵形成对照，说明这一周的关注度在向底层基础设施回流。
5. **金融 AI 冒头** — shiyu-coder/Kronos（Python 榜第六）是面向金融市场的语言基础模型，值得做交易/行情相关项目的人留意。

---

## 1. 全站总榜 Top 5

| # | 项目 | 语言 | 说明 |
|---|------|------|------|
| 1 | thedotmack/claude-mem | TypeScript | 跨会话持久上下文：记录 Agent 每次会话的行为，AI 压缩后注入未来会话，支持 Claude Code、OpenClaw、Codex、Gemini、Hermes、Copilot、OpenCode 等。本周新增约 9,318 星 |
| 2 | Donchitos/Claude-Code-Game-Studios | Shell | 把 Claude Code 变成完整游戏开发工作室：49 个 AI Agent、72 个工作流技能，按真实工作室层级协调。本周新增约 6,685 星 |
| 3 | pingdotgg/t3code | TypeScript | T3 团队的编程 Agent 工具（连续两周上榜）。本周新增约 16,235 星（第三方汇总口径；官方展示顺序不完全按增星排序） |
| 4 | max-sixty/worktrunk | Rust | 面向并行 AI Agent 工作流的 Git worktree 管理 CLI。本周新增约 1,802 星 |
| 5 | Nutlope/hallmark | CSS | 反 AI 味设计技能，面向 Claude Code、Cursor 和 Codex。本周新增约 6,994 星 |

紧随其后：anthropics/skills（本周 +3,072）、milind-soni/OpenMausBot（本周 +5,580）、pbakaus/impeccable（本周 +9,303）、obra/superpowers（本周 +5,131）、HKUDS/DeepTutor（本周 +6,229）。

项目链接：
- https://github.com/thedotmack/claude-mem
- https://github.com/Donchitos/Claude-Code-Game-Studios
- https://github.com/pingdotgg/t3code
- https://github.com/max-sixty/worktrunk
- https://github.com/Nutlope/hallmark

---

## 2. Python / AI 与数据 Top 5

1. **anthropics/skills** — Anthropic 官方 Agent Skills 公共仓库（连续三周上榜）
   https://github.com/anthropics/skills
2. **HKUDS/DeepTutor** — 终身个性化家教：Lifelong Personalized Tutoring。本周新增约 6,229 星
   https://github.com/HKUDS/DeepTutor
3. **calesthio/OpenMontage** — 世界首个开源 Agent 视频制作系统：12 条制作管线、100+ 工具、700+ Agent 技能与制作知识文件。本周新增约 4,132 星
   https://github.com/calesthio/OpenMontage
4. **The-PR-Agent/pr-agent** — 开源 PR 评审 Agent
   https://github.com/The-PR-Agent/pr-agent
5. **D4Vinci/Scrapling** — 高性能 Web 爬取框架，从单次请求到大规模爬取。本周新增约 7,487 星
   https://github.com/D4Vinci/Scrapling

后面值得注意：shiyu-coder/Kronos（金融市场语言基础模型，本周 +2,979）、github/spec-kit（规格驱动开发工具包）、blader/humanizer（去除 AI 写作痕迹的 Agent 技能）、AgriciDaniel/claude-seo、ethanplusai/sellbird（开源外联平台）。

---

## 3. TypeScript / 前端与 Agent 工具 Top 5

1. **thedotmack/claude-mem** — Agent 跨会话持久上下文
   https://github.com/thedotmack/claude-mem
2. **pingdotgg/t3code** — T3 团队的编程 Agent 工具
   https://github.com/pingdotgg/t3code
3. **milind-soni/OpenMausBot** — 开源 Grok Bot 替代品，自带虚拟机供 Bot 使用。本周新增约 5,580 星
   https://github.com/milind-soni/OpenMausBot
4. **nightly-labs/openbot** — 本地优先的持久 AI 队友桌面工作区：Codex、Claude、Grok 各有专属工作区、任务队列、文件共享与 Agent 间协作。本周新增约 2,085 星
   https://github.com/nightly-labs/openbot
5. **garrytan/gstack** — Garry Tan 的 Claude Code 配置：23 个按 CEO、设计师、工程经理、发布经理、文档工程师、QA 分工的工具
   https://github.com/garrytan/gstack

后面值得注意：Vincentwei1021/video-shotcraft（AI 视频技能，Remotion 制作产品宣传片）、CopilotKit/OpenBot（每个 AI 同事配一台自己的电脑）、tashfeenahmed/freellmapi（34 个免费 LLM 供应商聚合为一个 /v1 接口）、remotion/remotion、openclaw/openclaw、stablyai/orca。

---

## 4. JavaScript Top 5

1. **cloudflare/security-audit-skill** — 让编程 Agent 做多阶段安全审计，独立验证、机器可读的结果（连续三周登顶 JS 榜）
   https://github.com/cloudflare/security-audit-skill
2. **Leonxlnx/taste-skill** — 给编码 Agent“品味”的技能：艺术指导、参考图、浏览器实测，拒绝通用 AI 页面
   https://github.com/Leonxlnx/taste-skill
3. **HunYiSage/dsh-purge** — DeepSeek Harness 破甲工具：让所有模型都能换提示词破甲，默认提示词面向国产模型
   https://github.com/HunYiSage/dsh-purge
4. **affaan-m/ECC** — Agent harness 性能优化系统：技能、本能、记忆、安全与研究优先开发
   https://github.com/affaan-m/ECC
5. **github/awesome-copilot** — 社区贡献的 Copilot 指令、Agent、技能与配置精选
   https://github.com/github/awesome-copilot

后面值得注意：techjarves/Portable-Local-Studio（便携本地 AI 工作室：文生图、GGUF 本地模型、语音合成与转写）、DeanChensj/jiangshan-map（江山时序·中国历史交互地图）、coreyhaines31/marketingskills、ConardLi/garden-skills。

---

## 5. Rust / 系统工具 Top 5

1. **max-sixty/worktrunk** — 面向并行 AI Agent 工作流的 Git worktree 管理 CLI
   https://github.com/max-sixty/worktrunk
2. **pbakaus/impeccable** — 给编码 Agent 的设计词汇（连续三周上榜）
   https://github.com/pbakaus/impeccable
3. **herdrdev/herdr** — “你的编码 Agent 住的运行时”
   https://github.com/herdrdev/herdr
4. **openai/codex** — 在终端运行的轻量编码 Agent
   https://github.com/openai/codex
5. **zed-industries/zed** — 高性能多人代码编辑器，Atom 与 Tree-sitter 原班人马出品
   https://github.com/zed-industries/zed

后面值得注意：cjpais/Handy（完全离线的开源语音转文字）、vercel-labs/agent-browser（给 AI Agent 的浏览器自动化 CLI）、leepokai/Codync（开源 Grok Bot 替代品，Rust 编写）、xai-org/x-algorithm（X 推荐流算法开源）、agentgateway/agentgateway。

---

## 6. Go / 云原生与 AI 服务 Top 5

1. **moby/moby** — Moby 项目：容器生态系统的协作项目
   https://github.com/moby/moby
2. **multica-ai/multica** — 让人类与 AI Agent 像一个团队协作，开源、可自托管（连续两周上榜）
   https://github.com/multica-ai/multica
3. **go-gitea/gitea** — 自托管一站式软件开发服务：Git 托管、代码评审、协作、包注册与 CI/CD
   https://github.com/go-gitea/gitea
4. **argoproj/argo-cd** — 面向 Kubernetes 的声明式持续部署
   https://github.com/argoproj/argo-cd
5. **docker/compose** — 定义并运行多容器应用
   https://github.com/docker/compose

后面值得注意：netbirdio/netbird（基于 WireGuard 的零信任组网）、infiniflow/ragflow、prometheus/prometheus、golang/go、kubernetes/kubernetes、gastownhall/beads（给编码 Agent 的记忆升级）。

---

## 7. Java / Android 与逆向 Top 5

*按 GitHub Trending Java 周榜展示顺序*

1. **floci-io/floci** — 轻量免费的 AWS 本地模拟器替代品
   https://github.com/floci-io/floci
2. **keycloak/keycloak** — 面向现代应用与服务的开源身份与访问管理
   https://github.com/keycloak/keycloak
3. **elastic/elasticsearch** — 免费开源的分布式 RESTful 搜索引擎
   https://github.com/elastic/elasticsearch
4. **cryptomator/cryptomator** — 云存储的客户端加密工具，保障隐私与数据控制权
   https://github.com/cryptomator/cryptomator
5. **StarRocks/starrocks** — 全球最快的开源查询引擎之一，湖仓内外亚秒级分析
   https://github.com/StarRocks/starrocks

后面值得注意：spring-projects/spring-framework、openjdk/jdk、skylot/jadx（Dex 转 Java 反编译）、termux/termux-app、bazelbuild/bazel、floci-io/floci-az（本地 Azure 模拟器）。

---

## 值得 Xtop 亲自试的 4 个

结合你之前 Star 过的方向（AI/Agent 工具、本地模型、MCP）和你在做的项目：

1. **thedotmack/claude-mem** — 本周全站第一。Agent 跨会话记忆正是你 Pro Crypto 项目和 AI 工程师学习里会反复碰到的痛点：让 Agent 记得上次做到哪、踩过什么坑
2. **max-sixty/worktrunk** — 用 Git worktree 让多个 Agent 并行改不同功能、互不干扰，配合 OpenCode/Claude Code 一起用很顺手
3. **Donchitos/Claude-Code-Game-Studios** — 49 个 Agent 按工作室层级分工的协调系统，架构思路可以直接借鉴到多 Agent 协作的设计里
4. **shiyu-coder/Kronos** — 面向金融市场的语言基础模型，和你关注的行情、交易方向直接相关，值得看看它怎么把市场数据变成语言

---

## 数据来源

- GitHub Trending 官方周榜：https://github.com/trending?since=weekly 及各语言子榜（python / typescript / javascript / rust / go / java），查证于 2026-11-07 08:00 CST
- 第三方汇总快照：gaojihao.github.io/github-hot/trending-weekly.html（更新于 2026-11-07 03:38 北京时间）
- 与上期（2026-10-31）对比：全站榜单几乎全部换血，仅 t3code、anthropics/skills、impeccable、superpowers 等少数项目连续在榜；主题从“技能数量与安全”转向“Agent 记忆、并行协作与整条生产线的 Agent 化”，同时云原生与 Java 基础设施老将明显回潮

*说明：项目自述的性能数字（如 token 缩减、推理速度）均为项目方自家基准，未经第三方复现，导入前建议用自己的工作负载重测。*
