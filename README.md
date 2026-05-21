# Agentic Methodology

Agentic Methodology is a human-centered framework for structuring collaboration between people and specialized AI agents through modular workflows, controlled iteration, and conscious operational governance.

The project focuses on practical methods for using AI systems as disciplined assistants within human-led work, where decisions, validation, and repository ownership remain under human authority.

## Philosophy

AI agents can amplify execution, analysis, and documentation when their responsibilities are explicit, their context is controlled, and their outputs are reviewed before they become persistent changes.

This methodology treats AI collaboration as an operational system: small scopes, specialized roles, traceable changes, synchronized documentation, and manual validation before commits or publication.

## Core Principles

- Human authority remains final over AI-generated work.
- AI agents assist specific responsibilities instead of owning the repository.
- Work is performed in small, reviewable iterations.
- Commits and pushes require manual human approval.
- Documentation evolves together with workflows and artifacts.
- Context is minimized to what each task requires.
- Changes should be traceable, reversible, and easy to validate.

See [PRINCIPLES.md](PRINCIPLES.md) for the foundational operational principles.

## Repository Structure

```text
agentic-methodology/
|-- README.md
|-- PRINCIPLES.md
|-- ROADMAP.md
|-- LICENSE
|-- programming/
|   |-- README.md
|   |-- global/
|   |-- roles/
|   |-- protocols/
|   `-- templates/
|-- data-analysis/
|   |-- README.md
|   |-- global/
|   |-- roles/
|   |-- protocols/
|   `-- templates/
|-- documentation/
|   |-- README.md
|   |-- global/
|   |-- roles/
|   |-- protocols/
|   `-- templates/
|-- examples/
`-- docs/
    `-- theory/
```

## Initial Workflow Overview

The initial workflow model is intentionally simple:

1. Define a small human-approved objective.
2. Assign limited responsibilities to specialized AI agents.
3. Minimize context to the files, documentation, and decisions required.
4. Produce a reviewable change or artifact.
5. Validate manually before persistence, commit, or publication.
6. Update documentation when the workflow or repository structure changes.

## Human Governance

This methodology assumes that AI systems do not own intent, accountability, or repository state. Human maintainers define direction, approve scope, review outputs, and decide when changes become persistent.

Controlled autonomy is allowed only inside explicit task boundaries. Agents may analyze, draft, refactor, or propose changes, but human validation remains required before commits, pushes, or operational decisions.

## Planned Domains

- Programming workflows
- Data analysis workflows
- Documentation and report generation workflows

## Project Status

This methodology is evolving. The current iteration establishes the foundational repository structure and documentation baseline without defining prompts, agent personalities, integrations, automation, or implementation-specific tooling.

## License

This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License. See [LICENSE](LICENSE) for details.

## Author

Created and maintained by Osmar Yesid Rincón Zorro (Ingeniero Yesid).
