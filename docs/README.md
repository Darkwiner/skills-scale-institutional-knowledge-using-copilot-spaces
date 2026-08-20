# OctoAcme Project Management Process Documentation

Welcome to the OctoAcme project management knowledge base. This directory contains comprehensive guidance on how OctoAcme runs projects, from initiation through retrospective. Use these docs as the single source of truth for project charters, planning, execution, releases, and continuous improvement.

## Brief Overview
OctoAcme follows a structured yet flexible project management lifecycle: Initiation (validate and authorize work), Planning (break approved initiatives into an actionable backlog), Execution (iterative delivery with clear team rhythm), Release (standardized deployment and rollback procedures), and Close/Retrospective (capture learnings and convert them into improvements). Our approach is guided by five core principles: customer-first, iterative delivery, clear ownership, data-informed decisions, and psychological safety.

## Process Documentation (organized)
- Foundational
  - [Project Management Overview](octoacme-project-management-overview.md) — Start here for a concise intro to OctoAcme’s approach, roles, and artifacts.
  - [Roles & Personas](octoacme-roles-and-personas.md) — Responsibilities and communication patterns for Developers, Product Managers, and Project Managers.

- Lifecycle Processes
  - [Project Initiation](octoacme-project-initiation.md) — Steps to validate ideas, create a one-pager, and decide go/no-go for planning.
  - [Project Planning](octoacme-project-planning.md) — Turn initiatives into backlog, estimates, Definition of Done, and release planning.
  - [Execution & Tracking](octoacme-execution-and-tracking.md) — Day-to-day delivery practices: boards, PR workflow, team rhythm, quality gates, and blocker escalation.
  - [Release & Deployment](octoacme-release-and-deployment.md) — Pre-release checks, deployment checklist, rollback, and post-deploy verification.
  - [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Run timeboxed retrospectives and track action items.

- Cross-cutting
  - [Risk Management & Communication](octoacme-risks-and-communication.md) — Risk register, stakeholder comms, templates, and escalation paths.

## Quick Reference
| I want to... | Read this... |
|---|---|
| Understand how OctoAcme runs projects | [Project Management Overview](octoacme-project-management-overview.md) |
| Start a new project | [Project Initiation](octoacme-project-initiation.md) |
| Break down work and plan | [Project Planning](octoacme-project-planning.md) |
| Manage daily delivery | [Execution & Tracking](octoacme-execution-and-tracking.md) |
| Release to production | [Release & Deployment](octoacme-release-and-deployment.md) |
| Run a retrospective | [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) |
| Identify and manage risks | [Risk Management & Communication](octoacme-risks-and-communication.md) |
| Understand roles & responsibilities | [Roles & Personas](octoacme-roles-and-personas.md) |

## Brief summary of OctoAcme project management processes
OctoAcme uses a lightweight, stage-gated lifecycle to move initiatives from idea to impact. Initiation focuses on a one-pager to confirm the problem, stakeholders, and measurable success criteria; planning breaks approved initiatives into prioritized backlogs, defines the Definition of Done, and identifies risks and dependencies; execution involves iterative delivery against milestones with a predictable team rhythm; release standardizes pre-release checks, automated deployments, and rollback plans; closing activities capture learnings in retrospectives and convert them into backlog action items.

Work is organized on a project board with columns (Backlog → Ready → In Progress → In Review → QA → Done) and a PR workflow that emphasizes small, well-described PRs, CI checks before review, and explicit acceptance criteria. Quality assurance is layered: unit and integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA where needed; deployments include smoke tests and post-deploy verifications.

Roles are explicit: Product Managers define outcomes and success metrics, Project Managers coordinate delivery and communications, Developers implement and test, QA validates acceptance, and Stakeholders provide input and approvals. Communication cadence includes daily standups, weekly delivery syncs, PM–PdM alignment, and monthly stakeholder updates; escalation paths and incident communication templates are defined to ensure timely responses and blameless post-incident learning.

## How to use these docs in Copilot Spaces
- Keep the Project Charter updated in your project repo.
- Add process-specific docs to `.copilot/` if you want Copilot Spaces to use them as context.
- Reference these docs when creating charters, kickoff materials, and onboarding.
- Use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to propose updates.

## Acceptance Criteria
- [x] Content aligns with existing process docs
- [x] Update improves clarity or closes a documented gap
- [ ] Proposed content has been reviewed with stakeholders (if needed)
