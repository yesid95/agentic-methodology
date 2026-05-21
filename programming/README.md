# Programming Workflows

The programming domain defines a human-led methodology for software development work supported by specialized AI agents.

## Purpose

This domain provides operational guidance for planning, implementing, documenting, auditing, and validating programming iterations. It keeps AI assistance scoped, reviewable, and subordinate to human repository ownership.

## Specialized Agent Overview

- **Implementer:** executes scoped code or structure changes without inventing features or committing work.
- **Documenter:** synchronizes documentation with implemented reality and maintains roadmap visibility.
- **Auditor:** validates coherence, governance, modularity, and technical quality without directly implementing changes.

## Workflow Summary

Programming iterations follow a controlled sequence:

1. A human defines the iteration objective and constraints.
2. The Implementer executes scoped changes.
3. The Documenter updates relevant documentation.
4. The Auditor validates the result.
5. The human reviews and decides whether to commit manually.

## Governance Philosophy

AI agents may assist with execution, analysis, and documentation, but they do not own repository history, product direction, or final decisions. Commits and pushes remain human-controlled actions.

## Roadmap Synchronization

The roadmap is treated as a living governance artifact. Updates must reflect implemented repository reality only. Completed iterations should improve roadmap visibility, while speculative progress and fictional milestones are forbidden.

## Current Structure

```text
programming/
|-- README.md
|-- global/
|   |-- programming-principles.md
|   |-- context-management.md
|   `-- git-governance.md
|-- roles/
|   |-- implementer.md
|   |-- documenter.md
|   `-- auditor.md
|-- protocols/
|   |-- iteration-workflow.md
|   |-- audit-workflow.md
|   `-- documentation-sync-workflow.md
`-- templates/
    |-- iteration-template.md
    `-- audit-template.md
```

## Current Maturity Level

Initial operational methodology. The domain defines foundational roles, governance rules, workflows, and reusable templates. It does not yet define implementation-specific tooling, automation, or executable processes.
