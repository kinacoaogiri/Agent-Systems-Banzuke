# Evidence Policy

## 1. Evidence is a gate, not a bonus

Evidence does not add points. It limits what can be publicly recognized in each domain.

`Recognized Level_i = min(Capability Level_i, Evidence Level_i)`

Evidence does not transfer across domains.

## 2. Evidence Levels

| Level | Evidence state |
|---|---|
| E0 — Unverified | No public verifiable evidence sufficient for recognition. |
| E1 — Specified | Public specification/design/architecture clearly defines the capability. |
| E2 — Implemented | Public source/executable artifact establishes implementation. |
| E3 — Demonstrated | Tests, demos, benchmarks, reproducible procedures or equivalent establish actual execution. |
| E4 — Operationally Validated | Sustained operation, real-world/environment use, or comparable operational validation establishes practical execution. |
| E5 — Independently Established | Third-party reproduction, adoption, sustained independent evaluation, or comparable evidence independently establishes the capability. |

The source label does not determine the level. Grade what the evidence directly establishes.

## 3. Unknown is not zero

Failure to find evidence does not establish non-existence.

> **We do not conclude that the capability does not exist. We conclude that it was not publicly verifiable/recognized at the cutoff.**

Unverified capability cannot be used to obtain Banzuke rank.

## 4. Discovery policy

> **Search broadly. Grade by evidentiary value, not by platform.**

### Baseline

Inspect all reasonably identifiable public GitHub repositories materially related to the system, including runtime, benchmark, docs, examples and control-plane repositories when the relationship is established. Repositories from the same organization are not automatically one system.

### Ranked candidates

Broaden to relevant official docs/sites, papers, technical reports, benchmarks, demos, releases, executable artifacts, maintainer technical blogs and public operational reports.

### Upper-rank candidates

Broaden further to X/other public social posts, YouTube/public demonstrations, independent repositories, third-party papers/evaluations/articles, Hacker News, Reddit and materially relevant community reports.

A social-media claim alone is Claim Evidence unless it directly records the relevant fact or leads to stronger evidence.

### Yokozuna candidates

Perform an adversarial public-web search for **counter-evidence, failures, contradictory reports and disconfirming evidence**, not only support.

## 5. Conflicting evidence

Prefer evidence that is more direct, relevant, reproducible and representative of the assessed system state. A specification does not override contradictory execution evidence. A single failure does not automatically erase broad demonstrated capability.

## 6. Cutoff and freshness

Each Basho publishes an Evidence cutoff. Assessment records should identify evaluated versions, commits or releases where practical.

For a normal Basho, the Evidence Period runs from the **15th of the preceding month through the 14th of the named month**. Earlier public evidence remains admissible if still relevant to system state at cutoff.

Evidence after cutoff cannot retroactively change a published result. Evidence that existed before cutoff but is discovered later may be appended as a Retrospective Finding and considered in a later Basho.

## 7. Public-evidence principle

Evidence must have been publicly accessible to an independent third party by the applicable cutoff. Private repositories, private conversations, unpublished internal documents and evaluator-only knowledge cannot establish a recognized level.

## 8. Assessment corpus lifecycle

Working evidence and GPT first-pass assessments remain **provisional** during candidate discovery.

The final corpus is frozen only after:

1. canonical audit/readiness;
2. candidate discovery and identity cleanup;
3. evidence collection and GPT first-pass for the full candidate field;
4. upper-rank external/counter-evidence passes as required.

Only the resulting common frozen corpus is sent to Claude and Copilot for independent Fresh-read review.
