<div align="center">

# Lucas Chang

**Independent developer · AI systems engineering · Computational finance**

Building local-first AI software, information systems, and engineering infrastructure.
Studying Finance at Shanghai Normal University; learning mathematics and computer science alongside independent development.

[简体中文](README.zh-CN.md) · [Projects](#selected-projects) · [Codex contributions](#upstream-contributions-to-openai-codex) · [Engineering evidence](#engineering-evidence)

</div>

---

## Selected projects

### [FlowTracer](https://github.com/lucaschang2021/FlowTracer) — AI information acquisition & opportunity discovery

**Status: Alpha integration / acceptance; not publicly released.**

A Windows desktop intelligence workspace built around **Radar → Source → acquisition → Signals → Memory / Opportunities / notifications**. It is designed to help users monitor changing information sources and surface relevant findings.

- **Stack:** Python, FastAPI, Celery, PostgreSQL/pgvector, Redis, Tauri 2, React, TypeScript.
- **Verified engineering milestones:** Static/Native backend handoff accepted; the documented independent backend baseline passed **504 tests at 89.49% coverage**. A separate Windows desktop G4 candidate passed **71 UI tests** and local installation/start/reopen checks.
- **Still in progress:** end-to-end native integration, reliable cleanup, live-source and production-provider acceptance, interactive onboarding, and release.

**Evidence:** [Current stage gate](https://github.com/lucaschang2021/FlowTracer/blob/main/docs/CURRENT-GATE.md) · [Backend independent acceptance](https://github.com/lucaschang2021/FlowTracer/blob/main/docs/78-ACQ1-INDEPENDENT-ACCEPTANCE.md) · [Desktop release candidate](https://github.com/lucaschang2021/FlowTracer/blob/main/frontend/RELEASE-CANDIDATE.md)

### [Möbius](https://github.com/lucaschang2021/Mobius) — Engineering governance for AI-assisted software development

**Status: pre-alpha / architecture-first.** Defines architecture contracts, change authority, evidence gates, repository workflows, and review boundaries for coding agents. **Codex-first, not Codex-only**; the project is about governing engineering changes, not merely orchestrating agents.

### [Rasputin](https://github.com/lucaschang2021/Rasputin) — Computational capital & AI execution control

**Status: architecture and early executable contracts.** Exploring how workloads, model/tool/compute budgets, policy, outcome evidence, and recovery can be governed across heterogeneous AI execution resources. Design ambitions are not presented as shipped capabilities.

### Other open-source work

- **[Gallop](https://github.com/lucaschang2021/gallop)** — Local-first, evidence-driven learning continuity and mentorship infrastructure, with an append-only journal, provenance-aware learning evidence, recovery, and Obsidian projections. The repository documents a **v1.2 source baseline**; source, tags, and releases have distinct statuses.
- **[FinTerminal](https://github.com/lucaschang2021/finterminal)** — An early-stage, Apache-2.0 local-first financial research toolkit with MCP, quantitative analysis, retrieval, and data provenance. Includes [contribution guidelines](https://github.com/lucaschang2021/finterminal/blob/main/CONTRIBUTING.md), CI, and [release-workflow PRs](https://github.com/lucaschang2021/finterminal/pull/9).

## Upstream contributions to OpenAI Codex

I participate in **public technical discussions and bug investigations** in [openai/codex](https://github.com/openai/codex). These are issue analyses and reproduction reports, **not claims of merged upstream code or official maintainer status**.

| Discussion | My contribution |
| --- | --- |
| [#45974 — long-running jobs and inference polling](https://github.com/openai/codex/issues/45974#issuecomment-5706485793) | Analyzed goal continuation and background-process lifecycle; proposed event-driven waiting and regression criteria to avoid spending model inference on deterministic polling. |
| [#32188 — background completion wakeups](https://github.com/openai/codex/issues/32188#issuecomment-5707525658) | Traced subagent completion watchers and suggested bounded, exactly-once parent wakeup registration. |
| [#17179 — Windows sandbox ownership/ACL failures](https://github.com/openai/codex/issues/17179#issuecomment-5460612183) | Supplied a reproducible Windows diagnostic case, permission evidence, elevated/unelevated comparison, and a documented workaround. |

My interests in coding-agent runtimes include **execution lifecycle, resource efficiency, correctness under concurrency, and observable recovery**.

## Engineering evidence

Rather than treating architectural plans or test counts as proof of a finished product, I try to keep implementation, verification, and release status separate.

- **Reproducible checkpoints:** tests, code commits, failure records, migrations, and build artifacts are tied to explicit revisions where available.
- **Explicit capability boundaries:** offline/fake-provider evidence is not represented as live production integration; accepted stages do not imply a public release.
- **Governed changes:** architectural constraints, security assumptions, review authority, and rollback/recovery are part of the development process.

## Research interests

- **AI systems:** adaptive information acquisition, memory, coding-agent infrastructure, execution governance.
- **AI economics:** measuring effective compute, inference cost, resource allocation, and outcome value.
- **Finance × statistics:** empirical economics, quantitative research, and reproducible financial analysis.

<details>
<summary>Languages & tooling</summary>

Python · TypeScript · React · FastAPI · Tauri · PostgreSQL · Redis · Docker · Git/GitHub Actions · pytest · Ruff · Rust tooling

</details>

---

<div align="center">

**Build useful systems. Make the work verifiable.**

[GitHub](https://github.com/lucaschang2021) · [FlowTracer](https://github.com/lucaschang2021/FlowTracer) · [Möbius](https://github.com/lucaschang2021/Mobius) · [Gallop](https://github.com/lucaschang2021/gallop)

<sub>Independent community contributions do not imply employment, endorsement, or official affiliation with OpenAI or any other organization.</sub>

</div>
