# HOPE Quick Project Sprint

## Goals and Objectives

We will create **[specific artifact]** for **[named user or audience]** so they can **[complete a task or make a decision]**. The agent will use only **[named files or public sources]** and produce the artifact at **[exact output path]**. Success means **[observable functional, quality, source-support, and user-acceptance tests]** pass. The agent may perform local, reversible work inside this repository, but must stop before publication, external communication, credential use, spending, deletion, live-system changes, or decisions involving security, privacy, professional judgment, or human taste.

## Quick Fallback Project

If you do not have a project ready, use this one:

> Using the public source files in `context/`, create `output/project-playbook.md` for a named audience. Explain the objective, provide a practical sequence of steps, identify assumptions and risks, cite supporting sources, and include a ten-item user acceptance checklist.

## Source Packet

Read these first:

- `context/` - authoritative input files for this exercise.
- `[add exact path]` - [what it contains and why it is authoritative].

Known gaps and assumptions:

- [List missing information or uncertainty. Do not silently invent facts.]

## Deliverables

- Primary output: `output/[artifact-name]`
- Test and inspection evidence: `evidence/`
- Independent review reports: `reviews/`

## Scope and Authority

The agent may:

- read the named source packet;
- create or edit exercise files inside this repository;
- run local, reversible tests; and
- update this sprint record.

The agent must stop and ask before:

- changing the scope, audience, deliverable, or success criteria;
- making consequential quality, taste, privacy, or security decisions;
- using credentials, external services, or non-public information; or
- publishing, deploying, pushing, spending, deleting, or contacting anyone.

The agent must never claim human acceptance that has not occurred.

## Success Tests

1. **Functional:** the declared artifact exists, opens or runs, and contains every required element.
2. **Quality:** it is accurate, clear, useful to the named audience, and free of unsupported claims.
3. **Traceability:** material factual claims trace to the source packet; assumptions are labeled.
4. **Adversarial:** a breaker tests realistic omissions, misuse, ambiguity, and failure modes.
5. **User acceptance:** a human performs the named task and records `ACCEPT` or `REVISE`.

## Phase 1 - Contract

Agent work:

- Read the source packet.
- Refine this sprint and identify missing context.
- Propose the smallest useful first slice.

**Human Gate 1:** `CONTINUE` / `REVISE` / `STOP`

## Phase 2 - Build

Agent work:

- Create the smallest useful artifact.
- Save commands, test output, screenshots, or other proof under `evidence/`.
- Update Current Status below.

**Human Gate 2:** inspect usefulness, quality, taste, and security.

## Phase 3 - Review, Break, Repair, Verify

Follow [`04-QUARTET-REVIEW-PROMPTS.txt`](04-QUARTET-REVIEW-PROMPTS.txt) and the public [`ready-rock-quartet` skill](https://github.com/dazzaji/interlateral_agents/blob/main/.agents/skills/ready-rock-quartet/SKILL.md):

- **LEAD:** owns integration and remains the only writer.
- **REVIEWER:** checks the exact artifact against this sprint and source packet.
- **BREAKER:** attacks hidden traps, unsupported claims, misuse, and failure modes.
- **LEAD:** repairs material findings and reruns affected checks.
- **VERIFIER:** goes last and checks the repaired, frozen artifact and evidence.

For this short exercise, these roles may use bounded, fresh CLI one-shot processes. Record the actual model and harness, prompt, output path, and whether the review was genuinely independent. For a long-running project, use the full quartet's unique sessions, role lock, handshakes, and visible evidence protocol.

**Human Gate 3:** `ACCEPT` / `REVISE` / `STOP`

## Phase 4 - Close

- Summarize the deliverable, evidence, tests, review findings, repaired defects, and residual risks.
- Record the human's decision.
- Confirm no server, watcher, or agent process remains running unintentionally.

## CLI Review Plan

Discover available tools without altering the system:

```bash
command -v codex || true
command -v claude || true
```

When available, use bounded one-shot invocations appropriate to the installed CLI, such as `codex exec` or `claude -p`. Give each reviewer the exact contract, source packet, frozen artifact, test evidence, output report path, and done marker. Do not use permission-bypass flags for this exercise.

Expected reports:

- `reviews/reviewer.md`
- `reviews/breaker.md`
- `reviews/verifier.md`

If no fresh CLI is available, record `INDEPENDENT_REVIEW: UNAVAILABLE` and return to the human gate. Do not mislabel same-context self-review as independent.

## Current Status

- Phase: `CONTRACT`
- Lead agent and harness: `[identify them]`
- Human decision: `PENDING`
- Artifact: `NOT STARTED`
- Tests: `NOT RUN`
- Reviewer: `NOT STARTED`
- Breaker: `NOT STARTED`
- Verifier: `NOT STARTED`
- Blockers: `[none or list]`
- Next action: refine this sprint and request Human Gate 1.

## Decision Log

| Time | Decision | Owner | Reason |
|---|---|---|---|
| [time] | [CONTINUE / REVISE / STOP / ACCEPT] | [human] | [reason] |

## Status Request

At any point, the human may say:

> Pause after the current safe step. Update `03-SPRINT.md` with the current phase, completed artifacts, tests, blockers, next action, and decisions needed. Preserve all completed work and do not restart.

## Closeout

- Deliverable:
- Evidence:
- Review verdicts:
- Human acceptance:
- Residual risks:
- Next decision:
