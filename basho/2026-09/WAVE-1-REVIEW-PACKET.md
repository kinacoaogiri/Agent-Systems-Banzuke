# September 2026 Basho — Wave 1 Independent Review Packet

**Packet freeze: 2026-09-13**  
**Purpose:** independent Fresh-read assessment by Claude and Copilot, followed by Human adjudication.

This packet defines the review contract for Wave 1. Reviewers must not use the GPT provisional scores as authority and must not infer missing facts from prior knowledge or conversation history.

## Systems

1. Ancienttwo / repo-harness
2. artificemachine / superharness
3. c9r-io / orchestrator

## Canonical assessment rules

Reviewers must apply the repository's frozen rules:

- `RUBRIC.md`
- `EVIDENCE.md`
- `GOVERNANCE.md`
- `RULES.md`

The five domains are Capability Expansion, Delegation Depth, Autonomy, Reliability, and Human Control.

For every domain report:

`Capability Level / Evidence Level / Recognized Level / rationale`

where:

`Recognized Level = min(Capability Level, Evidence Level)`

Do not average domains. Do not award points for novelty, popularity, GitHub Stars, organization size, or being an individual project.

## Evidence corpus contract

The evidence corpus consists only of public artifacts directly attributable to the evaluated system plus explicitly identified third-party evidence. Maintainer statements are admissible but must be graded according to what they directly establish. Test volume, release activity, catalog inclusion, or architectural sophistication do not automatically establish E4 operational validation.

### Ancienttwo / repo-harness

Corpus facts frozen for review:

- Public repository implements a file-backed session contract and authorized long-running programs.
- Public artifacts expose durable plans/contracts/checks/reviews/handoffs.
- Authorized programs expose operator-minted authorization, budget ledgers, leases, receipts, bounded unattended controllers, persistent acceptance review, and explicit stop conditions.
- Public install/verification and CI-equivalent procedures exist.
- Public release material records a gate with 2,445 passing tests, 1 skipped, 0 failed.
- ClaudeAtlas independently indexes/evaluates a repository review skill and reports a 90/100 quality score.
- No sustained independent operational use of the complete harness has been established in this corpus.

### artificemachine / superharness

Corpus facts frozen for review:

- Public repository implements SQLite-backed coordination across multiple coding-agent CLIs.
- Public artifacts expose queue delegation, persistent task lifecycle, handoffs/ledger state, autonomous dispatch, approvals, discussions, consensus/deadlock state, heartbeat/liveness, retry/stale cleanup, watchdog deadlines, and telemetry.
- Repository-originated material reports 5,000+ tests and exposes status examples containing thousands of archived/done task records.
- Those status/test signals originate from the project itself.
- No independent sustained use or third-party reproduction sufficient to establish E4/E5 has been established in this corpus.

### c9r-io / orchestrator

Corpus facts frozen for review:

- Public project implements/describes a Rust control plane for shell-native coding agents using declarative workflows.
- Public artifacts expose daemon, SQLite persistence, workers, task/event state, workflow guards, sandbox enforcement, triggers, logs, recovery paths, mTLS/RBAC/secrets policy surfaces, and durable plan → implement → test → review → fix loops.
- Public install/quick-start and design/QA material exists.
- The GitHub repository was archived by its owner on 2026-09-03 and is read-only at this cutoff.
- Archival does not erase previously evidenced capability.
- Current sustained operation, migration/replacement, and independent operational validation have not been established in this corpus.

## Required reviewer output

For each system return exactly this structure:

```text
System: <owner/repo>
Reviewer: <Claude|Copilot>

Capability Expansion: Cx / Ex / Rx
Rationale: ...

Delegation Depth: Cx / Ex / Rx
Rationale: ...

Autonomy: Cx / Ex / Rx
Rationale: ...

Reliability: Cx / Ex / Rx
Rationale: ...

Human Control: Cx / Ex / Rx
Rationale: ...

Recognized Total: x/25
Provisional Rank Qualification: ...
Unresolved Evidence Gaps: ...
Rubric/Evidence Ambiguities: ...
```

## Reviewer constraints

- Fresh-read the rules and this packet.
- Do not read or copy `ASSESSMENT-WAVE-1.md` before producing the independent result.
- Do not use another reviewer's score as evidence.
- Do not resolve uncertainty by majority vote.
- If the corpus does not establish a fact, state the gap.
- Capability and Evidence must be reasoned independently.
- A system may have C4/C5 architecture while remaining E3 or below.
- Repository archival is a factual lifecycle signal, not an automatic capability penalty.
- A third-party catalog/review is not automatically operational validation.

## Adjudication rule

After GPT, Claude, and Copilot results exist, differences are compared domain-by-domain against the same Evidence corpus and Rubric. Human adjudication is the final Gyoji ruling. The Human is an Authority Holder, not a fourth equal vote.

No Torikumi may be opened from this packet alone. Torikumi requires final adjudicated same-Rank + same-Score status.
