# OctoAcme Project Management Docs

This folder contains OctoAcme's program and project management process documents. The README below links to each file and provides a short summary of the processes so team members can quickly find the guidance they need.

## Project management processes (brief overview)

OctoAcme follows a pragmatic, outcome-oriented lifecycle: Initiation, Planning, Execution, Release, and Close/Retrospective. New work starts with a lightweight Project One-pager to validate the problem, define SMART objectives and success metrics, and align stakeholders before moving into planning. Planning creates a prioritized backlog with clear acceptance criteria, estimates, and a Definition of Done so work is broken into shippable increments.

Day-to-day execution is managed via a project board (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined pull request workflow (small PRs, include issue link and acceptance criteria, passing CI, and required approvals). Teams operate a regular cadence of daily standups, weekly delivery syncs, and end-of-sprint demos or reviews. Releases use checklist-driven pipelines with staging smoke tests, post-deploy verifications, and rollback/playbooks for incidents.

Roles are explicitly defined: Product Managers (define outcomes and prioritize), Project Managers (coordinate delivery and communications), Developers (implement, test, and document), QA (validate acceptance), and Stakeholders (approve and provide input). Communication combines short tactical syncs with scheduled stakeholder updates and clear escalation paths for blockers.

Quality and risk management are embedded in the process: unit and integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA where needed. A simple Risk Register tracks ID, impact, likelihood, owner, mitigation, and status; risks are reviewed weekly and escalated as needed. Retrospectives convert learnings into prioritized action items tracked in the backlog to support continuous improvement.

## Links to process documents

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risks & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)

## How to use these docs

- Keep the Project One-pager and project README updated in the project repo.
- Use the issue template 'Add Content to Project Management Process Docs' to propose changes or new documents.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
