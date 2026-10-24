# Weekly Highlights

每周 GitHub 热门项目精选。来源是 GitHub Trending 官方周榜（`since=weekly`）及各语言子榜，按领域整理成清单；每周六早上 8 点更新一期，完整周报见 `reports/<日期>/`。

> 说明：这里是项目清单版 — 项目以链接形式收录，不把上游仓库的代码本体复制进来。点击项目名即可跳转到原仓库。

## 最新一期：2026-10-24（2026-10-18 至 2026-10-24）

- 完整周报：[reports/2026-10-24/github-weekly-2026-10-24.md](reports/2026-10-24/github-weekly-2026-10-24.md)

本周主线：几乎所有榜单都被 AI Agent / 编程助手占领。
1. Agent 工程从拼功能转向拼成本 — context-mode、xerj、ECC、caveman 都在让 Agent 少读、少写、少烧 Token。
2. 插件 / 技能分发制度化 — Anthropic 官方插件目录上线，方法论和科研流程被做成可安装的技能包。
3. 推理与创作工具回落本地 — DeepInfer、VoiceStudio、ComfyUI 等强调本地运行，并预留 Agent 接口。

### 全站总榜 Top 5

| # | 项目 | 说明 |
|---|------|------|
| 1 | [morluto/rea](https://github.com/morluto/rea) | 让 Agent 做逆向工程，从应用行为一路分析到原生二进制 |
| 2 | [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) | Anthropic 官方维护的 Claude Code 插件目录 |
| 3 | [ruvnet/ruflo](https://github.com/ruvnet/ruflo) | 多 Agent 集群 / 工作流 harness，带自适应记忆、RAG |
| 4 | [android/skills](https://github.com/android/skills) | Android 官方技能库 |
| 5 | [anomalyco/opencode](https://github.com/anomalyco/opencode) | 开源编程 Agent |

### Python / AI 与数据 Top 5

| # | 项目 | 说明 |
|---|------|------|
| 1 | [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) | Claude Code 官方插件目录 |
| 2 | [HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything) | 让所有软件都变成 Agent-Native 的 CLI 工具集 |
| 3 | [Comfy-Org/ComfyUI](https://github.com/Comfy-Org/ComfyUI) | 模块化扩散模型 GUI / API / 后端，节点图界面 |
| 4 | [debpalash/VoiceStudio](https://github.com/debpalash/VoiceStudio) | 完全本地的 ElevenLabs 替代品，语音克隆/配音/转写，646 种语言 |
| 5 | [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) | 把 Agent 变成 AI 科学家，177 个科研技能 + 100+ 科学数据库 |

### TypeScript / 前端与 Agent 工具 Top 5

| # | 项目 | 说明 |
|---|------|------|
| 1 | [morluto/rea](https://github.com/morluto/rea) | Agent 逆向工程工具 |
| 2 | [ruvnet/ruflo](https://github.com/ruvnet/ruflo) | Agent 集群 harness |
| 3 | [anomalyco/opencode](https://github.com/anomalyco/opencode) | 开源编程 Agent |
| 4 | [stablyai/orca](https://github.com/stablyai/orca) | 统一管理一队编程 Agent 的平台，支持桌面、移动和远程 |
| 5 | [cursor/plugins](https://github.com/cursor/plugins) | Cursor 插件规范和官方插件 |

### JavaScript Top 5

| # | 项目 | 说明 |
|---|------|------|
| 1 | [michael-denyer/pstack-claude](https://github.com/michael-denyer/pstack-claude) | 把 pstack 严谨 Agent 工作流移植到多个 harness |
| 2 | [hmjz100/LinkSwift](https://github.com/hmjz100/LinkSwift) | 网盘直链下载工具，支持八大网盘 |
| 3 | [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill) | 让编程 Agent 做多阶段安全审计，独立验证、机器可读 |
| 4 | [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail) | 让 Agent 像“最懒的资深工程师”一样思考 |
| 5 | [plugin87/ux-ui-agent-skills](https://github.com/plugin87/ux-ui-agent-skills) | 把 Claude 变成资深设计架构师的 UI/UX 技能包 |

### Rust / 系统工具 Top 5

| # | 项目 | 说明 |
|---|------|------|
| 1 | [akitaonrails/ai-memory](https://github.com/akitaonrails/ai-memory) | 给编程 Agent CLI 做长期记忆，支持厂商间交接 |
| 2 | [xerj-org/xerj](https://github.com/xerj-org/xerj) | 本地优先搜索引擎 + MCP Server，单个 Rust 二进制做混合检索 |
| 3 | [oven-sh/bun](https://github.com/oven-sh/bun) | 极快的 JavaScript 运行时、打包器、测试器和包管理器 |
| 4 | [mixelpixx/Konnect](https://github.com/mixelpixx/Konnect) | AI 辅助 PCB 设计，KiCad 10 原生 Rust 插件 |
| 5 | [GCWing/OpenBitFun](https://github.com/GCWing/OpenBitFun) | Rust 高性能 Agent 运行时 + 桌面应用 |

### Go / 云原生与 AI 服务 Top 5

| # | 项目 | 说明 |
|---|------|------|
| 1 | [ollama/ollama](https://github.com/ollama/ollama) | 本地跑 Kimi、GLM、DeepSeek、Qwen、Gemma 等模型 |
| 2 | [gitleaks/gitleaks](https://github.com/gitleaks/gitleaks) | 扫描代码和提交里的密钥泄漏 |
| 3 | [mudler/LocalAI](https://github.com/mudler/LocalAI) | 开源本地 AI 引擎，无 GPU 也可跑 LLM/视觉/语音/图像/视频 |
| 4 | [etcd-io/etcd](https://github.com/etcd-io/etcd) | 分布式可靠键值存储 |
| 5 | [Asymptote-Labs/agent-beacon](https://github.com/Asymptote-Labs/agent-beacon) | 跨 harness 的 Agent 自改进记忆层 |

### Java / Android 与逆向 Top 5

| # | 项目 | 说明 |
|---|------|------|
| 1 | [NationalSecurityAgency/ghidra](https://github.com/NationalSecurityAgency/ghidra) | NSA 开源软件逆向工程（SRE）框架 |
| 2 | [HMCL-dev/HMCL](https://github.com/HMCL-dev/HMCL) | 多功能、跨平台的 Minecraft 启动器 |
| 3 | [iBotPeaches/Apktool](https://github.com/iBotPeaches/Apktool) | Android APK 逆向工程工具 |
| 4 | [AbdurazaaqMohammed/MP-Manager](https://github.com/AbdurazaaqMohammed/MP-Manager) | 专注 APK 的双栏 Android 文件管理器 |
| 5 | [modelcontextprotocol/java-sdk](https://github.com/modelcontextprotocol/java-sdk) | Model Context Protocol 官方 Java SDK，与 Spring AI 合作维护 |

## 往期周报

| 日期 | 完整周报 |
|------|----------|
| 2026-10-24 | [reports/2026-10-24/github-weekly-2026-10-24.md](reports/2026-10-24/github-weekly-2026-10-24.md) |

## 数据来源

- GitHub Trending 官方周榜：https://github.com/trending?since=weekly 及各语言子榜
- 排名以官方周榜展示顺序为准；星数/增星来自第三方汇总站快照，不同来源因抓取时间不同会有差异
- 项目自述的性能数字均为项目方自家基准，未经第三方复现
