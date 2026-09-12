# September 2026 Basho — Assessment Wave 4

**Assessment snapshot: 2026-09-13**

Status: **Evidence collection / provisional GPT fresh-read**

Wave 4 continues GPT primary assessment. Claude/Copilot review remains deferred until candidate/evidence completion.

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

### Public evidence observed

The current `acumenix/agent-orchestrator` README is not merely similar to `c9r-io/orchestrator`: its badges, installation command, documentation links, integration repository, and project text directly point to `c9r-io/orchestrator`. The repository's visible recent commits are authored by `gpgkd906`, while the README installs binaries from the c9r-io path.

### Assessment disposition

**Do not score as a separate Rikishi at this stage.**

The evidence establishes a material identity/lineage relationship that must be resolved before treating `acumenix/agent-orchestrator` and `c9r-io/orchestrator` as independent systems. Counting both now risks double-entry of the same implementation lineage.

Status: **IDENTITY HOLD — canonical repository/lineage resolution required.**

This is not a zero score and not an exclusion on quality grounds. It is a Fact First identity gate.

## Wave 4 observation

Wave 4 produces three distinct outcomes:

- `chapzin/codex-harness-mcp` demonstrates a substantial governance/evidence control plane, but its own explicit non-execution boundary caps Autonomy and Delegation. This is a Capability-scope limit, not an Evidence penalty.
- `highflame-ai/codeoid` reaches the recurring 15-point Sekiwake band, with unusually strong apparent Human Control architecture around identity, delegation and budgeted autonomy; E3 still caps recognition.
- `acumenix/agent-orchestrator` is held out of scoring because the public artifacts directly reference `c9r-io/orchestrator`, creating a likely duplicate/lineage issue. The Banzuke must establish system identity before assigning a second rank.

No Claude/Copilot review or Torikumi is started at this stage.
