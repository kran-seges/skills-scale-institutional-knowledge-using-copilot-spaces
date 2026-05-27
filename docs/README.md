# OctoAcme Project Management Docs

Welcome! This README provides a quick introduction to how OctoAcme manages projects and links to all detailed process documentation. It serves as the navigational entry point for contributors and stakeholders who are new to the project.

## Summary of Project Management Processes

OctoAcme uses a lightweight but structured project management lifecycle that moves from initiation to planning, execution, release, and retrospective. Projects begin with a short initiation phase focused on validating the business need, defining measurable outcomes, identifying stakeholders, and deciding whether work should proceed into planning. Once approved, the team creates a practical delivery plan that breaks work into shippable increments, prioritizes a backlog, estimates effort, maps milestones, and records dependencies and risks. Across the documentation, the emphasis is on iterative delivery, clear ownership, and using simple artifacts like a one-pager, backlog, release plan, risk register, and retrospective notes to keep projects aligned and traceable.

The process is built around a few clearly defined personas. Project Managers coordinate delivery, schedules, risks, resources, and communication, while Product Managers define the problem, success metrics, roadmap priorities, and trade-offs. Developers are responsible not just for implementation, but also for testing, documentation, estimation, and surfacing technical risks. QA and testing functions are explicitly included in the overall operating model as validators of acceptance criteria and product quality. This suggests OctoAcme treats delivery as a cross-functional effort, with named ownership for both execution and product outcomes rather than relying on informal collaboration alone.

Communication is handled through a regular cadence and a clear escalation model. The docs describe weekly PM–product alignment, daily or twice-weekly team standups, weekly delivery syncs, sprint-end demos, and monthly or milestone-based stakeholder updates. OctoAcme also favors a single source of truth for status, such as a project README or release document, and uses lightweight templates for weekly status updates and incident communication. When blockers emerge, they are escalated in stages from team triage to the Project Manager, then to the Product Lead, and finally to a sponsor if the issue has significant business impact. That structure helps preserve transparency while keeping most issues resolved at the lowest practical level.

Quality assurance is embedded throughout execution and release rather than treated as a final gate. Planning includes documenting acceptance criteria, a Definition of Done, and an initial QA approach. During execution, teams are expected to use small pull requests, link work to issues and acceptance criteria, and pass automated tests, linting, and security scans in CI before review and merge. Testing expectations include unit tests for new logic, integration tests where relevant, end-to-end smoke tests for critical flows, and manual QA for feature acceptance when needed. Releases require passing CI, documented rollback plans, staged deployment checks, and post-deploy verification, while retrospectives after sprints, releases, or incidents ensure that lessons learned become actionable improvements with owners and due dates.

## Docs Index

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
