---
title: About the historical record
type: explanation
summary: "Why superseded documents are retained, and how to read them safely."
audience: maintainer
status: current
verified: 2026-08-15
---

# About the historical record

This part preserves documents that recorded the state of the system at a point in
time: audits, incident reports, planning documents, and session logs. They are
kept because they explain how the system reached its present shape, and because
deleting the reasoning behind a decision makes the decision impossible to revisit.

## How to read these pages

**Do not follow instructions from this part.** Commands, paths, repository names,
and component counts in these documents were accurate when written and are not
maintained. Several describe repositories that are now archived and procedures
that have been replaced.

Every page here opens with a banner stating that it is a historical record. Front
matter carries `status: historical`.

For current material:

- Procedures — [How-to guides](index.md)
- Exact values — [Reference](index.md)
- Design reasoning — [Architecture](index.md)
- Decisions and their status — [Architecture decision records](index.md)

## What belongs here

A document moves into History when it meets any of these conditions:

- It describes a state of the system rather than its intended behaviour, such as
  an audit or a status report.
- It records an event, such as an incident report.
- It was superseded by a later document, and the replacement is linked from it.
- Its claims can no longer be verified against committed code, and no maintainer
  is willing to correct it.

A document is never edited to appear current. If the content is still accurate
and useful, it is rewritten as a current page and the historical copy is removed
rather than kept in both places.

## Relationship to architecture decision records

Architecture decision records are not historical documents, even when superseded.
An ADR remains in [Governance](index.md) with a status field
recording whether it is accepted or superseded, because the record of a decision
is permanently relevant. Audits and incident reports describe circumstances
rather than decisions, so they live here.

## Related

- [Documentation policy](https://github.com/gaganjainse/shesh-docs/blob/main/src/governance/documentation-policy.md) — the rules for
  when a page is written, corrected, or retired.
- [Architecture decision records](index.md) — the decision
  trail, including superseded entries.
