# September 2026 Basho — Candidate Field

**Discovery snapshot: 2026-09-13**
**Status: OPEN / provisional until the 2026-09-14 bootstrap cutoff**

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

**Not a separate Rikishi.** GitHub repository metadata explicitly identifies `acumenix/agent-orchestrator` as a **fork** whose `parent` and `source` are both `c9r-io/orchestrator`. The canonical system remains `c9r-io/orchestrator`. The previous Identity Hold is therefore resolved as a duplicate/fork relationship, not a second candidate.

### superharness name collision

`artificemachine/superharness` and `backmeupplz/superharness` are **distinct non-fork repositories** with different owners, implementations and descriptions. They must not be merged merely because the repository name is identical.

`backmeupplz/superharness` is promoted below as a separate candidate.

## Third-pass candidate additions — 2026-09-13

The following repositories were verified as materially relevant public Agent Systems Engineering candidates and are added for full evidence review:

- nodera-studio / agent-os — portable project-agnostic Claude Code harness with orchestration pipelines, skills, hooks and project bootstrap.
- Dusttoo / orka — multi-agent Claude Code orchestration: implement → independent code review → independent security review → merge-on-green, with worktree isolation and mechanical merge guard.
- dwiedeman / work-harness — backlog decomposition into PR-sized units, autonomous leads across local/SSH/cloud hosts, and persistent shepherding through merge.
- kim-dongho / agent-harness-starter — coding-agent harness with quality-enforcement hooks and SDLC skills across Claude Code, Gemini CLI and Codex CLI.
- backmeupplz / superharness — distinct autonomous multi-agent orchestrator for coding agents via tmux.
- Untrivial-ai / agent-orchestrator — project-level workspace/orchestrator supervising coding-agent teams from planning through PR/CI/review/merge across many agent backends.
- HKUDS / DeepCode — open agentic-coding system explicitly covering agent harness, loop engineering and multi-agent orchestration, with associated research artifact.
- limboo-ai / limboo — desktop application for orchestrating multiple coding agents.
- junhoyeo / contrabass — project-level coding-agent orchestrator implementing an OpenAI Symphony-style architecture.
- aterrylu / autonomOS — multi-agent harness / mission-control layer for CLI coding agents including Claude Code and Codex.

These descriptions are discovery rationale only and do not establish Rubric levels.

## Field count after identity cleanup

- Original nominal repository entries: **24**
- `acumenix/agent-orchestrator`: removed as a separate Rikishi because it is a GitHub fork of `c9r-io/orchestrator`
- Verified third-pass additions: **10**
- Current provisional distinct candidate systems: **33**

The field remains open until the bootstrap cutoff; **33 is not yet a frozen final count**.

## Discovery exclusions / watchlist

Watchlist status is a discovery decision only, not a formal eligibility ruling.

Current context/watchlist examples:

- getlatentic / agent-harness — normalized programmatic interface/event stream across agent runtimes.
- madebywild / agent-harness — unified provider-specific agent configuration generation.
- sevenschulte / agentic-harness — reference harness configuration; autonomous workflow execution is separated into a companion project.

Broad search also returns catalogs, generic coding agents and very small reference projects; these are not promoted solely because search terms match. A candidate must show apparent system-level harness/orchestration/governance relevance sufficient to justify evidence review.

## Discovery policy

The September bootstrap field/evidence cutoff is **2026-09-14**. No candidate acquires a rank merely by appearing here.

After field cleanup, evidence collection and GPT first-pass must cover the complete field. Only after that work and required upper-rank external/counter-evidence passes are complete may the common evidence corpus be frozen for Claude/Copilot Fresh-read.
