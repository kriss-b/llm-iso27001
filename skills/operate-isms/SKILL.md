---
name: operate-isms
description: Operate an ISO 27001 / ISO 42001 / NIS 2 information security management system stored as markdown in this repository. Use when the user asks to instantiate, review, update, or run compliance checks against their ISMS, policies, risk register, or Statement of Applicability.
license: MIT
metadata:
  version: "1.0"
---

# Operate the ISMS

This repository is an ISO 27001 (+ISO 42001 +NIS 2) ISMS: policies, procedures,
risk register, and a Statement of Applicability (SoA), all in markdown and
versioned in git.

## Core rules

- The SoA is the single source of truth for control coverage. Never mark a
  control implemented without a document behind it.
- Git is the audit trail. Commit every change with a clear message.
- This repository can be the system of record on its own — nothing else is
  required. When content already lives elsewhere (Confluence, Notion, Jira,
  Probo, CISO Assistant...), the agent can read it and reconcile it here —
  typically importing it so git becomes the source of truth, or leaving the
  external tool as the reference when that fits better. A deliberate choice,
  made per source, never assumed.
- One source of truth per topic — extend existing documents rather than
  duplicating them.

## Checks

Files under `checks/` (and framework-specific `checks/` subfolders) are
executable verifications. Each reads its requirement from a policy or
procedure — never hard-coded — and returns pass/fail. Run a check by reading
its instructions and executing them against the real environment.

See `AGENTS.md` at the repository root for the full operating rules.
