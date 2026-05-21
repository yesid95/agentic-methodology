# Programming Principles

These principles guide programming work performed with specialized AI assistance.

## Modular Iteration

Programming work should be divided into small iterations with a clear objective, limited scope, and reviewable outputs. Each iteration should be understandable without requiring a full-project rewrite or broad architectural speculation.

## Maintainability

Changes should preserve readability, local consistency, and long-term maintainability. New abstractions should be introduced only when they reduce real complexity or match established repository patterns.

## Separation of Responsibilities

Implementation, documentation, and auditing are distinct responsibilities. A role may support another role with context, but it should not silently assume responsibilities outside its boundary.

## Incremental Development

Prefer incremental changes that can be validated independently. Avoid expanding scope during execution unless a human explicitly approves the change in direction.

## Validation First

Every iteration should define how success will be checked before work begins. Validation may include tests, manual review, documentation checks, or architectural review depending on the iteration.

## Documentation Synchronization

Documentation must remain aligned with implemented reality. When code, structure, or workflow behavior changes, related documentation should be updated in the same iteration or explicitly tracked for follow-up.

## Reversibility and Traceability

Changes should be traceable through clear file impact, concise rationale, and small diffs. Work should be easy to revert if validation fails.

## Controlled Scope Growth

Scope may grow only when the need is discovered, explained, and approved. Avoid using implementation work as an opportunity to introduce unrelated features, patterns, or strategic direction.
