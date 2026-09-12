# Evidence Policy

## 1. Evidence is a gate, not a bonus

Evidence never raises a capability above what the system actually demonstrates. It limits the level that can be recognized.

Evidence is assessed **independently for each capability domain**.

`Recognized Level_i = min(Capability Level_i, Evidence Level_i)`

A strong autonomy demonstration does not automatically establish Human Control, Reliability, or Delegation at the same level.

## 2. Evidence Levels

| Level | Evidence state |
|---|---|
| E0 — Unverified | No publicly verifiable evidence sufficient for recognition. |
| E1 — Specified | Public specification, design, architecture, or equivalent clearly defines the claimed capability. |
| E2 — Implemented | Public source, executable artifact, or equivalent establishes implementation. |
| E3 — Demonstrated | Tests, demos, benchmarks, reproducible procedures, or equivalent establish actual execution. |
| E4 — Operationally Validated | Sustained operation, real-environment use, or comparable validation establishes practical execution. |
| E5 — Independently Established | Independent reproduction, adoption, sustained third-party evaluation, or comparable evidence independently establishes the capability. |

The label on the source does not determine its level. Evidence is graded by what it directly establishes.

## 3. Unknown is not zero

Failure to find evidence does not establish that a capability does not exist.

The finding is **Unverified**, not "non-existent." However, capability that cannot be publicly verified by the assessment cannot be used to obtain Banzuke rank.

## 4. Discovery policy

Search broadly; grade by evidentiary value, not by platform.

### Baseline discovery

For an assessed system, reviewers should inspect all reasonably identifiable **public GitHub repositories materially related to that system**, including separately maintained runtime, benchmark, documentation, example, or control-plane repositories when their relationship is established.

Repositories belonging to the same organization are not automatically aggregated into one system.

### Ranked candidates

Discovery expands to relevant:

- official documentation and websites;
- papers and technical reports;
- benchmarks and public demos;
- releases and executable artifacts;
- maintainer technical blogs;
- public operational reports.

### Upper-rank candidates

For serious upper-rank candidates, discovery should additionally include relevant public maintainer and third-party media such as:

- X and other public social posts;
- YouTube or other public demonstrations;
- independent repositories;
- third-party papers and evaluations;
- technical articles;
- community reports such as Hacker News or Reddit where materially relevant.

A social-media claim may be useful for discovery but is only Claim Evidence unless it directly establishes the fact in question or leads to stronger evidence.

### Yokozuna review

A Yokozuna candidate receives an adversarial public-web review seeking **contradictory or disconfirming evidence as well as supporting evidence**. The question is not merely whether evidence can support Yokozuna, but whether the classification survives serious public scrutiny.

## 5. Evidence value

As a general tendency, direct and independently reproducible evidence is stronger than indirect assertion. Examples include:

independent reproduction / real-world operation
→ reproducible benchmark or test
→ executable artifact and source
→ technical documentation or specification
→ maintainer claim
→ marketing claim

This is not a mechanical platform hierarchy. A third-party repository reproducing a capability may be stronger evidence than an official README. Evidence must be matched to the specific capability it is claimed to establish.

## 6. Conflicting evidence

When evidence conflicts, prefer evidence that is more direct, relevant, reproducible, and representative of the assessed system state.

A specification does not override contradictory execution evidence. A single failure report also does not automatically invalidate a broad capability. Reviewers must evaluate what each item actually establishes.

## 7. Cutoff and freshness

Each Basho must publish an evidence cutoff. Assessment records should identify evaluated version(s), commit(s), or release(s) where practical.

Earlier evidence remains admissible when it is still relevant to the system state at cutoff. Evidence published after cutoff cannot be retroactively used to change the already published result.

If evidence available before cutoff is discovered only later, it may be recorded as a **Retrospective Finding** and considered in the next Basho. The historical published Banzuke remains intact.

## 8. Public-evidence principle

Eligible evidence must have been publicly accessible to an independent third party by the applicable cutoff.

Private repositories, private conversations, unpublished internal documents, or evaluator-only knowledge cannot establish a Banzuke capability level.

Maintainers are therefore encouraged to make important capabilities and their supporting evidence reasonably discoverable. The assessment team also bears a duty to perform the discovery process defined here.
