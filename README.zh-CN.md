<div align="center">

# Lucas Chang

**独立开发者 · AI 系统工程 · 计算金融**

构建本地优先的 AI 软件、信息系统与工程基础设施。
上海师范大学金融学本科在读，同时学习数学、计算机科学，并开展独立软件开发。

[English](README.md) · [代表项目](#代表项目) · [Codex 上游贡献](#参与-openai-codex-上游技术讨论) · [工程证据](#工程证据)

</div>

---

## 代表项目

### [FlowTracer](https://github.com/lucaschang2021/FlowTracer) — 自适应信息获取与机会发现引擎

**状态：Alpha 集成验收阶段，尚未正式发布。**

Windows 桌面 AI 情报工作台，围绕 **Radar → Source → 采集 → Signals → Memory / Opportunities / 通知** 构建，旨在持续关注动态信息源，识别与沉淀有价值的信息。

- **技术栈：** Python、FastAPI、Celery、PostgreSQL/pgvector、Redis、Tauri 2、React、TypeScript。
- **已记录的工程证据：** Static/Native 后端通过独立交接验收，指定历史基线 **504 项测试通过、覆盖率 89.49%**；另有 Windows G4 桌面候选 **71 项 UI 测试通过**及本地安装、启动、重开证据。
- **尚待完成：** 完整原生集成业务闭环、自动清理可靠性、真实信息源与商业模型验收、交互式引导和正式发布。

**证据入口：** [当前阶段闸门](https://github.com/lucaschang2021/FlowTracer/blob/main/docs/CURRENT-GATE.md) · [后端独立验收](https://github.com/lucaschang2021/FlowTracer/blob/main/docs/78-ACQ1-INDEPENDENT-ACCEPTANCE.md) · [桌面发行候选记录](https://github.com/lucaschang2021/FlowTracer/blob/main/frontend/RELEASE-CANDIDATE.md)

### [Möbius](https://github.com/lucaschang2021/Mobius) — AI 软件工程治理

**状态：Pre-alpha，架构先行。** 探索以架构合同、变更授权、测试证据、仓库工作流和审查边界治理 AI coding agents 对软件系统的持续修改。**Codex-first，而非 Codex-only**；核心不是简单的多 Agent 编排。

### [Rasputin](https://github.com/lucaschang2021/Rasputin) — 计算资本与 AI 执行控制

**状态：架构与早期可执行合同。** 研究如何在预算、模型/工具/算力限制、策略权限和风险约束下配置 AI 工作负载，并使用真实结果与恢复机制反馈决策。架构目标不等于已经交付的功能。

### 其他开源作品

- **[Gallop](https://github.com/lucaschang2021/gallop)** — 本地优先、证据驱动的学习连续性与导师治理基础设施，涵盖追加式 Journal、证据来源区分、恢复及 Obsidian 投影。仓库记载 **v1.2 源码基线**；不混淆源码、Tag 与正式 Release 的状态。
- **[FinTerminal](https://github.com/lucaschang2021/finterminal)** — Apache-2.0 许可的早期本地金融研究工具，包含 MCP、量化分析、检索和数据溯源；已有 [贡献指南](https://github.com/lucaschang2021/finterminal/blob/main/CONTRIBUTING.md)、CI 和 [发行流程 PR](https://github.com/lucaschang2021/finterminal/pull/9)。

## 参与 OpenAI Codex 上游技术讨论

我在 [openai/codex](https://github.com/openai/codex) 参与过**公开技术讨论、源码分析及故障复现**。以下属于 Issue 技术贡献，**不代表已有合并的上游代码 PR，也不代表 OpenAI 官方维护者身份**。

| 讨论 | 我的贡献 |
| --- | --- |
| [#45974 — 长任务推理轮询与额度消耗](https://github.com/openai/codex/issues/45974#issuecomment-5706485793) | 分析 Goal Continuation 与后台任务生命周期，提出事件驱动等待及回归测试思路，避免用模型推理进行确定性轮询。 |
| [#32188 — 后台任务完成唤醒](https://github.com/openai/codex/issues/32188#issuecomment-5707525658) | 分析子 Agent 完成监听器，提出有界且避免重复唤醒的父 Agent 完成通知方案。 |
| [#17179 — Windows Sandbox 所有权与 ACL 问题](https://github.com/openai/codex/issues/17179#issuecomment-5460612183) | 提供 Windows 可复现诊断、权限证据、Elevated/Unelevated 对照及有效缓解方法。 |

我重点关注 coding-agent runtime 的**执行生命周期、资源效率、并发正确性与可观测恢复**。

## 工程证据

我尽量将设计计划、实际实现、历史验收与正式发布严格区分，而不是只展示项目概念或测试数量。

- **可追溯检查点：** 在可行时将测试、代码提交、失败记录、迁移与构建产物绑定到明确版本。
- **明确能力边界：** 离线/Fake Provider 测试不等于真实生产接入；阶段验收不等于正式发布。
- **受治理的变更：** 在研发过程中重视架构约束、安全边界、审查授权与失败恢复。

## 研究兴趣

- **AI 系统：** 自适应信息获取、记忆、coding-agent 基础设施、执行治理。
- **AI 经济学：** 有效算力计量、推理成本、计算资源配置与结果价值。
- **金融 × 统计：** 实证经济学、量化研究与可复现的金融分析。

<details>
<summary>语言与工具</summary>

Python · TypeScript · React · FastAPI · Tauri · PostgreSQL · Redis · Docker · Git/GitHub Actions · pytest · Ruff · Rust 工具链

</details>

---

<div align="center">

**Build useful systems. Make the work verifiable.**  
**构建有用的系统，让成果可以被验证。**

[GitHub](https://github.com/lucaschang2021) · [FlowTracer](https://github.com/lucaschang2021/FlowTracer) · [Möbius](https://github.com/lucaschang2021/Mobius) · [Gallop](https://github.com/lucaschang2021/gallop)

<sub>独立的社区贡献不代表与 OpenAI 或其他机构存在雇佣、官方背书或官方关联。</sub>

</div>
