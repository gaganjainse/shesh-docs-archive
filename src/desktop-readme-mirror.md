---
title: Shesh Documentation
type: reference
summary: "This directory is the single source of truth for the Shesh ecosystem — the production-grade,."
audience: maintainer
status: historical
verified: 2026-08-15
---

# Shesh Documentation

> **Historical record.** This document describes the state of the system at the time it was written and is retained for provenance. It is not maintained and may contradict current behaviour. For current documentation, see the [reference section](index.md).

This directory is the single source of truth for the **Shesh** ecosystem — the production-grade,
local-first, AI-assisted desktop built on this fork of `end-4/dots-hyprland` for the MSI Sword
16 HX B14VEKG on CachyOS 260628.

**Start with [`SHESH/00_INDEX.md`](desktop-plan-index.md).** It contains the verified hardware/software
facts (correcting errors in earlier AI audits) and the map of every document.

| Document | Purpose |
|---|---|
| [00_INDEX](desktop-plan-index.md) | Master index, verified facts, philosophy, vision |
| [01_AUDIT](desktop-audit-2026-08-13.md) | Independent audit of the live repo — every issue with exact fixes |
| [02_ROADMAP](desktop-roadmap.md) | Phased execution plan (effort, dependencies, exit criteria) |
| [03_DISK_STRUCTURE](https://github.com/gaganjainse/shesh-docs/blob/main/src/explanation/disk-layout.md) | On-disk layout: job vs personal vs projects, backup policy |
| [04_DEVICE_PROFILE](https://github.com/gaganjainse/shesh-docs/blob/main/src/explanation/target-hardware.md) | MSI Sword + CachyOS tuning: GPU/MUX, 144 Hz, power, kernel |
| [05_SMART_ORGANIZER_V2](https://github.com/gaganjainse/shesh-docs/blob/main/src/how-to/configure-the-organizer.md) | Real-time AI file organizer (Rust watcher + Python classifier) |
| [06_SHESH_AGENT](https://github.com/gaganjainse/shesh-docs/blob/main/src/how-to/configure-the-desktop-agent.md) | The voice agent: Newelle + Ollama + MCP + audit log |
| [07_AUTOMATIONS](https://github.com/gaganjainse/shesh-docs/blob/main/src/how-to/configure-automations.md) | Every autonomous job, unit, and udev rule |
| [08_ECOSYSTEM_TOOLS](desktop-tooling-survey.md) | More tools to build + what to steal from other repos + phone harness |
| [09_AI_PROMPTS](desktop-build-prompts.md) | Copy-paste prompts for AI pair-programming per phase/situation |
| [10_LICENSES_AND_SOURCES](https://github.com/gaganjainse/shesh-docs/blob/main/src/reference/licences.md) | License manifest, pinned versions, all links audited |
| [checklist](https://github.com/gaganjainse/shesh-docs/blob/main/src/reference/desktop-checklist.md) | Tick these as you implement |

The audit and roadmap supersede the two earlier AI documents you provided (`shesh-desktop-audit.md`
and the 63-page master-plan PDF). Both contained errors — most notably the wrong display resolution
and GPU, plus new bugs introduced while "fixing" the repo — all catalogued in `01_AUDIT.md`.
