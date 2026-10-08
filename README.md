# Agent Team Starter

**The one starter for teams building with AI agents.**

Your team brings the idea. This repo brings shared context, clear ownership, and a workflow that helps agents collaborate without overwriting each other.

For hackathons, work teams, and side projects. Any stack. No framework to learn.

## Start in one step

Paste this into your coding harness with GitHub access:

```text
Create my project from https://github.com/mashathepotato/agent-team-starter
using GitHub's template feature (ask me for the project name and visibility).
Clone it, read AGENTS.md, and help me fill in docs/PROJECT.md.
Follow the team workflow for every change, including onboarding:
use your own branch and worktree, agree on scope, and open a PR.
```

Or click **[Use this template](https://github.com/mashathepotato/agent-team-starter/generate)**. Forking works too.

Prefer the terminal? With GitHub CLI installed and signed in:

```sh
gh repo create YOUR-PROJECT --template mashathepotato/agent-team-starter --private --clone
```

## One agent. One task. One branch.

1. **Read the context.** `AGENTS.md` and `docs/PROJECT.md` tell agents what you’re building and how to work together.
2. **Agree on ownership.** Use a task issue to name the owner, files or areas they can change, and acceptance criteria. Resolve overlapping work before editing.
3. **Work in isolation.** From the clone, run:

   ```sh
   python3 scripts/start-task.py alex add-login
   ```

   This creates `agent/alex/add-login` and a separate checkout beside your repo. Open that checkout in your harness. Requires Git and Python 3.9+.
4. **Hand off a PR.** Test your changes, push your branch, and open a PR. A teammate or designated reviewer checks the diff before merging.

Agents must not revert someone else’s changes, force-push shared branches, or merge without authorization. These are working agreements; configure repository protections to enforce review and push restrictions.

## Everything has a home

| File | What belongs here |
| --- | --- |
| [`AGENTS.md`](AGENTS.md) | The rules every agent follows |
| [`docs/PROJECT.md`](docs/PROJECT.md) | Goal, stack, commands, boundaries, and who decides |
| [`docs/DECISIONS.md`](docs/DECISIONS.md) | Decisions the next agent must understand |
| [Task issues](../../issues) | Owner, scope, progress, and handoff |
| [Pull requests](../../pulls) | Changes, evidence, review, and integration |

Includes task and PR templates, a practical `.gitignore`, environment variable example, a ready-to-enable CI example, and entry points for harnesses that read `AGENTS.md`, `CLAUDE.md`, or GitHub Copilot instructions. For other harnesses, explicitly ask them to read `AGENTS.md` before working. Instruction files are guidance, not a sandbox.

Start small: fill in the project brief, create a task, and build. Add your app and its real test/build commands when you choose a stack. See [contributing](CONTRIBUTING.md) for the full workflow and first-time repository settings.

MIT licensed. Make it yours.
