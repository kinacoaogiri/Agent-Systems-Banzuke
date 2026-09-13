# September 2026 Basho — Assessment Wave 4

**Assessment snapshot: 2026-09-13**

Status: **Evidence collection / provisional GPT fresh-read**

> **Audit status:** This is a provisional GPT working record created before completion of the 2026-09-13 canonical audit. It is preserved as working history, not a final Banzuke result. Scores/rank labels must be re-evaluated against the restored canonical rules after field/identity cleanup and full-field evidence collection. Claude/Copilot Fresh-read occurs only after final corpus freeze.
>
> **Sequence note:** This wave was produced before the required canonical audit/identity-cleanup stage was complete. It is retained for traceability; it does not establish a final assessment sequence or rank.

Wave 4 continues GPT primary assessment.

## chapzin / codex-harness-mcp

### Public evidence observed

The public project explicitly describes itself as a local harness-engineering control plane for Codex CLI and MCP-compatible coding agents. It implements project-local execution contracts, RAG memory, raw traces, verification records, governance policy and PASS/FLAG/BLOCK audits, observability reports, harness profiles/eval records, proposal/promotion records, failure-recovery recommendations, handoff context and completion gates. It is intentionally dependency-free and local, and explicitly does **not** execute shell commands, remote calls, benchmark commands, generated harness code, or agent tasks itself; external clients/users execute the work and feed evidence back to the MCP.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 3 | 3 | **3** | Durable contracts, memory, evidence and governance materially improve long-running agent work, and the implemented MCP surface is directly inspectable. |
| Delegation Depth | 2 | 3 | **2** | The system bounds and records delegated work but explicitly does not run tasks; Task-level system-owned delegation is the safer ceiling. |
| Autonomy | 1 | 3 | **1** | It supports the agent loop but intentionally leaves execution and eval commands outside the MCP. The control plane itself has little autonomous execution responsibility. |
| Reliability | 3 | 3 | **3** | Durable traces, verification evidence, governance audits, eval records, recovery recommendations and completion gates directly support repeatable/operational control of its actual scope. |
| Human Control | 4 | 3 | **3** | Budgets, permissions, policy audits, stop-on-BLOCK semantics, side-effect/subagent bounds and inspectable state provide strong governed-control architecture. |

**Provisional recognized total: 12 / 25**

**Provisional qualification:** Komusubi. Sekiwake mandatory Autonomy >=3 is not satisfied. Not a final rank.

### Evidence gaps

- The project intentionally does not own task execution; higher Autonomy cannot be inferred from the client agent.
- Independent sustained operational evidence for E4+.
- Evidence that the MCP itself owns workflow/role delegation rather than recording and governing external execution.

---

## highflame-ai / codeoid

### Public evidence observed

The public project is an executable multi-agent harness with parallel coding-agent sessions, multiple backends/frontends, cross-session workspace memory, persistent tool/result/reasoning episodes, worktree-based parallelism, autonomous runs with write/exec budgets, device handoff, telemetry and per-turn cost/context instrumentation. In ZeroID mode, agents and sub-agents receive cryptographic identities with delegation chains, scope attenuation and revocation; local mode explicitly discloses weaker self-asserted identity. Public npm packaging, CI and coverage surfaces are exposed. The README also distinguishes its own long-horizon session/memory/identity scope from broader general-purpose orchestration.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 3 | **3** | Parallel sessions, shared verbatim memory, multi-device control and heterogeneous backends materially expand one operator's long-horizon execution capacity. |
| Delegation Depth | 3 | 3 | **3** | Autonomous sessions, parallel worktrees and shared memory support workflow-level delegation; continuing Role ownership is not established. |
| Autonomy | 3 | 3 | **3** | Budget-bounded autonomous runs and persistent multi-session operation establish workflow autonomy, but evidence does not establish sustained Role autonomy. |
| Reliability | 4 | 3 | **3** | Persistent episodes, recall, context rotation, audit records, CI/coverage and durable session control provide strong demonstration-level reliability mechanisms. |
| Human Control | 5 | 3 | **3** | Budget return-to-human behavior plus cryptographic identities, delegation chains, scope attenuation, revocation, audit attribution and explicit local-mode warnings strongly support governed autonomy. |

**Provisional recognized total: 15 / 25**

**Provisional qualification:** Sekiwake threshold and mandatory recognized levels appear satisfied. Not a final rank.

### Evidence gaps

- Independent sustained adoption/operation sufficient for E4/E5.
- Evidence for continuing Human Role delegation/substitution.
- Third-party validation of reliability and identity/governance behavior under long-running exception-heavy workloads.

---

## acumenix / agent-orchestrator — identity finding

### Original working finding

This pre-audit wave placed the repository on an identity hold because its public artifacts directly referenced `c9r-io/orchestrator`.

### Audit resolution — 2026-09-13

**Resolved: not a separate Rikishi.** GitHub repository metadata identifies `acumenix/agent-orchestrator` as a **fork** whose `parent` and `source` are both `c9r-io/orchestrator`. Under `RULES.md` → **Unit of Assessment / Rikishi Identity**, the repository is evidence/artifact of the same system lineage and is not counted as an additional independent Agent System.

Canonical Rikishi for this implementation lineage: **`c9r-io/orchestrator`**.

This resolution is an identity determination, not a zero score or a quality exclusion.

## Wave 4 observation

Wave 4 originally produced three working outcomes. After canonical identity cleanup:

- `chapzin/codex-harness-mcp` remains a provisional scored Rikishi whose explicit non-execution boundary caps Autonomy and Delegation.
- `highflame-ai/codeoid` remains a provisional scored Rikishi at the E3 working level.
- `acumenix/agent-orchestrator` is resolved as a duplicate fork of the already-counted `c9r-io/orchestrator` Rikishi and therefore receives no separate Banzuke entry.

No Claude/Copilot review or Torikumi is started at this stage.
