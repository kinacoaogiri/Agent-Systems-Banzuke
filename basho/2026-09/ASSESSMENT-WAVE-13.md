# September 2026 Basho — Assessment Wave 13

**Assessment snapshot: 2026-09-13**

Status: **Evidence collection / provisional GPT fresh-read**

> **Audit status:** This is a provisional GPT working record. Canonical rules had been restored before this assessment, but field/identity cleanup and full-field evidence review were still in progress. It is not a final Banzuke result. Claude/Copilot Fresh-read occurs only after final corpus freeze.

This wave assesses three systems added by the final discovery sweep. Scores are provisional and do not freeze the field or corpus.

## opensesh / KARIMO

### Public evidence observed

KARIMO presents a PRD-driven Claude Code orchestration harness spanning research, planning, task decomposition, review, dependency-aware wave execution and final inspection. Public documentation describes worktree isolation, ordered/parallel execution, recovery behavior and configurable review/authority boundaries.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 3 | **3** | A structured PRD-to-inspection multi-agent workflow materially expands one Human's ability to coordinate implementation. |
| Delegation Depth | 4 | 3 | **3** | Research, plan, tasks, implementation waves, review and inspection form a substantial delegated workflow. |
| Autonomy | 4 | 3 | **3** | Dependency-aware wave execution and recovery provide role-like autonomy architecture, evidence-capped at demonstrated workflow level. |
| Reliability | 4 | 3 | **3** | Isolation, ordered dependencies, review and inspection provide strong verification/recovery mechanisms without sustained-operation evidence. |
| Human Control | 4 | 3 | **3** | Configurable review and authority boundaries keep execution under explicit Human governance. |

**Provisional recognized total: 15 / 25**

**Provisional qualification:** Sekiwake. Not a final rank.

---

## blundergoat / goat-flow

### Public evidence observed

GOAT Flow is an executable coding-agent harness and local dashboard for Claude Code, Codex, Google Antigravity and GitHub Copilot. It installs a common READ→SCOPE→ACT→VERIFY execution loop, eight structured skills, deterministic audit surfaces, enforcement hooks, autonomy tiers, recovery/handoff mechanisms and a learning loop that persists verified failures, footguns and decisions. Hooks reject covered dangerous actions before execution; workflows expose Human gates. The CLI supports audit output for CI/SARIF and deterministic installation/update with path-safety and conflict handling.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 3 | 3 | **3** | Cross-agent reusable enforcement, verification, recovery and learning materially improve coding-agent workflows. |
| Delegation Depth | 3 | 3 | **3** | Structured skills can own coherent engineering workflows, but GOAT Flow is primarily the harness around externally executing agents rather than a sustained project-role orchestrator. |
| Autonomy | 3 | 3 | **3** | Autonomy tiers and feedback/recovery mechanisms automate bounded workflow progression while retaining Human gates. |
| Reliability | 4 | 3 | **3** | Deterministic audit, runtime hooks, atomic installer behavior, verification and recovery are strong demonstrated reliability mechanisms; no E4 sustained-operation record is recognized here. |
| Human Control | 5 | 3 | **3** | Tool-level blocks, autonomy tiers, Human gates, path-safety rules and explicit trusted-target boundaries provide governance-grade design, evidence-capped at E3. |

**Provisional recognized total: 15 / 25**

**Provisional qualification:** Sekiwake. Not a final rank.

---

## Kibertum / tausik-core

### Public evidence observed

TAUSIK is an executable discipline/governance layer for coding agents. It uses fail-closed task lifecycle gates, acceptance criteria, a separate verify phase, ed25519-signed verification receipts bound to gate state and commit SHA, persistent project/cross-project memory, runtime hooks, metrics/routing and explicit push authority. The repository reports 7,115 tests and 76% line coverage, states that TAUSIK was built with TAUSIK, and records zero tasks closed without verification evidence. The documentation explicitly limits its threat model: receipts provide tamper-evidence against outside edits, not protection from a determined agent holding the key.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 3 | **3** | Hard, verifiable engineering discipline and durable memory materially expand safe use of coding agents, but the public proof is primarily self-hosted/project-originated rather than sustained external operation. |
| Delegation Depth | 3 | 3 | **3** | Plan→task→code→review/test→verify→commit/offer-push is a coherent delegated engineering workflow, while the underlying coding agent performs implementation. |
| Autonomy | 3 | 3 | **3** | Hooks, batch execution, memory injection and verification automate bounded workflow progression but do not establish sustained autonomous role ownership. |
| Reliability | 5 | 3 | **3** | Fail-closed gates, signed receipts and 7,115 tests indicate unusually strong reliability capability; evidence remains E3 because self-build/test evidence is not by itself sustained real-world operation. |
| Human Control | 5 | 3 | **3** | No-code-without-task, no-close-without-proof, push tickets, explicit authority and honest threat-model boundaries closely match delegated-governance design; E3 caps recognition. |

**Provisional recognized total: 15 / 25**

**Provisional qualification:** Sekiwake. Not a final rank.

### Counter-evidence / limitation

- TAUSIK explicitly says it is a discipline rail, not a firewall against a determined agent.
- Its strongest quantitative evidence is self-hosted development/testing; this pass does not promote that to E4 sustained operation.

## Wave 13 observation

All three systems provisionally qualify as Sekiwake at E3. TAUSIK has especially strong Reliability/Human-Control capability architecture, but the common Evidence Gate prevents architectural strength and large self-test counts from being mistaken for sustained E4 operation.

No Claude/Copilot review or Torikumi is started at this stage.
