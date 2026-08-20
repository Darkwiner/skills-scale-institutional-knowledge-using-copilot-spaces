# OctoAcme Project Management Process Documentation

Welcome to the OctoAcme project management knowledge base. This directory contains concise, actionable guidance on how OctoAcme runs projects — from initiation through retrospective — and links to the full process documents.

## Brief overview
OctoAcme follows a lightweight, outcome-driven lifecycle: Initiation (validate and align), Planning (break work into shippable increments and identify risks), Execution (deliver and verify), Release (deploy and observe), and Retrospective (capture learnings and improve). The approach emphasizes five core principles: customer-first, iterative delivery, clear ownership, data-informed decisions, and psychological safety. Teams use a project board and a CI-first PR workflow with small, reviewable changes to reduce risk and speed feedback loops.

Day-to-day delivery is coordinated through a regular rhythm (daily standups, weekly delivery syncs, demos), and roles are clearly defined so responsibilities and handoffs are explicit. Quality is enforced through layered testing (unit, integration, smoke/end-to-end), CI security scanning, and manual QA where needed. Risks and dependencies are tracked in a simple register and escalated through defined paths to keep stakeholders informed.

## Process documentation (organized links)
Foundational
- [Project Management Overview](octoacme-project-management-overview.md) — Start here for a concise introduction to OctoAcme's approach, roles, and artifacts.
- [Roles & Personas](octoacme-roles-and-personas.md) — Responsibilities and communication patterns for Developers, Product Managers, and Project Managers.

Lifecycle processes
- [Project Initiation](octoacme-project-initiation.md) — Steps to validate ideas, align stakeholders, and build a lightweight plan (one-pager).
- [Project Planning](octoacme-project-planning.md) — Turning approved initiatives into prioritized backlogs, estimates, and release plans.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Team rhythm, PR workflow, CI requirements, and blocker escalation.
- [Release & Deployment](octoacme-release-and-deployment.md) — Pre-release requirements, deployment checklist, rollback playbook, and release notes template.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Running retros, tracking action items, and measuring improvement.

Cross-cutting
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Maintaining the risk register, stakeholder updates, and escalation paths.

## Quick reference
| I want to... | Read this... |
|---|---|
| Understand how OctoAcme runs projects | [Project Management Overview](octoacme-project-management-overview.md) |
| Start a new project | [Project Initiation](octoacme-project-initiation.md) |
| Break down work and plan a release | [Project Planning](octoacme-project-planning.md) |
| Manage daily delivery and QA | [Execution & Tracking](octoacme-execution-and-tracking.md) |
| Release to production safely | [Release & Deployment](octoacme-release-and-deployment.md) |
| Capture learnings and improve | [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) |
| Identify and communicate risks | [Risk Management & Communication](octoacme-risks-and-communication.md) |
| See role responsibilities | [Roles & Personas](octoacme-roles-and-personas.md) |

## How to use these docs with Copilot Spaces
1. Keep your Project Charter and key artifacts up to date in the project repo.
2. Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
3. Reference these docs when creating charters, kickoffs, onboarding, or planning materials.
4. To propose updates, use the Add Content to Project Management Process Docs issue template: ../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml

## Maintenance & acceptance
- This README is intended to be the single entry point for process docs in docs/.
- Keep links current and update descriptions when process changes are adopted.
- Use the documented issue template to request updates or additions.
