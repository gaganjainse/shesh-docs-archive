# shesh-docs-archive

Superseded documentation for the Shesh fleet, preserved as a historical record.

- **Licence:** GPL-3.0-or-later
- **Owner:** Gagan Jain ([@gaganjainse](https://github.com/gaganjainse))
- **Current documentation:** [shesh-docs](https://github.com/gaganjainse/shesh-docs)

## Read this first

**Nothing in this repository is maintained.** Every document here describes the
state of the system at the time it was written. Commands, paths, repository
names, and component counts were accurate then and are not corrected now.
Several describe repositories that have since been archived and procedures that
have been replaced.

Do not follow instructions from this repository. For current documentation, use
[shesh-docs](https://github.com/gaganjainse/shesh-docs).

## Why it exists

Deleting the reasoning behind a decision makes the decision impossible to
revisit. These records answer questions the current documentation cannot: what
the system looked like before a change, which failure motivated a safeguard, and
what was considered and rejected.

They were separated from the main book because they are read rarely and were
close to half its bulk. Splitting them keeps the working documentation short
without losing provenance.

## Contents

| Category | Documents |
|---|---|
| Audits | Fleet audits and gap analyses from 2026-08-11 and 2026-08-12 |
| Incidents | Post-mortems, including the 2026-08-11 parallel-agent collision |
| Decision logs | Full prompt and decision trail across working sessions |
| Session records | Handoff documents and generated session prompts |
| Planning | Superseded desktop plans, roadmaps, and tooling surveys |
| Studies | Provider surveys and research notes |

## What belongs here

A document moves here when any of these is true:

- It describes a state of the system rather than its intended behaviour.
- It records an event, such as an incident.
- It was superseded, and the replacement is linked from it.
- Its claims can no longer be verified against committed code, and no maintainer
  will correct them.

Documents are never edited to appear current. If content is still accurate and
useful, it is rewritten as a page in `shesh-docs` and the copy here is removed
rather than kept in both places.

## What does not belong here

Architecture decision records stay in
[shesh-docs](https://github.com/gaganjainse/shesh-docs) even when superseded. An
ADR carries a status field recording whether it is accepted or superseded,
because the record of a decision remains permanently relevant and needs a stable
link target.

## Licence

GPL-3.0-or-later — see [LICENSE](LICENSE).
