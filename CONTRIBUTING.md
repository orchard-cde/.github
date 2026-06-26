# Contributing to Orchard

Thanks for your interest in contributing.

## Reporting bugs and requesting features

File an issue on the relevant repository using the bug or feature template. Security issues should NOT be filed as public issues — see [SECURITY.md](SECURITY.md).

## Submitting changes

> **GitHub is the source of truth.** Pull requests are accepted only on GitHub. The [gitlab.com/orchard-cde](https://gitlab.com/orchard-cde) mirror is a read-only backup — issues, PRs, and merge requests opened there are not monitored.

1. Fork the repo and create a feature branch from `main`.
2. Make your change. Keep PRs focused: one concern per PR.
3. Add or update tests. Every repo's CI must pass.
4. Open a pull request against `main`. The PR template prompts for a summary and test plan.
5. Address review feedback; squash-merge is the default.

## Code style

Each repo documents its own conventions in its README or `AGENTS.md`. In general:

- Match the surrounding style. Don't reformat unrelated code.
- Don't add comments that just restate what the code does.
- Don't add backwards-compatibility shims unless explicitly requested.

## License

All contributions are licensed under [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0). By opening a pull request you agree your contribution may be released under that license, consistent with section 5 of the Apache 2.0 terms.
