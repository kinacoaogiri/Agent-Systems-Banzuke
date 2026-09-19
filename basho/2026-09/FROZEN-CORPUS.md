# September 2026 — Frozen Common Assessment Corpus

**Status: FROZEN FOR INDEPENDENT FRESH-READ**  
**Freeze date: 2026-09-19**  
**Evidence cutoff: 2026-09-14**  
**Field: 59 Rikishi**

## Freeze declaration

The September common assessment corpus is frozen after:

1. canonical audit/readiness;
2. candidate discovery and Rikishi identity cleanup;
3. full-field GPT provisional first-pass;
4. bounded Field Close at 59 Rikishi;
5. uniform full-field GPT re-evaluation and consistency audit;
6. upper-rank external/counter-evidence pass.

No post-cutoff evidence may be introduced into this frozen September corpus. No reviewer may use another reviewer's assessment as authority.

## Canonical authority included

Reviewers must apply, as frozen at this declaration:

- `RULES.md`
- `RUBRIC.md`
- `EVIDENCE.md`
- `GOVERNANCE.md`
- `basho/2026-09/CANDIDATES.md`
- `basho/2026-09/FIELD-CLOSE-AUDIT.md`
- `basho/2026-09/FIELD-CLOSE-FIRST-PASS.md`
- `basho/2026-09/UNIFORM-REEVALUATION.md`
- `basho/2026-09/UPPER-RANK-EVIDENCE-PASS.md`
- preserved `ASSESSMENT-WAVE-*.md` records only as evidence/history, not as another reviewer's authority.

## Frozen field

The field contains **59 distinct Rikishi**. Candidate identity/count authority is `CANDIDATES.md` plus `FIELD-CLOSE-AUDIT.md`.

## Frozen GPT working state

GPT's pre-independent-review working distribution is preserved as evidence of GPT's own assessment, but **must not be supplied as an answer key** to Claude or Copilot:

- Yokozuna: 0
- Ozeki: 4
- Sekiwake: 42
- Komusubi: 13

This distribution is not final Human adjudication.

## Fresh-read contract

Claude and Copilot each independently assess the same 59 Rikishi against the same frozen canonical rules and cutoff-public evidence.

For every Rikishi and each of the five domains, each reviewer returns:

- Capability Level (0–5);
- Evidence Level (E0–E5);
- Recognized Level = min(C, E);
- concise supporting evidence/rationale;
- contrary evidence or material uncertainty.

Each reviewer also returns Total Score and the highest Rank whose mandatory conditions are satisfied.

Reviewers must not:
- infer unavailable capability from reputation or popularity;
- transfer evidence between domains;
- credit base-model/host capability outside the Rikishi boundary;
- import evidence first made public after 2026-09-14;
- treat GPT's working score/rank as authority;
- resolve disagreement by majority vote.

## Next gate

After both independent Fresh-reads are recorded, perform a domain-by-domain discrepancy review against the frozen Rubric/Evidence. Then return disagreements to the Human Authority Holder for adjudication. Corpus freeze does not itself publish a Banzuke.
