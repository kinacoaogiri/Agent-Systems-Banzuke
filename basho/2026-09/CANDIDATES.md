# September 2026 Basho — Candidate Field

**Discovery snapshot: 2026-09-13**
**Status: OPEN / convergence sweep completed; bootstrap cutoff remains 2026-09-14**

This is a discovery list, not a ranking and not an assessment result. Inclusion means only that the system has enough apparent relevance to justify a full evidence review.

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

**Not a separate Rikishi.** GitHub repository metadata explicitly identifies `acumenix/agent-orchestrator` as a **fork** whose `parent` and `source` are both `c9r-io/orchestrator`. The canonical system remains `c9r-io/orchestrator`.

### superharness name collision

`artificemachine/superharness` and `backmeupplz/superharness` are **distinct non-fork repositories** with different owners, implementations and descriptions.

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

These inclusions are discovery decisions only and do not establish Rubric levels.

## Field count after identity cleanup and convergence sweep

- Original nominal repository entries: **24**
- `acumenix/agent-orchestrator`: removed as a separate Rikishi because it is a GitHub fork of `c9r-io/orchestrator`
- Verified third-pass additions: **10**
- Late-discovery additions: **7**
- Convergence-sweep additions: **3**
- Current provisional distinct candidate systems: **43**

The convergence sweep materially reduced the remaining search surface but still found three distinct executable systems. Therefore **Field Close is not declared solely from search exhaustion**. The field remains open through the 2026-09-14 bootstrap cutoff, and the three new candidates require GPT evidence assessment before corpus freeze.

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

After field cleanup, evidence collection and GPT first-pass must cover the complete field. Only after that work and required upper-rank external/counter-evidence passes are complete may the common evidence corpus be frozen for Claude/Copilot Fresh-read.
