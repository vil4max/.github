# .github — repository notes

<!-- repository-visibility-policy -->
Repository visibility: **PUBLIC**.

## Data handling

Never include confidential or sensitive personal data in source, documentation,
Git history, commit messages, issues, pull requests, logs, or artifacts. This
includes private financial information, compensation expectations or offers,
personal assessments, health or family details, private correspondence, and
application records. Use fictional data in examples and tests. Never commit
credentials, tokens, passwords, session data, or private keys.

## Documentation quality

Write public-facing documentation in clear, technical English for readers
without access to private workspace context. Keep instructions accurate,
repository-relative, and reproducible. Distinguish implemented behavior from
plans, state relevant prerequisites and limitations, and update documentation
with the behavior it describes. Exclude personal notes, internal handoffs,
machine-specific paths, and unsupported claims.
<!-- /repository-visibility-policy -->

GitHub profile and shared community metadata for `vil4max/.github`.

- Profile content lives in `profile/`.
- Community documents and issue/PR templates live at the repository root.
- Local ownership is recorded in `.agents/project-context.yaml` (`personal`, `core`).
- Shared agent behavior lives in `../../agent-engineering-kit/AGENTS.md`.

For documentation changes, inspect Markdown links and run `git diff --check`.
This repository has no application build.
