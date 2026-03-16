# OctoAcme Project Management Docs

This README is the entry point for OctoAcme's project management process documentation. Use it to navigate the team's workflows, lifecycle stages, key artifacts, and roles.

## Overview

OctoAcme's project management approach follows a lightweight, repeatable lifecycle that emphasizes iterative delivery, clear ownership, and measurable outcomes. Work typically starts with **Initiation**, where a project idea is validated through a short one-pager (problem, SMART objective, success metrics), stakeholder identification, an initial risk/dependency scan, and a go/no-go decision to move into planning. Once approved, the team moves into **Planning**, turning the initiative into an actionable backlog by breaking work into shippable increments, defining acceptance criteria and a Definition of Done, estimating scope, mapping milestones and releases, and documenting early QA/test plans and cross-team dependencies.

Roles are defined to create clear accountability across delivery. A **Project Manager (PM)** coordinates schedules, delivery execution, risks, and communications; a **Product Manager (PdM)** owns outcomes, prioritization, and measuring success; **Developers** design and implement solutions with tests and documentation; **QA/Testing** validates quality and acceptance criteria; and **Stakeholders** provide input and approvals. Day-to-day execution is managed via a project board and a pull-request workflow that encourages small PRs, CI checks before review, and at least one approval before merge.

Communication is structured around a consistent cadence plus explicit escalation paths — short daily standups, a weekly delivery sync, and regular stakeholder updates. Risks are tracked in a **Risk Register** with impact/likelihood, owner, mitigation, and status. Quality assurance is treated as continuous: unit tests, integration tests, and end-to-end smoke tests are expected alongside CI automation (tests, linting, security scanning). Releases follow a checklist-driven process ending with post-deploy verification and stakeholder communications. Retrospectives occur after sprints, releases, milestones, and incidents, producing a small set of owned action items tracked back into the backlog.

## Key Artifacts

- **Project charter / one-pager** — problem statement, SMART objectives, success metrics, stakeholders
- **Roadmap / release plan** — milestones, release dates, scope per increment
- **Backlog** — prioritized list of work items with acceptance criteria and Definition of Done
- **Risk Register** — impact/likelihood ratings, owners, mitigations, and statuses
- **Retrospective action items** — learnings and improvements tracked back into the backlog

## Process Documents

| Document | Description |
|---|---|
| [Project Management Overview](./octoacme-project-management-overview.md) | High-level lifecycle, principles, and phases |
| [Project Initiation](./octoacme-project-initiation.md) | One-pager template, stakeholder identification, go/no-go |
| [Project Planning](./octoacme-project-planning.md) | Backlog breakdown, estimation, milestones, QA planning |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Project board, PR workflow, standups, delivery syncs |
| [Risks & Communication](./octoacme-risks-and-communication.md) | Risk Register, escalation paths, status reporting |
| [Release & Deployment](./octoacme-release-and-deployment.md) | Release types, checklists, rollback playbooks |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Retro format, action-item tracking, improvement cadence |
| [Roles & Personas](./octoacme-roles-and-personas.md) | PM, PdM, Developer, QA, Stakeholder responsibilities |
