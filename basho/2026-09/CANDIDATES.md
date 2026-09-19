# September 2026 Basho — Candidate Field

**Discovery snapshot: 2026-09-13**
**Status: FIELD CLOSE AUDIT / bootstrap cutoff passed (2026-09-14)**

This is a discovery list, not a ranking and not an assessment result. Inclusion means only that the system has enough apparent relevance to justify a full evidence review.

Candidate identity and counting follow `RULES.md` → **Unit of Assessment / Rikishi Identity**. One Rikishi is one independent Agent System / product-system; a GitHub repository is evidence/artifact, not itself the unit of assessment. Counts below are counts of distinct systems after identity resolution, not raw repository entries.

## Initial field

- Ancienttwo / repo-harness
- artificemachine / superharness
- kai-linux / agent-os
- smartcomputer-ai / agent-os
- earthwalker17 / agent-os
- buildermethods / agent-os

## Discovery additions — 2026-09-13

- majiayu000 / harness
- DIodide / Harness
- ldaume / agentic-engineering-harness
- affectionatec / agentic-engineering
- giuliastro / harness-remote
- XpressAI / xpressclaw
- chapzin / codex-harness-mcp
- highflame-ai / codeoid
- SUNRNEHUI / agent-harness
- c9r-io / orchestrator
- 0xenzyme / agent-harness
- deepklarity / harness-kit
- backnotprop / orchestrator
- Ghosteken / agent-harness
- LanNguyenSi / harness
- lunarnexus / orchestra
- TimothyVang / Coding-Agent-Harness

## Identity cleanup — resolved

### acumenix / agent-orchestrator

**Not a separate Rikishi.** GitHub repository metadata explicitly identifies `acumenix/agent-orchestrator` as a **fork** whose `parent` and `source` are both `c9r-io/orchestrator`. Under the canonical Rikishi Identity rule, the canonical system remains `c9r-io/orchestrator` and the fork is not counted as an additional system.

### superharness name collision

`artificemachine/superharness` and `backmeupplz/superharness` are **distinct non-fork repositories** with different owners, implementations and descriptions. They remain separate Rikishi because identity is determined at the independent system/product level rather than by repository name alone.

## Third-pass candidate additions — 2026-09-13

- nodera-studio / agent-os
- Dusttoo / orka
- dwiedeman / work-harness
- kim-dongho / agent-harness-starter
- backmeupplz / superharness
- Untrivial-ai / agent-orchestrator
- HKUDS / DeepCode
- limboo-ai / limboo
- junhoyeo / contrabass
- aterrylu / autonomOS

## Late-discovery additions — 2026-09-13

- Stanshy / AgentHub
- opensesh / KARIMO
- blundergoat / goat-flow
- Kibertum / tausik-core
- senweaver / SenWeaverCoding
- WecoAI / weco-cli
- QoderAI / better-harness

## Convergence-sweep additions — 2026-09-13

- **xai-org / grok-build** — official open-source Grok Build coding-agent system: terminal/TUI agent runtime with file editing, shell/web tools, long-running tasks, headless/CI mode, ACP embedding, workspace/checkpoints, MCP, skills, hooks and sandboxing. This is a distinct executable Agent System, not merely a base model.
- **coleam00 / Linear-Coding-Agent-Harness** — executable long-running autonomous coding harness using an initializer + continuation coding-agent pattern, Linear as durable project/work/handoff state, browser verification, security restrictions and repeated sessions.
- **context-labs / whip** — executable Go coding-agent harness with a tool-use loop, subagents, parallel tool calls, provider routing, interactive runtime, MCP support and goal-driven work-until-done mode.

These inclusions are discovery decisions only and do not establish final Rubric levels.

## Field count after identity cleanup and convergence sweep

- Original nominal repository entries: **24**
- `acumenix/agent-orchestrator`: removed as a separate Rikishi because it is a GitHub fork of `c9r-io/orchestrator`
- Verified third-pass additions: **10**
- Late-discovery additions: **7**
- Convergence-sweep additions: **3**
- Current provisional distinct candidate systems: **43**

The count **43** is a count of provisional distinct Agent Systems after the resolved identity cleanup above, not a count of repositories.

All **43/43** currently listed distinct candidate systems have a provisional GPT first-pass working assessment in the preserved assessment-wave records. The **2026-09-14 bootstrap cutoff has now passed**. The field is not yet declared closed: a bounded Field Close Audit is being used to resolve cutoff-valid omissions without reopening unconstrained discovery. Any admitted omission must complete identity resolution, evidence collection and GPT first-pass before the field is closed. After Field Close, the complete field receives one uniform full-field re-evaluation under the restored canonical rules and common Evidence Gate interpretation; required upper-rank external/counter-evidence review follows before final corpus freeze.

## Discovery exclusions / watchlist

Watchlist status is a discovery decision only, not a formal eligibility ruling.

Current context/watchlist examples:

- getlatentic / agent-harness — normalized programmatic interface/event stream across agent runtimes.
- madebywild / agent-harness — unified provider-specific agent configuration generation.
- sevenschulte / agentic-harness — reference harness configuration; autonomous workflow execution is separated into a companion project.
- kuldeeps48 / agentic-engineering — substantial written Agentic Project Harness specification, but the surfaced artifact is principally a repository operating-layer specification rather than a distinct executable orchestration/control-plane product.
- drjoeshepherd / agentic-engineering-harness — substantial AI-native delivery operating-system starter/policy/spec structure; retained as context/watchlist pending evidence of a distinct executable control plane beyond repository artifacts.
- china-qijizhifeng / agentic-harness-engineering and multiple `harness-engineering` educational/template repositories — discovery context until distinct executable-system evidence is established.
- benchmark/evaluation-only repositories — evidence infrastructure rather than Rikishi unless they also constitute an independently usable Agent System.

Broad search also returns catalogs, handbooks, generic coding agents, forks, optimization tools and small reference projects; these are not promoted solely because search terms match. A candidate must show apparent system-level harness/orchestration/governance relevance sufficient to justify evidence review.

## Discovery policy

The September bootstrap field/evidence cutoff is **2026-09-14**. No candidate acquires a rank merely by appearing here.

The provisional GPT first-pass now covers the complete currently listed field. After audit cleanup, the same restored canonical Rubric and Evidence Gate interpretation must be applied uniformly across all 43 Rikishi. Only after that uniform re-evaluation and required upper-rank external/counter-evidence passes are complete may the common evidence corpus be frozen for independent Claude/Copilot Fresh-read.


## Field Close Audit — bounded final omission check

This is an **ending procedure**, not a new open-ended discovery wave. It starts from the resolved 43-system field and asks only whether a materially relevant independent Agent System was publicly present by the **2026-09-14 cutoff** but omitted from the working field.

### Fixed search families

The final omission check is limited to the already-used system families and close synonyms: agent harness / coding-agent harness; agent orchestrator / coding-agent orchestrator; agent runtime / control plane; AgentOS / agent operating system; multi-agent coding orchestration. Keyword matches alone do not establish inclusion.

### Classification

Every surfaced item is resolved as one of: **IN / DUPLICATE / OUT OF SCOPE / WATCHLIST / POST-CUTOFF**. Forks and same-name repositories follow the canonical Rikishi Identity rule in `RULES.md`.

### Stop condition

The Field Close Audit ends after one bounded final omission check of the fixed search families plus resolution of the resulting candidate set. It does not recursively expand search terms from newly found candidates. New post-cutoff systems belong to a later Basho.

### Cutoff-valid omission candidates requiring evidence review

The bounded check surfaced the following independent, non-fork repositories with public system material at or before the cutoff. They are **not yet admitted Rikishi**; each requires scope/identity/evidence resolution against its cutoff state:

- `aylee/agent-os` — filesystem-first, runtime-neutral operating system for agent-assisted work; repository predates cutoff.
- `use-agent-os/agent-os` — local-first AgentOS with a shared agent loop, gateway sessions/approvals/scheduling and sandboxed tools; cutoff-day release/commits are publicly visible.
- `pheathtwilio/agent-orchestrator` — parallel coding-agent orchestrator with planning, spawned agents, CI-fix/merge-conflict/code-review automation; repository predates cutoff.
- `pjcau/agent-orchestrator` — provider-agnostic multi-agent orchestration framework with roles, routing, graph execution and cooperation; cutoff-day commits are publicly visible.
- `manikDH/coding_agent_orchestrator` — CLI multi-coding-agent orchestration; repository predates cutoff.
- `andrewgolovanov/agent-os` — local-first task board/control plane for Codex with durable tasks and multi-project workflows; repository predates cutoff.
- `SapienXai/AgentOS` — human-operated control plane for teams of digital workers, tasks, approvals, observability and runtime state; cutoff-day commits are publicly visible.
- `alexandrmotologa/agent-harness` — sandboxed multi-agent runtime/time-travel inspector with zero-trust execution and immutable decision DAGs; created 2026-09-11.
- `jxiaow/agent-harness` — portable process layer for coding agents covering requirements, design, implementation, verification and closeout; repository predates cutoff.
- `MikeyBeez/agent-os` — registry-oriented operating-system architecture for AI agents; repository predates cutoff.
- `bishopZ/2026-agent-harness` — Agent Harness project with activity before cutoff.
- `htekdev/agent-harness` — agent guardrail/harness library with budgets, observability, retries and human checkpoints; requires scope resolution because it may be a component rather than an independent Agent System.
- `Success6666/agent-runtime-governance` — framework-agnostic runtime for durable approvals, idempotent execution and signed audit; requires scope resolution because it may be a governance component rather than a complete Agent System.
- `nderman/agent-harness` — deterministic test/eval/observability harness; requires scope resolution because it may be evaluation infrastructure rather than a Rikishi.
- `Enderfga/claw-orchestrator` — persistent coding-agent runtime with multi-engine sessions and multi-agent orchestration; release/commits precede cutoff.
- `prathamesh-git9/agent-runtime` — durable resumable tool-calling-agent runtime with approval gates and crash recovery; requires scope resolution.
- `clearideas/agent-runtime` — provider-neutral runtime with graph scheduling, authorization boundaries, checkpoints, approvals and resumable runs; cutoff-day release/commits are publicly visible.
- `alamops/agetor` — local-first kanban/control plane for parallel CLI coding agents with worktree isolation, approvals and persistent run state; cutoff-day commits are publicly visible.
- `ordewell/ordewell` — coding-agent planner/orchestrator that turns a goal into editable multi-runner tasks and executes/verifies them; release/commits precede cutoff.
- `JSCOP/atc-kanban` — multi-agent task orchestration with kanban/MCP/dashboard; repository predates cutoff.
- `mco-org/mco` — CLI-first orchestration for parallel coding agents, comparison/review and implementation workflows; repository predates cutoff.

### Duplicate / lineage resolution found in the bounded check

- `Pritom14/agent-orchestrator-go` — GitHub fork of `Untrivial-ai/agent-orchestrator`; **DUPLICATE**, not a separate Rikishi absent material independent divergence.
- `krowxx/hydra` — GitHub fork of `mikecubed/Hydra`; **DUPLICATE** at repository level pending no separate independent product identity.
- `mikecubed/Hydra` — non-fork repository whose description states lineage from PrimeLocus/Hydra; lineage/scope must be resolved before any Rikishi admission.

This audit record deliberately does **not** assign scores or ranks. The next step inside Field Close is to resolve this finite set, admit only qualifying cutoff-valid systems, and give any admitted systems their missing GPT first-pass.