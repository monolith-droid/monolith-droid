# MONOLITH Droid

Small, careful tools for AI-assisted open source maintenance.

MONOLITH is a public lab name for building practical maintainer utilities around
Codex and coding agents. The tone is a little space-age: quiet black slab, calm
mission console, no surprise launches.

## Now Building

### [I/O Safety Kit for OSS](https://github.com/monolith-droid/io-safety-kit-for-oss)

[![CI](https://github.com/monolith-droid/io-safety-kit-for-oss/actions/workflows/ci.yml/badge.svg)](https://github.com/monolith-droid/io-safety-kit-for-oss/actions/workflows/ci.yml)
[![Release](https://img.shields.io/github/v/release/monolith-droid/io-safety-kit-for-oss?label=release)](https://github.com/monolith-droid/io-safety-kit-for-oss/releases)

A stable v1 fail-closed I/O safety layer for OSS maintainers using Codex and
other coding agents for PR review, issue triage, release prep, security checks,
and handoff reports.

What it focuses on:

- approval manifests,
- scoped agent input,
- report-only defaults,
- fail-closed gates,
- safe output promotion,
- evidence bundle review,
- auditable maintainer reports,
- regression tests for high-risk actions.

## Public Boundary

This profile only publishes the reusable OSS layer: tools, docs, examples,
fixtures, and releases. Private operations, personal details, secrets, local
paths, and service-specific workflows stay off the public surface.

## Next Signals

- downstream adapter confidence for the v1 line
- adapter-safe JSON handling
- synthetic maintainer case studies
- safer downstream dogfooding patterns

## Links

- [Project repository](https://github.com/monolith-droid/io-safety-kit-for-oss)
- [Latest release](https://github.com/monolith-droid/io-safety-kit-for-oss/releases/tag/v1.0.0)
- [Security model](https://github.com/monolith-droid/io-safety-kit-for-oss/blob/main/docs/security-model.md)
- [Downstream dogfooding](https://github.com/monolith-droid/io-safety-kit-for-oss/blob/main/docs/downstream-dogfooding.md)
