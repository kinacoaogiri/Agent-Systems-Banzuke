# September 2026 Basho — Assessment Wave 9

**Assessment snapshot: 2026-09-13**

Status: **Evidence collection / provisional GPT fresh-read — upper-rank E4 review refreshed**

> **Audit status:** This is a provisional GPT working record. Canonical rules had been restored before this assessment, but field/identity cleanup and full-field evidence review were still in progress. It is not a final Banzuke result. Claude/Copilot Fresh-read occurs only after final corpus freeze.

## nodera-studio / agent-os

Provisional GPT result unchanged: **15/25, Sekiwake**. Evidence remains E3.

## Dusttoo / orka

Provisional GPT result unchanged: **15/25, Sekiwake**. Evidence remains E3.

## dwiedeman / work-harness

### Public evidence observed

`work` decomposes projects into PR-sized units, dispatches autonomous leads across local/SSH/cloud hosts and uses a persistent shepherd to move PRs through review to merge, backed by an append-only ledger. It publishes measured evidence across four runs / 25 PRs and a concrete production run dated 2026-08-13: **14 issues dispatched, 8 PRs merged, 8 issues closed, 42 lead spawns, 35 handoffs, 3,869,918,152 ledger-folded tokens and 46.51 hours**. It also publishes measured review-round behavior by diff size, explicit cost floor (~$2,225 for the cited run), preflight checks designed to fail visibly, version-skew enforcement, mandatory plan review and cross-run calibration that refuses self-comparison.

### Provisional GPT fresh-read — E4 consistency review

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 5 | 4 | **4** | Multi-host backlog delivery materially substitutes substantial execution/coordination effort and is supported by multiple-run measurements plus a 46.51-hour production record. |
| Delegation Depth | 5 | 4 | **4** | Planner/lead/shepherd roles carry PR-sized work from decomposition through review/merge over long runs. |
| Autonomy | 5 | 4 | **4** | Persistent shepherding, session replacement survival and multi-host dispatch are evidenced over long-running real operation. |
| Reliability | 4 | 4 | **4** | Concrete successes, incomplete delivery, review rounds, cost and failure-capable preflight make this unusually falsifiable operational evidence. It supports Dependable, not Role-grade, recognition. |
| Human Control | 4 | 4 | **4** | The Human `/work` session remains explicit orchestrator; mandatory plan review, risk/gate mechanisms, append-only ledger and bounded dispatch preserve authority and observability. |

**Provisional recognized total: 20 / 25**

**Provisional qualification:** Ozeki. Not a final rank.

### Contrary / limiting evidence

- The project explicitly says **“You are the orchestrator; the harness is the plumbing you shell out to.”** Full Human Role Holder substitution is therefore not recognized.
- The cited production run merged only 8 of 14 dispatched issues and required 42 lead spawns/35 handoffs.
- Resource cost is extreme: the project reports ~3.87B ledger-folded tokens and an estimated ~$2,225 floor for that run.
- Broad web/community search did not locate qualifying independent reproduction/adoption evidence in this pass. E5 remains unrecognized.

**E4 ruling:** **CONFIRMED.** This is the clearest E4 example in the current field because it publishes sustained real-operation duration, volume, outcomes, inefficiency and cost rather than only a success showcase.

## kim-dongho / agent-harness-starter

Provisional GPT result unchanged: **15/25, Sekiwake**. Evidence remains E3.

## Wave 9 upper-rank review observation

`dwiedeman/work-harness` remains provisionally Ozeki at 20/25. Its evidence is project-originated but qualifies for E4 because E4 requires sustained operation/real-world evidence, not independence. The same facts also prevent over-ranking: Human orchestration remains explicit, only 8/14 dispatched issues merged in the cited run, and cost is very high.

No Claude/Copilot review or Torikumi is started at this stage.
