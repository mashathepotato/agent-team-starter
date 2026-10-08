# Shared context and supporting docs

- **Owner:** codex
- **Updated:** 2026-10-08
- **Status:** ready for review
- **Task / PR:** User request to add agent communication and supporting metadata folders; PR from the branch below.
- **Branch:** agent/codex/shared-context
- **Scope:** Context/docs scaffolding, README, contributor/agent instructions, and PR template.

## Current state

Added per-task handoffs in `context/`, a project plan, and supporting notes under `docs/`. Instructions limit routine reading to relevant context and explain that separate worktrees exchange notes through Git.

## For the next agent

- **Next action and owner:** Repository owner reviews the PR for integration.
- **Dependencies / blockers:** None.
- **Checks and results:** `git diff --check` passed; all six starter integration tests passed.
- **Relevant context:** [Coordination guide](../../README.md), [docs index](../../../docs/README.md).
