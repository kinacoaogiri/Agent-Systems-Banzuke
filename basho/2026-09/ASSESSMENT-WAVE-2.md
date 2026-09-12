# September 2026 Basho — Assessment Wave 2

**Assessment snapshot: 2026-09-13**

Status: **Evidence collection / provisional GPT fresh-read**

Wave 2 continues GPT primary assessment. Claude/Copilot review is intentionally deferred until the candidate field and evidence collection are complete.

## majiayu000 / harness

### Public evidence observed

The public Rust repository presents a fleet control plane for coding agents. It exposes structured thread/task/turn lifecycles, parallel fleet orchestration, automatic independent cross-agent review, a Starlark policy engine, sandbox modes and privilege enforcement, signal-driven remediation, GitHub webhook automation, OpenTelemetry export, MCP server mode, CI/CD integration, Postgres persistence, health probing, recovery-oriented server tests, and explicit validation ladders. The README also documents limitations and unsafe modes rather than treating all adapters as equally sandboxable.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 3 | **3** | A fleet control plane materially expands a human operator's ability to coordinate heterogeneous coding agents. Public implementation and reproducible procedures establish demonstration-level evidence. |
| Delegation Depth | 4 | 3 | **3** | Task/thread/turn lifecycle, dispatch, independent review and remediation support coherent multi-task workflow delegation. Continuing Human Role substitution is not yet established. |
| Autonomy | 4 | 3 | **3** | Fleet dispatch, webhook triggers, remediation loops and persistent server state support workflow autonomy; sustained role autonomy requires stronger operating evidence. |
| Reliability | 4 | 3 | **3** | Validation ladders, DB-backed tests, recovery paths, health probes and CI are strong E3 signals. Sustained independent operational validation has not yet been established in this pass. |
| Human Control | 5 | 3 | **3** | Policy enforcement, sandbox tiers, privilege controls, independent review, observability and explicit unsafe-mode disclosures strongly support governed autonomy, but evidence remains capped at E3 here. |

**Provisional recognized total: 15 / 25**

**Provisional qualification:** Sekiwake threshold and mandatory recognized levels appear satisfied. Not a final rank.

### Evidence gaps

- Sustained third-party/real-world operational evidence.
- Independent reproduction/adoption beyond project-originated validation.
- Evidence that continuing role responsibility, rather than workflows, is delegated in practice.

---

## DIodide / Harness

### Public evidence observed

The public monorepo is a control plane over Claude Code, Codex CLI and Cursor running in isolated cloud sandboxes. It exposes persistent realtime conversation/workspace state, live agent/tool streaming, owner/editor/viewer authority distinctions, inline approvals, server-side encrypted credentials, restricted sandbox egress with server-side MCP relay, background-agent observability, rewind/fork, usage ledger, CI tests and deployment configuration. The project explicitly shows a real agent run and describes the security boundaries around shared sessions and credentials.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 3 | 3 | **3** | Makes remote/shared operation and observation of coding agents practical and materially expands collaborative control, though the evidence does not establish transformation of a full engineering role. |
| Delegation Depth | 3 | 3 | **3** | Multi-step agent plans, background agents and tool execution establish workflow-level delegation more clearly than continuing Role delegation. |
| Autonomy | 3 | 3 | **3** | Background agents and long-running commands support workflow autonomy, while approval surfaces intentionally retain human intervention at sensitive boundaries. |
| Reliability | 3 | 3 | **3** | CI, persistent state, sandbox isolation, fail-soft Redis behavior and deployment architecture support operationally designed repeatability; sustained external validation is not established. |
| Human Control | 4 | 3 | **3** | Approval cards, viewer/editor distinctions, server-side secrets, sandboxing, restricted egress, usage accounting, live observability and rewind/fork provide strong governance architecture. |

**Provisional recognized total: 15 / 25**

**Provisional qualification:** Sekiwake threshold and mandatory recognized levels appear satisfied. Not a final rank.

### Evidence gaps

- Independent sustained use/reproduction.
- Evidence for Role-level delegation or sustained autonomous responsibility.
- External operational evidence sufficient for E4 Reliability/Human Control.

---

## ldaume / agentic-engineering-harness

### Public evidence observed

This repository explicitly describes itself as installable Agent Skills plus harness blueprints, **not a control plane for another system**. It defines single-repository, multi-repository and multi-team operating models; Git-owned authority and context; explicit decision rights; fast/full gates; fresh-agent critique; recovery paths; L1-L7 delegation guidance; cost-aware/provider-neutral routing; and a closed signal → discovery → implementation → delivery → operations → evolution loop. It also states that humans retain goals, policy, risk and accountability, and that autonomy should expand only when evidence supports it. Validation includes installation testing across multiple agent hosts, but actual runtime execution remains delegated to those hosts and to adopter repositories.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 2 | **2** | The operating model can structurally expand agent-assisted engineering, but the repository is primarily executable skills plus blueprints rather than an integrated runtime. Public implementation supports E2; representative adopter operation is needed for E3+. |
| Delegation Depth | 5 | 2 | **2** | The design explicitly reaches high delegation levels and continuing loops, but the repository itself does not establish that Role Substitution is implemented and demonstrated as one system. |
| Autonomy | 4 | 2 | **2** | The blueprint supports autonomous progress under bounded authority, but execution depends on external agent hosts/adopter harnesses. |
| Reliability | 4 | 2 | **2** | Strong verification philosophy, gates and recovery contracts are implemented as skills/blueprints; representative sustained runtime evidence for the composed system is not established. |
| Human Control | 5 | 2 | **2** | Human authority, decision rights, escalation, evidence-gated autonomy and stop paths are exceptionally explicit, but the Evidence Gate prevents architectural specification from being treated as demonstrated governed runtime. |

**Provisional recognized total: 10 / 25**

**Provisional qualification:** Komusubi threshold and mandatory recognized levels appear satisfied. Not a final rank.

### Evidence gaps

- A concrete public adopter/system instance demonstrating the complete harness model.
- Representative workloads proving that the skills and blueprint compose into the claimed delegation/autonomy loop.
- Operational and independent evidence for Reliability and Human Control above E2.

## Wave 2 observation

Wave 2 exposes a useful boundary in the rubric. `majiayu000/harness` and `DIodide/Harness` contain integrated executable control planes and can presently reach E3 recognition from public implementation/demonstration evidence. `ldaume/agentic-engineering-harness` describes a sophisticated governance and delegation architecture, but explicitly identifies itself as skills and blueprints rather than the runtime control plane. Under Fact First, that distinction materially lowers the Evidence Gate rather than the apparent architectural Capability ceiling.

No Claude/Copilot review or Torikumi is started at this stage.
