# MONOLITH Droid

Small, careful tools for AI-assisted open source maintenance.

MONOLITH is a public lab name for building practical maintainer utilities around
Codex and coding agents. The tone is a little space-age: quiet black slab, calm
mission console, no surprise launches.

## Now Building

### [Codex Maintainer Safety Kit](https://github.com/monolith-droid/codex-maintainer-safety-kit)

[![CI](https://github.com/monolith-droid/codex-maintainer-safety-kit/actions/workflows/ci.yml/badge.svg)](https://github.com/monolith-droid/codex-maintainer-safety-kit/actions/workflows/ci.yml)
[![Release](https://img.shields.io/github/v/release/monolith-droid/codex-maintainer-safety-kit?label=release)](https://github.com/monolith-droid/codex-maintainer-safety-kit/releases)

A fail-closed operations layer for maintainers using Codex for PR review, issue
triage, release prep, security checks, and handoff reports.

What it focuses on:

- approval manifests,
- report-only defaults,
- fail-closed gates,
- auditable maintainer reports,
- regression tests for high-risk actions.

## Public Boundary

This profile only publishes the reusable OSS layer: tools, docs, examples,
fixtures, and releases. Private operations, personal details, secrets, local
paths, and service-specific workflows stay off the public surface.

## Next Signals

- PR review report rendering
- issue triage report rendering
- signed approval manifest design
- safer downstream dogfooding patterns

## Links

- [Project repository](https://github.com/monolith-droid/codex-maintainer-safety-kit)
- [Security model](https://github.com/monolith-droid/codex-maintainer-safety-kit/blob/main/docs/security-model.md)
- [Downstream dogfooding](https://github.com/monolith-droid/codex-maintainer-safety-kit/blob/main/docs/downstream-dogfooding.md)