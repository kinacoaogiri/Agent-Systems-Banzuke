# Agent Systems Banzuke

**An evidence-first banzuke for Agent Systems Engineering.**

Agent Systems Banzuke evaluates **systems, not base models**.

The governing question is:

> **人間の行為にどれだけ有益か**
>
> **How much does this system materially expand or improve human action?**

Human Capability Impact may be realized by **Augmentation** or **Delegation / Substitution**. Novel architecture is evidence of how impact is achieved; novelty itself is not a scoring domain.

## Yokozuna principle

The sumo metaphor is deliberate. The technical analogue of strength plus 品格 is:

> **強大なCapabilityを持ちながら、その力をHuman Authorityの下で適切に行使できること**

> **強くなければ横綱になれない。強いだけでも横綱になれない。**

Human Control is therefore not moral decoration. It is a technical requirement that powerful autonomous capability remain observable, bounded, governable, and return material exceptions to Human Authority.

## Fact First

> **事実first。公開されてしまった時点で認定出来なかった事実があったとしても、公開されてしまった番付もまた事実なので覆せない。**

We distinguish **System Fact** from **Banzuke Fact**. A published Banzuke is a historical fact. Later evidence is appended as a Retrospective Finding and may affect a later Basho; it does not silently rewrite the published result. Clerical factual errors may be recorded as Corrections.

## Divisions

- **Open** — all eligible systems.
- **Team** — two or more human development/research principals.
- **Individual** — principal architecture and implementation decisions led by one human. Agents do not count as humans.

The same rubric applies to every division. There is no solo bonus.

## Five domains

1. Capability Expansion — **能力拡張**
2. Delegation Depth — **委任深度**
3. Autonomy — **自律性**
4. Reliability — **遂行信頼性**
5. Human Control — **人間統制可能性**

Each domain has Capability and Evidence levels from 0–5:

`Recognized Level_i = min(Capability Level_i, Evidence Level_i)`

Maximum total: **25**.

## Ranks

**Yokozuna / Ozeki / Sekiwake / Komusubi / Maegashira**

Ranks are qualification classes, not a forced global 1-to-N list. A rank, including Yokozuna, may be vacant. Within the same rank, East precedes West.

When final adjudication produces the **same Rank + same Score**, East/West is decided by a public **GitHub Discussion Poll** Torikumi.

> **実力を決めるのはRubric。東西を決めるのは取組。**

## Basho cadence

> **毎月15日、取組開始。毎月1日、番付発表。**

For a normal monthly Basho, its Evidence Period is the **15th of the preceding month through the 14th of the named month**. On the 15th, assessment results and required Torikumi cards are published; Torikumi runs through month-end; the Banzuke result is published on the 1st of the following month. While Torikumi is public, evidence collection for the next Basho is already running in parallel.

September 2026 is a bootstrap Basho; see `basho/2026-09/README.md`.

## Assessment pipeline

1. canonical audit / readiness
2. candidate discovery and identity cleanup
3. evidence collection + GPT first-pass across the full field
4. final evidence corpus freeze
5. independent Claude and Copilot Fresh-read against the same frozen corpus
6. discrepancy review against Rubric/Evidence
7. Human adjudication
8. Banzuke publication and Torikumi where applicable

AI reviewers are reviewers, not votes. Human adjudication is the final Gyoji/Authority Holder ruling.

## Canonical documents

- `RULES.md` — competition, Basho, Torikumi, Monoii, historical integrity
- `RUBRIC.md` — capability levels and rank qualification
- `EVIDENCE.md` — evidence gate and discovery policy
- `GOVERNANCE.md` — Fresh-read, adjudication and authority
- `basho/` — Basho working and published records
- `rikishi/` — per-system records

## Independence

Agent Systems Banzuke is an independent technology-evaluation project. It is not affiliated with or endorsed by the Japan Sumo Association or any evaluated project, vendor, or model provider.
