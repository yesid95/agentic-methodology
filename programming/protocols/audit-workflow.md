# Audit Workflow

The audit workflow validates that a programming iteration is coherent, scoped, and ready for human review.

## Audit Scope

An audit should cover files changed, related documentation, relevant roadmap state, and any validation evidence produced during the iteration.

## Validation Sequence

1. Confirm the iteration objective and constraints.
2. Inspect repository status and changed files.
3. Review implementation coherence and scope alignment.
4. Review documentation updates for accuracy.
5. Check roadmap synchronization when repository evolution changed.
6. Identify risks, inconsistencies, or missing validation.
7. Produce an audit report for human review.

## Consistency Checks

- Changes match the approved objective.
- Responsibilities between roles remain separated.
- No unsupported features or workflows were invented.
- No unrelated domains were modified.
- Git governance rules were followed.

## Documentation Coherence Checks

- Documentation reflects implemented reality.
- Roadmap status does not claim speculative progress.
- Terminology is consistent across affected files.
- Diagrams, if present, match the documented structure.

## Implementation Coherence Checks

- Changes are modular and maintainable.
- Scope growth is justified and approved.
- Validation evidence is adequate for the iteration.
- The result is traceable and reversible.

## Reporting Structure

Audit reports should include:

- iteration reviewed;
- files analyzed;
- validation results;
- inconsistencies detected;
- recommendations;
- final audit status.
