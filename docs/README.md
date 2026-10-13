# OctoAcme Project Management Docs

This folder describes how OctoAcme runs cross-functional projects. Start here, then follow the links below for details.

OctoAcme projects are customer-first, delivered iteratively in small testable increments, and each has a named Project Manager (PM) and Product Lead. Work moves through five high-level stages: initiation (problem statement, stakeholders, one-pager, decision gate), planning (scope, resources, milestones, dependencies, backlog and sprint planning), execution (build, test, review, iterate), release (deploy, verify, announce), and a close-out retrospective that captures learnings and next steps.

Delivery is shared across a few key roles. The Project Manager coordinates schedules, risks and communications; the Product Manager defines outcomes and prioritizes the backlog; developers implement and design for testability; QA validates acceptance criteria; and stakeholders provide input and approvals. Persona details, responsibilities, and typical communication for each role are in the roles and personas doc.

Communication follows a regular cadence: a weekly PM + PdM sync, standups for the delivery team, and weekly or milestone-based stakeholder updates using a single source of truth. Risks are tracked in a risk register reviewed weekly, and blockers escalate in three levels: team triage in standup, PM to Product Lead and dependent teams, then sponsor-level for business-impacting issues. Quality is built in through unit, integration and end-to-end smoke tests, security scanning in CI, and manual QA when needed. Releases follow a deployment checklist (staging smoke tests, post-deploy verification, stakeholder announcement) with a rollback and incident playbook, and retrospectives turn lessons into tracked improvements.

## Documents

- [Project Management Overview](octoacme-project-management-overview.md) – principles, roles, artifacts, lifecycle
- [Project Initiation](octoacme-project-initiation.md) – one-pager, checklist, decision gate
- [Project Planning](octoacme-project-planning.md) – objectives, backlog items, sprint planning
- [Execution & Tracking](octoacme-execution-and-tracking.md) – team rhythm, workflows, quality, metrics, blocker escalation
- [Risks & Communication](octoacme-risks-and-communication.md) – risk register, stakeholder updates, escalation paths
- [Release & Deployment](octoacme-release-and-deployment.md) – release types, checklist, rollback, release notes
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) – running retros and tracking actions
- [Roles & Personas](octoacme-roles-and-personas.md) – developers, product managers, project managers
