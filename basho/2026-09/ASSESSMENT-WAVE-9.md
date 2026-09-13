# September 2026 Basho — Assessment Wave 9

**Assessment snapshot: 2026-09-13**

Status: **Evidence collection / provisional GPT fresh-read**

## nodera-studio / agent-os

### Public evidence observed

A production-extracted Claude Code harness containing 51 orchestration prompts across eight workflows, 29 commands, 11 skills and enforcement hooks. Planning uses explorer/research plus two independent architects and a judge. Implementation uses separate Claude/Codex reviewers and an author-blind conformance-test writer. Review/debug/audit workflows use independent agents and adversarial/consensus passes. Manual mode retains approval gates; `/auto-mode` can run a declared goal through repeated plan→implement→PR→poll→fix→merge waves without gates between waves.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 3 | **3** | Multi-role independent reasoning and automated goal waves materially expand one builder's engineering capacity, evidence-capped at demonstrated/project evidence. |
| Delegation Depth | 4 | 3 | **3** | Declared goals can drive multi-wave implementation/review/PR progression, but sustained role delegation is not operationally established at E4. |
| Autonomy | 4 | 3 | **3** | Auto-mode and dispatcher fallback provide role-like architecture; current evidence supports workflow-level recognition. |
| Reliability | 4 | 3 | **3** | Independent reviewers, blind conformance testing, deterministic tool steering and hard gates are strong demonstrated reliability mechanisms. |
| Human Control | 4 | 3 | **3** | Manual approval mode, bounded pipelines, hooks and explicit shipping authority provide governed architecture. |

**Provisional recognized total: 15 / 25**

**Provisional qualification:** Sekiwake. Not a final rank.

---

## Dusttoo / orka

### Public evidence observed

Orka is a high-throughput engineering orchestration harness with isolated worktrees, separate implementation/code-review/security-review roles, mechanical all-green merge enforcement, Jira sprint operation, bounded design/repair loops, hard spend/run ceilings, ticket-scoped continuations, recovery/decomposition queues, provider-safe usage accounting and durable workflow state. Its explicit rule is that it may recover, repair, decompose and continue within declared policy but cannot manufacture authority or bypass failed gates.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 3 | **3** | Parallel sprint execution with independent gates and bounded recovery structurally expands engineering throughput, evidence-capped at E3. |
| Delegation Depth | 4 | 3 | **3** | Ticket/sprint pipelines own implementation through review/merge under policy, but sustained operational role evidence is not yet established. |
| Autonomy | 4 | 3 | **3** | Autonomous intervention queues, decomposition, repairs and continuation support role-like autonomy architecture. |
| Reliability | 4 | 3 | **3** | Mechanical merge guard, fresh-context reviewers, bounded convergence and exact-head validation provide strong demonstrated reliability design. |
| Human Control | 5 | 3 | **3** | Hard budgets, approvals, authority capabilities, failed-gate refusal and escalation closely match delegated-governance architecture, evidence-capped. |

**Provisional recognized total: 15 / 25**

**Provisional qualification:** Sekiwake. Not a final rank.

---

## dwiedeman / work-harness

### Public evidence observed

`work` decomposes projects into PR-sized units, dispatches autonomous leads across local/SSH/cloud hosts and uses a persistent shepherd to move PRs through review to merge, backed by an append-only ledger. The README publishes measured results across multiple runs and a concrete production run: 14 issues dispatched, 8 PRs merged, 8 issues closed, 42 lead spawns, 35 handoffs, roughly 3.87B ledger-folded tokens and 46.51 hours. It also publishes review-round measurements across 25 PRs, preflight checks, version-skew enforcement, mandatory plan review and telemetry/calibration procedures.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 5 | 4 | **4** | Multi-host overnight backlog delivery materially substitutes substantial coordination/execution effort and has concrete production-run evidence. |
| Delegation Depth | 5 | 4 | **4** | Planner/lead/shepherd roles carry PR-sized work from decomposition through merge over long runs, supporting role-level recognized delegation. |
| Autonomy | 5 | 4 | **4** | Persistent shepherding, session replacement survival, host dispatch and long-running runs support sustained architecture and role-level operational recognition. |
| Reliability | 4 | 4 | **4** | Multi-run measurements, production metrics, mandatory gates, version enforcement and explicit failure-capable preflight support Dependable recognition. |
| Human Control | 4 | 4 | **4** | Human orchestrator remains authority; plan review, risk lanes, gates, ledger and explicit dispatch keep autonomous workers governed and observable. |

**Provisional recognized total: 20 / 25**

**Provisional qualification:** Ozeki. Not a final rank.

### Contrary / limiting evidence

- The project explicitly says the human `/work` session is the orchestrator; the harness is plumbing, so full Human Role Holder substitution should not be inferred.
- The published real run merged 8 of 14 dispatched issues and consumed very high resources; this supports operational honesty but not Reliability 5.
- E4 is maintainer/project-originated production evidence, not independent E5. Upper-rank external/counter-evidence review is required.

---

## kim-dongho / agent-harness-starter

### Public evidence observed

A cross-agent harness for Claude Code, Gemini CLI and Codex CLI. Shared hooks enforce scope/scaffold constraints, lint/type/security checks, session initialization and stop review. Errors can enter bounded self-heal loops; repeated errors create learned coding standards; metrics record blocks, first-pass success and self-heal success. SDLC skills support Jira/Figma planning through quality gates, commit and merge-request creation.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 3 | 3 | **3** | Cross-agent enforcement, learning and SDLC automation add a meaningful reusable capability layer. |
| Delegation Depth | 3 | 3 | **3** | `/start` and `/done` span coherent multi-step engineering workflows. |
| Autonomy | 3 | 3 | **3** | Automatic hooks, self-heal and learning progress without stepwise human operation inside bounded workflows. |
| Reliability | 3 | 3 | **3** | Deterministic hooks, quality gates, tests and measured self-heal behavior support demonstrated operational-style workflow reliability, without sustained-use evidence. |
| Human Control | 4 | 3 | **3** | Scope guards, security confirmation, quality gates and shared configuration provide strong bounded/observable control. |

**Provisional recognized total: 15 / 25**

**Provisional qualification:** Sekiwake. Not a final rank.

## Wave 9 observation

`dwiedeman/work-harness` enters the provisional Ozeki band because it publishes unusually concrete multi-run/production operational records, but the human remains explicitly the orchestrator and Reliability 5 is not recognized. The other three systems show substantial workflow-level orchestration/governance with E3 evidence and provisionally qualify as Sekiwake.

No Claude/Copilot review or Torikumi is started at this stage.
