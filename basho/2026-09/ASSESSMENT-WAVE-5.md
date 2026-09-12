# September 2026 Basho — Assessment Wave 5

**Assessment snapshot: 2026-09-13**

Status: **Evidence collection / provisional GPT fresh-read**

Wave 5 continues GPT primary assessment. Claude/Copilot review remains deferred until candidate/evidence completion.

## SUNRNEHUI / agent-harness

### Public evidence observed

The public project is a runtime-neutral Agent Skill for continuity and acceptance control across file/shell-capable coding agents. It defines Native, Portable and Audited modes; intent-to-contract alignment; bounded workers; deterministic portable contracts and append-only events; checkpoint/handoff/resume; ownership epochs; workspace-drift and corruption checks; fail-closed continuation; evidence digests; progress circuit breaking; audited acceptance receipts; evaluator separation; and manager re-verification. Public release packaging, checksums, CI and deterministic packaging/validation procedures are exposed. The project deliberately reuses the host runtime's Plan and execution rather than claiming to be a separate execution engine.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 3 | **3** | Durable cross-session/model continuation, bounded context reconstruction and acceptance controls materially expand long-horizon agent work. Public runtime packaging and verification support E3. |
| Delegation Depth | 3 | 3 | **3** | The manager can dispatch bounded workers and preserve work across boundaries, but the skill deliberately leaves core execution/orchestration to the host runtime. Workflow-level delegation is the safer ceiling. |
| Autonomy | 3 | 3 | **3** | Portable/Audited execution can progress through worker execution, checkpoint, handoff and resume under bounded rules, while final acceptance remains manager-owned. |
| Reliability | 4 | 3 | **3** | Fail-closed continuation, ownership fencing, drift/corruption checks, deterministic capsules, evidence digests and progress circuit breaking provide strong demonstrated reliability controls. |
| Human Control | 5 | 3 | **3** | Approval boundaries, explicit decisions, proportional execution, manager acceptance, stop conditions, takeover reasons and audited escalation strongly support governed autonomy. |

**Provisional recognized total: 15 / 25**

**Provisional qualification:** Sekiwake threshold and mandatory recognized levels appear satisfied. Not a final rank.

### Evidence gaps

- Independent sustained operational/adoption evidence sufficient for E4/E5.
- Evidence that Role-level delegation is owned by Agent Harness rather than the host runtime.
- Third-party validation of boundary recovery and audited controls under long-running real projects.

---

## 0xenzyme / agent-harness

### Public evidence observed

The public project describes an adapter-driven control plane with a durable hierarchy `Roadmap -> Milestone -> Goal -> Task -> Run -> Evidence -> State Sync`. It exposes host-direct, host-direct-postflight and durable-harness execution paths; repository Goals/Runs; prepared Run manifests; execution DAGs; worker ownership; candidate versus accepted evidence; revision-safe checkpoints for enforced managed Runs; fail-closed behavior on contract drift/external-state uncertainty; deterministic CLI gates; state synchronization; dry-run-first artifact lifecycle; project adapters; evaluation fixtures; and bounded Human escalation for unresolved direction, credentials, paid APIs, production access, destructive actions or external effects outside accepted scope. The README explicitly says Codex is the first host pack and warns not to claim complete support for all coding agents until a second host is empirically validated.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 3 | **3** | Durable goal/run state, DAG execution contracts, evidence acceptance and state synchronization materially reduce the need for a human task router. |
| Delegation Depth | 4 | 3 | **3** | Goals, Tasks, Runs, multi-worker DAG ownership and controller responsibility support deep workflow delegation; continuing Role substitution is not established. |
| Autonomy | 4 | 3 | **3** | Durable-harness mode supports multi-worker/persistent execution with limited Human pause conditions, but scheduling/concurrency remains delegated to the host runtime. |
| Reliability | 4 | 3 | **3** | Revision-safe checkpoints, fail-closed drift handling, deterministic gates, evidence acceptance, state sync and evaluation fixtures strongly support demonstration-level reliability. |
| Human Control | 5 | 3 | **3** | Accepted-state authority, explicit work-mode resolution, external-action boundaries, candidate-evidence treatment, escalation conditions and controlled cleanup form a strong governance model. |

**Provisional recognized total: 15 / 25**

**Provisional qualification:** Sekiwake threshold and mandatory recognized levels appear satisfied. Not a final rank.

### Evidence gaps

- Independent operational/adoption evidence for E4/E5.
- Empirical validation of additional host packs; the project itself explicitly limits the current support claim.
- Evidence that host-provided scheduling/concurrency does not become the dominant source of claimed system autonomy.

---

## deepklarity / harness-kit

### Public evidence observed

The public project is an integrated harness-engineering toolkit containing `odin` multi-agent orchestration, `taskit` proof-of-work task board, local services and sandboxed task execution. It decomposes specs into dependency graphs, runs independent tasks in parallel, routes work by capability/cost/quota, records task evidence/cost/duration, uses reviewer-model checks before merge, applies root-cause analysis instead of blind retries, and routes uncertainty to Human questions. Its documented end-to-end quickstart runs plan -> sandbox -> review -> merge. The maintainers label the project experimental but state that they ship with it daily; the roadmap says the kit plans/builds itself through its own board and grades itself against its scorecard.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 4 | **4** | Integrated orchestration, dependency-wave parallelism, sandbox execution, review and accumulated knowledge materially expand software-delivery capacity; maintainer-reported daily use provides operational evidence beyond a one-off demo. |
| Delegation Depth | 4 | 4 | **4** | Spec decomposition through execution/review/merge and dependency-aware multi-agent routing supports continuing workflow/role-like delegation in the maintained operating system. |
| Autonomy | 4 | 4 | **4** | Dependency graphs, parallel execution, reviewer loops and root-cause/retry discipline support role-level autonomous progression within bounded work. |
| Reliability | 4 | 4 | **4** | Proof-of-work, sandboxing, reviewer checks, TDD/RCA patterns, evidence trails and maintainer-reported daily operation support Dependable-level recognition, while the explicit experimental status argues against Role-grade L5. |
| Human Control | 4 | 4 | **4** | Human questions on uncertainty, assignment override, approval-oriented adoption, evidence board and inspectable task state provide governed Human authority over the autonomous loop. |

**Provisional recognized total: 20 / 25**

**Provisional qualification:** Ozeki threshold and mandatory recognized levels appear satisfied. Not a final rank.

### Evidence caution

The E4 finding is based on a public maintainer statement of daily operational use plus the integrated executable workflow and end-to-end quickstart. It is **not** E5 independent establishment. Before final adjudication, the upper-rank evidence pass must seek external adoption/reproduction and counter-evidence, especially around the project's explicitly experimental status and known rough edges.

### Evidence gaps

- Independent third-party reproduction/adoption sufficient for E5.
- Concrete duration/volume/failure-rate evidence for the maintainer-reported daily use.
- Counter-evidence review of known gaps and rough edges before any final Ozeki ruling.

## Wave 5 observation

Wave 5 produces the first provisional score above the recurring E3 ceiling.

`SUNRNEHUI/agent-harness` and `0xenzyme/agent-harness` both expose sophisticated durability, evidence and Human-control mechanisms, but their reviewed public evidence remains capped at E3 and significant execution responsibility remains in host runtimes.

`deepklarity/harness-kit` differs because the public project combines the orchestrator, proof-of-work board and sandbox execution into an end-to-end system **and** explicitly reports that the maintainers use it daily. Under the current Evidence rubric that is sufficient for a provisional E4 operational signal, not E5. Because that raises the system into Ozeki territory, it now requires the broader upper-rank external-evidence and counter-evidence pass before final adjudication.

No Claude/Copilot review or Torikumi is started at this stage.
