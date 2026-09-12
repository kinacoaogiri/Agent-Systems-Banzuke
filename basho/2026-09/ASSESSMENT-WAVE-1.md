# September 2026 Basho — Assessment Wave 1

**Assessment snapshot: 2026-09-13**

Status: **Evidence collection / provisional GPT fresh-read**

This document begins the first evidence-bearing assessment wave. Scores are deliberately not final Banzuke results. Claude and Copilot fresh-reads and Human adjudication remain required by GOVERNANCE.md.

## Method

For each system:

1. Identify the system and directly related public evidence.
2. Separate maintainer claims from implemented/demonstrated evidence.
3. Assess Capability Level and Evidence Level independently for each domain.
4. Recognized Level = min(Capability Level, Evidence Level).
5. Record unresolved evidence gaps rather than filling them by inference.

## Ancienttwo / repo-harness

### Public evidence observed

The public repository describes two explicit layers: a file-backed session contract and authorized long-running programs. Durable plans, contracts, checks, reviews, and handoffs are treated as authority rather than chat memory. Authorized programs require operator-minted authorization and use budget ledgers, leases, receipts, bounded unattended controllers, persistent acceptance review, and explicit stop conditions. The repository also exposes install/verification procedures and a CI-equivalent gate.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 3 | **3** | Enables a substantially smaller human control surface for long-running engineering work; public implementation and reproducible procedures are visible, but independent/operational validation has not yet been established in this review. |
| Delegation Depth | 4 | 3 | **3** | Authorized programs can advance multi-step engineering work across sessions under stored authority; evidence currently establishes workflow-level delegation more safely than full continuing Human Role substitution. |
| Autonomy | 4 | 3 | **3** | Unattended controller, leases, budgets, retry caps, resumability and persistent programs directly support workflow autonomy. Sustained role autonomy requires stronger operational evidence. |
| Reliability | 4 | 3 | **3** | Structured checks, receipts, review artifacts, CI gates, retries and failure states are strong reliability mechanisms; this review has not yet established sustained external operational validation. |
| Human Control | 5 | 3 | **3** | Authority, budgets, leases, hard edit-boundary enforcement, review surfaces and explicit stop conditions strongly support governed autonomy. Evidence strength, not apparent architecture, currently caps recognition. |

**Provisional recognized total: 15 / 25**

**Provisional qualification:** Sekiwake score threshold and mandatory recognized levels appear satisfied. This is not a final rank.

### Evidence gaps

- Independent reproduction/adoption evidence.
- Sustained real-world operating history sufficient for E4/E5 claims.
- Evidence directly demonstrating delegation of a continuing Human Role rather than bounded engineering programs.

---

## artificemachine / superharness

### Public evidence observed

The public repository presents a SQLite-backed multi-agent coordination system spanning Claude Code, Codex CLI, Gemini CLI, OpenCode and Pi. It exposes queue delegation, persistent task lifecycle, handoffs/ledger state, autonomous dispatch, approvals, discussions, consensus/deadlock state, heartbeat/liveness, retry/stale cleanup, watchdog deadlines, telemetry, and a large regression-test suite. The public status example exposes thousands of archived/done task records, but this review does not treat a maintainer-provided status snapshot by itself as independent operational validation.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 3 | **3** | Multi-agent coordination and autonomous dispatch materially expand one operator's execution capacity; public implementation/test evidence supports demonstration level. |
| Delegation Depth | 4 | 3 | **3** | Persistent queues and autonomous task lifecycle support multi-task workflow delegation; continuing Human Role substitution is not yet established. |
| Autonomy | 4 | 3 | **3** | Autonomous dispatch, watcher/heartbeat, retry, stale cleanup and deadlines support workflow autonomy and recovery behavior. |
| Reliability | 4 | 3 | **3** | 5,000+ tests are claimed and concrete lifecycle/watchdog mechanisms are public; independent or sustained operational validation remains to be established. |
| Human Control | 4 | 3 | **3** | Approvals, waiting-input states, discussions, lifecycle states and observable status provide meaningful governed control; stronger evidence is needed for E4 recognition. |

**Provisional recognized total: 15 / 25**

**Provisional qualification:** Sekiwake score threshold and mandatory recognized levels appear satisfied. This is not a final rank.

### Evidence gaps

- Independent reproduction/adoption evidence.
- Operational history establishing E4 Reliability/Autonomy.
- Direct evidence for Role-level delegation and authority boundaries comparable to the strongest governance-oriented candidates.

---

## c9r-io / orchestrator

### Public evidence observed

The project describes a Rust control plane for shell-native coding agents using declarative workflows. Public documentation exposes a daemon, SQLite persistence, workers, task/event state, workflow guards, sandbox enforcement, triggers, logs, recovery paths, mTLS/RBAC/secrets policy surfaces, and durable plan → implement → test → review → fix loops. Documentation includes install/quick-start procedures and dedicated design/QA material.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 3 | **3** | Converts multiple shell-native agents into a reusable engineering control plane and durable workflow system. |
| Delegation Depth | 4 | 3 | **3** | Long-running multi-step workflows and trigger-based tasks support workflow delegation; Human Role substitution has not been established. |
| Autonomy | 4 | 3 | **3** | Persistent daemon/workers, triggers, guarded loops and recovery paths support workflow autonomy. |
| Reliability | 4 | 3 | **3** | Persistence, loop guards, QA material and recovery mechanisms support demonstrated operational design, but E4 external/long-running validation remains unestablished here. |
| Human Control | 4 | 3 | **3** | RBAC, sandboxing, policy rails, secrets lifecycle, observability and guard steps provide strong bounded/governed control architecture. |

**Provisional recognized total: 15 / 25**

**Provisional qualification:** Sekiwake score threshold and mandatory recognized levels appear satisfied. This is not a final rank.

### Evidence gaps

- Independent reproduction or third-party sustained use.
- Evidence establishing long-duration role autonomy/reliability at E4+.
- Direct evidence of continuing Human Role delegation/substitution.

---

## Wave 1 observation

The first three strong candidates converge at **15 recognized points** under conservative evidence gating, despite architectural differences. This is useful: the per-domain Evidence Gate is preventing sophisticated design claims from automatically becoming Ozeki-level recognized capability.

No Torikumi is opened from this provisional tie. A Torikumi requires final adjudicated Rank + Score after the complete review process.

## Next

- Expand each Evidence corpus beyond project self-description.
- Search for operational and third-party evidence capable of moving individual domains from E3 to E4/E5.
- Run independent Claude and Copilot fresh-reads on the same frozen corpus.
- Continue Wave 2 with other high-signal candidates.
