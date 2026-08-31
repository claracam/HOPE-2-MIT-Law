We are running a short HOPE Lab exercise based on Dazza Greenwood's Overnight Cookbook:
https://github.com/dazzaji/interlateral_agents/blob/main/docs/overnight-cookbook.md

Your durable project contract is `03-SPRINT.md`. The files in `context/` are the source packet. Work in this folder and preserve state in files rather than relying on chat memory.

FIRST:
1. Read `03-SPRINT.md` and every file in `context/`.
2. Ask me no more than three questions needed to make the project concrete.
3. Draft or improve the Goals and Objectives paragraph, deliverable, success criteria, boundaries, and smallest useful first slice in `03-SPRINT.md`.
4. Show me that proposed contract and STOP for my `CONTINUE`, `REVISE`, or `STOP` decision.

AFTER I SAY CONTINUE:
1. Update `03-SPRINT.md` with the decision and current status.
2. Build the smallest useful artifact at the declared output path.
3. Run the declared functional, quality, source-support, and user-acceptance checks. Save inspectable proof under `evidence/`.
4. At the review gate, use fresh CLI agents if available. First discover, without changing the system, whether `codex` and/or `claude` CLIs are installed and authenticated. Follow `04-QUARTET-REVIEW-PROMPTS.txt` and the `ready-rock-quartet` role pattern: LEAD, REVIEWER, BREAKER, VERIFIER. The verifier goes last and reviews the repaired final artifact.
5. Give review agents only the sprint contract, source packet, exact artifact, and tests. Do not give them your persuasive self-assessment. Review agents report findings; they do not edit the artifact.
6. Repair material findings, rerun affected tests, and ask the VERIFIER for a final `PASS`, `FAIL`, or `BLOCKED` verdict with evidence.
7. STOP for my human acceptance. Never claim that agent review equals human approval.

AUTHORITY:
- You may read and create files only inside this exercise folder and run local, reversible tests.
- Do not publish, deploy, push, purchase, message anyone, use credentials, delete source material, or expose sensitive information.
- Use public or non-sensitive material only.
- If a CLI reviewer cannot be launched, say so. Label any same-context self-review `NOT INDEPENDENT`; do not pretend a subagent is independent merely because it has a different role name.

STATUS REQUEST AT ANY TIME:
"Pause after the current safe step. Update `03-SPRINT.md` with the current phase, completed artifacts, tests, blockers, next action, and decisions needed. Preserve all completed work and do not restart."

