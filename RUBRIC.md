# Rubric

## Governing purpose: Human Capability Impact

The highest-level question is:

> **How much does the system materially expand or improve human action?**

Human Capability Impact may be realized primarily through **Augmentation** (expanding what humans can do) or **Delegation/Substitution** (taking responsibility for coherent work previously performed by humans).

Technical architecture is evidence of how an outcome is achieved; novelty alone is not a scoring domain.

## Recognized score

Each of five domains has a Capability Level and an independently assessed Evidence Level.

`Recognized Level_i = min(Capability Level_i, Evidence Level_i)`

`Total Score = sum(Recognized Level_i)`

Maximum score: **25**.

## 1. Capability Expansion

| Level | Definition |
|---|---|
| 0 — None | Human feasible action is not materially expanded. |
| 1 — Assistance | Existing human action becomes easier or faster. |
| 2 — Extension | Scale, speed, or volume that is burdensome for a human becomes practical. |
| 3 — New Capability | Activity that is practically difficult for a human alone becomes feasible. |
| 4 — Structural Expansion | Work previously requiring multiple people, specialist organization, or substantial resources becomes feasible for a materially smaller human主体. |
| 5 — Transformative Expansion | The practical boundary of human action changes enough to enable a new sustained mode of activity. |

## 2. Delegation Depth

| Level | Definition |
|---|---|
| 0 — Tool | Human remains the executing主体; the system is used as a tool. |
| 1 — Action | A single concrete action can be delegated. |
| 2 — Task | A task with an objective and completion condition can be delegated. |
| 3 — Workflow | A coherent multi-task workflow can be delegated. |
| 4 — Role | Continuing responsibility and judgment within a defined role can be delegated. |
| 5 — Role Substitution | Within a defined responsibility scope, the system can practically substitute for the execution of a Human Role Holder without requiring human step-by-step performance. |

Role substitution does not imply transfer of legal or ultimate human accountability.

## 3. Autonomy

| Level | Definition |
|---|---|
| 0 — Operated | Human operation or instruction is required for each material action. |
| 1 — Local Autonomy | A narrow specified action can execute autonomously internally. |
| 2 — Task Autonomy | The system can select and execute means through task completion. |
| 3 — Workflow Autonomy | The system manages multiple tasks and handles ordinary branches and failures. |
| 4 — Role Autonomy | The system autonomously manages priorities, methods, and progress within an ongoing responsibility, escalating exceptional cases. |
| 5 — Sustained Autonomy | The system sustains responsibility across time and changing conditions, maintaining or recovering its state while limiting human intervention to appropriate boundaries. |

## 4. Reliability

| Level | Definition |
|---|---|
| 0 — Unreliable | Work outcomes cannot reasonably be expected. |
| 1 — Demonstrable | Successful examples exist, but stable repeatability is not established. |
| 2 — Repeatable | Requirements are repeatedly met under defined routine conditions. |
| 3 — Operational | The system can be used continuously under ordinary operating conditions and handles common failures. |
| 4 — Dependable | High execution stability is evidenced across repetition, duration, and exceptions, including failure detection or recovery. |
| 5 — Role-grade Reliability | Public evidence establishes continuity, quality, and failure handling sufficient to entrust the relevant human-role-level responsibility in practice. |

## 5. Human Control

| Level | Definition |
|---|---|
| 0 — Uncontrolled | Human operators cannot adequately understand or control system action, authority, or state. |
| 1 — Intervention | Humans can start, stop, or directly intervene. |
| 2 — Bounded Control | Authority, targets, execution scope, or comparable boundaries can be defined in advance. |
| 3 — Observable Control | State, decisions, and execution are observable and humans can approve, reject, or correct at material points. |
| 4 — Governed Autonomy | Authority, gates, escalation, and auditability are systematic while autonomous execution remains under human governance. |
| 5 — Delegated Governance | Without continuous supervision, the system maintains defined authority boundaries and recognizes deviation, uncertainty, or material exceptions sufficiently to return them to appropriate human authority. |

Human Control is the technical counterpart to the Banzuke's demand that strength remain governable. Level 5 moves the human from continuous operator toward authority holder; it does not remove human authority.

## Rank qualification

All thresholds use **recognized** levels after Evidence Gate application.

| Rank | Minimum total | Mandatory conditions |
|---|---:|---|
| Maegashira | 5 | At least one domain >= 2 |
| Komusubi | 10 | Delegation >= 2; Reliability >= 2 |
| Sekiwake | 14 | Delegation >= 3; Autonomy >= 3; Reliability >= 3; Human Control >= 2 |
| Ozeki | 18 | Delegation >= 4 **or** Capability Expansion >= 4; Reliability >= 4; Human Control >= 3 |
| Yokozuna | 22 | Delegation = 5 **or** Capability Expansion = 5; Autonomy >= 4; Reliability = 5; Human Control >= 4 |

A system receives the highest rank for which **both** its total-score threshold and every mandatory condition are satisfied.

### Yokozuna principle

Yokozuna is not awarded merely because a system leads the table. It represents sustained, practical Human Capability Impact at human-role substitution level or an equivalent-or-greater degree of augmentation, backed by role-grade reliability and strong human governance.

Therefore:

> **A system must be strong to become Yokozuna. Strength alone is not sufficient.**

Yokozuna may be vacant.
