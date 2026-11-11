# OctoAcme Project Management Docs

This directory contains OctoAcme’s project management guidance across the project lifecycle. Use this page as a starting point to understand the process and find detailed guidance for each stage.

## Process overview

OctoAcme’s project lifecycle begins with **initiation**, where the team validates the business need, identifies stakeholders, defines measurable outcomes, and makes a go/no-go decision for planning. During **planning**, the team turns approved work into a prioritized and estimated backlog, clarifies acceptance criteria and the Definition of Done, assigns ownership, and maps dependencies, risks, and milestones. In **execution**, teams deliver in small increments, track work on a project board, and use pull requests to review changes while keeping progress and blockers visible. **Release and deployment** include readiness checks, smoke tests, stakeholder updates, and rollback planning. After a sprint, release, milestone, or incident, teams **reflect and improve** by capturing lessons and tracking owned action items.

## Process documents

- [Project Management Overview](octoacme-project-management-overview.md) — OctoAcme’s principles, roles, lifecycle, key artifacts, and communication cadence.
- [Project Initiation](octoacme-project-initiation.md) — validating an idea, aligning stakeholders, preparing a one-pager, and deciding whether to proceed to planning.
- [Project Planning](octoacme-project-planning.md) — creating a prioritized backlog, estimating work, defining the Definition of Done, and planning milestones and dependencies.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — day-to-day delivery, project board and PR workflow, quality checks, progress reporting, and blocker escalation.
- [Risk Management & Communication](octoacme-risks-and-communication.md) — maintaining the risk register, managing dependencies, providing stakeholder updates, and escalating issues.
- [Release & Deployment](octoacme-release-and-deployment.md) — release readiness, deployment checks, verification, release notes, and rollback guidance.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — running retrospectives and tracking improvement actions.
- [Roles and Personas](octoacme-roles-and-personas.md) — responsibilities and communication patterns for developers, product managers, and project managers.

## Roles and communication

The Project Manager coordinates delivery, schedules, risks, dependencies, and communications. The Product Manager or Product Lead defines outcomes, prioritizes work, and measures success. Developers implement and test changes, QA validates quality and acceptance criteria, and stakeholders provide input and approvals. Regular standups, delivery syncs, demos, and stakeholder updates help teams share progress and surface decisions, risks, and blockers early. Risks and dependencies are tracked with owners and mitigation plans, reviewed regularly, and escalated through the agreed path when needed.

## Quality assurance

Quality is integrated throughout delivery: new logic should have unit tests, integration tests where applicable, and end-to-end smoke tests for critical flows. CI should run automated tests and linting, and security scanning is part of the process. Pull requests should be small where possible, link to an issue and acceptance criteria, and receive at least one approval or follow the team’s agreed review policy. Before production release, confirm acceptance criteria and checks have passed, prepare release notes and smoke tests, and document a rollback or mitigation plan. Verify the deployment afterward and capture follow-up learnings in retrospectives.
