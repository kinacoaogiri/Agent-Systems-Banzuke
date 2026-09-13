# September 2026 Basho — Assessment Wave 11

**Assessment snapshot: 2026-09-13**

Status: **Evidence collection / provisional GPT fresh-read**

> **Audit status:** This is a provisional GPT working record. Canonical rules had been restored before this assessment, but field/identity cleanup and full-field evidence review were still in progress. It is not a final Banzuke result. Claude/Copilot Fresh-read occurs only after final corpus freeze.

## junhoyeo / contrabass

### Public evidence observed

Contrabass is a terminal-first project-level orchestrator for issue-driven coding-agent runs with TUI/headless/web modes. It supports Linear/GitHub/Internal Board trackers; Codex/OpenCode/OMX/OMC runners; isolated git worktrees; dependency gating; claim/release and orphan recovery; branch-advance verification; stall detection; deterministic retry; graceful shutdown; JSONL/heartbeat persistence; and team execution through plan→exec→verify phases. Team mode supports tmux process isolation or in-process workers and persistent local state.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 3 | **3** | Project-level issue orchestration, teams and tracker integration materially expand multi-agent engineering throughput. |
| Delegation Depth | 4 | 3 | **3** | Issue and team workflows can be delegated through plan/execute/verify and completion handling. |
| Autonomy | 4 | 3 | **3** | Dependency gating, retries, orphan recovery, liveness/stall handling and persistent team state provide role-like autonomous mechanics. |
| Reliability | 4 | 3 | **3** | Unit/integration/snapshot tests, branch verification, deterministic retry and crash recovery provide strong demonstrated reliability. |
| Human Control | 4 | 3 | **3** | Workflow configuration, governance policies, dashboards, state visibility and bounded execution keep Human control explicit. |

**Provisional recognized total: 15 / 25**

**Provisional qualification:** Sekiwake. Not a final rank.

---

## aterrylu / autonomOS

### Public evidence observed

autonomOS is a self-hosted daemon and browser/PWA mission-control layer for heterogeneous CLI coding agents. Claude Code and Codex are fully supported and Gemini partially supported. A shared URI message bus and MCP toolbelt let agents spawn, message and organize one another across runtimes. Agents form manager/report hierarchies; telemetry exposes live state; sessions resume across server restarts; agents can create one-time/recurring scheduled jobs; the daemon has authenticated access, release upgrade/rollback and OS-native supervision.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 3 | **3** | Cross-CLI direct agent coordination, hierarchy and always-on remote operation materially expand human orchestration capacity. |
| Delegation Depth | 3 | 3 | **3** | Managers can delegate work down an agent hierarchy and agents coordinate directly, supporting workflow delegation; evidence does not establish autonomous ownership of an engineering role. |
| Autonomy | 4 | 3 | **3** | Always-on daemon, direct inter-agent messaging, scheduling and session persistence support role-like autonomy architecture. |
| Reliability | 3 | 3 | **3** | Releases, CI, OS-native supervision, resume, delivery acknowledgement and upgrade rollback support demonstrated operational workflow reliability. |
| Human Control | 4 | 3 | **3** | Authenticated dashboard, org chart, status telemetry, permission modes and explicit hierarchy make the fleet observable and governable. |

**Provisional recognized total: 15 / 25**

**Provisional qualification:** Sekiwake. Not a final rank.

## Wave 11 observation

Both systems provisionally qualify as Sekiwake. Contrabass is stronger on issue/worktree/retry/verification mechanics; autonomOS is stronger on cross-runtime live coordination and persistent agent organization. Neither is raised to E4 in this first pass solely from product claims/releases; sustained operational evidence remains to be evaluated where relevant.

No Claude/Copilot review or Torikumi is started at this stage.
