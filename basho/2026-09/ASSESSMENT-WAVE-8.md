# September 2026 Basho — Assessment Wave 8

**Assessment snapshot: 2026-09-13**

Status: **Evidence collection / provisional GPT fresh-read — upper-rank E4 review refreshed**

> **Audit status:** This is a provisional GPT working record. Canonical rules had been restored before this assessment, but field/identity cleanup and full-field evidence review were still in progress. It is not a final Banzuke result. Claude/Copilot Fresh-read occurs only after final corpus freeze.

## kai-linux / agent-os

### Public evidence observed

Agent OS describes an autonomous-first software organization for supervised rollout: backlog issues are dispatched to coding agents, work executes in worktrees, branches/PRs are produced, CI/PR monitoring can merge green work, and failures retry/escalate. The repository exposes a public reliability dashboard sourced from runtime metrics plus production feedback. At the refreshed snapshot that dashboard reports a rolling 14-day **124 tasks, 85 successes (69%), 21 escalations (17%)**, with daily and per-agent breakdowns. It also exposes a concrete issue→agent→tests→PR→merge example and recurring incident scanning, backlog grooming, strategic planning and log analysis that feed self-fix work back into the delivery loop.

### Provisional GPT fresh-read — E4 consistency review

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 5 | 4 | **4** | A backlog-to-shipped-work organization plus recursive operational improvement materially changes what one technical founder/operator can sustain. Multi-day production telemetry supports E4, while transformative recognition remains evidence-capped. |
| Delegation Depth | 5 | 4 | **4** | The system accepts backlog-level responsibility and manages dispatch, execution, PR health and self-improvement loops over sustained recorded operation. |
| Autonomy | 5 | 4 | **4** | Cron-driven dispatch, queue, PR monitor, planner/groomer/scanner loops, retries and escalation are evidenced by sustained runtime records rather than a single demo. |
| Reliability | 4 | 4 | **4** | Multi-day task/success/escalation records, explicit blocker categories and end-to-end merged-task evidence support Dependable recognition, not Role-grade reliability. |
| Human Control | 5 | 4 | **4** | Supervised rollout, escalation, bounded retries, staged promotion to autonomy, observable metrics and operator controls support governed delegation. |

**Provisional recognized total: 20 / 25**

**Provisional qualification:** Ozeki. Not a final rank.

### Contrary / limiting evidence

- The refreshed rolling window remains **69% successful** and escalation increased to **17%**; daily success is volatile. This is strong operational evidence but also direct counter-evidence against Reliability 5.
- Blockers include missing credentials, no-diff runs, quota limits and prompt-size failures.
- Maintainer explicitly says results are workload-specific and fresh external repos should start supervised.
- Broad web/community search did not locate qualifying independent reproduction/adoption evidence in this pass. E5 remains unrecognized.

**E4 ruling:** **CONFIRMED** under the common rule: project-originated evidence can satisfy E4 when it records sustained real operation with concrete duration/volume/outcomes/failures. Independence is not required until E5.

---

## smartcomputer-ai / agent-os

### Public evidence observed

AgentOS is a Rust runtime for governed self-evolving agents. It provides a deterministic kernel, typed AIR control plane, explicit effects, signed receipts, replayable event history, durable backends and a propose→shadow→approve→apply→execute→receipt→audit self-modification lifecycle. A Demiurge agent and smoke fixtures exercise the current runtime. The project explicitly states it is **not quite ready for daily use yet** and remains in active development.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 3 | **3** | Governed runtime self-modification and replayable worlds are a meaningful new systems capability, but current proof remains pre-daily-use. |
| Delegation Depth | 3 | 3 | **3** | Task-driven agent workflows and declared effects support workflow-level delegation, not demonstrated continuing engineering-role ownership. |
| Autonomy | 4 | 3 | **3** | Agents can propose and execute governed runtime evolution, but demonstrated maturity caps recognition at workflow autonomy. |
| Reliability | 4 | 3 | **3** | Determinism, signed receipts, replay and durable journals are strong reliability architecture with smoke/demo evidence; daily operational reliability is explicitly not established. |
| Human Control | 5 | 3 | **3** | Typed effects, review gates, provenance and approval phases strongly support governance architecture, but E3 caps recognition. |

**Provisional recognized total: 15 / 25**

**Provisional qualification:** Sekiwake. Not a final rank.

---

## earthwalker17 / agent-os

### Public evidence observed

Agent OS is a local-first project operating system with a Main Agent/Coding Agent split, durable project memory, sandbox chokepoint, planning/task graphs, parallel agent teams, real command verification, browser verification, visual review, bounded recovery, audited Git/GitHub delivery and approval-gated production connectors. The repository reports 820+ backend tests. Its Pulseboard showcase records one real end-to-end product build from empty repository through build, browser/visual verification, repair, Git delivery, Vercel production deployment, Supabase migration and Stripe test-mode checkout/webhook persistence.

### Provisional GPT fresh-read — E4 consistency review

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 5 | 3 | **3** | The demonstrated loop is structurally powerful, but the assessed operational proof is primarily one project-maintained showcase rather than sustained operation across duration/volume. |
| Delegation Depth | 5 | 3 | **3** | The showcase demonstrates deep end-to-end delegation, but does not by itself establish sustained role-level operation under the E4 rule. |
| Autonomy | 4 | 3 | **3** | Parallel execution and bounded recovery demonstrate workflow autonomy; a single showcased product does not establish sustained role-level autonomy. |
| Reliability | 4 | 3 | **3** | 820+ tests and real verification/recovery provide strong E3 demonstration, but not sustained operational reliability. |
| Human Control | 5 | 3 | **3** | Sandbox, approval contracts, recovery budgets and audit artifacts strongly demonstrate governance architecture; E3 caps recognition. |

**Refreshed provisional recognized total: 15 / 25**

**Refreshed provisional qualification:** Sekiwake. Not a final rank.

### Contrary / limiting evidence

- The strongest real-world evidence found is the project-maintained Pulseboard showcase. It is unusually complete but still principally one showcased product/run lineage.
- No sustained duration/volume/failure-rate corpus comparable to `kai-linux/agent-os` or `dwiedeman/work-harness` was found in this pass.
- Broad web/community search did not locate qualifying independent reproduction/adoption evidence.

**E4 ruling:** **NOT ESTABLISHED.** Previous E4 recognition conflated an excellent real-world demonstration with sustained operation. The showcase remains strong E3 evidence.

---

## buildermethods / agent-os

### Public evidence observed

Agent OS helps coding agents discover and document codebase standards, inject relevant standards, shape implementation specs and index those standards. It works alongside external coding agents rather than owning their execution loop.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 2 | 2 | **2** | Standards extraction/injection and spec shaping extend consistency and planning quality. |
| Delegation Depth | 2 | 2 | **2** | Coherent standards/spec tasks can be delegated, but the product does not demonstrate ownership of the implementation workflow. |
| Autonomy | 2 | 2 | **2** | Standards discovery/injection can automate bounded tasks inside an external agent workflow. |
| Reliability | 2 | 2 | **2** | Public implementation/product availability supports repeatable bounded function, without stronger operational evidence in the assessed README. |
| Human Control | 3 | 2 | **2** | Lightweight alignment and documented standards provide useful boundaries, but evidence does not establish a deeper governance control plane. |

**Provisional recognized total: 10 / 25**

**Provisional qualification:** Komusubi. Not a final rank.

## Wave 8 upper-rank review observation

The E4 consistency pass separates **sustained operation** from a **real but bounded showcase**. `kai-linux/agent-os` remains provisionally Ozeki because its public telemetry records repeated real operation including failures and escalations. `earthwalker17/agent-os` is reduced to E3/Sekiwake because its impressive Pulseboard proof is primarily a single project-maintained end-to-end showcase rather than sustained operational evidence.

No Claude/Copilot review or Torikumi is started at this stage.
