# Contributing to TeamFlow

Thank you for contributing to TeamFlow. To keep development organised and reduce conflicts, all developers should follow these basic Git workflow rules.

## Branching

Always create a new feature branch from an up-to-date `main` branch.

Before creating a branch, update `main`:

```bash
git switch main
git pull
```

Then create your feature branch.

Use clear branch names that describe the work being done, for example:

```bash
feature/task-dashboard
feature/project-docs
```

Do not develop features directly on `main`.

## Commits

Make meaningful commits that clearly describe the work completed.

Where possible, include the relevant TeamFlow ticket number in the commit message.

For example:

```bash
git commit -m "TF-002: add contribution guidelines"
```

Avoid vague commit messages such as:

```text
update
changes
fixed stuff
```

## Pull Requests

Feature work should be merged into `main` using a Pull Request.

Before opening or merging a Pull Request, review your changes and make sure the branch is working correctly.

Do not merge unfinished or untested work into `main`.

## Keeping Feature Branches Updated

If `main` changes while you are working on a feature, update your feature branch before merging.

This may require rebasing or otherwise bringing the latest changes from `main` into your branch.

Keeping feature branches up to date helps reduce merge conflicts and makes Pull Requests easier to review.

## Summary

TeamFlow developers should:

* Create feature branches from an up-to-date `main`.
* Use descriptive branch names such as `feature/task-dashboard`.
* Make meaningful commits and reference tickets such as `TF-002`.
* Never work directly on `main`.
* Use Pull Requests to merge feature work.
* Update or rebase feature branches when necessary before merging.

