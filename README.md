# HOPE Lab Test 01

This repository is a compact exercise for turning a broad objective into a managed, agent-ready project. It follows the operating pattern in Dazza Greenwood's [Overnight Cookbook](https://github.com/dazzaji/interlateral_agents/blob/main/docs/overnight-cookbook.md).

## Start Here

1. Clone or download this repository.
2. Put only public, non-confidential source material in `context/`.
3. Open your agent in this repository folder.
4. Give the agent [`prompt.md`](prompt.md).
5. Answer up to three framing questions.
6. Review the agent's proposed changes to [`03-SPRINT.md`](03-SPRINT.md).
7. Say `CONTINUE`, `REVISE`, or `STOP`.

The basic loop is:

> Contract -> smallest useful artifact -> review -> break -> repair -> verify -> human acceptance.

## Files

- [`prompt.md`](prompt.md) - kickoff instructions to give your agent.
- [`03-SPRINT.md`](03-SPRINT.md) - the durable project contract, plan, status, and decision record.
- [`04-QUARTET-REVIEW-PROMPTS.txt`](04-QUARTET-REVIEW-PROMPTS.txt) - fresh-agent prompts for reviewer, breaker, and final verifier roles.
- `context/` - source material the agent is authorized to use.
- `output/` - the project deliverable.
- `evidence/` - test output, screenshots, and other proof.
- `reviews/` - reviewer, breaker, and verifier reports.

## Safety Boundary

Use public or non-sensitive material only. This exercise does not authorize publishing, deployment, credential use, purchases, deletion, external communication, or live-system changes. Human acceptance remains a separate final gate.

The full four-agent role discipline is documented in the [`ready-rock-quartet` skill](https://github.com/dazzaji/interlateral_agents/blob/main/.agents/skills/ready-rock-quartet/SKILL.md). For this short exercise, fresh CLI one-shot reviewers are sufficient when available. They must be identified honestly; same-context role-play is not independent review.
