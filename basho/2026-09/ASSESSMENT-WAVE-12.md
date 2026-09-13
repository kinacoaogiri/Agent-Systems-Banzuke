# September 2026 Basho — Assessment Wave 12

**Assessment snapshot: 2026-09-13**

Status: **Evidence collection / provisional GPT fresh-read**

> **Audit status:** This is a provisional GPT working record. Canonical rules had been restored before this assessment, but field/identity cleanup and full-field evidence review were still in progress. It is not a final Banzuke result. Claude/Copilot Fresh-read occurs only after final corpus freeze.

## Stanshy / AgentHub

### Public evidence observed

AgentHub is an executable Electron desktop harness-engineering control plane built on top of Claude Code. It models a virtual software organization with 46 role definitions across nine departments and an explicit reporting hierarchy. The implemented harness layer includes 24 workflow Skills, runtime Hooks that block dangerous commands and validate completion, seven quality Gates (requirements through production release), live FileWatcher synchronization between Markdown task state and the GUI, embedded agent sessions, a Kanban task board, project scaffolding, trigger logs, role permission scopes and reporting chains. The README exposes build, typecheck, unit-test and Playwright E2E commands and explicitly states that Claude Code performs the actual agent work.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 3 | **3** | A structured virtual development organization, live management surface and enforceable harness layer materially expand one Human's ability to coordinate coding-agent work. |
| Delegation Depth | 3 | 3 | **3** | Tasks, roles, Skills and reporting chains support coherent multi-step workflow delegation, but the public evidence does not establish sustained autonomous ownership of a Human engineering role. |
| Autonomy | 3 | 3 | **3** | Hooks, Skills, status transitions and agent sessions automate bounded workflow progression, while the Human/Boss remains the active command authority and Claude Code supplies execution. |
| Reliability | 4 | 3 | **3** | Runtime blocking, stop validation, seven quality gates, tests/typechecks/E2E and live state synchronization are strong demonstrated reliability mechanisms; sustained operational reliability is not evidenced at E4. |
| Human Control | 5 | 3 | **3** | The architecture explicitly centers the Human as Boss, defines role scopes/reporting chains, blocks unsafe actions and requires quality gates. Capability is governance-grade in design but evidence-capped at E3. |

**Provisional recognized total: 15 / 25**

**Provisional qualification:** Sekiwake. Not a final rank.

### Contrary / limiting evidence

- AgentHub explicitly depends on Claude Code for actual agent execution; some claimed system capability therefore belongs to the combined AgentHub + Claude Code stack rather than AgentHub alone.
- The current README labels the implemented product as v0.1 and primarily documents architecture/features rather than sustained production-run statistics.
- The 46-agent organizational roster is a role/configuration structure; it must not be interpreted as evidence that 46 autonomous workers have operated concurrently or sustainably.
- No E4 sustained-operation record or E5 independent reproduction/adoption is recognized in this pass.

## Wave 12 observation

AgentHub is materially in scope and should have been present in the candidate field before the final discovery sweep. Its strongest differentiator is enforceable Human-governed organizational structure rather than independent execution-runtime ownership. Under the common Evidence Gate it remains E3/Sekiwake provisionally.

No Claude/Copilot review or Torikumi is started at this stage.
