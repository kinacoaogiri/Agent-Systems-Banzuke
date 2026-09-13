# September 2026 Basho — Assessment Wave 6

**Assessment snapshot: 2026-09-13**

Status: **Evidence collection / provisional GPT fresh-read**

> **Audit status:** This is a provisional GPT working record created before completion of the 2026-09-13 canonical audit. It is preserved as working history, not a final Banzuke result. Scores/rank labels must be re-evaluated against the restored canonical rules after field/identity cleanup and full-field evidence collection. Claude/Copilot Fresh-read occurs only after final corpus freeze.
>
> **Sequence note:** This wave was produced before the required canonical audit/identity-cleanup stage was complete. It is retained for traceability; it does not establish a final assessment sequence or rank.

Wave 6 continues GPT primary assessment.

## backnotprop / orchestrator

### Public evidence observed

The public project is a local orchestration skill plus CLI used from an existing coding harness. It launches heterogeneous background workers, resolves live model catalogs and provider limits, tracks each worker as a named task with status/logs/output/follow-up/resume/stop controls, and owns process supervision/task state. The README explicitly states that the calling agent retains judgment, delegation and synthesis, and explicitly says `Orchestrator is not a harness`.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 3 | 3 | **3** | Heterogeneous parallel workers and process supervision materially expand the calling agent/human's execution capacity. |
| Delegation Depth | 3 | 3 | **3** | Named background tasks, dependency-style prompting and reviewer assignment support workflow delegation, but higher-level judgment remains outside this system. |
| Autonomy | 2 | 3 | **2** | The CLI supervises processes/tasks, while the calling agent explicitly owns judgment, delegation and synthesis; system-owned autonomous workflow control is therefore bounded. |
| Reliability | 3 | 3 | **3** | Status/log/output/resume/interrupt controls and runtime model discovery provide demonstrated supervision and recoverability for its actual scope. |
| Human Control | 4 | 3 | **3** | Explicit stop/interrupt, preferences/fallbacks, live capability resolution and calling-agent authority provide strong observable control. |

**Provisional recognized total: 14 / 25**

**Provisional qualification:** Komusubi. Sekiwake mandatory Autonomy >=3 is not satisfied. Not a final rank.

---

## Ghosteken / agent-harness

### Public evidence observed

The public repository is a large installable engineering-skill/plugin suite covering DEFINE -> PLAN -> BUILD -> VERIFY -> REVIEW -> SHIP. Its `/build auto` path generates a plan, asks for one approval, then implements every task autonomously while retaining per-task test/commit verification and pausing on failures or risky steps. The repository exposes 177 curated skills, a 24-skill lifecycle core, specialist agent personas, TDD, independent/adversarial review patterns, debugging/recovery, security, CI/CD, observability and shipping practices across multiple host integrations. Runtime execution remains primarily supplied by the host agent/plugin environment.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 3 | **3** | A coherent full-lifecycle skill system materially expands the engineering work a coding agent can execute consistently. |
| Delegation Depth | 4 | 3 | **3** | `/build auto` can carry an approved plan through all tasks and verification, supporting deep workflow delegation. |
| Autonomy | 3 | 3 | **3** | One-plan approval followed by autonomous task execution with failure/risk pauses supports workflow autonomy, while the host remains the execution runtime. |
| Reliability | 4 | 3 | **3** | TDD, task verification, independent review, debugging/recovery and shipping gates provide strong demonstrated process controls. |
| Human Control | 5 | 3 | **3** | Plan approval, pauses on risky/failing steps, scoped personas/skills and explicit quality gates support governed Human authority. |

**Provisional recognized total: 15 / 25**

**Provisional qualification:** Sekiwake threshold and mandatory recognized levels appear satisfied. Not a final rank.

---

## TimothyVang / Coding-Agent-Harness

### Public evidence observed

The public Python system describes a Multi-Agent Orchestrator coordinating 13 specialized agents across multiple projects. It includes a prioritized dependency-aware task queue with retry, pub/sub/direct message bus, persistent agent memory and mistake/pattern learning, vector similarity search, checklist/subtask blocking, project registry/load balancing, real-time TUI monitoring, E2B-isolated execution with hard-fail if the sandbox is unavailable, file locking, security redirection, integration tests and a verification script. The documented workflow routes a project spec through the orchestrator/agent pool, task queue/message bus, E2B sandbox and checklist system.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 3 | **3** | Multi-project orchestration and a specialist agent pool materially expand one operator's software-development capacity. |
| Delegation Depth | 4 | 3 | **3** | Architect/build/test/review/devops/documentation roles coordinated through task/dependency infrastructure support deep workflow delegation. |
| Autonomy | 4 | 3 | **3** | Automatic task matching, retries, inter-agent messaging, memory and multi-project coordination support substantial workflow autonomy. |
| Reliability | 3 | 3 | **3** | Blocking subtasks, retry, locking, hard-fail sandboxing, verification scripts and integration tests support demonstrated operational repeatability, but stronger sustained-use evidence is absent in this pass. |
| Human Control | 4 | 3 | **3** | TUI monitoring, hard-fail execution boundaries, sandbox isolation, project status and explicit security controls provide governed/observable operation. |

**Provisional recognized total: 15 / 25**

**Provisional qualification:** Sekiwake threshold and mandatory recognized levels appear satisfied. Not a final rank.

## Wave 6 observation

`backnotprop/orchestrator` is a useful boundary case: it is deliberately a subordinate process/task orchestration layer, and the calling agent retains judgment and synthesis. Its lower Autonomy recognition is therefore a scope finding rather than a quality criticism.

`Ghosteken/agent-harness` reaches deeper lifecycle delegation through `/build auto`, but execution remains host-mediated and public operational evidence is still E3 in this pass.

`TimothyVang/Coding-Agent-Harness` is an integrated multi-agent execution system rather than only a skill library. Its architecture supports higher apparent Capability ceilings, but the current public evidence reviewed here does not justify raising recognition beyond E3.

No Claude/Copilot review or Torikumi is started at this stage.
