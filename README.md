<div align="center">

# Lucas Chang

**AI Systems · Information Infrastructure · Engineering Governance**

Independent developer · Finance undergraduate at Shanghai Normal University

[中文](README.zh-CN.md) · [GitHub projects](https://github.com/lucaschang2021?tab=repositories) · [Upstream technical discussions](#upstream-codex-contributions)

*Build useful systems. Make the work verifiable.*

</div>

---

## What I'm building

I work at the intersection of **AI systems engineering, reliable automation, and computational economics**. My focus is on software that can acquire information, govern engineering changes, and allocate limited computational resources—with explicit boundaries between **implemented behavior, verified evidence, and future plans**.

| Project | Focus | Current stage |
| :--- | :--- | :--- |
| **[FlowTracer](https://github.com/lucaschang2021/FlowTracer)** | Adaptive information acquisition and opportunity discovery; Radar, Sources, Signals, Memory, Opportunities, and desktop delivery | **Alpha integration** · not released |
| **[Möbius](https://github.com/lucaschang2021/Mobius)** | Architecture contracts, change governance, evidence-based verification, and controlled AI-assisted engineering | **Pre-alpha / architecture-first** |
| **[Rasputin](https://github.com/lucaschang2021/Rasputin)** | Computational-capital allocation, policy authority, execution control, and outcome-driven recovery | **Architecture & early executable contracts** |
| **[Gallop](https://github.com/lucaschang2021/gallop)** | Local-first, evidence-driven learning continuity and progressive mentorship | **Open-source v1.2 code baseline** |
| **[FinTerminal](https://github.com/lucaschang2021/finterminal)** | Local-first financial research toolkit with MCP, quantitative workflows, and data provenance | **Early-stage open source** |

### Featured: FlowTracer

A Windows desktop intelligence system built around user-defined **Radars**: collect RSS/URL sources, preserve source evidence, analyze and score content, and surface information through Signals, Memory, and Opportunities.

- **Backend:** Python · FastAPI · Celery · PostgreSQL/pgvector · Redis
- **Desktop:** Tauri 2 · React · TypeScript · a navigable galaxy-style workspace
- **Evidence:** [independent backend acceptance](https://github.com/lucaschang2021/FlowTracer/blob/main/docs/78-ACQ1-INDEPENDENT-ACCEPTANCE.md) (historical: **504 tests**, **89.49% coverage**) and [G4 desktop candidate acceptance](https://github.com/lucaschang2021/FlowTracer/blob/main/docs/FE-001-G4-ADMISSION.md) (historical: **71/71 UI tests**)
- **Still in progress:** native end-to-end integration, real-provider/public-internet acceptance, onboarding, and release. Test results belong to their recorded commits; they are not a claim of production readiness.

[Repository](https://github.com/lucaschang2021/FlowTracer) · [Current stage gate](https://github.com/lucaschang2021/FlowTracer/blob/main/docs/CURRENT-GATE.md)

## Upstream Codex contributions

I participate in technical discussions in **[openai/codex](https://github.com/openai/codex)**, especially runtime scheduling, background work, and Windows sandbox reliability. Selected public evidence:

| Discussion | My contribution |
| :--- | :--- |
| [#45974 — background polling and inference usage](https://github.com/openai/codex/issues/45974#issuecomment-5706485793) | Traced goal-continuation/watcher boundaries; proposed event-driven waits and regression invariants to avoid inference-only polling. |
| [#32188 — event-driven completion wakeups](https://github.com/openai/codex/issues/32188#issuecomment-5707525658) | Examined subagent completion watchers and proposed an opt-in, exactly-once parent wake-up contract. |
| [#17179 — Windows sandbox ACL failure](https://github.com/openai/codex/issues/17179#issuecomment-5460612183) | Reported a reproducible Windows ACL/ownership failure with logs, an elevated/unelevated A/B comparison, and a workaround. |

These are **public issue analyses and debugging contributions**, not a claim of merged upstream code, official maintainer status, employment, or OpenAI endorsement.

## How I engineer

```text
Problem → Architecture / contracts → Implementation → Tests
        → Independent review → Evidence → Controlled release
```

I care about reproducibility, explicit failure states, reviewable changes, source attribution, access boundaries, and honest reporting of what is and is not verified.

My open-source work includes [Gallop](https://github.com/lucaschang2021/gallop) (Apache-2.0, evidence-oriented learning systems) and [FinTerminal](https://github.com/lucaschang2021/finterminal) (Apache-2.0, CI, release and contribution workflows). I welcome focused issues, reproducible bug reports, and technical feedback.

## Research interests

**AI systems & economics:** measuring effective compute, model/token economics, inference efficiency, resource allocation, and verification cost.

**Finance & quantitative research:** statistics, econometrics, market data, and reproducible computational research.

---

<div align="center">

**Code is a starting point. Evidence is what makes it credible.**

[FlowTracer](https://github.com/lucaschang2021/FlowTracer) · [Möbius](https://github.com/lucaschang2021/Mobius) · [Rasputin](https://github.com/lucaschang2021/Rasputin) · [Gallop](https://github.com/lucaschang2021/gallop)

</div>
