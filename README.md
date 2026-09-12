# Agent Systems Banzuke

**An evidence-first banzuke for agent systems engineering.**

Agent Systems Banzuke evaluates **systems**, not base models. Its highest-level question is simple:

> **How much does this system materially expand or improve human action?**

The project borrows the structure of professional sumo because the metaphor fits the problem: strength alone is not enough for the highest rank. Powerful agent systems must also remain governable under human authority.

## Philosophy

- **Fact First.** Record what can be established from evidence.
- **Strength and dignity.** Capability matters; so do reliability and human control.
- **Evidence, not reputation.** Stars, company size, popularity, and marketing claims do not raise a score.
- **One rubric.** Open, Team, and Individual divisions use the same technical standard.
- **Yokozuna may be vacant.** The highest score does not automatically produce a Yokozuna.
- **Append, don't rewrite.** A published banzuke is itself a historical fact. Later findings are appended rather than silently rewriting history.

## Divisions

- **Open Division** — all eligible systems, regardless of organization size.
- **Team Division** — systems led by two or more human development/research principals.
- **Individual Division** — systems whose principal architecture and implementation decisions are led by one human. Agents do not count as humans.

A system may appear in its applicable division and the Open Division. There is no solo bonus or organization-size adjustment.

## Evaluation

Five domains are each recognized from **0 to 5**, for a maximum of **25**:

1. Capability Expansion
2. Delegation Depth
3. Autonomy
4. Reliability
5. Human Control

Evidence is assessed independently for each domain. It does not add points; it limits what can be recognized:

`Recognized Level_i = min(Capability Level_i, Evidence Level_i)`

`Total Score = sum(Recognized Level_i)`

Rank requires both a score threshold and mandatory capability conditions. See [RUBRIC.md](RUBRIC.md).

## Ranks

**Yokozuna / Ozeki / Sekiwake / Komusubi / Maegashira**

Ranks are qualification classes, not a forced global 1-to-N ranking. Sanyaku and above use absolute standards. Maegashira is limited to five ranks per side and is ordered within the eligible field.

East/West follows banzuke semantics: within the same rank, **East is placed above West**.

Systems with the same rank and score enter a public **Torikumi** tie-break. The rubric determines strength; Torikumi determines ordering among otherwise tied systems.

## Basho cycle

- **1st:** previous month's Banzuke result is published; Monoii period begins.
- **1st–14th:** Monoii may be filed against the immediately preceding result, with evidence required.
- **14th:** evidence cutoff for the coming Basho.
- **15th–end of month:** Torikumi period.
- **1st of next month:** result published.

The inaugural September 2026 Basho is a bootstrap cycle: Torikumi runs **2026-09-15 through 2026-09-30**, with the first result published **2026-10-01**.

## Monoii

Anyone may challenge an assessment with concrete evidence during the Monoii period. A successful challenge does not erase a published historical result. Findings are recorded and become evidence for the next Basho. Factual clerical errors may be corrected explicitly as corrections.

## Assessment

Initial assessment uses independent fresh-read reviews by **GPT, Claude, and Copilot**, followed by evidence-based human adjudication. Review disagreement is investigated against the evidence rather than resolved by model majority vote.

## Repository

- [RULES.md](RULES.md) — competition and historical-record rules
- [RUBRIC.md](RUBRIC.md) — capability levels and rank qualification
- [EVIDENCE.md](EVIDENCE.md) — evidence gates and discovery policy
- [GOVERNANCE.md](GOVERNANCE.md) — assessment and adjudication
- `basho/` — immutable published Basho records and retrospective findings
- `rikishi/` — system assessment records

## Independence

Agent Systems Banzuke is an independent technology-evaluation project. It is not affiliated with or endorsed by the Japan Sumo Association or any evaluated project, vendor, or model provider.
