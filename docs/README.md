# OctoAcme Project Management Docs

Welcome! This README provides a comprehensive overview of OctoAcme's project management processes and serves as the central entry point for all project management documentation.

## Project Management Process Overview

OctoAcme follows a structured five-phase project lifecycle: **Initiation, Planning, Execution, Release, and Close & Retrospective**. During initiation, teams validate business needs and create a lightweight Project One-pager that defines the problem statement, objectives, success metrics, stakeholders, and initial risks. Once stakeholders align and the go/no-go decision is made, the project moves into planning, where the team breaks work into shippable increments, creates a prioritized backlog with clear acceptance criteria, and establishes a Definition of Done. Throughout execution, the team follows an iterative delivery model with daily standups (15 minutes focused on progress and blockers), twice-weekly delivery syncs, and weekly PM-PdM alignment meetings. Work is tracked on a project board with columns for Backlog, Ready, In Progress, In Review, QA, and Done, with pull requests kept small (≤400 lines when possible) and requiring at least one approval before merging.

OctoAcme emphasizes **clear ownership** through defined personas: **Project Managers** coordinate delivery, schedules, risks, and communications; **Product Managers** define outcomes, prioritize the backlog, and measure success; **Developers** implement features and collaborate on design and testability; and **QA/Testing** validates quality against acceptance criteria. This structure ensures each person understands their role and how it contributes to the overall project. Communication follows a consistent cadence with weekly syncs between PM and PdM, twice-weekly team standups, monthly stakeholder updates, and ad-hoc escalations when needed. A three-level escalation path—from team-level triage in standups to PM-to-Product Lead escalation to sponsor-level involvement—ensures blockers are resolved quickly without creating bottlenecks.

Quality is embedded throughout the delivery process rather than deferred to the end. Teams write unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows before release. CI pipelines run automated tests and linting, security scans are performed, and manual QA validates feature acceptance when needed. Risk management is continuous: teams maintain a Risk Register during planning and update it weekly during syncs, capturing ID, description, impact, likelihood, owner, and mitigation plan for each risk. Dependencies and cross-team risks are marked on the project board and escalated during weekly meetings. Before any release, teams verify that all acceptance criteria are met, PRs are merged, CI passes, release notes are drafted, and rollback/mitigation plans are documented. This comprehensive approach—combining iterative delivery, rigorous testing, proactive risk tracking, and stakeholder transparency—enables OctoAcme to deliver reliable increments while maintaining psychological safety and continuous improvement through post-sprint and post-incident retrospectives.

## Key Practices

- **Lightweight, shareable docs** for all projects
- **Backlogs and milestones** managed in GitHub
- **Iterative progress** via sprints and standups
- **Standard checklists** for initiation, planning, execution, release, and retrospectives
- **Escalation paths** and risk management processes
- **Clear roles and responsibilities** with defined personas

## Documentation Links

### Core Guides
- **[Project Management Overview](octoacme-project-management-overview.md)** — Introduction to OctoAcme's approach, principles, core roles, and lifecycle
- **[Roles and Personas](octoacme-roles-and-personas.md)** — Detailed descriptions of Project Managers, Product Managers, Developers, and QA/Testing roles

### Project Execution
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Steps to validate and authorize work, align stakeholders, and create a Project One-pager
- **[Project Planning](octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and backlog
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day execution, team rhythms, workflows, and progress tracking

### Risk, Communication & Release
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks; stakeholder communication strategies
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardized release process, deployment checklist, and rollback procedures
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements

## How to Use These Docs

- **New team members**: Start with [Project Management Overview](octoacme-project-management-overview.md) and your specific [Roles and Personas](octoacme-roles-and-personas.md) guide.
- **Starting a new project**: Follow the [Project Initiation Guide](octoacme-project-initiation.md) and [Project Planning](octoacme-project-planning.md).
- **Day-to-day work**: Reference [Execution & Tracking](octoacme-execution-and-tracking.md) and the team rhythm section.
- **Managing risks**: Use [Risk Management & Communication](octoacme-risks-and-communication.md) for risk registers and escalation paths.
- **Releasing features**: Follow the [Release & Deployment Guide](octoacme-release-and-deployment.md).
- **Improving processes**: Conduct retrospectives using [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md).

## Copilot Spaces Integration

These docs are part of a Copilot Spaces knowledge base to centralize project management knowledge and give all team members equal access to processes, decisions, and rationale. Keep these documents updated as processes evolve, and reference them when establishing new project structures or onboarding team members.
