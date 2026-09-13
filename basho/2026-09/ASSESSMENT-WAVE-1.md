# September 2026 Basho — Assessment Wave 1

**Assessment snapshot: 2026-09-13**

Status: **Evidence collection / provisional GPT fresh-read**

> **Audit status:** This is a provisional GPT working record created before completion of the 2026-09-13 canonical audit. It is preserved as working history, not a final Banzuke result. Scores/rank labels must be re-evaluated against the restored canonical rules after field/identity cleanup and full-field evidence collection. Claude/Copilot Fresh-read occurs only after final corpus freeze.

This document begins the first evidence-bearing assessment wave. Scores are deliberately not final Banzuke results. Independent Claude/Copilot Fresh-read and Human adjudication remain required by `GOVERNANCE.md`, but Claude/Copilot review is a **post-freeze full-corpus stage**, not a per-wave stage.

## Method

For each system:

1. Identify the system and directly related public evidence.
2. Separate maintainer claims from implemented/demonstrated evidence.
3. Assess Capability Level and Evidence Level independently for each domain.
4. Recognized Level = min(Capability Level, Evidence Level).
5. Record unresolved evidence gaps rather than filling them by inference.

## Ancienttwo / repo-harness

### Public evidence observed

The public repository describes two explicit layers: a file-backed session contract and authorized long-running programs. Durable plans, contracts, checks, reviews, and handoffs are treated as authority rather than chat memory. Authorized programs require operator-minted authorization and use budget ledgers, leases, receipts, bounded unattended controllers, persistent acceptance review, and explicit stop conditions. The repository exposes install/verification procedures and a CI-equivalent gate. Public release material records a release gate with 2,445 passing tests (1 skipped, 0 failed). A third-party skill index, ClaudeAtlas, independently indexes the repository's review skill and reports a 90/100 quality score; this establishes external discovery/evaluation, but does not by itself establish sustained operational use of the harness.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 3 | **3** | Enables a substantially smaller human control surface for long-running engineering work; implementation, reproducible procedures and release verification are public. External operational validation is not yet established. |
| Delegation Depth | 4 | 3 | **3** | Authorized programs can advance multi-step engineering work across sessions under stored authority; evidence currently establishes workflow-level delegation more safely than full continuing Human Role substitution. |
| Autonomy | 4 | 3 | **3** | Unattended controller, leases, budgets, retry caps, resumability and persistent programs directly support workflow autonomy. Sustained role autonomy requires stronger operational evidence. |
| Reliability | 4 | 3 | **3** | Structured checks, receipts, review artifacts, CI gates and public release-test evidence support E3 strongly; sustained real-world/independent validation required for E4 remains missing. |
| Human Control | 5 | 3 | **3** | Authority, budgets, leases, hard edit-boundary enforcement, review surfaces and explicit stop conditions strongly support governed autonomy. Evidence strength, not apparent architecture, currently caps recognition. |

**Provisional recognized total: 15 / 25**

**Provisional qualification:** Sekiwake score threshold and mandatory recognized levels appear satisfied. This is not a final rank.

### Evidence gaps

- Independent reproduction/adoption showing actual use of the complete harness rather than indexing/reviewing its published artifacts.
- Sustained real-world operating history sufficient for E4/E5 claims.
- Evidence directly demonstrating delegation of a continuing Human Role rather than bounded engineering programs.

---

## artificemachine / superharness

### Public evidence observed

The public repository presents a SQLite-backed multi-agent coordination system spanning Claude Code, Codex CLI, Gemini CLI, OpenCode and Pi. It exposes queue delegation, persistent task lifecycle, handoffs/ledger state, autonomous dispatch, approvals, discussions, consensus/deadlock state, heartbeat/liveness, retry/stale cleanup, watchdog deadlines, telemetry, and a large regression-test suite. The public status example exposes thousands of archived/done task records and the repository reports 5,000+ tests. These are strong project-originated demonstration signals, but the external discovery pass did not establish independent sustained use or third-party reproduction sufficient for E4/E5 recognition.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 3 | **3** | Multi-agent coordination and autonomous dispatch materially expand one operator's execution capacity; public implementation/test evidence supports demonstration level. |
| Delegation Depth | 4 | 3 | **3** | Persistent queues and autonomous task lifecycle support multi-task workflow delegation; continuing Human Role substitution is not yet established. |
| Autonomy | 4 | 3 | **3** | Autonomous dispatch, watcher/heartbeat, retry, stale cleanup and deadlines support workflow autonomy and recovery behavior. |
| Reliability | 4 | 3 | **3** | Extensive tests and concrete lifecycle/watchdog mechanisms strongly support E3; independent or sustained operational validation remains unestablished. |
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

**Lifecycle finding:** the public GitHub repository was archived by its owner on **2026-09-03** and is read-only. This is a material System Fact at the September cutoff. Archival does not erase capability already evidenced, but it weakens any inference of current continuing operation and makes E4/E5 operational validation especially important before recognizing higher Reliability or sustained Autonomy.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 3 | **3** | Converts multiple shell-native agents into a reusable engineering control plane and durable workflow system. |
| Delegation Depth | 4 | 3 | **3** | Long-running multi-step workflows and trigger-based tasks support workflow delegation; Human Role substitution has not been established. |
| Autonomy | 4 | 3 | **3** | Persistent daemon/workers, triggers, guarded loops and recovery paths support workflow autonomy as implemented capability. Current sustained operation is not established. |
| Reliability | 4 | 3 | **3** | Persistence, loop guards, QA material and recovery mechanisms support demonstration-level reliability; repository archival blocks any casual inference of current operational validation. |
| Human Control | 4 | 3 | **3** | RBAC, sandboxing, policy rails, secrets lifecycle, observability and guard steps provide strong bounded/governed control architecture. |

**Provisional recognized total: 15 / 25**

**Provisional qualification:** Sekiwake score threshold and mandatory recognized levels appear satisfied. This is not a final rank.

### Evidence gaps

- Reason/status of archival and whether development or operation continued elsewhere.
- Independent reproduction or third-party sustained use.
- Evidence establishing long-duration role autonomy/reliability at E4+.
- Direct evidence of continuing Human Role delegation/substitution.

---

## External evidence pass — 2026-09-13

The first broader search was explicitly aimed at finding evidence capable of lifting E3 recognition to E4/E5: sustained real-world operation, independent reproduction/adoption, or third-party evaluation.

**Result:** no Wave 1 candidate is promoted above E3 in any domain on this pass.

- **repo-harness:** public release verification and third-party indexing/evaluation strengthen E3, but do not yet establish sustained independent operational use.
- **superharness:** substantial repository-originated test and lifecycle evidence remains strong E3 evidence; no qualifying E4 external operational evidence was established in this pass.
- **c9r-io/orchestrator:** the repository's 2026-09-03 archival is recorded as counter-evidence against assuming current sustained operation. Capability evidence remains valid, but operational continuity must be proved rather than inferred.

This pass demonstrates an important distinction in the Evidence Gate: popularity, release activity, test volume, or a third-party catalog entry can strengthen confidence in E3 without automatically satisfying E4.

## Wave 1 observation

The first three strong candidates remain at **15 recognized points** under conservative evidence gating, despite architectural differences. The per-domain Evidence Gate is preventing sophisticated design claims from automatically becoming Ozeki-level recognized capability.

No Torikumi is opened from this provisional tie. A Torikumi requires final adjudicated Rank + Score after the complete review process.

## Next

- Preserve this Wave 1 record as pre-audit working history.
- Complete field/identity cleanup and full-field evidence collection.
- Re-evaluate all Rikishi uniformly against the restored canonical rules.
- Freeze one common final evidence corpus only after the full-field and upper-rank evidence passes are complete.
- Run independent Claude/Copilot Fresh-read only on that frozen corpus.
