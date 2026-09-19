# September 2026 — Upper-Rank External / Counter-Evidence Pass

**Status: COMPLETE / PRE-FREEZE**  
**Evidence cutoff: 2026-09-14**  
**Field: 59 Rikishi (FIELD CLOSED)**

This pass follows the uniform 59-Rikishi re-evaluation. Its purpose is not to discover new Rikishi. It searches for evidence capable of changing upper-rank recognition: sustained real operation (E4), independent establishment (E5), and contrary/failure evidence that limits Reliability, Autonomy, Delegation or Human Control.

## Search scope

The pass broadened beyond root READMEs to cutoff-public repository operational reports, dated run/eval records, changelogs, issue/PR evidence, papers/benchmarks where surfaced, and exact-name public-web searches for adoption, sustained use, production operation and failures. The common E4 rule remains: project-originated evidence may qualify when duration/volume/outcomes/failures are concrete and interpretable; independence begins at E5.

No candidate is promoted from stars, popularity, release count, a single showcase, bare cumulative counters, or maintainer assertion alone.

## Material changes

### majiayu000 / harness — E4 established

Cutoff-public operational evidence materially exceeds the earlier E3 reading.

- `evals/cursor-real/production-recovery-20260910.md` records deployment to an existing production server whose GitHub intake covered **87 configured repositories** with **20 concurrent runtime slots**.
- The same production recovery found **41 stopped parent workflows**; 35 still-open PR subjects were eligible and all **35 recovery requests** were accepted through the runtime API, producing 20 running and 15 pending local-review activities.
- `docs/workflow-multi-project-batch.md` records a multi-project batch with **16 PRs created, 11 merged, 6 merge conflicts resolved, ~2 hours** for the P0+P1 cycle.
- `docs/features/8-31/agent-contract-slice-d-production-dogfood.md` preserves a real production Codex dispatch, concrete timing/token/accounting, restart/replay proof and multiple failure discoveries/corrections rather than only a success claim.
- Counter-evidence is preserved: automatic merge was disabled in the recovery record; some evaluation paths explicitly say they do not prove long-running reliability; the Slice-D run itself was deliberately bounded.

**Refreshed recognized vector: 4 / 4 / 4 / 4 / 4 = 20/25.**  
**Working qualification: Ozeki.**

The E4 recognition is based on repeated real production workflow operation with concrete repository count, concurrency, stopped/recovered workflow population, PR outcomes and failure/recovery evidence. It is not an E5 finding; independent third-party establishment was not located in this pass.

### Enderfga / claw-orchestrator — E4 established

The cutoff changelog contains unusually concrete operational evidence.

- `CHANGELOG.md` v6.0.4 (2026-08-26) reports measurement over **1,834 production sessions** for an OpenAI-compatible conversation-history defect, including comparative success counts (**2/32** on the affected path versus **235/309** on another engine path).
- The same record preserves the failure mechanism and corrective boundary rather than reporting only successful use.
- v7.0.0 (2026-09-04) records autoloop defects surfaced in real use, explicitly describes autoloops intended to run for **hours or days**, and adds bounded send deadlines, inactivity leases, hard lifetime caps and recoverable `awaiting_resume` behavior.
- v7.1.x / v7.2.0 records repeated live engine sweeps through the real wrapper and concrete permission-denial / model-registry findings across supported engines.
- Counter-evidence is material: the 1,834-session record exposes a severe history-carry failure on one path, and later releases document timeout, permission-denial and wrapper-regression defects. These prevent any Reliability-5 inference.

**Refreshed recognized vector: 4 / 4 / 4 / 4 / 4 = 20/25.**  
**Working qualification: Ozeki.**

Again, this is E4 project-originated operational evidence, not E5 independent establishment.

## Existing Ozeki counter-evidence retained

### kai-linux / agent-os — 20/25 retained

The existing rolling operational record remains qualifying E4 because it publishes repeated task volume, successes, escalations and blocker categories over time. The same evidence remains direct counter-evidence against Reliability 5: success rate and escalation rate are visibly imperfect and workload-specific.

### dwiedeman / work-harness — 20/25 retained

The dated production run and four-run/25-PR corpus remain qualifying E4. The same corpus limits over-ranking: the cited production run merged 8 of 14 dispatched issues, required 42 lead spawns / 35 handoffs, and reported very high token/cost consumption. Human orchestration also remains explicit.

## Strong evidence that remains below E4 recognition

- **Ancienttwo/repo-harness:** multiple dated real-provider canaries, self-hosted release/run artifacts and candid negative experiments materially strengthen E3, but the reviewed corpus does not yet tie the complete authorized-program capability to a sustained operational workload with a sufficiently interpretable duration/volume/outcome record across the scored domains. No promotion.
- **artificemachine/superharness:** large tests and accumulated status counters remain insufficient without interpretable duration/run context. No promotion.
- **earthwalker17/agent-os:** strong end-to-end showcase remains a bounded showcase rather than sustained operation. No promotion.
- **deepklarity/harness-kit:** maintainer-use assertions remain insufficient without concrete sustained records. No promotion.
- **smartcomputer-ai/agent-os:** project explicitly stated it was not yet ready for daily use in the assessed state. No promotion.
- **mco-org/mco:** its own cutoff-public material describes v0.1.0 as a minimum usable baseline and explicitly excludes a multi-day production soak from the dry-run scope. No promotion.
- **majiayu000/harness** and **Enderfga/claw-orchestrator** are the two systems whose newly surfaced cutoff-public operational records cross the common E4 threshold in this pass.

For the remaining Sekiwake field, exact-name public-web and repository searches did not establish another qualifying E4 operational corpus in this pass. This is an evidence finding, not a claim that no such operation occurred.

## E5 / Yokozuna check

No system in the September field is granted E5 from this pass. Public popularity, papers, package/release availability, third-party cataloging, or community discussion do not by themselves establish third-party reproduction/adoption of the scored system capability at the required level.

No current candidate reaches the Yokozuna mandatory Reliability 5 condition on the cutoff-public corpus. **Yokozuna remains vacant in GPT pre-freeze working state.**

## Updated GPT pre-freeze distribution

- **Yokozuna: 0**
- **Ozeki: 4** — `kai-linux/agent-os`, `dwiedeman/work-harness`, `majiayu000/harness`, `Enderfga/claw-orchestrator`
- **Sekiwake: 42**
- **Komusubi: 13**

Total: **59 Rikishi**.

## Gate result

The required upper-rank external/counter-evidence pass is complete. The next pipeline action is **final common evidence corpus freeze**. Claude and Copilot must not be asked to assess until that frozen corpus is created and both receive the same corpus/rubric.
