# Example 3: Public CSV Cleanup and Validation

## Goals and Objectives

We will create a cleaned, documented copy of a public workshop-registration CSV for a program coordinator so the coordinator can reliably count attendance preferences and tool selections. The agent will preserve the source file unchanged, use only `context/registrations-public-sample.csv`, and produce `output/registrations-clean.csv`, `output/data-dictionary.md`, and `output/validation-report.md`. Success means row preservation and exclusions are reconciled, required fields and normalization rules are documented, duplicate handling is transparent, validation checks pass, and a human can reproduce three sample records from source to cleaned output. The exercise must not use real private registration data, infer sensitive attributes, contact registrants, upload data, or overwrite the source.

## Source Packet

- `context/registrations-public-sample.csv` - synthetic or intentionally public sample data; authoritative input.
- `context/cleanup-rules.md` - human-approved normalization and exclusion rules.

Known gaps and assumptions:

- Similar-looking names are not duplicates without an approved deterministic rule.
- Blank values remain blank unless `cleanup-rules.md` authorizes a replacement.

## Deliverables

- `output/registrations-clean.csv` - cleaned data with stable column order.
- `output/data-dictionary.md` - field definitions, allowed values, and transformations.
- `output/validation-report.md` - counts, exclusions, duplicates, nulls, transformations, tests, and residual issues.

## Scope and Authority

The agent may read the approved sample, create new outputs, and run local scripts or spreadsheet checks. It must not alter the source, use real participant information, infer missing personal facts, upload the data, merge uncertain duplicates, or contact anyone.

## Success Tests

1. `source rows = output rows + documented exclusions`.
2. Column names and order match the approved schema.
3. Required fields, blank counts, allowed-value violations, and duplicate-key candidates are reported.
4. Every transformation is documented and deterministic.
5. Re-running the process produces the same outputs.
6. The breaker tests malformed rows, encoding, dates, multi-select values, accidental data loss, and false duplicate matches.
7. A human traces three sample rows from source through transformations and records `ACCEPT` or `REVISE`.

## Work Plan

### Phase 1 - Contract

- Profile the sample without changing it.
- Propose the schema, transformations, duplicate rule, and exclusion rule.
- Stop for Human Gate 1.

### Phase 2 - Transform

- Produce new outputs only.
- Save commands, row counts, checksums, and validation output under `evidence/`.

### Phase 3 - Review, Break, Repair, Verify

- Reviewer checks the outputs against approved rules and reconciles counts.
- Breaker attacks data-loss, ambiguity, malformed-value, and false-duplicate cases.
- Lead repairs transformations and reruns all checks.
- Fresh verifier independently reruns critical reconciliation checks last.

### Phase 4 - Close

- Record human spot checks, unresolved anomalies, and whether the outputs are fit for the coordinator's stated use.

## Current Status

- Phase: `CONTRACT`
- Human decision: `PENDING`
- Source preservation: `REQUIRED`
- External upload authorized: `NO`
- Next action: profile the approved sample and request approval of cleanup rules.
