# September 2026 Basho — Assessment Wave 14

**Assessment snapshot: 2026-09-13**

Status: **Evidence collection / provisional GPT fresh-read**

## senweaver / SenWeaverCoding

### Public evidence observed

SenWeaverCoding is an installable desktop and headless autonomous-agent runtime rather than only a prompt/configuration layer. The Rust runtime exposes 130+ tools, persistent SQLite/Markdown/vector memory, checkpoints/rewind, context compaction, cron automations, Hooks, Skills, MCP, subagent delegation, sandbox/guardrails, browser and code-intelligence tooling, multiple provider backends and SDK/RPC access. Agent mode is described as a fully autonomous orchestrator that decomposes tasks, executes end-to-end and self-verifies. Other modes alter tool allowlists, approval policy and verification behavior. Cross-platform release packaging is automated. The repository explicitly states that it contains no test files and relies on cargo/type checks plus manual desktop smoke testing.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 5 | 3 | **3** | An integrated autonomous coding runtime with broad tool, memory, browser, automation and delegation surfaces has transformative-capability potential, but evidence is capped at E3. |
| Delegation Depth | 4 | 3 | **3** | Agent mode owns end-to-end task decomposition/execution/self-verification and subagent delegation, supporting deep workflow capability without sustained role-operation evidence. |
| Autonomy | 4 | 3 | **3** | Cron, persistent sessions/checkpoints, full-auto mode and subagents provide role-like autonomy architecture. |
| Reliability | 3 | 2 | **2** | Checkpoints, guardrails and verification modes exist, but the repository explicitly has no test files and relies on static checks/manual smoke tests; repeatable executable evidence supports E2, while stronger reliability demonstration is not established. |
| Human Control | 4 | 3 | **3** | Per-mode tool allowlists, approval policy, sandbox, PII redaction and guardrails provide bounded/governed control surfaces. |

**Provisional recognized total: 14 / 25**

**Provisional qualification:** Komusubi. Sekiwake Reliability≥3 condition is not satisfied. Not a final rank.

### Counter-evidence / limitation

- The repository explicitly says there are deliberately no test files.
- Broad capability claims therefore must not be converted into higher Reliability Evidence solely from feature breadth or packaged releases.

---

## WecoAI / weco-cli

### Public evidence observed

Weco CLI is an executable autonomous optimization/autoresearch loop. It iteratively changes code, executes an evaluation function, compares measurable outcomes and searches for improved implementations. The project explicitly frames the loop as applicable not only to conventional optimization but to agent/harness engineering when the target behavior can be reduced to an evaluation metric.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 4 | 3 | **3** | Autonomous empirical search over implementation alternatives creates a meaningful new optimization capability for measurable engineering problems. |
| Delegation Depth | 3 | 3 | **3** | A bounded optimization/research objective can be delegated as a complete iterative workflow. |
| Autonomy | 4 | 3 | **3** | The core loop repeatedly edits, evaluates and selects without stepwise Human operation. |
| Reliability | 3 | 3 | **3** | Objective evaluation closes the loop and provides demonstrated verification for the bounded optimization task. |
| Human Control | 3 | 3 | **3** | Human authority is primarily exercised by defining the target/evaluation boundary; the loop is measurable and bounded but less governance-rich than dedicated control-plane systems. |

**Provisional recognized total: 15 / 25**

**Provisional qualification:** Sekiwake. Not a final rank.

### Scope note

Weco is architecturally different from most coding-agent harnesses in the field: its delegated unit is an empirical optimization/research loop rather than general software-project ownership. It remains in scope because the Rubric evaluates Agent Systems Engineering by Human Capability Impact, not by conformity to one orchestration architecture.

---

## QoderAI / better-harness

### Public evidence observed

Better Harness is an executable multi-host inspection/evidence/improvement system for coding-agent work loops. It supports Claude Code, Codex, Qoder, Cursor, Copilot and additional adapters. It collects project/session evidence, keeps missing evidence explicit, uses independent evidence agents before unified analysis, evaluates task understanding, controlled execution, validation, delivery and learning capture, produces evidence-backed reports/history, and proposes scoped repairs with acceptance checks. The project explicitly distinguishes configured mechanisms from proof that those mechanisms were actually exercised, and distinguishes a current passing check from longitudinal proof of improvement.

### Provisional GPT fresh-read

| Domain | Capability | Evidence | Recognized | Rationale |
| --- | ---: | ---: | ---: | --- |
| Capability Expansion | 3 | 3 | **3** | Cross-host evidence inspection and longitudinal workflow analysis materially improve a Human's ability to govern and refine agent engineering. |
| Delegation Depth | 2 | 3 | **2** | Better Harness delegates analysis/diagnosis/repair-planning tasks, not the underlying software-delivery role itself. |
| Autonomy | 2 | 3 | **2** | Evidence collectors/analyzers automate bounded assessment tasks, while actual engineering execution remains with the host agent/Human. |
| Reliability | 4 | 3 | **3** | Explicit evidence states, source boundaries, independent collectors and validation routes provide strong demonstrated epistemic reliability. |
| Human Control | 5 | 3 | **3** | The system deliberately exposes uncertainty/missing evidence and keeps repair scope/validation visible to Human authority. |

**Provisional recognized total: 13 / 25**

**Provisional qualification:** Komusubi. Sekiwake Delegation/Autonomy conditions are not satisfied. Not a final rank.

## Wave 14 observation

These systems illustrate why the Rubric must separate capability from evidence and delegation scope. SenWeaverCoding has very broad autonomous-runtime capability but insufficient Reliability evidence for Sekiwake in this pass. Weco has a narrower but genuinely autonomous measurable research loop. Better Harness is governance/evidence infrastructure whose strongest value lies in epistemic control rather than software-role delegation.

No Claude/Copilot review or Torikumi is started at this stage.
