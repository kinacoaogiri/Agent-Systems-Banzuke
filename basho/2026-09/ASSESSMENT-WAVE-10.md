# September 2026 Basho — Assessment Wave 10

**Assessment snapshot: 2026-09-13**

Status: **Evidence collection / provisional GPT fresh-read**

## backmeupplz / superharness

### Public evidence observed

A Rust/tmux multi-agent orchestrator for Claude Code, OpenCode and Codex CLI. It spawns parallel workers in isolated git worktrees, handles permission prompts, detects stalls, respawns crashed workers with context, manages dependency-gated tasks, checkpoints/resume/memory and cleans up. Away Mode continues safe work autonomously while queuing uncertain architectural/destructive decisions for Human review.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 3 | **3** | Parallel autonomous worker coordination materially expands one operator's engineering capacity, evidence-capped at demonstrated implementation. |
| Delegation Depth | 4 | 3 | **3** | Orchestrator decomposition, worker execution, merge and cleanup span substantial workflows, but operational role delegation is not yet evidenced at E4. |
| Autonomy | 4 | 3 | **3** | Away mode, auto-approval, dependency handling, stall recovery and respawn provide role-like autonomy architecture. |
| Reliability | 3 | 3 | **3** | Heartbeats, stall detection, crash recovery, worktree isolation and checkpoints support demonstrated operational workflow reliability. |
| Human Control | 4 | 3 | **3** | Safe operations can be delegated while uncertain/destructive decisions are queued for Human authority. |

**Provisional recognized total: 15 / 25**

**Provisional qualification:** Sekiwake. Not a final rank.

---

## Untrivial-ai / agent-orchestrator

### Public evidence observed

Agent Orchestrator (AO) is a cross-platform desktop workspace and local daemon that gives each coding task an isolated agent/worktree and tracks conversations, terminal state, changed files, browser preview, PR, CI and review. A persistent project orchestrator reasons over project goals plus live worker/PR/CI/review state, decomposes larger outcomes, spawns/redirects workers and coordinates follow-up. The project publishes desktop installers/releases and supports 27 coding-agent backends through one supervised workflow.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 3 | **3** | Project-level multi-agent planning and a unified operational workspace materially expand human coordination capacity; current assessed evidence does not yet establish sustained delegated operation. |
| Delegation Depth | 4 | 3 | **3** | Project orchestrator can decompose outcomes and delegate implementation/PR work across workers. |
| Autonomy | 3 | 3 | **3** | Workers operate independently and the orchestrator coordinates them, while the product remains explicitly a supervised workspace. |
| Reliability | 3 | 3 | **3** | Released cross-platform product, daemon state tracking, worktree isolation and PR/CI/review feedback loops support demonstrated operational workflow reliability. |
| Human Control | 4 | 3 | **3** | Live Kanban, Needs-you state, direct session inspection and supervised feedback keep the Human in project-level authority. |

**Provisional recognized total: 15 / 25**

**Provisional qualification:** Sekiwake. Not a final rank.

---

## HKUDS / DeepCode

### Public evidence observed

DeepCode is an open agentic-coding system with TUI/Desktop/Web clients sharing a local background service, durable Sessions/projects, goals, skills, permissions and automations. It supports goal-driven loop engineering, evidence-driven completion, parallel agents without file collisions, headless automation and Paper2Code. Recent public releases document persistent background work across client reconnection, explicit pending approvals, context compaction/memory boundaries, sandbox/security fixes and active maintenance. The project is also associated with a public research paper.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 3 | **3** | Goal-driven coding, parallel agents, automation and Paper2Code materially expand practical engineering/research implementation capability. |
| Delegation Depth | 4 | 3 | **3** | Goals and automations can drive substantial coding workflows, but assessed evidence does not yet establish role-level sustained operation at E4. |
| Autonomy | 4 | 3 | **3** | Background service, headless automation and persistent work provide role-like autonomy architecture, with Human approvals still explicit. |
| Reliability | 4 | 3 | **3** | Shared durable service, evidence-driven completion, active release fixes and sandbox boundaries support strong demonstrated reliability but not E4 from this pass alone. |
| Human Control | 4 | 3 | **3** | Shared permissions, approval handling, service management and sandbox boundaries support governed workflow operation. |

**Provisional recognized total: 15 / 25**

**Provisional qualification:** Sekiwake. Not a final rank.

### Evidence note

The associated paper and broader public adoption footprint may materially affect Evidence Levels. This candidate requires a broader evidence pass before final corpus freeze.

---

## limboo-ai / limboo

### Public evidence observed

Limboo explicitly positions itself as the durable environment around coding agents rather than an agent loop itself. It owns project/session state, repository-delta reconciliation, provider-neutral durable memory/search, worktree isolation, Git, terminals, services and a shared authorization core with an OS-level sandbox. Claude and Cursor currently share the same platform services and permissions through adapters. Cross-platform installers/releases, CI/security workflows and provenance attestations are published.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 3 | **3** | Provider-independent durable environment/reality reconciliation materially expands safe continuity across coding agents. |
| Delegation Depth | 2 | 3 | **2** | Limboo deliberately does not own the agent loop or engineering delegation; it supplies infrastructure around externally executing agents. |
| Autonomy | 2 | 3 | **2** | Automatic reconciliation, indexing and environment services operate autonomously, but engineering progression remains with the hosted agent/human. |
| Reliability | 4 | 3 | **3** | Releases, CI/security, typed subsystems, sandboxing and durable state support strong demonstrated platform reliability. |
| Human Control | 5 | 3 | **3** | Shared authorization core, provider-neutral sandbox, path/process guards and approval surfaces are the system's strongest capability, evidence-capped. |

**Provisional recognized total: 13 / 25**

**Provisional qualification:** Komusubi. Sekiwake Delegation/Autonomy conditions are not satisfied. Not a final rank.

## Wave 10 observation

Three candidates (`backmeupplz/superharness`, AO and DeepCode) provisionally reach Sekiwake on workflow-level orchestration with E3 recognition. Limboo is intentionally different: its strongest contribution is provider-neutral environment integrity and Human governance, while it explicitly declines ownership of the coding-agent execution loop, capping Delegation/Autonomy for this Rubric.

No Claude/Copilot review or Torikumi is started at this stage.
