# Rules

## 1. Scope

Agent Systems Banzuke ranks publicly assessable **Agent Systems Engineering systems**, not base-model intelligence in isolation.

The governing purpose is Human Capability Impact: **人間の行為にどれだけ有益か**.

### Unit of Assessment / Rikishi Identity

A **Rikishi is one independent Agent System / product-system**. A Rikishi is not a user, author, organization, GitHub repository, or base model.

- One system spanning multiple repositories is one Rikishi; repositories are evidence/artifacts.
- One author or organization may have multiple Rikishi when they are distinct independently maintained/positioned systems.
- A fork that remains substantively the same system is generally not a separate Rikishi.
- A fork that materially diverges into an independently maintained and positioned system may qualify as a separate Rikishi after identity review.
- Same-name independently implemented and maintained products are separate Rikishi.
- Candidate counts are counts of distinct systems after identity resolution, not raw repository entries.

## 2. Yokozuna principle

The technical interpretation of sumo's demand for strength plus 品格 is:

> **強大なCapabilityを持ちながら、その力をHuman Authorityの下で適切に行使できること**

> **強くなければ横綱になれない。強いだけでも横綱になれない。**

Capability matters, but the highest rank also requires role-grade Reliability and strong Human Control. Human Control means technical governance under Human Authority, not a vague moral or aesthetic judgment.

## 3. Fact First

> **事実first。公開されてしまった時点で認定出来なかった事実があったとしても、公開されてしまった番付もまた事実なので覆せない。**

Assessment distinguishes:

- **System Fact** — what was actually implemented, demonstrated, operated, or otherwise evidenced by the cutoff.
- **Banzuke Fact** — what the assessment recognized and what rank was actually published.

A published Banzuke is not silently rewritten because stronger or previously missed evidence is later found. Later findings are appended as **Retrospective Findings** and may affect a later Basho.

A pure clerical factual error may be explicitly recorded as a **Correction**.

When public evidence cannot establish a capability, the correct finding is: **we do not conclude that the capability does not exist; we conclude that it was not publicly verifiable/recognized at the cutoff.**

## 4. Divisions

- **Open Division** — all eligible systems.
- **Team Division** — two or more human development/research principals responsible for principal architecture or implementation decisions.
- **Individual Division** — principal architecture and implementation decisions led by one human. AI agents do not count as additional humans.

The same Rubric applies to all divisions. There is no solo bonus, organization-size adjustment, popularity bonus, or vendor bonus.

## 5. Ranks

1. Yokozuna
2. Ozeki
3. Sekiwake
4. Komusubi
5. Maegashira

Yokozuna through Komusubi are absolute qualification classes and may be vacant. Maegashira is limited to **Maegashira 1 through 5 on each side**, at most ten systems per division.

Within the same rank, East precedes West.

## 6. Torikumi

Torikumi is used **only when final technical adjudication produces the same Rank and the same recognized Total Score**.

The formal Torikumi result is a **GitHub Discussion Poll**. Comments are spectator seats. Reactions such as 👍 may be enjoyed informally as **Zabuton**, but are not the formal result. GitHub Stars are never a tie-breaker.

Torikumi cannot change a capability score, waive a mandatory rank condition, or promote a lower-scoring system over a higher-scoring system.

> **実力を決めるのはRubric。東西を決めるのは取組。**

No tied-poll procedure is defined at present. A future procedure must be adopted explicitly and prospectively; assessors must not invent one ad hoc.

## 7. Basho calendar

> **毎月15日、取組開始。毎月1日、番付発表。**

For a Basho named for month M:

- **Evidence Period:** 15th of the preceding month through the 14th of month M.
- **Evidence cutoff:** end of the 14th of month M.
- **15th:** assessment results and any required Torikumi cards may be published; Torikumi begins.
- **15th through month-end:** public Torikumi period.
- **1st of the following month:** Banzuke result is published.

The next Basho's Evidence Period therefore overlaps the current Basho's public Torikumi period. Older public evidence remains admissible when still relevant to the system state at cutoff.

### September 2026 bootstrap

The inaugural Basho may use relevant public evidence available before the bootstrap cutoff. Its assessment field/evidence cutoff is **2026-09-14**; Torikumi begins **2026-09-15** and runs through **2026-09-30**; the first Banzuke result is published **2026-10-01**.

## 8. Monoii

A **Monoii** is an evidence-backed challenge to the immediately preceding published Banzuke result.

- Window: publication date through the next Basho evidence cutoff; under the normal cadence this is the **1st through 14th**.
- Only the immediately preceding result may be challenged.
- Concrete evidence is mandatory.
- Unsupported disagreement, reputation, popularity, or marketing claims are insufficient.
- Initial adjudication authority is the **Human Authority Holder supported by the AI evaluation group** under `GOVERNANCE.md`.

A sustained Monoii does not erase the published Banzuke. It is recorded and may affect the next Basho. Clerical errors are Corrections; evidence/judgment findings are Monoii or Retrospective Findings.

## 9. Sumo terminology

| Term | Project meaning |
|---|---|
| Banzuke | Monthly published ranking/classification record |
| Basho | Monthly evaluation cycle |
| Rikishi | One independent Agent System / product-system |
| Torikumi | Public GitHub Discussion Poll tie-break for same Rank + same Score |
| Monoii | Evidence-backed objection to the immediately preceding result |
| Gyoji | Assessment / initial ruling function; final publication ruling belongs to the Human Authority Holder |
| Shimpan | Reassessment/review function |
| Result | Formal GitHub Discussion Poll result where Torikumi applies |
| East / West | Ordering within the same rank |
| Zabuton | Informal spectator reaction/joke only; not a formal vote |

## 10. Historical integrity

Published Basho records identify their evidence cutoff and, where practical, evaluated versions or commits.

Historical rule:

> **Append, don't rewrite.**
