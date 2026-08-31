# Ant Newman

CEO, Tortoise AI | 20 years getting AI into production

I build AI for environments where failure is not an option: defence, nuclear, aviation, and now live sports broadcasting.

When the frameworks I need don't exist, I build them open source.

---

## Frameworks

**[ARMM (Agent Readiness Maturity Model)](https://tortoiseai.co.uk/armm)**  
Assessing organisational readiness to deploy AI agents in production.  
Four dimensions. Five levels. Weakest-link principle. CC BY 4.0.

**Decision Latency Framework** *(coming 2026)*  
A scoring methodology for knowing how much time a decision should take.

---

## Open Source Projects

**[pda-platform](https://github.com/antnewman/pda-platform)**  
Open infrastructure for AI-enabled project delivery. Universal PM data parser, MCP servers for Claude integration, AI reliability tooling. MIT.

**[agent-task-planning](https://pypi.org/project/agent-task-planning/)**  
AI reliability framework with confidence extraction and outlier mining. Multi-provider. Production guardrails. MIT.

**[pm-data-tools](https://pypi.org/project/pm-data-tools/)**  
Universal parser for project management data. 8 formats + NISTA. MIT.

**[ARMM Assessment Tool](https://tortoiseai.co.uk/armm)**  
Interactive self-assessment across 251 criteria. AGPL-3.0.

**[Universal Dashboard Specification](https://github.com/Tortoise-AI/uds)**  
Vendor-neutral declarative format for AI-native analytical dashboards. Apache 2.0.

---

## Contributions to AI safety tooling

**[inspect_ai](https://github.com/UKGovernmentBEIS/inspect_ai)** — the UK AI Safety Institute's LLM evaluation framework.

Merged:

- [Atomic log file writes](https://github.com/UKGovernmentBEIS/inspect_ai/pull/3950) — eval logs no longer corrupt when a run fills the disk or is interrupted mid-write.
- [`aggregate(key, agg=...)` metric factory](https://github.com/UKGovernmentBEIS/inspect_ai/pull/3850) — per-key aggregation for metrics computed over grouped samples.
- [Warn when task arguments are entirely unconsumed](https://github.com/UKGovernmentBEIS/inspect_ai/pull/4224) — surfaces silently ignored arguments instead of running an evaluation that quietly differs from the one asked for.
- [Fix the MMLU CLI command on the Evals page](https://github.com/UKGovernmentBEIS/inspect_ai/pull/3852).

In review:

- [Distinguish `math()` answer-extraction failures from wrong answers via `Score.reason`](https://github.com/UKGovernmentBEIS/inspect_ai/pull/4091) — an unparseable answer and an incorrect one currently score the same.

**[inspect_evals](https://github.com/UKGovernmentBEIS/inspect_evals)** — the companion suite of published evaluations.

In review:

- [Flag model roles that can silently fall back to the model under evaluation](https://github.com/UKGovernmentBEIS/inspect_evals/pull/2321) — a lint check for graders that, left unconfigured, end up grading their own output.
- [Make the grader configurable via the grader model role](https://github.com/UKGovernmentBEIS/inspect_evals/pull/2172) across agieval, math and frontierscience.
- [Fix a `UnicodeDecodeError` that stops the lint tool running on Windows](https://github.com/UKGovernmentBEIS/inspect_evals/pull/2322).

**[inspect_scout](https://github.com/meridianlabs-ai/inspect_scout)** — in-depth analysis of AI agent transcripts.

In review:

- [Collect concurrent scan reads with `tg_collect`](https://github.com/meridianlabs-ai/inspect_scout/pull/587) — moves the remaining `asyncio.gather` call sites onto the project's structured-concurrency helper.

---

## Published Work

**[Verified Autonomy: A Field Guide to Engineering Trust in AI Systems](https://doi.org/10.5281/zenodo.19096229)** (May 2026)  
A field guide for engineering trust into production AI systems, covering calibration, conformal prediction, audit trails, and constrained autonomy. Ant Newman, Shanti Greene, Malia Hosseini, Philip Kitchener, Rainier Potgieter, Hadley Christoffels. Companion repo: [verified-autonomy](https://github.com/antnewman/verified-autonomy).  
CC BY 4.0 (content), MIT (code).

**[From Policy to Practice: An Open Framework for AI-Ready Project Delivery](https://doi.org/10.5281/zenodo.18711384)** (Feb 2026)  
An open framework for AI-ready project delivery. Ant Newman. Companion repo: [Project-Delivery-Toolkit](https://github.com/Tortoise-AI/Project-Delivery-Toolkit).  
CC BY 4.0.

**[Agent Readiness Maturity Model (ARMM) Framework v1.1](https://doi.org/10.5281/zenodo.18775086)** (Jan 2026)  
A maturity model that scores whether an organisation is ready to deploy AI agents in production, applying a weakest-link rule across four dimensions and five levels. Ant Newman. Interactive tool: [tortoiseai.co.uk/armm](https://tortoiseai.co.uk/armm).  
CC BY 4.0.

**[The Sharon Instability Theorem: Generic Instability of the M-Invariant](https://doi.org/10.5281/zenodo.18777394)** (Dec 2025)  
Proves the M-invariant in multiparameter persistence is generically unstable, resolving an open question in the field. Ant Newman. Companion repo: [sharon-instability](https://github.com/Tortoise-AI/sharon-instability).  
CC BY 4.0.

---

## Writing

I publish on AI deployment, decision-making under complexity, and what production-grade reliability actually requires. I also write Radical Productivity, a weekly Substack on productivity systems and inclusion.

[Radical Productivity](https://antnewman.substack.com) · [LinkedIn](https://linkedin.com/in/ant-newman) · [tortoiseai.co.uk/insights](https://tortoiseai.co.uk/insights)

---

## Contact

antjsnewman@outlook.com  
[tortoiseai.co.uk](https://tortoiseai.co.uk)
