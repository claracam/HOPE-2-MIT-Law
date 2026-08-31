# Example 2: Read-Only Website Quality Review

## Goals and Objectives

We will produce a prioritized quality review of a local static website for its owner so the owner can decide what to fix before publication. The agent will inspect only the local files under `site/`, run the site locally if needed, and write `output/site-review.md`; it will not modify website files. Success means the report identifies reproducible functional, content, responsive-layout, accessibility, and security or privacy issues; includes evidence and severity; distinguishes observed defects from suggestions; and gives the owner a short manual acceptance walkthrough. The agent must stop before editing the site, publishing, deploying, using credentials, submitting forms, or contacting external services.

## Source Packet

- `site/` - the complete local website under review.
- `context/intended-audience.md` - authoritative audience and purpose statement.
- `context/review-requirements.md` - authoritative list of pages and workflows that matter most.

Known gaps and assumptions:

- Production behavior, analytics, authenticated pages, and third-party services are out of scope unless separately authorized.
- External links may be inventoried, but they must not be treated as verified merely because they appear in HTML.

## Deliverable

Create `output/site-review.md` containing:

- executive summary;
- findings ordered by severity;
- exact file, page, viewport, and reproduction steps;
- screenshots or test evidence paths;
- recommended repair and expected outcome;
- observed defects separated from optional improvements; and
- a five-step human acceptance walkthrough.

## Scope and Authority

The agent may read local files, start a local development server, use browser automation against localhost, and save screenshots under `evidence/`. It must not edit the site, send forms, use live credentials, publish, deploy, or make external changes.

## Success Tests

1. Every required page is reviewed at desktop and mobile widths.
2. Navigation and named critical workflows are exercised locally.
3. Each defect has reproducible steps and evidence.
4. Text overflow, broken links within the local site, missing accessible names, and obvious contrast or keyboard issues are checked.
5. The breaker tests false positives, viewport edge cases, and ways automated checks could miss the real user experience.
6. A human completes the acceptance walkthrough and records whether the report is useful and accurate.

## Work Plan

### Phase 1 - Contract

- Inventory pages, frameworks, start commands, and critical workflows.
- Propose the browser and viewport test matrix.
- Stop for Human Gate 1.

### Phase 2 - Inspect

- Start only a local server if required.
- Run the approved checks without editing source files.
- Save screenshots and command output under `evidence/`.

### Phase 3 - Review, Break, Verify

- Reviewer checks report completeness and evidence quality.
- Breaker attempts to reproduce or falsify the highest-severity findings.
- Lead corrects report errors only.
- Fresh verifier confirms final findings against the frozen site and evidence.

### Phase 4 - Close

- Stop the local server.
- Record verified findings, uncertainties, and the owner's next decision.

## Current Status

- Phase: `CONTRACT`
- Human decision: `PENDING`
- Site modifications authorized: `NO`
- Next action: inventory the local site and request approval of the test matrix.
