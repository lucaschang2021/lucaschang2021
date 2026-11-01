<div align="center">

# Lucas Chang

**AI 系统 · 信息基础设施 · 工程治理**

独立开发者 · 上海师范大学金融学本科生

[English](README.md) · [项目仓库](https://github.com/lucaschang2021?tab=repositories) · [Codex 技术贡献](#codex-上游技术贡献)

*构建有用的系统，让成果能够被验证。*

</div>

---

## 我正在构建什么

我关注 **AI 系统工程、可靠自动化与计算经济学** 的交叉：构建能够获取信息、治理软件变更、合理配置有限算力资源的系统。尤其重视将 **已实现功能、已经核实的证据与未来规划** 严格区分。

| 项目 | 方向 | 当前阶段 |
| :--- | :--- | :--- |
| **[FlowTracer](https://github.com/lucaschang2021/FlowTracer)** | 自适应信息获取与机会发现；Radar、Source、Signal、Memory、Opportunity 与桌面交付 | **Alpha 集成阶段** · 尚未发布 |
| **[Möbius](https://github.com/lucaschang2021/Mobius)** | 架构契约、变更治理、证据验证与受控 AI 软件工程 | **Pre-alpha / 架构先行** |
| **[Rasputin](https://github.com/lucaschang2021/Rasputin)** | 计算资本配置、策略授权、执行控制与结果驱动恢复 | **架构与早期可执行契约** |
| **[Gallop](https://github.com/lucaschang2021/gallop)** | 本地优先、证据驱动的学习连续性与渐进式导师系统 | **开源 v1.2 源码基线** |
| **[FinTerminal](https://github.com/lucaschang2021/finterminal)** | MCP、量化研究与数据溯源的本地金融研究工具 | **早期开源项目** |

### 重点项目：FlowTracer

围绕用户定义的 **Radar** 构建 Windows 桌面情报系统：采集 RSS/URL 信息源、保存原始证据、分析与评分内容，并通过 Signal、Memory 和 Opportunity 呈现高价值信息。

- **后端：** Python · FastAPI · Celery · PostgreSQL/pgvector · Redis
- **桌面端：** Tauri 2 · React · TypeScript · 星图式导航工作台
- **可核验证据：** [后端独立验收记录](https://github.com/lucaschang2021/FlowTracer/blob/main/docs/78-ACQ1-INDEPENDENT-ACCEPTANCE.md)（历史记录 **504 项测试通过、89.49% 覆盖率**）；[G4 桌面候选验收](https://github.com/lucaschang2021/FlowTracer/blob/main/docs/FE-001-G4-ADMISSION.md)（历史记录 **71/71 项 UI 测试通过**）
- **尚未完成：** 完整原生业务集成、真实服务商与公网采集验收、交互式教程和正式发布。历史测试数据对应特定提交，不代表生产就绪。

[查看仓库](https://github.com/lucaschang2021/FlowTracer) · [当前阶段闸门](https://github.com/lucaschang2021/FlowTracer/blob/main/docs/CURRENT-GATE.md)

## Codex 上游技术贡献

我参与 **[openai/codex](https://github.com/openai/codex)** 的公开技术讨论，主要关注运行时调度、后台任务完成事件和 Windows Sandbox 可靠性。以下内容均可直接核对：

| 讨论 | 我的具体工作 |
| :--- | :--- |
| [#45974 — 长任务轮询与模型额度消耗](https://github.com/openai/codex/issues/45974#issuecomment-5706485793) | 分析 Goal Continuation / Watcher 边界，提出事件驱动等待机制与回归约束，减少无效推理轮询。 |
| [#32188 — 后台任务完成唤醒](https://github.com/openai/codex/issues/32188#issuecomment-5707525658) | 分析 Subagent 完成事件与父线程唤醒路径，提出按需注册、恰好一次触发的改进思路。 |
| [#17179 — Windows Sandbox ACL 故障](https://github.com/openai/codex/issues/17179#issuecomment-5460612183) | 提供故障日志、权限对照实验、可复现症状和有效的临时解决办法。 |

以上属于**公开 Issue 技术分析与调试贡献**，不代表代码已被上游合并，也不代表 OpenAI 官方维护者、雇员或合作伙伴身份。

## 我的工程方法

```text
问题 → 架构 / 契约 → 实现 → 测试
     → 独立审查 → 证据 → 受控发布
```

我重视可复现性、明确的失败状态、可审查的变更、来源溯源、权限边界，以及对未验证能力的如实说明。

我的开源工作还包括 [Gallop](https://github.com/lucaschang2021/gallop)（Apache-2.0、学习证据与连续性系统）和 [FinTerminal](https://github.com/lucaschang2021/finterminal)（Apache-2.0、CI 与发布流程）。欢迎针对具体技术问题提交 Issue、复现记录和改进建议。

## 研究兴趣

**AI 系统与经济学：** 有效算力计量、模型与 Token 经济学、推理效率、计算资源配置和验证成本。

**金融与量化研究：** 统计、计量经济学、市场数据与可复现计算研究。

---

<div align="center">

**代码是起点，证据使成果可信。**

[FlowTracer](https://github.com/lucaschang2021/FlowTracer) · [Möbius](https://github.com/lucaschang2021/Mobius) · [Rasputin](https://github.com/lucaschang2021/Rasputin) · [Gallop](https://github.com/lucaschang2021/gallop)

</div>
