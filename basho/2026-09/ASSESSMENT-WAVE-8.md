# September 2026 Basho — Assessment Wave 8

**Assessment snapshot: 2026-09-13**

Status: **Evidence collection / provisional GPT fresh-read**

Canonical audit and first identity cleanup have completed. Wave 8 resumes GPT primary assessment. All results remain provisional until the complete candidate field/evidence pass is finished and the common corpus is frozen. Claude/Copilot remain deferred.

## kai-linux / agent-os

### Public evidence observed

Agent OS describes an autonomous-first software organization for supervised rollout: backlog issues are dispatched to coding agents, work executes in worktrees, branches/PRs are produced, CI/PR monitoring can merge green work, and failures retry/escalate. It publishes a rolling 14-day reliability snapshot of 88 tasks, 61 successes (69%), and 10 escalations (11%), plus a real issue→agent→tests→PR→merge example. It also runs recurring incident scanning, backlog grooming, strategic planning and log analysis that can generate self-fix issues back into the same delivery loop. The project explicitly warns that fresh repositories should begin in supervised `dispatcher_only` mode rather than assuming unattended reliability.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 5 | 4 | **4** | A backlog-to-shipped-work organization plus recursive operational improvement materially changes what one technical founder/operator can sustain. Public evidence supports structural expansion, while transformative level remains evidence-capped. |
| Delegation Depth | 5 | 4 | **4** | The system accepts backlog-level responsibility and manages dispatch, execution, PR health and self-improvement loops; operational evidence supports role-level delegation but not independently established full role substitution. |
| Autonomy | 5 | 4 | **4** | Cron-driven dispatch, queue, PR monitor, planner/groomer/scanner loops, retries and escalation support sustained autonomous responsibility, evidence-capped at E4. |
| Reliability | 4 | 4 | **4** | Real rolling operational metrics, merged issue-to-PR evidence, retries/recovery and explicit failure/escalation accounting support Dependable rather than Role-grade recognition. |
| Human Control | 5 | 4 | **4** | Supervised rollout, escalation, kill switch, bounded retries, explicit promotion from dispatcher-only to fuller autonomy, observable metrics and operator controls support governed delegation. |

**Provisional recognized total: 20 / 25**

**Provisional qualification:** Ozeki. Not a final rank.

### Contrary / limiting evidence

- Published success is 69%, not role-grade reliability.
- Maintainer explicitly says results are workload-specific and fresh external repos usually need tuning.
- Recommended adoption starts with manual dispatch/review and only promotes autonomy after measured stability.
- E4 is project-originated operational evidence, not E5 independent establishment; upper-rank external/counter-evidence review is required.

---

## smartcomputer-ai / agent-os

### Public evidence observed

AgentOS is a Rust runtime for governed self-evolving agents. It provides a deterministic kernel, typed AIR control plane, explicit effects, signed receipts, replayable event history, durable backends and a propose→shadow→approve→apply→execute→receipt→audit self-modification lifecycle. A Demiurge agent and smoke fixtures exercise the current runtime. The project explicitly states it is **not quite ready for daily use yet** and remains in active development.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 3 | **3** | Governed runtime self-modification and replayable worlds are a meaningful new systems capability, but current proof remains pre-daily-use. |
| Delegation Depth | 3 | 3 | **3** | Task-driven agent workflows and declared effects support workflow-level delegation, not demonstrated continuing engineering-role ownership. |
| Autonomy | 4 | 3 | **3** | Agents can propose and execute governed runtime evolution, but demonstrated maturity caps recognition at workflow autonomy. |
| Reliability | 4 | 3 | **3** | Determinism, signed receipts, replay and durable journals are strong reliability architecture with smoke/demo evidence; daily operational reliability is explicitly not established. |
| Human Control | 5 | 3 | **3** | Typed effects, review gates, provenance and approval phases strongly support governance architecture, but E3 caps recognition. |

**Provisional recognized total: 15 / 25**

**Provisional qualification:** Sekiwake. Not a final rank.

### Contrary / limiting evidence

- README explicitly says AgentOS is not quite ready for daily use.
- Current proof centers on Demiurge and smoke fixtures rather than sustained software-delivery operation.
- Strong governance architecture must not be mistaken for higher operational Evidence Level.

---

## earthwalker17 / agent-os

### Public evidence observed

Agent OS is a local-first project operating system with a Main Agent/Coding Agent split, durable project memory, sandbox chokepoint, planning/task graphs, parallel agent teams, real command verification, browser verification, visual review, bounded recovery, audited Git/GitHub delivery and approval-gated production connectors. The repository reports 820+ backend tests. Its public Pulseboard showcase states the system took an empty repository through planning, implementation, build/browser/visual verification, bounded self-repair, Git delivery, Vercel production deployment, Supabase migration and Stripe test-mode checkout/webhook persistence, with the human limited to contract approvals.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 5 | 4 | **4** | End-to-end product construction and deployment with a human primarily approving contracts is structural/near-transformative expansion; project-originated real-world showcase caps evidence at E4. |
| Delegation Depth | 5 | 4 | **4** | Natural-language product intent can progress through plan, implementation, verification, repair, delivery and deployment, supporting role-level delegation in the demonstrated scope. |
| Autonomy | 4 | 4 | **4** | Task graphs, parallel teams, verification, bounded repair and delivery progression provide role-level autonomy, while explicit approvals remain deliberate authority gates. |
| Reliability | 4 | 4 | **4** | 820+ tests plus real build/browser/visual/deployment verification and demonstrated recovery support Dependable operation. |
| Human Control | 5 | 4 | **4** | Sandbox boundaries, explicit dispatch, approval contracts, bounded recovery budgets, audit artifacts and preview→confirm external actions provide strong governed Human authority. |

**Provisional recognized total: 20 / 25**

**Provisional qualification:** Ozeki. Not a final rank.

### Contrary / limiting evidence

- The strongest operational evidence is a project-maintained showcase/sample product rather than independent sustained adoption.
- Explicit human approvals remain at material external/destructive boundaries; this is compatible with governance but limits claims of unrestricted substitution.
- E5 is not established; upper-rank external/counter-evidence review is required.

---

## buildermethods / agent-os

### Public evidence observed

Agent OS helps coding agents discover and document codebase standards, inject relevant standards, shape implementation specs and index those standards. It works alongside external coding agents rather than owning their execution loop. The public README is concise and primarily presents standards/spec alignment capabilities and installation/documentation links.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 2 | 2 | **2** | Standards extraction/injection and spec shaping extend consistency and planning quality. |
| Delegation Depth | 2 | 2 | **2** | Coherent standards/spec tasks can be delegated, but the product does not demonstrate ownership of the implementation workflow. |
| Autonomy | 2 | 2 | **2** | Standards discovery/injection can automate bounded tasks inside an external agent workflow. |
| Reliability | 2 | 2 | **2** | Public implementation/product availability supports repeatable bounded function, without stronger operational evidence in the assessed README. |
| Human Control | 3 | 2 | **2** | Lightweight alignment and documented standards provide useful boundaries, but evidence does not establish a deeper governance control plane. |

**Provisional recognized total: 10 / 25**

**Provisional qualification:** Komusubi. Not a final rank.

## Wave 8 observation

The previously unassessed original field contains two systems (`kai-linux/agent-os` and `earthwalker17/agent-os`) that provisionally satisfy Ozeki requirements under the audited Rubric, both on E4 project-originated operational evidence. `smartcomputer-ai/agent-os` presents unusually strong deterministic/governance architecture but explicitly self-caps operational maturity by stating it is not ready for daily use. `buildermethods/agent-os` is materially useful but is principally a standards/spec alignment layer rather than an autonomous execution system.

No Claude/Copilot review or Torikumi is started at this stage.
