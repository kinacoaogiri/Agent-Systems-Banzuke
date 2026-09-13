# September 2026 Basho — Assessment Wave 15

**Assessment snapshot: 2026-09-13**

Status: **Evidence collection / provisional GPT fresh-read**

> **Audit status:** This is a provisional GPT working record. Canonical rules had been restored before this assessment, but the field remains open through the bootstrap cutoff and full-field evidence review is not frozen. It is not a final Banzuke result. Claude/Copilot Fresh-read occurs only after final corpus freeze.

## xai-org / grok-build

### Public evidence observed

Grok Build is SpaceXAI's official terminal-based AI coding-agent system. The public source includes the TUI and agent runtime, file editing, shell execution, web search, workspace/VCS execution, checkpoints, headless operation for scripting/CI, Agent Client Protocol embedding, MCP servers, skills, plugins, hooks and sandboxing. Prebuilt binaries are released for macOS, Linux and Windows. The public changelog also records fixes around checkpoints and interactive permission/plan-approval flows.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 3 | **3** | A complete coding-agent runtime with tools, headless/CI operation, workspace state and extension surfaces materially expands software-engineering execution capacity. |
| Delegation Depth | 3 | 3 | **3** | Long-running and headless tasks support workflow delegation, but this pass does not establish independent ownership of a broader engineering role. |
| Autonomy | 3 | 3 | **3** | The runtime can continue long-running/headless work with tool execution and persisted workspace/session mechanics; sustained role autonomy is not established here. |
| Reliability | 4 | 3 | **3** | Public source, released binaries, checkpoint mechanics and a maintained changelog demonstrate substantial engineering reliability, but E4 sustained-operation evidence is not yet graded. |
| Human Control | 4 | 3 | **3** | Permission prompts, plan approval, sandboxing, hooks and interactive/headless boundaries provide explicit Human governance surfaces. |

**Provisional recognized total: 15 / 25**

**Provisional qualification:** Sekiwake. Not a final rank.

---

## coleam00 / Linear-Coding-Agent-Harness

### Public evidence observed

Linear-Coding-Agent-Harness is an executable demonstration of long-running autonomous coding built on the Claude Agent SDK. An initializer agent creates a Linear project and issue backlog; continuation coding-agent sessions query priority work, verify previously completed features, claim issues, implement and browser-test them, record implementation notes, mark work done and update a META issue for session handoff. Linear is used as durable project/work state rather than local handoff files. The harness also documents OS-level sandboxing, project-directory filesystem restrictions, a Bash allowlist and explicit MCP permissions.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 2 | **2** | The initializer/continuation pattern and external durable work state materially expand coding-agent continuity, but this pass has not established public test/demo evidence sufficient for E3. |
| Delegation Depth | 4 | 2 | **2** | A backlog can be delegated across repeated coding sessions through issue claiming and completion, but recognized depth is evidence-capped. |
| Autonomy | 4 | 2 | **2** | Unlimited continuation iterations and automatic priority selection imply workflow autonomy, but recognized autonomy is evidence-capped. |
| Reliability | 3 | 2 | **2** | Re-verification of completed features, browser testing and durable issue state are strong design mechanics; public reproducibility/test evidence remains to be established. |
| Human Control | 4 | 2 | **2** | Linear visibility plus sandbox/filesystem/command/MCP restrictions provide clear bounded Human control; recognized level is evidence-capped. |

**Provisional recognized total: 10 / 25**

**Provisional qualification:** Komusubi. Not a final rank.

---

## context-labs / whip

### Public evidence observed

whip is an executable Go coding-agent harness with a direct LLM tool-use loop for bash/read/write/edit/subagent actions, interactive terminal operation, provider-routable models, parallel tool calls and streaming. It exposes a `/goal` mode intended to work until completion, supports MCP discovery, and documents architecture, agent-loop, concurrency and feature maps linked to code/tests. It is distributed as checksum-verified prebuilt binaries and source-installable Go software.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 3 | 3 | **3** | A fast integrated tool loop, subagents, provider routing and MCP materially expand an individual coding workflow. |
| Delegation Depth | 3 | 3 | **3** | Goal-driven work-until-done supports workflow delegation, while this pass does not establish role substitution. |
| Autonomy | 3 | 3 | **3** | The goal loop and subagent/tool execution support autonomous workflow progress after delegation. |
| Reliability | 3 | 3 | **3** | Released binaries plus code/test-linked documentation and concurrency controls provide demonstrated implementation evidence; sustained operational E4 is not established. |
| Human Control | 3 | 3 | **3** | Interactive interruption, readable configuration and explicit tool/runtime surfaces keep operation observable and bounded, though stronger governance evidence is not established here. |

**Provisional recognized total: 15 / 25**

**Provisional qualification:** Sekiwake. Not a final rank.

## Wave 15 observation

The three convergence-sweep candidates are materially different systems and remain separate Rikishi. Grok Build and whip provisionally qualify as Sekiwake on the evidence currently surfaced. Linear-Coding-Agent-Harness is capability-rich in design but is capped at E2 in this first pass because the surfaced evidence is principally executable source/specification rather than a public test/demo/benchmark/reproduction record.

With this wave, every currently listed candidate system has a provisional GPT first-pass. This does **not** freeze the field or corpus: the bootstrap field/evidence cutoff remains 2026-09-14, audit-context cleanup and uniform full-field re-evaluation remain required, and upper-rank/E4 candidates require broader external and counter-evidence review before corpus freeze.

No Claude/Copilot review or Torikumi is started at this stage.
