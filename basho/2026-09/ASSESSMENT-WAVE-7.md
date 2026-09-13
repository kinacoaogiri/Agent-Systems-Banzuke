# September 2026 Basho — Assessment Wave 7

**Assessment snapshot: 2026-09-13**

Status: **Evidence collection / provisional GPT fresh-read**

Wave 7 continues GPT primary assessment. Claude/Copilot review remains deferred until candidate/evidence completion.

## lunarnexus / orchestra

### Public evidence observed

The public project is an agent-agnostic orchestration layer for dispatching focused subagents from an existing coding-agent harness. It supports asynchronous background dispatch, heterogeneous main/subagent harnesses, roles, skills/environment injection, fallbacks, budgets, concurrency/timeouts, status/history/stop/debug controls and live smoke/E2E tests. The maintainer also publishes unusually explicit benchmark observations: orchestration can slightly improve quality while consuming roughly 2x–5x tokens and 2x–3x completion time, with larger benefits on long-horizon/context-compaction-heavy work. The project is explicitly Beta, current host support is narrower than some tables imply, and Codex is scaffold-only.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 3 | 3 | **3** | Heterogeneous async subagents and context-preserving offload materially expand main-session execution capacity. |
| Delegation Depth | 3 | 3 | **3** | PLAN-driven dispatch and specialized roles support workflow delegation, but the main host remains orchestrator/planner. |
| Autonomy | 3 | 3 | **3** | Background dispatch, auto-return, timeout and fallback support bounded workflow autonomy. |
| Reliability | 3 | 3 | **3** | Live smoke/E2E checks, status/history/debug, timeout/fallback and candid benchmark results support demonstrated reliability of current scope. |
| Human Control | 4 | 3 | **3** | Explicit on/off, stop, roles, budgets, fallbacks and honest capability matrices support governed operation. |

**Provisional recognized total: 15 / 25**

**Provisional qualification:** Sekiwake. Not a final rank.

### Contrary / limiting evidence

- Project explicitly says Beta and warns of large incoming interface/config changes.
- Current support is narrower than the broad feature matrix; Pi is the supported path until core stabilization, while Codex is scaffold-only.
- Maintainer benchmarks report substantial token/time overhead for many orchestration workloads.

---

## artificemachine / superharness — evidence refresh

### Public evidence observed

This system was scored in Wave 1. The current public README now reports 5,700+ tests, a live status example containing 1,655 completed and 46 failed inbox runs plus 10,254 archived tasks, background watcher operation, typed telemetry, dual watchdogs, queue/discussion/approval lifecycle, parallel fan-out, swarm mode with reviewer selection, auto-clean/recovery, persistent SQLite runtime state, cross-platform background services, and self-audit findings retained even when unfavorable. It explicitly says superharness is used to audit superharness and documents previously discovered security/integrity defects together with failing-test reproduction and fixes.

### Provisional GPT refresh

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 4 | **4** | Multi-agent persistent coordination, unattended operation, fan-out/swarm and recovery materially expand practical execution capacity; current public operational state exceeds a one-off demonstration. |
| Delegation Depth | 4 | 4 | **4** | Queue dispatch, lifecycle, unattended watcher, fan-out/swarm and approval/review flows support continuing role-like workflow delegation. |
| Autonomy | 4 | 4 | **4** | Auto-mode, background watcher, watchdogs, retries, stale cleanup and unattended services support Role-level autonomous operation within bounded tasks. |
| Reliability | 4 | 4 | **4** | 5,700+ tests, watchdogs, telemetry, CI health checks, lifecycle enforcement, recovery and candid self-audit evidence support Dependable operational recognition. |
| Human Control | 4 | 4 | **4** | Approval state, dispatch preview, status/interrupt surfaces, print-only preview, audit trail and lifecycle gates support governed Human authority. |

**Refreshed provisional recognized total: 20 / 25**

**Refreshed provisional qualification:** Ozeki threshold and mandatory levels appear satisfied. Not a final rank.

### Evidence caution

E4 is based on public project-originated operational records and sustained self-use signals, not independent establishment. E5 remains unrecognized. Upper-rank external evidence and counter-evidence search is mandatory before final adjudication.

---

## LanNguyenSi / harness

### Public evidence observed

The public project is a declarative governance/control plane that compiles one manifest into runtime configuration and enforces policy at tool-call time. It can deny actions before execution, requires evidence-ledger facts, records every decision, provides audit/explain traces, policy packs, risk classification, Human approvals, pause/resume, branch protection, understanding-before-execution, solution-acceptance and post-merge gates, runtime-reality drift checks, HMAC-signed approval markers and explicit fail-loud behavior. The current README documents a long shipped release progression through v0.46.0 and a concrete incident that motivated deterministic preflight enforcement. It intentionally adds governance to another harness rather than owning the engineering execution loop itself.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 3 | **3** | Runtime policy enforcement and auditable evidence gates add a materially new governance capability to existing coding agents. |
| Delegation Depth | 2 | 3 | **2** | The system governs delegated execution but does not itself own the engineering workflow or worker execution. |
| Autonomy | 2 | 3 | **2** | Enforcement is automatic at runtime, but autonomous engineering progression remains in the host harness. |
| Reliability | 4 | 3 | **3** | Deterministic interception, evidence queries, audit replay, shipped policy packs and fail-loud checks provide strong demonstrated reliability for governance scope. |
| Human Control | 5 | 3 | **3** | This is the system's strongest dimension: Human approval, risk gates, protected boundaries, signed markers, pause/resume and explainable deny/allow traces closely match Delegated Governance architecture. |

**Provisional recognized total: 13 / 25**

**Provisional qualification:** Komusubi. Sekiwake Delegation/Autonomy requirements are not satisfied. Not a final rank.

## Wave 7 observation

Wave 7 materially changes the provisional leaderboard because `artificemachine/superharness` now presents stronger operational evidence than was captured in Wave 1. Under Fact First, provisional pre-publication assessment is updated rather than preserving a stale lower evidence level.

The result is now two provisional Ozeki-band systems:

- `deepklarity/harness-kit` — 20/25 provisional
- `artificemachine/superharness` — 20/25 provisional after evidence refresh

Both remain E4, not E5, and both require external/counter-evidence review before final adjudication.

`lunarnexus/orchestra` remains Sekiwake-band because it owns meaningful orchestration but candidly documents Beta/support/efficiency limitations. `LanNguyenSi/harness` demonstrates unusually strong Human-governance architecture, but because it deliberately governs another harness rather than executing the engineering workflow itself, Delegation and Autonomy cap its rank.

No Claude/Copilot review or Torikumi is started at this stage.
