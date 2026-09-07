# OctoAcme Project Management Docs

This README is an index for OctoAcme's project management process documents and provides a concise summary of how we run projects. It centralizes links and short descriptions to help contributors and stakeholders find the right guidance quickly.

## Brief summary of OctoAcme project management processes

OctoAcme follows a lightweight, documentation-driven lifecycle that moves work from initiation through planning, execution, release, and retrospective. Initiation begins with a Project One-pager that captures the problem, goals, success metrics, stakeholders, and an initial timeline; that artifact is the basis for deciding whether to proceed to planning. Planning turns approved initiatives into a prioritized backlog with acceptance criteria, estimates, a Definition of Done, and a release/milestone map to guide delivery.

Execution emphasizes small, iterative increments and clear handoffs: use a project board (Backlog → Ready → In Progress → In Review → QA → Done), keep pull requests small and linked to issues with acceptance criteria, and require automated CI (linting, tests, security scans) before requesting review. Risk and dependency management are explicit — maintain a simple Risk Register and review it in regular syncs — with an established escalation path from team triage up to sponsor-level for business-impacting issues.

Roles and communication are clear and structured. Core personas include Project Manager (coordinates delivery, schedule, risks, communications), Product Manager (defines outcomes and prioritizes the backlog), Developers (implement and test), QA/Testing (validate acceptance), and Stakeholders (inputs and approvals). The team cadence uses daily standups for progress and blockers, a weekly delivery sync, demos at the end of sprints or milestones, and periodic stakeholder updates; the docs also provide templates for status and incident communications.

Quality assurance is integrated across the pipeline and release process. Developers are expected to include unit and integration tests, while critical flows have end-to-end smoke tests. CI gates automated tests, linters, and security scans before merging; manual QA is used where appropriate. Release checklists require staging smoke tests and post-deploy verifications, and retrospectives capture action items that are turned into backlog issues to drive continuous improvement.

## Links to process documents

- [Project management overview](docs/octoacme-project-management-overview.md)
- [Project initiation](docs/octoacme-project-initiation.md)
- [Project planning](docs/octoacme-project-planning.md)
- [Execution and tracking](docs/octoacme-execution-and-tracking.md)
- [Risks and communication](docs/octoacme-risks-and-communication.md)
- [Release and deployment](docs/octoacme-release-and-deployment.md)
- [Retrospective and continuous improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles and personas](docs/octoacme-roles-and-personas.md)

## How to contribute

If you add or update process docs under docs/, please update this README with a link and a short summary so the index stays current. Use the existing issue template (.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose additions or changes.
