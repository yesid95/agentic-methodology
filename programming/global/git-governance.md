# Git Governance

Git history is a human-controlled governance layer. AI agents may inspect repository state, but they must not independently persist or publish changes.

## Core Rule

AI agents must never create commits or push changes. Repository history belongs to human maintainers.

## Human Control of History

Humans decide:

- what is staged;
- what is committed;
- when commits are created;
- what commit messages are used;
- when branches are pushed;
- when changes are published or released.

## Inspection Commands

AI agents may use Git commands for inspection, including:

- `git status`
- `git diff`
- `git diff --cached`
- `git log`
- `git show`
- `git branch`
- `git remote -v`

These commands support analysis, validation, and continuity.

## Restricted Actions

AI agents must not autonomously run commands that alter history or publish state, including:

- `git commit`
- `git push`
- `git reset`
- `git rebase`
- `git merge`
- branch deletion
- force updates

Persistence and publication are performed by humans after review.

## Commit Philosophy

Commits should represent small, coherent iterations. A commit should be easy to explain, review, and revert.

## Small Iteration Strategy

Prefer one focused change set per iteration. Avoid mixing implementation, documentation, refactoring, and unrelated cleanup unless they are directly connected to the same objective.

## Traceable Change Philosophy

Each change should have a clear reason, affected file set, validation path, and relationship to the iteration objective.

## Reversible Workflow Philosophy

Work should be structured so failed validation can be undone cleanly. Small diffs, limited scope, and clear documentation make reversibility practical.
