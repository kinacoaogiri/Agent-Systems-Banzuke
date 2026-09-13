# September 2026 Basho — Assessment Wave 5

**Assessment snapshot: 2026-09-13**

Status: **Evidence collection / provisional GPT fresh-read — upper-rank E4 review refreshed**

## SUNRNEHUI / agent-harness

Provisional GPT result unchanged: **15/25, Sekiwake**. Evidence remains E3.

## 0xenzyme / agent-harness

Provisional GPT result unchanged: **15/25, Sekiwake**. Evidence remains E3.

## deepklarity / harness-kit

### Public evidence observed

Harness Kit integrates `odin` multi-agent orchestration, `taskit` proof-of-work task board, local services and sandboxed execution. It decomposes specs into dependency graphs, runs independent tasks in parallel, routes work by capability/cost/quota, records evidence/cost/duration, reviews work before merge and uses structured RCA rather than blind retries. Its end-to-end quickstart runs plan→sandbox→review→merge. The README labels the project **experimental** and says **“We ship with it daily, and edges are rough.”** It also says the kit plans/builds itself through its own board.

### E4 consistency review

The common E4 rule established in the upper-rank pass is:

> Project-originated evidence may satisfy E4, but it must establish sustained real operation through concrete duration, volume, repeated outcomes, failure records, or an equivalent operational corpus. A maintainer assertion of daily use, by itself, does not establish E4.

Harness Kit's current public evidence establishes an executable end-to-end system and a maintainer claim of daily use, but this pass did not find concrete public duration/volume/failure-rate records comparable to the confirmed E4 systems.

### Refreshed provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 3 | **3** | Integrated orchestration, dependency-wave parallelism, sandbox execution and accumulated patterns materially expand delivery capacity; sustained operational evidence is not concretely quantified. |
| Delegation Depth | 4 | 3 | **3** | Spec decomposition through execution/review/merge supports deep workflow delegation, but role-level operational recognition remains evidence-capped. |
| Autonomy | 4 | 3 | **3** | Dependency graphs, parallel execution, reviewer loops and RCA support role-like architecture; current public corpus supports E3. |
| Reliability | 4 | 3 | **3** | Proof-of-work, sandboxing, reviewer checks and TDD/RCA provide strong demonstrated reliability. Experimental status plus absence of concrete sustained metrics prevent E4 in this pass. |
| Human Control | 4 | 3 | **3** | Human questions on uncertainty, assignment override, evidence board and inspectable state provide governed architecture, evidence-capped at E3. |

**Refreshed provisional recognized total: 15 / 25**

**Refreshed provisional qualification:** Sekiwake. Not a final rank.

### Contrary / limiting evidence

- Project explicitly labels itself experimental and says edges are rough.
- “We ship with it daily” is an operational claim, but no concrete duration/volume/failure-rate corpus was located in this pass.
- Broad web/community search did not locate qualifying independent reproduction/adoption evidence. E5 remains unrecognized.

**E4 ruling:** **NOT ESTABLISHED on current public corpus.** The previous E4/Ozeki result is withdrawn before publication because it treated a maintainer daily-use statement as sufficient sustained-operation evidence.

## Wave 5 upper-rank review observation

The first provisional Ozeki finding for `deepklarity/harness-kit` does not survive the normalized E4 rule. The system remains technically substantial, but Fact First requires distinguishing **claimed daily use** from a public operational record that lets a reviewer observe duration, volume, outcomes and failures.

No Claude/Copilot review or Torikumi is started at this stage.
