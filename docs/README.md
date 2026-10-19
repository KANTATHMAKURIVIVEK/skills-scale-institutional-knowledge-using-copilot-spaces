# OctoAcme Project Management Docs

This folder contains OctoAcme's project management process documents and provides a concise orientation for new team members.

OctoAcme runs projects through an initiation → planning → execution → release → retrospective lifecycle. Initiation captures the problem, stakeholders, measurable outcomes, and a go/no‑go on a Project One‑pager. Planning turns approved work into a prioritized backlog, estimates, and a release plan with a clear Definition of Done and risk tracking. Execution uses a visible project board and a disciplined pull request workflow (small PRs, CI/lint gating, acceptance criteria) while tracking velocity and blockers. Releases follow pre‑release checks, staged deploys, smoke tests, and a rollback playbook. Retrospectives capture learnings and convert them into backlog action items that are measured and tracked.

Roles and responsibilities are defined so ownership is explicit: Product Managers (define outcomes and success metrics), Project Managers (coordinate schedules, risks, and communications), Developers (implement and test), and QA (validate acceptance). Templates and artifacts (Project One‑pager, backlog item template, risk register, release notes) are used as single sources of truth to make decisions traceable and reduce single‑person dependencies.

Communication follows a predictable cadence: short daily standups for blockers, weekly delivery syncs and PM+PdM alignment, milestone demos, and periodic stakeholder updates. Risk and incident communication use a maintained Risk Register and templates for status and incident updates; escalation paths are documented. Quality is enforced through unit/integration tests, CI and security scanning, smoke tests for critical flows, and manual QA where needed.

Links to the full documents in this folder:
- docs/octoacme-project-management-overview.md
- docs/octoacme-project-initiation.md
- docs/octoacme-project-planning.md
- docs/octoacme-execution-and-tracking.md
- docs/octoacme-release-and-deployment.md
- docs/octoacme-retrospective-and-continuous-improvement.md
- docs/octoacme-risks-and-communication.md
- docs/octoacme-roles-and-personas.md
