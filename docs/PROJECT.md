# Project context

Fill this in together before agents start implementation. Keep it short and current. “Not decided” is better than an invented requirement.

## What we are building

- **Name:** Not decided
- **Problem and users:** Not decided
- **Success looks like:** Not decided
- **Out of scope:** Not decided
- **Deadline or demo:** Not decided

## People and coordination

- **Human lead / final decision maker:** Not assigned
- **Reviewer / integration owner:** Not assigned
- **Task board:** GitHub issues in this repository
- **Ownership:** One assigned owner per task; list files/areas in the issue. Resolve overlaps before editing. Shared files need explicit coordination.
- **Communication:** Task issues and PRs; external messages require human authorization.

## Technical context

- **Stack and architecture:** Not chosen; this starter does not include an application.
- **Source layout and module boundaries:** Define when choosing the stack.
- **Shared interfaces:** Record contracts and their owners here before parallel implementation.
- **External services / data:** None configured. Add only approved services and data sources.
- **Environment:** Copy `.env.example` to `.env` only if needed. Never commit real secrets.

## Commands

These check the starter tooling, not your future application:

```sh
python3 -m unittest discover -s tests -v
```

- **App install:** Not configured
- **App dev server:** Not configured
- **App test / lint / build:** Not configured — replace these entries and enable/extend the CI example in `docs/checks.yml.example` when adding the app.
- **Deploy:** Not configured; requires explicit authorization.

## Current priorities

1. Agree on the project brief and choose the stack.
2. Define module boundaries and create scoped task issues.
3. Build the smallest useful end-to-end version.
