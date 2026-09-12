# September 2026 Basho — Assessment Wave 3

**Assessment snapshot: 2026-09-13**

Status: **Evidence collection / provisional GPT fresh-read**

Wave 3 continues GPT primary assessment. Claude/Copilot review remains deferred until candidate/evidence completion.

## affectionatec / agentic-engineering

### Public evidence observed

The public repository provides ten chain skills, a router, and a verify-gated loop driver for documentation-first long-running development. Public mechanisms include PRD/spec/ADR/implementation-plan contracts, dependency-ordered atomic tasks, worktree isolation, independent fresh-context verification, binary evidence-backed PASS/FAIL, a three-failure circuit breaker, append-only status/handoff memory, branch/PR-per-task workflow, protected main, human merge gate, documentation drift detection, and brownfield onboarding. The repository presents these mechanisms as installable skills/commands operating through external coding-agent hosts.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 2 | **2** | The chain can materially expand coherent long-running agent development, but public evidence reviewed here primarily establishes implemented skills/contracts rather than an independently demonstrated integrated runtime. |
| Delegation Depth | 4 | 2 | **2** | The verify-gated loop driver and task chain support workflow/role-like delegation by design, but demonstrated continuing Role execution is not established. |
| Autonomy | 3 | 2 | **2** | Build→verify loops, checkpoints and circuit breaking permit bounded workflow autonomy while retaining human merge authority. |
| Reliability | 4 | 2 | **2** | Fresh-context verification, test ratchet, locked done conditions, crash recovery and evidence-carrying PRs are strong reliability mechanisms; operational evidence remains the gate. |
| Human Control | 5 | 2 | **2** | Human merge authority, immutable contracts, permission gates, stop/escalation conditions and audit history strongly specify governed autonomy, but E3+ runtime evidence is not established in this corpus. |

**Provisional recognized total: 10 / 25**

**Provisional qualification:** Komusubi threshold and mandatory recognized levels appear satisfied. Not a final rank.

### Evidence gaps

- Reproducible end-to-end demonstration of the complete chain on a representative project.
- Public adopter/operational evidence.
- Independent evidence of sustained loop execution and recovery.

---

## giuliastro / harness-remote

### Public evidence observed

The public project is explicitly a local-first control plane around native coding-agent Sessions rather than a replacement agent. It supports Codex CLI, Claude Code, OpenCode, OMP and PI; native Session discovery/resume; live activity; remote prompting and controls; cross-harness handoff with durable lineage; multi-machine access; reconnect recovery; and local-first credential/code boundaries. The project explicitly states that native harnesses retain reasoning, tool execution, permissions and session authority, and also documents current limitations: broad orchestration and additional concurrent ACP instances remain follow-up work.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 3 | 3 | **3** | Cross-device/native-session continuity and explicit cross-agent handoff materially extend practical human operation of coding agents. |
| Delegation Depth | 2 | 3 | **2** | It controls and continues native sessions, but intentionally leaves task intelligence/orchestration to underlying harnesses; Task-level delegation is the safer system-level recognition. |
| Autonomy | 2 | 3 | **2** | The system provides continuity/control rather than owning autonomous workflow execution; current README explicitly limits broad orchestration. |
| Reliability | 3 | 3 | **3** | Validated session discovery/continuation, reconnect recovery, durable lineage and stale-snapshot protection support demonstrated operational reliability of its actual scope. |
| Human Control | 4 | 3 | **3** | Native authority preservation, explicit handoff, remote Stop/control, local-first boundaries and honest capability discovery support strong observable/bounded governance. |

**Provisional recognized total: 13 / 25**

**Provisional qualification:** Komusubi. Sekiwake mandatory Autonomy >=3 is not satisfied. Not a final rank.

### Evidence gaps

- Broader autonomous orchestration is explicitly not yet the current validated scope.
- Independent sustained operational/adoption evidence for E4+.
- Evidence for Workflow/Role delegation owned by Harness Remote itself rather than inherited from native agents.

---

## XpressAI / xpressclaw

### Public evidence observed

The public Rust project describes a distributed, multiplayer control plane around native coding harnesses. It exposes durable Projects, Conversations, Tasks, persistent Agent identities and retained containers, queued autonomous task execution, recurring schedules, typed multi-agent workflows, implementation/review loops across different agents, shared memory, provenance, artifacts, questions/review decisions, cancellation, reconnect replay, interrupted-work queue recovery, isolated reusable environments, GitHub PR/review continuation, and desktop installers/releases. It explicitly separates harness-owned intelligence from its own control-plane responsibilities.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 3 | **3** | Persistent multi-agent work, automation and distributed control materially expand one human/team's practical execution capacity. |
| Delegation Depth | 4 | 3 | **3** | Durable Tasks, schedules and multi-agent workflows support coherent workflow delegation; continuing Human Role substitution is not yet established by the reviewed evidence. |
| Autonomy | 4 | 3 | **3** | Queued work, cron schedules, workflows, retained environments and restart recovery support workflow autonomy and persistence. |
| Reliability | 4 | 3 | **3** | Durable timelines, provenance, reconnect replay, interrupted-work recovery and released installers support strong demonstration-level reliability; independent sustained validation remains unestablished here. |
| Human Control | 4 | 3 | **3** | Structured questions/review decisions, provenance, cancellation, isolation, credential boundaries, observability and explicit network warnings provide governed control mechanisms. |

**Provisional recognized total: 15 / 25**

**Provisional qualification:** Sekiwake threshold and mandatory recognized levels appear satisfied. Not a final rank.

### Evidence gaps

- Independent sustained adoption/operation sufficient for E4/E5.
- Direct evidence of Role-level delegation rather than workflow automation.
- External validation of reliability across long-duration/exception-heavy operation.

## Wave 3 observation

Wave 3 separates three different system shapes that superficially share the word "harness":

- `affectionatec/agentic-engineering` has deep contracts, verification and Human gates, but its reviewed evidence is primarily an implemented skill/command suite, so the Evidence Gate holds recognition at E2.
- `giuliastro/harness-remote` is an executable control plane with demonstrated continuity/recovery, but deliberately does **not** claim ownership of broad autonomous orchestration. Its Capability levels, not Evidence levels, therefore cap Delegation and Autonomy.
- `XpressAI/xpressclaw` owns durable Tasks, schedules and multi-agent workflows as part of the control plane itself, so both Capability and E3 evidence support Sekiwake-level recognition.

This is precisely the distinction the rubric needs to preserve: Evidence weakness and Capability-scope weakness are different reasons for arriving at a lower Recognized Level.

No Claude/Copilot review or Torikumi is started at this stage.
