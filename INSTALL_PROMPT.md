# Install this project with an AI coding agent

This file is intentionally part of the repository template. **Replace all
PROJECT placeholders and verify commands before publishing a derived repo.**
Never present placeholder installation commands as working instructions.

Copy and adapt the following prompt for ChatGPT Work, Codex, OpenCode,
Claude Code, Cursor or a comparable coding agent.

~~~text
Help me install and configure PROJECT from PROJECT_REPOSITORY_URL.

My goal is to run the project locally, not to deploy to production.

1. Read the project's latest README.md, AGENTS.md, INSTALL_PROMPT.md and
   relevant docs before selecting commands.
2. Inspect my OS, architecture, required runtimes, package managers and
   existing installation. Summarize missing prerequisites.
3. Ask before installing packages, changing persistent files, granting
   permissions, creating accounts or interacting with external services.
4. Preserve existing configuration. Back up before altering shared files.
5. Follow documented, pinned install steps and project tests. Do not invent
   scripts when the repo has no verified setup instructions.
6. Use local/demo credentials only if documented as such; never expose or
   commit secrets, access tokens or private keys.
7. Verify a real working local result (or report precise limitations).
8. Give me a short summary of changes, checks, unresolved setup steps
   and instructions to undo the changes.

SAFETY:
- Never deploy, merge, migrate databases, alter cloud services, edit DNS,
  grant wide privileges or modify production without separate approval.
- No unreviewed pipe-to-shell installers, destructive cleanup or silent
  overwrites. Do not assume test success without running the checks.
- Prefer existing well-maintained dependencies; do not create unnecessary
  new infrastructure, agents, queues, retries or auth layers.
~~~

## Maintainers of generated repos

Replace PROJECT / PROJECT_REPOSITORY_URL, customize dependencies and tests,
and update the README's install prompt block for the actual repository.
Keep this prompt aligned with AGENTS.md and the project's security boundaries.
