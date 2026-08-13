# MONOLITH Droid

Small, careful tools for AI-assisted open source maintenance.

MONOLITH is a public lab name for building practical maintainer utilities around
Codex and coding agents. The current work is split into two small, reusable
layers: one for side-effect boundaries, and one for durable context.

The tone is a little space-age: quiet black slab, calm mission console, no
surprise launches.

## Now Building

### [I/O Safety Kit for OSS](https://github.com/monolith-droid/io-safety-kit-for-oss)

[![CI](https://github.com/monolith-droid/io-safety-kit-for-oss/actions/workflows/ci.yml/badge.svg)](https://github.com/monolith-droid/io-safety-kit-for-oss/actions/workflows/ci.yml)
[![Release](https://img.shields.io/github/v/release/monolith-droid/io-safety-kit-for-oss?label=release)](https://github.com/monolith-droid/io-safety-kit-for-oss/releases)

A stable v1 fail-closed I/O safety layer for OSS maintainers using Codex and
other coding agents for PR review, issue triage, release prep, security checks,
and handoff reports.

Latest: [v1.3.0](https://github.com/monolith-droid/io-safety-kit-for-oss/releases/tag/v1.3.0),
with a common JSON command-result contract plus wheel and tag-push CI checks.

It answers the operational question: what may an agent read, propose, render,
or promote without surprising the maintainer?

What it focuses on:

- approval manifests,
- scoped agent input,
- report-only defaults,
- fail-closed gates,
- safe output promotion,
- evidence bundle review,
- cross-platform downstream dogfooding,
- schema-backed JSON command results,
- auditable maintainer reports,
- regression tests for high-risk actions.

### [MONOLITH Core](https://github.com/monolith-droid/monolith-core)

[![CI](https://github.com/monolith-droid/monolith-core/actions/workflows/ci.yml/badge.svg)](https://github.com/monolith-droid/monolith-core/actions/workflows/ci.yml)
[![Release](https://img.shields.io/github/v/release/monolith-droid/monolith-core?label=release)](https://github.com/monolith-droid/monolith-core/releases)

A new public-safe core for durable agent memory: Obsidian-backed knowledge
cards, indexes, context packs, and branch-return checks for coding-agent
workflows.

Latest: [v0.3.0](https://github.com/monolith-droid/monolith-core/releases/tag/v0.3.0),
with a report-only adapter-readiness contract that rejects private or
host-specific references.

It answers the context question: how does useful project knowledge survive
beyond one chat, one branch, or one model session?

What it focuses on:

- one information unit per card,
- machine-readable knowledge indexes,
- task-specific context packs,
- branch-return reports,
- public-safe adapter-readiness reports,
- Hermes-style report-only curation,
- synthetic fixtures and CI-friendly validation.

## Public Boundary

This profile only publishes the reusable OSS layer: tools, docs, examples,
fixtures, and releases. Private operations, personal details, secrets, local
paths, and service-specific workflows stay off the public surface.

| Layer | Stable contract | Boundary |
| --- | --- | --- |
| I/O Safety Kit | side-effect gates and JSON command results | decides what an agent may read, report, or promote |
| MONOLITH Core | durable context and adapter-readiness reports | preserves reusable knowledge without runtime authority |

## Next Signals

- show the two-repo pattern clearly: I/O Safety Kit controls side effects;
  MONOLITH Core keeps context recoverable
- keep converting private downstream lessons into public-safe issues, docs,
  examples, tests, and releases
- publish lightweight maintainer workflow notes without private logs, local
  paths, secrets, or service-specific wiring

## Links

- [I/O Safety Kit for OSS](https://github.com/monolith-droid/io-safety-kit-for-oss)
- [I/O Safety Kit latest release](https://github.com/monolith-droid/io-safety-kit-for-oss/releases/tag/v1.3.0)
- [I/O Safety Kit security model](https://github.com/monolith-droid/io-safety-kit-for-oss/blob/main/docs/security-model.md)
- [I/O Safety Kit cross-platform dogfooding](https://github.com/monolith-droid/io-safety-kit-for-oss/blob/main/docs/cross-platform-dogfooding.md)
- [MONOLITH Core](https://github.com/monolith-droid/monolith-core)
- [MONOLITH Core latest release](https://github.com/monolith-droid/monolith-core/releases/tag/v0.3.0)
