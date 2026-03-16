# OctoAcme Project Management Docs

## Overview

OctoAcme manages cross-functional projects using a repeatable lifecycle: **Initiation → Planning → Execution → Release → Close & Retrospective**. Every project begins with an initiation step that clarifies the business need and measurable outcomes, identifies stakeholders, and produces a **Project One-pager** (problem statement, SMART goals, success metrics, timeline, risks, and resourcing needs). Progression to the next phase is gated by clear success metrics, agreed priorities, and confirmed team availability.

Planning focuses on breaking approved work into **shippable increments**, creating a prioritized backlog with explicit **acceptance criteria**, estimating scope (e.g., T-shirt sizing or story points), and establishing a **Definition of Done**. Dependencies and integration points are identified up front, captured in a **risk register** (impact, likelihood, owner, mitigation, and status), and revisited regularly. Cross-team dependencies are made visible on the project board and escalated as needed.

Day-to-day execution follows a project board workflow (**Backlog → Ready → In Progress → In Review → QA → Done**) and a steady team rhythm of **daily standups**, **weekly delivery syncs**, and **end-of-sprint/milestone demos**. Pull requests are expected to be small and focused, include issue links and acceptance criteria, pass CI (tests, lint, and security scanning) before review, and receive at least one approval prior to merge. Progress is reported using delivery metrics (velocity, burndown) alongside product success metrics from the one-pager, supported by dashboards for operational signals such as errors, latency, and usage.

Roles are defined for clear ownership: the **Project Manager** coordinates delivery, schedule, risk, and communications; the **Product Manager** defines outcomes, prioritizes the backlog, and measures success; **Developers** implement, test, and review; **QA/Testing** validates acceptance criteria; and **Stakeholders** provide inputs and approvals. Communication is structured through regular cadences (PM/PdM syncs, standups, stakeholder updates) and standardized templates for weekly status and incident communications, with a defined escalation path from team triage up through PM/Product Lead to sponsor level. Releases require completed acceptance criteria, passing CI and security scans, release notes, rollback/mitigation plans, staged deployments with smoke tests, and post-deploy verification — followed by retrospectives that convert learnings into owned, time-bound action items.

## Lifecycle at a Glance

1. **Initiation** — problem statement, stakeholders, high-level timeline, and one-pager
2. **Planning** — backlog, acceptance criteria, estimates, milestones, risk register
3. **Execution** — build, test, review, iterate; daily standups and weekly syncs
4. **Release** — staged deploy, smoke tests, release notes, post-deploy verification
5. **Close & Retrospective** — capture learnings, assign action items, update docs

## Process Documentation

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

## How to Use These Docs

- Start with the [Project Management Overview](octoacme-project-management-overview.md) for a concise introduction to OctoAcme's approach, principles, and key artifacts.
- Use the phase-specific guides (Initiation, Planning, Execution, Release, Retrospective) as checklists and templates when running a project.
- Refer to [Roles & Personas](octoacme-roles-and-personas.md) to understand responsibilities and communication expectations for each role.
- Keep project artifacts (one-pager, risk register, retrospective notes) stored in the project repository and linked from the project board.
- Add these docs to `.copilot/` if you want Copilot Spaces to use them as context for role-specific guidance.
