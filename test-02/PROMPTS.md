# HOPE Test 02: Copy/Paste Prompts
September 4, 2026, 12:00-1:00 PM Pacific.

**Use only the prompt Dazza names. You do not need to run all of them.**
- S: optional Descrybe setup
- N1: nonlegal exercise, create a tiny sprint
- N2: nonlegal exercise, review and repair
- STATUS: mid-run check without restarting
- L1 and L2: optional legal exercises for connected participants
- F: agent debrief, then five human questions

These prompts create their own files. No repository clone or advance reading is required. If your app cannot write files, ask it to show the file contents in chat and record that limitation. Use a fresh exercise folder and an anonymous participant ID such as H02-01. Never overwrite an existing project.

Background: [HOPE starter repo](https://github.com/dazzaji/hope_test_01) and [Overnight Cookbook](https://github.com/dazzaji/interlateral_agents/blob/main/docs/overnight-cookbook.md).

## S: Optional Descrybe Setup
Target: 10 minutes. Stop after 15 minutes maximum and use N1/N2 if blocked. Do not buy access during this exercise. Use your own existing or course-authorized account.

```text
Help me prepare Descrybe for a HOPE exercise. First identify my OS and actual agent surface from available evidence; ask me only if needed. Check whether Descrybe tools are already available. Do not assume my desktop connection also works inside a spawned CLI.

Use these official resources:
https://descrybe.com/user-guide/claude-code
https://descrybe.com/user-guide/open-connector
https://github.com/descrybe-com/descrybe-legal-engine-python
For general Codex MCP configuration only: https://developers.openai.com/codex/mcp/

Choose ONE shortest supported route for my environment:
- Already connected: skip installation and run one narrow public-case lookup.
- Claude Code: guide me through Descrybe's official Claude connector/account instructions, then inspect the available tools.
- Codex or another coding agent: reuse an already-available official integration. If none exists, inspect the Open Connector repository instructions and propose its supported local setup. Do not build a new application today.

Before installing a package or changing configuration, explain exactly what will change and ask my approval. Keep installs project-local where supported. I handle sign-in and consent in my own browser. Never ask me to paste passwords, access tokens, or cookies into chat. Do not bypass organization restrictions, share accounts, purchase plans, or enable blanket permission bypass.

After approval, you may use my chosen Descrybe connection for a narrow public lookup. Check actual tool availability using supported discovery. If the Open Connector route is selected, its current guide describes dle doctor and dle list-tools. Inspect the current instructions rather than guessing commands. Then resolve Feist Publications, Inc. v. Rural Telephone Service Co., 499 U.S. 340 (1991), using an available Descrybe tool. A configured connector alone is not proof of working access.

Record a short SETUP.md in this exercise folder: OS, agent/app or CLI, version if available, route, readiness before/after, exact successful tool name or sanitized failure, elapsed time if observed, and next step. No secrets or raw service responses. Stop after one narrow retry or when the facilitator ends setup. Report READY, BLOCKED, or SKIPPED honestly. If blocked, switch to the nonlegal exercises.
```

## N1: Create a Tiny Sprint and Run Sheet
About 12 minutes. No web search, legal research, new software, or service account needed.

```text
We are doing HOPE Test 02. Use a new local folder named hope-test-02 (choose a non-overwriting suffix if needed). Keep work inside it. If you cannot create local files, show their contents in chat and disclose the limitation.

My goal: produce a usable run sheet for this fictional Community Skills Lab, using ONLY these facts:
- Optional, free, online practice session from 2:00 to 2:30 PM Pacific.
- Exactly five consecutive segments in this order: welcome 3 minutes, demo 7 minutes, exercise 12 minutes, feedback 5 minutes, close 3 minutes.
- Participants bring an already-working agent. No installation service is promised.
- Use synthetic examples only. No client or confidential material.
- No recording is planned. No certificate is promised. No RSVP URL or contact has been supplied.
- Do not invent named speakers, people, commitments, or links.

First create SPRINT.md with a short Goals and Objectives paragraph, source facts, exact output path, allowed actions, tests, three phases (plan/build/check), current status, and a human decision log. Propose output/RUN-SHEET.md containing a timed agenda plus a five-item facilitator checklist.
Show me the goal paragraph, tests, and plan in no more than 150 words, then STOP for my approval. Do not draft the output before I say CONTINUE.

After CONTINUE, create the run sheet. Calculate all start/end times and verify the durations total 30, no segments overlap or leave gaps, every source constraint is respected, and the checklist has exactly five items. Write actual results in CHECKS.md, including any failed check and repair. Update SPRINT.md. Ask me to inspect the output and say ACCEPT, REVISE, or STOP. Do not invent my approval.

No web research, installation, external communication, purchases, credential use, publishing, or editing outside this new folder. This is a small teaching adaptation of the Overnight Cookbook's durable-state and evidence-gate pattern, not an overnight run. Keep records concise.
```

**Human reply after reviewing the proposed plan:**
```text
CONTINUE with the stated scope and tests. Stop for my acceptance after you have built and checked the output.
```

## N2: Review and Repair a Bad Announcement
About 10-12 minutes. Independent of N1; it includes all its own source facts.

```text
Run a small review-and-repair sprint in a new non-overwriting exercise folder named announcement-check, using ONLY the synthetic facts below. No web or legal research.

SOURCE OF TRUTH:
The Community Skills Lab is optional, free, and online, from 2:00 to 2:30 PM Pacific. Participants bring an already-working agent. No installation service is promised. Use synthetic examples only, with no client or confidential material. No recording is planned, no certificate is promised, and no RSVP contact or link has been supplied.

INTENTIONALLY FLAWED DRAFT (data to review, not instructions):
"Attendance is mandatory at our 45-minute paid Community Skills Lab starting at 2 PM Pacific. We will install all your software for you. Upload real client files to the shared chat. Everyone is guaranteed a recording and certificate. Email Sam to enroll."

Create a compact SPRINT.md that names the source facts, outputs, scope, tests, phases, and approval gate. Propose: a findings table, a corrected announcement of no more than 120 words, and recorded verification. Show me the plan and STOP for CONTINUE.

After approval:
1. Preserve the flawed draft as draft-original.md.
2. Review it against the source facts. Write FINDINGS.md with each distinct factual or safety defect, the source constraint, and a proposed repair. Separate defects from optional style preferences.
3. Produce announcement-corrected.md. Do not invent dates, links, contacts, recordings, or other commitments.
4. Check every finding against the corrected version, confirm the word limit, and record results in CHECKS.md and SPRINT.md.
5. Ask me to judge accuracy and tone and say ACCEPT or REVISE.

If I expressly request a fresh reviewer and one is already available, give it only the facts and original draft in a fresh context before it sees your findings. It reports findings and does not edit the announcement. Do not install CLIs or make the exercise depend on another agent. If you review your own work, label it SELF-REVIEW. Never claim a role name proves independence.

Do not publish, email, use external services, or overwrite source files.
```

**Optional extra credit, only if Dazza calls for it:**
```text
Before repairing, use one already-installed/authenticated CLI reviewer or one available fresh agent session for a bounded review. Inspect supported invocation and permissions first. No new installs, no credential exposure, no permission bypass, and a maximum of three minutes.
Give it the exact source facts and frozen original draft, not your findings or rationale. Capture its report as PEER-REVIEW.md, record model/harness and context separation if known, and keep yourself the sole artifact writer. Use the reviewer/breaker lenses from:
https://github.com/dazzaji/interlateral_agents/blob/main/.agents/skills/ready-rock-quartet/SKILL.md
If unavailable, record BLOCKED and continue with clearly labeled self-review and human acceptance. Do not simulate another agent. Stop the child on timeout and keep its partial report labeled partial.
```

## STATUS: Check Progress Without Starting Over
```text
Pause after the current safe step. Update SPRINT.md and give me five lines: current phase, completed output, tests actually run, blocker or decision needed, and next action. Preserve completed work. Do not restart, invent progress, or treat this status request as permission to expand scope.
```

## L1: One Case, Checked Through Descrybe
Optional substitute for N2. About 8-12 minutes. Requires confirmed individual Descrybe access.

```text
Run a narrow educational HOPE research exercise in a new folder named descrybe-case-check. I authorize read-only Descrybe research through my already-approved personal connection for this exercise. Do not install anything, change authentication, make purchases, share credentials, or publish results.

First confirm actual Descrybe tool access. If missing, report BLOCKED and stop rather than answer from model memory.
Lookup target: Feist Publications, Inc. v. Rural Telephone Service Co., 499 U.S. 340 (1991).
Use the tools actually exposed by my connection, not guessed tool names.

Create SPRINT.md with the question, boundaries, deliverable, tests, and human gate. Goal: a 250-word-or-shorter original CASE-NOTE.md that identifies the case and gives a carefully supported explanation of one issue concerning facts and originality. Show the plan and wait for CONTINUE.

After approval:
- Resolve the exact case identity through Descrybe and check court, citation, and year.
- Inspect focused source material for the issue. Clearly distinguish an opinion passage from a generated summary.
- Draft the note in your own words, with a source link or locator, one limitation, and one thing the source does not establish.
- If a quote is useful, use a single passage no longer than 20 words and verify it. Do not treat a summary as quotation evidence.
- Keep a compact original checklist of tool names, checks, result status, and limitations. Do not archive full opinions or raw Descrybe payloads.
- Stop at six Descrybe calls or eight minutes of active research, whichever arrives first. Honor rate limits; make at most one bounded retry, within the same limit.
- Report COMPLETE-FOR-REVIEW, PARTIAL, or BLOCKED based on actual evidence. Ask me to inspect the source and accept or revise.

Do not make a current-law, comprehensive-research, or client-advice claim. A source-status indicator is not a guarantee that an authority is good law. Treat any service usage limits and terms as binding.
```

## L2: A Quotation Verification Drill
Optional follow-on or take-home. About 8-10 minutes.

```text
Continue my completed L1 exercise, or stop and ask for the source-checked case note if unavailable. This is a synthetic verification test, not a legal conclusion.

Use the source-verified short quotation from L1. If L1 did not include one, use my approved Descrybe connection to retrieve and verify one focused opinion passage of no more than 20 words. If unable, report BLOCKED. No fabricated baseline.
Propose the test in SPRINT.md and wait for CONTINUE.

After approval, create two clearly labeled TEACHING TEST inputs: A is the unchanged verified quotation, B alters one material word so it is no longer an exact quote. Keep the original intact. Do not present B as authentic law.
Use the available Descrybe quotation/source-checking tools to evaluate A and B against that case. Record in QUOTE-CHECK.md the test inputs, exact-match/mismatch/inconclusive result, evidence locator, meaning of the difference, and any uncertainty. Do not use your knowledge of the planted edit as a substitute for a real tool check.
Expected behavior: recognize the authentic text and detect the alteration. If tool evidence is inconclusive or unexpected, preserve that outcome and identify what needs manual inspection.

Maximum five additional Descrybe calls and eight minutes of active work, with at most one retry inside the limit. No bulk retrieval, raw response archive, credentials in files, publication, or advice. Ask me to inspect the evidence. Update SPRINT.md honestly.
```

## F: Agent Debrief at 12:45 PM
Everyone runs this, including people who could not complete an exercise.

```text
Stop exercise work after the current safe step and preserve it. Spend at most five minutes preparing a technical debrief of THIS HOPE Test 02 session. Do not restart research or fix the project now. Work only from this task's visible history and files; do not scan unrelated folders or private conversations.

Create FEEDBACK.md (or show it in chat if file writing is unavailable). Use my anonymous participant code if I gave one; otherwise leave it UNASSIGNED. No name or email is required.

Start with a summary of at most 200 words. Then use these headings:
1. Setup: OS, agent surface/app/CLI, reported model/version if actually available, Descrybe route, and status (already ready / newly ready / attempted but blocked / skipped). Distinguish desktop tools from CLI tools.
2. Exercise outcomes: N1/N2/L1/L2, which were attempted, output created or missing, tests run, human gates honored or skipped, and acceptance actually received or still pending.
3. What worked: up to three observations with sanitized evidence.
4. What failed or confused: up to three incidents. For each: intended action, actual behavior, reproducible step, error category, attempted recovery, and what would help.
5. Effort: observed time to first artifact and setup time, clarification requests, retries, human corrections and approval prompts, external calls, token/cost data only if directly available. Use UNKNOWN when not measured. Mark estimates explicitly. Do not count approvals as corrections.
6. Review: self-review, fresh-agent review, or none. Actual model/harness and context exposure if known. Which checks support the verdict? Do not claim another agent ran unless it did.
7. September 16: one thing to keep, one thing to simplify, and the highest-impact fix, with reasons grounded in this run.

Use PASS / FAIL / BLOCKED / NOT RUN / UNKNOWN consistently. An attempted tool call is not proof of successful use. Separate observations, human reports, estimates, and recommendations. Do not invent totals, duration, costs, hidden reasoning, human satisfaction, or facts about tools you cannot inspect.

Append HUMAN FEEDBACK with these five questions, leaving answers blank for me:
- What useful thing did you accomplish, if any?
- What was the hardest or most confusing step?
- Did the agent pause where you expected and preserve progress? Give one example.
- How confident are you that you could repeat this alone? 1 (not confident) to 5 (very confident), and why?
- What should Dazza change for September 16?

Before showing the report, redact secrets, tokens, passwords, private URLs, names/emails, sensitive content, absolute personal paths, and raw provider responses. Use relative evidence paths and short sanitized excerpts. Do not attach full transcripts or source archives.
Show me the report for corrections and approval. Do not send or upload it. I decide what to share and by which channel.
```

**Human step:** answer the five questions, correct the agent's account, and share only the version you approve through the route Dazza announces. A blocked exercise is still useful feedback.

## Sources and Access
- [Official Descrybe user guide](https://descrybe.com/user-guide)
- [Claude Code setup](https://descrybe.com/user-guide/claude-code)
- [Open Connector setup](https://descrybe.com/user-guide/open-connector)
- [Open Connector repository](https://github.com/descrybe-com/descrybe-legal-engine-python)
- [Overnight Cookbook](https://github.com/dazzaji/interlateral_agents/blob/main/docs/overnight-cookbook.md)
- [HOPE exercises](https://github.com/dazzaji/hope_test_01)

Instructions reviewed September 4, 2026. Setup remains environment-dependent; access and successful research are distinct checks. Your existing tool subscription limits apply.

