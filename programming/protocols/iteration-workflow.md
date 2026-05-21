# Iteration Workflow

This workflow defines the standard sequence for programming iterations.

```text
Human defines iteration
    |
    v
Implementer executes
    |
    v
Documenter synchronizes knowledge
    |
    v
Auditor validates
    |
    v
Human reviews
    |
    v
Human commits manually
```

## 1. Human Defines Iteration

The human maintainer defines the objective, constraints, expected outputs, and validation criteria. Scope should be small enough to review and reverse.

## 2. Implementer Executes

The Implementer performs the approved code or structure changes. It must avoid unrelated features, broad refactors, and strategic documentation changes unless explicitly assigned.

## 3. Documenter Synchronizes Knowledge

The Documenter updates affected documentation so it reflects implemented reality. Roadmap changes are made only when the iteration changes repository evolution visibility.

## 4. Auditor Validates

The Auditor checks scope alignment, modularity, documentation coherence, roadmap accuracy, and governance compliance. The Auditor reports issues without directly implementing fixes.

## 5. Human Reviews

The human maintainer reviews the implementation, documentation, validation results, and remaining risks. The human decides whether the iteration is ready to persist.

## 6. Human Commits Manually

If accepted, the human creates the commit. AI agents do not control repository history.
