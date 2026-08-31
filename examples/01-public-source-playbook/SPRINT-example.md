# Example 1: Public-Source Project Playbook

## Goals and Objectives

We will create a concise project-planning playbook for a volunteer community workshop organizer so the organizer can turn an event idea into a workable one-page operating plan. The agent will use only the public or non-sensitive files listed under Source Packet and produce `output/workshop-playbook.md`. Success means the playbook contains the required sections, every material factual claim is traceable to a source, assumptions are labeled, the checklist is actionable, and a human organizer can use it to prepare a sample event without additional explanation. The agent may perform local, reversible work inside this repository, but must stop before publishing, contacting participants, committing money, changing a live calendar, or making privacy or security decisions.

## Source Packet

- `context/event-description.md` - organizer-provided description of the sample event; authoritative for purpose, audience, and constraints.
- `context/venue-guidance.md` - public guidance; supporting source for logistics only.
- `context/communications-policy.md` - authoritative rules for participant communications and data handling.

Known gaps and assumptions:

- No final date, venue booking, speaker commitment, or budget has been approved.
- The playbook must label all illustrative dates and names as examples.

## Deliverable

Create `output/workshop-playbook.md` with:

1. purpose and intended audience;
2. assumptions and unresolved decisions;
3. preparation sequence;
4. roles and responsibilities;
5. participant communications checklist;
6. privacy and security cautions;
7. a ten-item user acceptance checklist; and
8. source notes with links or file references.

## Scope and Authority

The agent may read the named files, draft the playbook, and run local checks. It must not invent commitments, contact anyone, publish anything, spend money, use personal information, or convert an example into a confirmed event fact.

## Success Tests

1. **Structure:** all eight required sections exist.
2. **Source support:** every external factual claim cites one of the named sources.
3. **Assumptions:** unconfirmed dates, people, prices, and commitments are clearly labeled.
4. **Quality:** the sequence is clear, concise, and usable by a first-time organizer.
5. **Breaker test:** identify at least five ways the playbook could cause confusion, overpromise, or mishandle participant information.
6. **Human acceptance:** an organizer uses the checklist to explain what they would do next and records `ACCEPT` or `REVISE`.

## Work Plan

### Phase 1 - Contract

- Read and inventory the source packet.
- Report any contradiction or missing file.
- Propose an outline and stop for Human Gate 1.

### Phase 2 - Build

- Draft the smallest complete playbook.
- Save a section-presence check and source-support table under `evidence/`.
- Stop for the organizer's usefulness and tone review.

### Phase 3 - Review, Break, Repair, Verify

- Reviewer checks completeness, accuracy, citations, and audience usefulness.
- Breaker attacks assumptions, ambiguous instructions, privacy risks, and overpromising.
- Lead repairs material findings.
- Fresh verifier checks the repaired artifact last.

### Phase 4 - Close

- Record review verdicts, human acceptance, residual risks, and unresolved event decisions.

## Current Status

- Phase: `CONTRACT`
- Human decision: `PENDING`
- Artifact: `NOT STARTED`
- Next action: validate the source packet and request Human Gate 1.
