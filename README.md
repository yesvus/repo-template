# New project

Minimal starting point for a new yesvus repository. **Replace this README with the project's actual purpose and commands before sharing it as an implementation.**

## Purpose

Describe the problem, current status, scope, and how to use the project.

## Install with an AI coding agent

Copy into your AI coding tool, replacing placeholders with the actual
repository name and URL after using this template:

~~~text
Help me install PROJECT from PROJECT_REPOSITORY_URL for local use.
Read INSTALL_PROMPT.md, README.md and AGENTS.md first.
Check prerequisites and ask before installing dependencies or changing
configuration. Run the project's actual documented tests and report results.
Never deploy or request/commit secrets without separate authorization.
~~~

[Full installation prompt template](INSTALL_PROMPT.md).

## Development

Add the real environment/setup and verification commands for this project's stack. Do not claim tests passed until they have been run.

## Project documentation

- [AGENTS.md](AGENTS.md): agent boundaries and places to find project-specific instructions
- [CLAUDE.md](CLAUDE.md): Claude Code compatibility import of AGENTS.md

## After creating this repository

1. Replace the placeholders and choose an appropriate license **if** this project is intended to be open source. A public GitHub repository without a license is not automatically open source.
2. Add a suitable `.gitignore` and CI tests for the chosen language/framework; this template deliberately does **not** add a fake green CI check.
3. Clone common labels if needed: `gh label clone yesvus/.github --repo OWNER/REPO` (existing destination labels are preserved).
4. Verify GitHub-hosted Actions runs with actual tests before considering a required check. Set branch rulesets and app permissions separately, with explicit review.
5. The account-wide issue/PR/security templates come from [yesvus/.github](https://github.com/yesvus/.github) when there are no local overrides.

Create another repository from this template:

```bash
gh repo create yesvus/NEW_REPO --private --template yesvus/repo-template --clone
```

Do not enable production secrets, deploy integrations, third-party apps, or self-hosted runners merely by using a template.
