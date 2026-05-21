# Documentation Synchronization Workflow

Documentation synchronization keeps repository knowledge aligned with implemented reality.

## When Documentation Must Be Updated

Documentation should be updated when an iteration changes:

- repository structure;
- programming workflows;
- role responsibilities;
- operational governance;
- validation expectations;
- roadmap visibility;
- diagrams or documented architecture.

## Synchronization Rules

- Documentation must describe actual repository state.
- Updates should be made in the same iteration when practical.
- Documentation gaps should be recorded when they cannot be resolved immediately.
- Terminology should remain consistent across domain files.
- Documentation should not create unsupported obligations or fictional capabilities.

## Roadmap Update Logic

The roadmap must be continuously synchronized with repository evolution. Updates must reflect implemented reality only.

Roadmap updates are appropriate when:

- an iteration completes a planned artifact;
- the repository structure changes;
- a phase becomes partially or fully complete;
- the methodology matures enough to adjust phase descriptions.

Roadmap updates are not appropriate when:

- work is only imagined or discussed;
- milestones are speculative;
- progress cannot be verified in the repository;
- future integrations or workflows are not implemented.

## Architecture Documentation Rules

Architecture documentation should describe actual structure, responsibilities, and decision boundaries. It should avoid premature design commitments and implementation-specific assumptions.

## Diagram Synchronization Philosophy

Diagrams are documentation artifacts. When diagrams exist, they must be updated when the structure or workflow they represent changes. Diagrams should not imply capabilities that are not documented or implemented.

## Repository Evolution Tracking

Completed iterations should improve visibility into how the repository is evolving. The roadmap, domain README files, and relevant protocols should remain aligned so future contributors can understand current maturity without reconstructing history from diffs alone.
