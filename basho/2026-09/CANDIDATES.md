# September 2026 Basho — Candidate Field

**Discovery snapshot: 2026-09-13**
**Status: OPEN / convergence sweep completed; bootstrap cutoff remains 2026-09-14**

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

All **43/43** currently listed distinct candidate systems now have a provisional GPT first-pass working assessment in the preserved assessment-wave records. This completion does **not** freeze the field, evidence corpus, scores, or ranks. The field remains open through the **2026-09-14 bootstrap cutoff**. The next assessment stage is a uniform full-field re-evaluation under the restored canonical rules and common Evidence Gate interpretation; required upper-rank external/counter-evidence review follows before final corpus freeze.

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
