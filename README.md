# Weekly Highlights

每周 GitHub 热门项目精选。来源是 GitHub Trending 官方周榜（`since=weekly`）及各语言子榜，按领域整理成清单；每周六早上 8 点更新一期，完整周报见 `reports/<日期>/`。

> 说明：这里是项目清单版 — 项目以链接形式收录，不把上游仓库的代码本体复制进来。点击项目名即可跳转到原仓库。

## 最新一期：2026-11-07（2026-11-01 至 2026-11-07）

- 完整周报：[reports/2026-11-07/github-weekly-2026-11-07.md](reports/2026-11-07/github-weekly-2026-11-07.md)

本周主线：从“技能”转向了 Agent 的记忆与协作基础设施。
1. Agent 记忆成为新瓶颈 — thedotmack/claude-mem 做跨会话持久上下文；max-sixty/worktrunk 用 Git worktree 让多个 Agent 并行干活不打架。
2. Agent 开始接管整条生产线 — Claude-Code-Game-Studios 把 Claude Code 变成游戏开发工作室（49 个 Agent、72 个工作流技能）；OpenMontage 是开源的 Agent 视频制作系统。
3. 反 AI 味设计连续三周在榜 — hallmark、impeccable、taste-skill 同时霸榜。
4. 基础设施老将回潮 — Go 榜前五几乎全是 moby、gitea、argo-cd、docker/compose 等云原生老牌项目。

### 全站总榜 Top 5

| # | 项目 | 说明 |
|---|------|------|
| 1 | [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem) | 跨会话持久上下文，Agent 行为压缩后注入未来会话 |
| 2 | [Donchitos/Claude-Code-Game-Studios](https://github.com/Donchitos/Claude-Code-Game-Studios) | 把 Claude Code 变成游戏开发工作室：49 个 Agent、72 个工作流技能 |
| 3 | [pingdotgg/t3code](https://github.com/pingdotgg/t3code) | T3 团队的编程 Agent 工具 |
| 4 | [max-sixty/worktrunk](https://github.com/max-sixty/worktrunk) | 面向并行 AI Agent 工作流的 Git worktree 管理 CLI |
| 5 | [Nutlope/hallmark](https://github.com/Nutlope/hallmark) | 反 AI 味设计技能，面向 Claude Code、Cursor 和 Codex |

### Python / AI 与数据 Top 5

| # | 项目 | 说明 |
|---|------|------|
| 1 | [anthropics/skills](https://github.com/anthropics/skills) | Anthropic 官方 Agent Skills 公共仓库 |
| 2 | [HKUDS/DeepTutor](https://github.com/HKUDS/DeepTutor) | 终身个性化家教 |
| 3 | [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage) | 开源 Agent 视频制作系统：12 条管线、700+ 技能文件 |
| 4 | [The-PR-Agent/pr-agent](https://github.com/The-PR-Agent/pr-agent) | 开源 PR 评审 Agent |
| 5 | [D4Vinci/Scrapling](https://github.com/D4Vinci/Scrapling) | 高性能 Web 爬取框架 |

### TypeScript / 前端与 Agent 工具 Top 5

| # | 项目 | 说明 |
|---|------|------|
| 1 | [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem) | Agent 跨会话持久上下文 |
| 2 | [pingdotgg/t3code](https://github.com/pingdotgg/t3code) | T3 团队的编程 Agent 工具 |
| 3 | [milind-soni/OpenMausBot](https://github.com/milind-soni/OpenMausBot) | 开源 Grok Bot 替代品，自带虚拟机供 Bot 使用 |
| 4 | [nightly-labs/openbot](https://github.com/nightly-labs/openbot) | 本地优先的持久 AI 队友桌面工作区 |
| 5 | [garrytan/gstack](https://github.com/garrytan/gstack) | Garry Tan 的 Claude Code 配置：23 个分工工具 |

### JavaScript Top 5

| # | 项目 | 说明 |
|---|------|------|
| 1 | [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill) | 让编程 Agent 做多阶段安全审计，独立验证、机器可读 |
| 2 | [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) | 给编码 Agent“品味”的技能：艺术指导、参考图、浏览器实测 |
| 3 | [HunYiSage/dsh-purge](https://github.com/HunYiSage/dsh-purge) | DeepSeek Harness 破甲工具，让所有模型换提示词破甲 |
| 4 | [affaan-m/ECC](https://github.com/affaan-m/ECC) | Agent harness 性能优化系统 |
| 5 | [github/awesome-copilot](https://github.com/github/awesome-copilot) | 社区贡献的 Copilot 指令、Agent、技能与配置精选 |

### Rust / 系统工具 Top 5

| # | 项目 | 说明 |
|---|------|------|
| 1 | [max-sixty/worktrunk](https://github.com/max-sixty/worktrunk) | 面向并行 AI Agent 工作流的 Git worktree 管理 CLI |
| 2 | [pbakaus/impeccable](https://github.com/pbakaus/impeccable) | 给编码 Agent 的设计词汇 |
| 3 | [herdrdev/herdr](https://github.com/herdrdev/herdr) | “你的编码 Agent 住的运行时” |
| 4 | [openai/codex](https://github.com/openai/codex) | 在终端运行的轻量编码 Agent |
| 5 | [zed-industries/zed](https://github.com/zed-industries/zed) | 高性能多人代码编辑器 |

### Go / 云原生与 AI 服务 Top 5

| # | 项目 | 说明 |
|---|------|------|
| 1 | [moby/moby](https://github.com/moby/moby) | Moby 项目：容器生态系统的协作项目 |
| 2 | [multica-ai/multica](https://github.com/multica-ai/multica) | 让人类与 AI Agent 像一个团队协作，开源、可自托管 |
| 3 | [go-gitea/gitea](https://github.com/go-gitea/gitea) | 自托管一站式软件开发服务 |
| 4 | [argoproj/argo-cd](https://github.com/argoproj/argo-cd) | 面向 Kubernetes 的声明式持续部署 |
| 5 | [docker/compose](https://github.com/docker/compose) | 定义并运行多容器应用 |

### Java / Android 与逆向 Top 5

| # | 项目 | 说明 |
|---|------|------|
| 1 | [floci-io/floci](https://github.com/floci-io/floci) | 轻量免费的 AWS 本地模拟器替代品 |
| 2 | [keycloak/keycloak](https://github.com/keycloak/keycloak) | 开源身份与访问管理 |
| 3 | [elastic/elasticsearch](https://github.com/elastic/elasticsearch) | 免费开源的分布式 RESTful 搜索引擎 |
| 4 | [cryptomator/cryptomator](https://github.com/cryptomator/cryptomator) | 云存储的客户端加密工具 |
| 5 | [StarRocks/starrocks](https://github.com/StarRocks/starrocks) | 开源查询引擎，湖仓内外亚秒级分析 |

## 往期周报

| 日期 | 完整周报 |
|------|----------|
| 2026-11-07 | [reports/2026-11-07/github-weekly-2026-11-07.md](reports/2026-11-07/github-weekly-2026-11-07.md) |
| 2026-10-31 | [reports/2026-10-31/github-weekly-2026-10-31.md](reports/2026-10-31/github-weekly-2026-10-31.md) |
| 2026-10-24 | [reports/2026-10-24/github-weekly-2026-10-24.md](reports/2026-10-24/github-weekly-2026-10-24.md) |

## 数据来源

- GitHub Trending 官方周榜：https://github.com/trending?since=weekly 及各语言子榜
- 排名以官方周榜展示顺序为准；星数/增星来自第三方汇总站快照，不同来源因抓取时间不同会有差异
- 项目自述的性能数字均为项目方自家基准，未经第三方复现
