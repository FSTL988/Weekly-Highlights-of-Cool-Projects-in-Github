# GitHub 热门项目周报 — 最近一周

**时间窗口：** 2026-10-18 至 2026-10-24（GitHub Trending `since=weekly`）
**查证时间：** 2026-10-24 13:54 CST（Asia/Shanghai）
**口径说明：** 排名以 GitHub 官方 Trending 周榜展示顺序为准；本周增星数引用第三方汇总站快照（2026-10-24 12:55 北京时间），不同汇总站因抓取时间不同，增星数会有差异。

---

## 本周总览

这一周的主线非常明确：几乎所有榜单都被 AI Agent / 编程助手占领。

1. **Agent 工程从拼功能转向拼成本** — context-mode、xerj、ECC、caveman 都在解决同一件事：让 Agent 少读、少写、少烧 Token。脉络窗口是有限资源，工具输出和文件读取是最大的消耗来源。
2. **插件 / 技能分发制度化** — Anthropic 推出官方插件目录，superpowers 把开发方法论做成可安装物件，K-Dense-AI 把科研流程收拢成 177 个技能。
3. **推理与创作工具同步落到本地** — DeepSeek 的 DeepInfer、TokenSpeed、VoiceStudio、ComfyUI、FilmCraft 都强调本地运行，并预留 Agent 可调用的接口。

---

## 1. 全站总榜 Top 5

| # | 项目 | 语言 | 说明 |
|---|------|------|------|
| 1 | morluto/rea | TypeScript | 让 Agent 做逆向工程，从应用行为一路分析到原生二进制。本周新增约 88,243 星（第三方汇总口径） |
| 2 | anthropics/claude-plugins-official | Python | Anthropic 官方维护的 Claude Code 插件目录。本周新增约 4,250 星 |
| 3 | ruvnet/ruflo | TypeScript | 多 Agent 集群 / 工作流 harness，带自适应记忆、自学习、联邦协作、向量 RAG，集成 Claude Code / Codex / Hermes 等 |
| 4 | android/skills | Kotlin | Android 官方技能库。本周新增约 1,471 星 |
| 5 | anomalyco/opencode | TypeScript | 开源编程 Agent。本周新增约 6,765 星 |

紧随其后：stablyai/orca（本周 +9,545）、cursor/plugins、akitaonrails/ai-memory、HKUDS/CLI-Anything、Comfy-Org/ComfyUI、debpalash/VoiceStudio、heygen-com/hyperframes、K-Dense-AI/scientific-agent-skills、NationalSecurityAgency/ghidra。

> 注：另一个按纯增星排序的周榜（2026-10-23）前五为：rea、orca、hyperframes、claude-plugins-official、ghidra，排序差异来自口径和抓取时间。

项目链接：
- https://github.com/morluto/rea
- https://github.com/anthropics/claude-plugins-official
- https://github.com/ruvnet/ruflo
- https://github.com/android/skills
- https://github.com/anomalyco/opencode

---

## 2. Python / AI 与数据 Top 5

1. **anthropics/claude-plugins-official** — Claude Code 官方插件目录
   https://github.com/anthropics/claude-plugins-official
2. **HKUDS/CLI-Anything** — “让所有软件都变成 Agent-Native” 的 CLI 工具集，CLI-Hub: clianything.cc
   https://github.com/HKUDS/CLI-Anything
3. **Comfy-Org/ComfyUI** — 模块化扩散模型 GUI / API / 后端，节点图界面，本地推理
   https://github.com/Comfy-Org/ComfyUI
4. **debpalash/VoiceStudio** — 完全本地的 ElevenLabs 替代品，语音克隆、语音设计、视频配音、听写、转写与有声书，支持 646 种语言
   https://github.com/debpalash/VoiceStudio
5. **K-Dense-AI/scientific-agent-skills** — 把 Agent 变成 AI 科学家，177 个已验证科研技能 + 100+ 科学数据库，覆盖生物、化学、医学、药物发现，兼容 Cursor / Claude Code / Codex 等
   https://github.com/K-Dense-AI/scientific-agent-skills

后面值得注意：vllm-project/vllm、fastapi/fastapi、sgl-project/sglang、yt-dlp/yt-dlp 持续上榜。

---

## 3. TypeScript / 前端与 Agent 工具 Top 5

1. **morluto/rea** — Agent 逆向工程工具
   https://github.com/morluto/rea
2. **ruvnet/ruflo** — Agent 集群 harness
   https://github.com/ruvnet/ruflo
3. **anomalyco/opencode** — 开源编程 Agent
   https://github.com/anomalyco/opencode
4. **stablyai/orca** — 统一管理一队编程 Agent（Grok Bot、Claude Code 等）的平台，用自己的订阅运行，支持桌面、移动和远程运行时
   https://github.com/stablyai/orca
5. **cursor/plugins** — Cursor 插件规范和官方插件
   https://github.com/cursor/plugins

---

## 4. JavaScript Top 5

1. **michael-denyer/pstack-claude** — 把 pstack 的严谨 Agent 工作流移植到 Claude Code、Codex、Copilot、Pi、OpenCode、Gemini 等多个 harness
   https://github.com/michael-denyer/pstack-claude
2. **hmjz100/LinkSwift** — 网盘直链下载工具，支持百度网盘 / 阿里云盘 / 中国移动云盘 / 天翼云盘 / 迅雷云盘 / 夸克网盘 / UC网盘 / 123云盘八大网盘
   https://github.com/hmjz100/LinkSwift
3. **cloudflare/security-audit-skill** — 让编程 Agent 做多阶段安全审计，独立验证、机器可读的结果
   https://github.com/cloudflare/security-audit-skill
4. **DietrichGebert/ponytail** — 让 AI Agent 像“最懒的资深工程师”一样思考：最好的代码是你没写的代码
   https://github.com/DietrichGebert/ponytail
5. **plugin87/ux-ui-agent-skills** — 把 Claude 变成资深设计架构师：DTCG tokens、52 个组件、WCAG 2.2、138 个设计系统
   https://github.com/plugin87/ux-ui-agent-skills

---

## 5. Rust / 系统工具 Top 5

1. **akitaonrails/ai-memory** — 给编程 Agent CLI 做长期记忆，支持不同 Agent 厂商之间交接 handoff
   https://github.com/akitaonrails/ai-memory
2. **xerj-org/xerj** — 本地优先搜索引擎 + MCP Server，单个 Rust 二进制索引代码、文档、日志、JSONL/CSV、PDF，支持 BM25 全文、向量和混合搜索，兼容 Elasticsearch API
   https://github.com/xerj-org/xerj
3. **oven-sh/bun** — 极快的 JavaScript 运行时、打包器、测试器和包管理器，一体化
   https://github.com/oven-sh/bun
4. **mixelpixx/Konnect** — AI 辅助 PCB 设计，KiCad 10 原生 Rust 插件，217 个原理图/布局/布线/审查工具暴露给 LLM
   https://github.com/mixelpixx/Konnect
5. **GCWing/OpenBitFun** — Rust 高性能 Agent 运行时 + 精致桌面应用，兼具 Code Agent 深度和通用工作能力
   https://github.com/GCWing/OpenBitFun

---

## 6. Go / 云原生与 AI 服务 Top 5

1. **ollama/ollama** — 本地跑大模型：Kimi、GLM、MiniMax、DeepSeek、gpt-oss、Qwen、Gemma 等
   https://github.com/ollama/ollama
2. **gitleaks/gitleaks** — 扫描代码和提交里的密钥泄漏
   https://github.com/gitleaks/gitleaks
3. **mudler/LocalAI** — 开源本地 AI 引擎，跑 LLM、视觉、语音、图像、视频，任意硬件，无 GPU 也可
   https://github.com/mudler/LocalAI
4. **etcd-io/etcd** — 分布式可靠键值存储，用于分布式系统最关键的数据
   https://github.com/etcd-io/etcd
5. **Asymptote-Labs/agent-beacon** — 跨 harness 的 Agent 自改进记忆层
   https://github.com/Asymptote-Labs/agent-beacon

后面值得注意：gin-gonic/gin、helm/helm、vxcontrol/pentagi（自主渗透测试 Agent）、github/github-mcp-server、hashicorp/terraform。

---

## 7. Java / Android 与逆向 Top 5

*按 GitHub Trending Java 周榜展示顺序*

1. **NationalSecurityAgency/ghidra** — NSA 开源软件逆向工程（SRE）框架，本周 +4,221 星，是被 rea 带火的老牌项目
   https://github.com/NationalSecurityAgency/ghidra
2. **HMCL-dev/HMCL** — 多功能、跨平台的 Minecraft 启动器
   https://github.com/HMCL-dev/HMCL
3. **iBotPeaches/Apktool** — Android APK 逆向工程工具，本周 +660 星
   https://github.com/iBotPeaches/Apktool
4. **AbdurazaaqMohammed/MP-Manager** — 专注 APK 的双栏 Android 文件管理器
   https://github.com/AbdurazaaqMohammed/MP-Manager
5. **modelcontextprotocol/java-sdk** — Model Context Protocol 官方 Java SDK，与 Spring AI 合作维护
   https://github.com/modelcontextprotocol/java-sdk

Java 榜的特征很明显：逆向工程（ghidra、Apktool、jadx）和 Android / Minecraft 启动器占了大半。

---

## 值得 Xtop 亲自试的 4 个

结合你之前 Star 过的方向（AI/Agent 工具、本地模型、MCP）和你在做的项目：

1. **morluto/rea** — Agent + 逆向，新范式，看看它怎么用 Ghidra/Hopper 做后端
2. **HKUDS/CLI-Anything** — 把任何软件变成 Agent 可调用的 CLI，和 MCP 思路互补
3. **xerj-org/xerj** — Rust 单二进制本地搜索/RAG，省 Token 的思路对长上下文项目直接有用
4. **mksglu/context-mode**（TypeScript 榜第 15，本周周报重点项目）— 把工具输出关进沙箱，宣称 98% 上下文缩减，持久化会话记忆

---

## 数据来源

- GitHub Trending 官方周榜：https://github.com/trending?since=weekly 及各语言子榜（python / typescript / javascript / rust / go / java）
- 第三方汇总快照：gaojihao.github.io/github-hot/trending-weekly.html（更新于 2026-10-24 12:55 北京时间）
- CyberQ GitHub 趨勢周報 Vol.39（2026-10-23 查证）：https://cyberq.tw/2026/10/23/github-trends-weekly-report-vol-39-proxy/
- 韩文周榜汇总（2026-10-23，按增星排序）：https://blog.amuse.ing/github-trending-2026-10-23/

*说明：项目自述的性能数字（如 token 缩减、推理速度）均为项目方自家基准，未经第三方复现，导入前建议用自己的工作负载重测。*
