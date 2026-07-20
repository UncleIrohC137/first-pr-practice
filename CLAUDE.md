# first-pr-practice

A sandbox repo for practicing the contribution workflow (branch → commit →
push → PR → merge), not a real application. Content is intentionally minimal
- there's no build, no dependencies, and no test suite to run.

## Conventions

- Default branch: `main`.
- Feature/fix branches: `fix/<short-description>` or `feature/<short-description>`.
- Open PRs with `gh pr create`, merge with `gh pr merge --squash --delete-branch`.
- Commit messages: short, imperative subject line (e.g. "Fix typo in README").
