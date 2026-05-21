# Context Management

Context management keeps AI-assisted programming focused, efficient, and reviewable.

## Minimize Unnecessary Context

Agents should receive the smallest useful set of files, diffs, decisions, and constraints needed for the task. Broad context increases noise and can lead to unrelated changes.

## Use Git for Scoped Analysis

Use inspection commands to understand the active work area:

- `git status --short` to identify changed files.
- `git diff` to inspect unstaged changes.
- `git diff --cached` to inspect staged changes.
- `git log --oneline -n <count>` to understand recent repository movement.

These commands are for analysis and continuity, not for autonomous history modification.

## Limit File Exposure

Open only files related to the objective, direct dependencies, or validation path. Avoid full-project analysis unless the iteration explicitly requires architectural review.

## Reduce Token Consumption

Prefer targeted searches, small file reads, and summarized findings. Avoid copying large files into working context when line-specific inspection is enough.

## Avoid Unnecessary Full-Project Analysis

Full-project analysis is appropriate only when the task involves architecture, cross-cutting behavior, major refactoring, or unclear ownership boundaries.

## Maintain Continuity Between Iterations

At the start of an iteration, review the current status, recent roadmap state, and relevant domain documentation. At the end, summarize decisions, files changed, validation performed, and any deferred work.

## Practical Recommendations

- Start with repository status before editing.
- Read domain documentation before changing domain behavior.
- Inspect diffs before handing work to review.
- Keep context aligned to the stated objective.
- Document unresolved assumptions instead of silently expanding scope.
