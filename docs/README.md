# OctoAcme Project Management Docs

This README is the entry point for OctoAcme's project management process documentation. It provides a summary of how OctoAcme plans, executes, and continuously improves its projects, along with links to the detailed process docs in this folder.

## Project Management Processes Summary

OctoAcme follows a structured, iterative project lifecycle spanning five phases: Initiation, Planning, Execution, Release, and Close & Retrospective. Work begins with a Project One-pager that defines the problem statement, goals, success metrics, stakeholders, and initial risks — moving forward only after a go/no-go decision gate confirms stakeholder alignment and team availability. During planning, approved initiatives are broken into shippable increments via a prioritized backlog with clear acceptance criteria, estimates, and a documented Definition of Done, along with a release plan. Execution is tracked on a project board (Backlog → Ready → In Progress → In Review → QA → Done), with a pull request workflow that favors small PRs (≤400 lines) and requires at least one approval before merging. Releases are categorized as patch, minor, or major, and are deployed to staging with smoke tests and a documented rollback plan before reaching production, followed by a Close & Retrospective phase.

Clear ownership is central to OctoAcme's approach, with well-defined personas guiding every project. The Project Manager coordinates delivery, schedules, risks, and communications. The Product Manager owns the product vision, prioritizes the backlog, and measures outcomes. Developers implement features, tests, and docs, while QA/Testing validates quality and acceptance criteria. Stakeholders provide inputs and approvals throughout. This structure reflects OctoAcme's core principles: customer-first thinking, iterative delivery, clear ownership, data-informed decisions, and psychological safety.

Communication operates on a deliberate cadence designed to maintain transparency and catch issues early. The team rhythm includes daily 15-minute standups, weekly delivery syncs, weekly PM + PdM alignment meetings, monthly stakeholder updates, and demos at the end of each sprint or milestone. Risks are tracked in a Risk Register and escalated through a defined path: team-level triage → PM escalation to Product Lead → sponsor-level escalation. Standardized templates for weekly status updates, incident communications, and release notes ensure a single source of truth for project status.

Quality assurance is embedded throughout the delivery pipeline rather than treated as a final gate. OctoAcme requires unit tests for new logic, integration tests, and end-to-end smoke tests for critical flows before release, supplemented by security scanning in CI and manual QA for feature acceptance when needed. Retrospectives are held after each sprint, release, or incident, producing 2-3 prioritized action items that are tracked in the backlog, ensuring learnings are converted into continuous process improvement.

## Docs

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
