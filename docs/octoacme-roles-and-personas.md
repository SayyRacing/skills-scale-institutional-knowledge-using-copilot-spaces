# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Scrum Master / Agile Facilitator

### Role Summary
Scrum Masters and Agile Facilitators help teams use an effective delivery cadence. They facilitate planning, standups, reviews, and retrospectives while helping the team remove impediments and improve its flow.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Track impediments, dependencies, and actions through resolution
- Help the team maintain working agreements, a healthy backlog, and visible work
- Surface delivery risks and capacity concerns early
- Guide retrospective improvements into subsequent planning and execution

### Goals
- Keep delivery predictable and focused
- Remove blockers quickly and encourage team ownership
- Build a sustainable rhythm of continuous improvement

### Typical Communication
- Daily standup facilitation and blocker updates
- Sprint planning and review coordination
- Retrospective notes, action items, and follow-ups

### Interactions with existing roles
- **Developers**: protects focus, removes impediments, and supports estimation and flow
- **Product Managers**: helps prepare prioritized work and validates that outcomes are reviewed
- **Project Managers**: aligns agile ceremonies and delivery metrics with the project plan, risks, and dependencies

---

## QA / Testing Lead

### Role Summary
QA and Testing Leads define how quality is evaluated throughout delivery. They coordinate test strategy, acceptance validation, and quality gates so that risks are identified before release.

### Responsibilities
- Define test strategy, coverage expectations, and entry and exit criteria
- Review acceptance criteria for testability and coordinate acceptance validation
- Coordinate exploratory, automated, regression, and integration testing
- Track defects, quality risks, and release-blocking findings
- Contribute quality evidence to planning, release readiness, and retrospectives

### Goals
- Detect defects early and protect customer outcomes
- Make quality status and residual risk visible
- Improve automation, testability, and prevention of recurring issues

### Typical Communication
- Test plans, test results, and defect triage
- Acceptance reviews with product and delivery teams
- Quality gate and release-readiness updates

### Interactions with existing roles
- **Developers**: collaborates on testability, automated coverage, defect reproduction, and fixes
- **Product Managers**: translates acceptance criteria into validation scenarios and communicates customer-impacting risk
- **Project Managers**: reports quality status, blockers, and schedule impact for tracking and escalation

---

## UX / Product Designer

### Role Summary
UX and Product Designers shape usable, accessible solutions from customer needs and research. They turn product problems into designs that the delivery team can validate and build.

### Responsibilities
- Conduct or synthesize user research and usability feedback
- Create user flows, wireframes, prototypes, and interaction specifications
- Define usability and accessibility considerations with acceptance criteria
- Validate designs with users and incorporate findings into backlog refinement
- Identify design risks, dependencies, and open decisions during planning and execution

### Goals
- Make products useful, usable, and accessible
- Reduce rework by validating problems and solutions early
- Connect customer evidence to measurable product outcomes

### Typical Communication
- Research readouts, journey maps, and design reviews
- Prototypes and handoff notes for implementation
- Usability findings and decisions in product and planning meetings

### Interactions with existing roles
- **Developers**: explains design intent, explores feasible implementations, and reviews accessible UI behavior
- **Product Managers**: partners on problem definition, research priorities, and outcome-focused scope
- **Project Managers**: communicates design dependencies, review dates, and risks affecting the delivery plan

---

## Release Manager

### Role Summary
Release Managers coordinate how changes move from development to production. They own release readiness, deployment checklists, and rollback planning so releases are predictable and low-risk.

### Responsibilities
- Maintain the release calendar, scope, and deployment checklist
- Confirm pre-release requirements are met, including passing CI, security checks, acceptance validation, and release notes
- Coordinate staging validation and production deployment with Developers and QA
- Confirm rollback, mitigation, monitoring, and incident-response readiness
- Announce releases and communicate deployment status, outcomes, or follow-up actions

### Goals
- Deliver predictable, low-risk releases
- Minimize production incidents and time to recovery
- Keep release documentation and deployment practices repeatable

### Typical Communication
- Release readiness reviews and go/no-go decisions
- Staging and production deployment status updates
- Release announcements, post-release summaries, and rollback notifications

### Interactions with existing roles
- **Developers**: coordinates merge cutoffs, CI checks, smoke tests, deployment execution, and hotfixes
- **Product Managers**: confirms release scope, acceptance status, and customer-facing messaging
- **Project Managers**: aligns release milestones with the project timeline and escalates schedule or readiness risk

---

## Business Analyst

### Role Summary
Business Analysts clarify business needs and translate them into actionable requirements. They make process flows, rules, edge cases, and acceptance expectations explicit for the delivery team.

### Responsibilities
- Elicit and document requirements, workflows, business rules, and edge cases
- Refine backlog items and clarify scope, assumptions, and dependencies
- Draft or improve acceptance criteria and examples
- Validate that delivered behavior supports the intended business process
- Record decisions, open questions, and requirement risks for planning and tracking

### Goals
- Reduce ambiguity and requirements-related rework
- Preserve traceability from business need through acceptance
- Help teams make timely, informed scope decisions

### Typical Communication
- Requirements workshops and process-flow reviews
- Backlog refinement and acceptance-criteria discussions
- Decision logs, issue clarifications, and stakeholder summaries

### Interactions with existing roles
- **Developers**: clarifies rules, edge cases, examples, and implementation questions
- **Product Managers**: turns product outcomes into refined requirements and highlights trade-offs
- **Project Managers**: reports requirement dependencies and decisions that affect scope, schedule, or risk

---

## Customer Success / Support Lead

### Role Summary
Customer Success and Support Leads represent customer needs during delivery and after release. They organize feedback, support readiness, and incident learnings so customer impact informs priorities and risks.

### Responsibilities
- Gather support trends, customer feedback, and recurring pain points
- Prepare support documentation, training, and launch readiness materials
- Coordinate customer-impact communication for releases, incidents, and mitigations
- Triage escalations and feed production issues into the project and product backlogs
- Share post-release adoption and support outcomes for retrospective improvement

### Goals
- Help customers adopt changes successfully
- Reduce avoidable support volume and time to resolution
- Ensure customer impact is visible in prioritization and risk decisions

### Typical Communication
- Support-readiness reviews and release announcements
- Escalation summaries, incident updates, and customer communications
- Feedback and adoption reports to product and delivery teams

### Interactions with existing roles
- **Developers**: provides reproducible customer issues and validates fixes or mitigations
- **Product Managers**: shares feedback, trends, adoption signals, and opportunities for prioritization
- **Project Managers**: reports customer-impacting risks, readiness tasks, and escalations for tracking

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide strategic direction, funding, approvals, and context for major decisions. They help confirm that project outcomes remain aligned with organizational and customer priorities.

### Responsibilities
- Set strategic context, success expectations, and decision principles
- Provide or secure funding, resources, and timely approvals
- Review milestones, scope changes, risks, and delivery outcomes
- Resolve escalations that require authority beyond the delivery team
- Participate in release, outcome, and retrospective reviews when decisions or investment are needed

### Goals
- Ensure investment produces meaningful business and customer value
- Make timely decisions on scope, priority, risk, and trade-offs
- Maintain alignment and confidence across affected groups

### Typical Communication
- Milestone reviews, steering updates, and decision requests
- Scope, risk, and escalation briefings
- Outcome summaries and release or retrospective readouts

### Interactions with existing roles
- **Developers**: provides context for high-impact trade-offs without directing implementation details
- **Product Managers**: aligns vision, priorities, funding, and success measures
- **Project Managers**: receives status and risk reporting, approves decisions, and helps resolve escalations

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
