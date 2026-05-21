# OctoAcme Project Management Docs

## Overview

This README centralizes links to all project management process documents for managing projects at OctoAcme. It includes concise summaries and navigation to resources for project managers, product managers, developers, and stakeholders.

---

## Project Management Processes Summary

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear accountability. The organization operates through five distinct phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During initiation, teams validate business need and create a lightweight Project One-pager that defines the problem statement, measurable success metrics, key stakeholders, and initial timeline. This decision-gate approach ensures alignment before committing resources. The planning phase then breaks approved work into shippable increments, establishing prioritized backlogs with acceptance criteria, estimating scope through T-shirt sizing or story points, and identifying dependencies and risks upfront.

Execution and delivery are managed through a clear team rhythm centered on daily standups (15 minutes), weekly delivery syncs, and end-of-sprint demos. Teams use GitHub Projects or similar tools to track work across Backlog, Ready, In Progress, In Review, QA, and Done columns. Pull requests are kept small (≤400 lines when possible) and require at least one approval before merging. Quality and testing are embedded throughout: unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, and security scanning in CI pipelines. Manual QA gates feature acceptance when needed. OctoAcme also maintains a Risk Register tracking likelihood and impact, with escalation paths from team-level triage through the PM, Product Lead, and Sponsor levels.

The organization defines clear roles with distinct responsibilities: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** define outcomes and prioritize backlogs; **Developers** implement features and maintain tests; and **QA/Testing** validates acceptance criteria. Communication happens through weekly PM-PdM syncs, twice-weekly standups, monthly stakeholder updates, and a single source of truth (project README or release doc) for status. Release management follows standardized checklists covering pre-release requirements, smoke tests, rollback plans, and post-deploy verification. Finally, retrospectives after each sprint or milestone capture learnings and convert them into prioritized action items with clear owners and due dates, reinforcing a culture of continuous improvement and psychological safety.

---

## Core Principles

OctoAcme project management operates with the following principles:

- **Customer-first** — Prioritize customer value and usability
- **Iterative delivery** — Ship small, testable increments
- **Clear ownership** — Each project has a named Project Manager (PM) and Product Lead
- **Data-driven decisions** — Measure impact and iterate based on evidence
- **Psychological safety** — Encourage feedback and learning

---

## Project Lifecycle

OctoAcme projects progress through five phases:

1. **Initiation** — Validate business need, align stakeholders, create a lightweight Project One-pager
2. **Planning** — Break work into shippable increments, prioritize backlog, identify dependencies and risks
3. **Execution & Tracking** — Build, test, review, iterate using daily standups and project boards
4. **Release & Deployment** — Deploy to production with pre-release checks, smoke tests, and rollback plans
5. **Close & Retrospective** — Capture learnings and convert them into actionable improvements

---

## Core Roles

- **Project Manager (PM)** — Coordinates delivery, schedules, risks, and communications
- **Product Manager (PdM)** — Defines outcomes, prioritizes backlog, measures success
- **Developers** — Implement features, collaborate on design and testability
- **QA/Testing** — Validate quality and acceptance criteria
- **Stakeholders** — Provide inputs, approvals, and strategic direction

---

## Key Practices

- **Daily standups** (15 min) — Focus on progress, blockers, dependencies
- **Weekly syncs** — PM-PdM alignment and delivery team updates
- **GitHub Projects** — Track work across Backlog, Ready, In Progress, In Review, QA, Done
- **Small PRs** — ≤400 lines when possible; require one approval before merge
- **Quality gates** — Unit tests, integration tests, E2E smoke tests, security scanning, manual QA
- **Risk management** — Maintain a Risk Register; escalate blockers through team → PM → Product Lead → Sponsor
- **Retrospectives** — After each sprint/milestone; capture learnings and prioritize 2–3 action items

---

## Docs Navigation

### Getting Started

- **[Project Management Overview](./octoacme-project-management-overview.md)** — Concise introduction to OctoAcme's approach, roles, and key artifacts. Start here for a quick primer.

### Phase-by-Phase Guides

- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Steps to validate and authorize work, align stakeholders, and create a lightweight plan. Includes the Project One-pager template and decision gate checklist.

- **[Project Planning](./octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and backlog. Covers kickoff, backlog prioritization, estimation, Definition of Done, and risk/dependency management.

- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Guidance for managing day-to-day execution and tracking progress toward milestones. Includes team rhythm, PR workflow, quality & testing standards, and blocker escalation.

- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardize how OctoAcme releases features to production. Covers release types, pre-release requirements, deployment checklist, and rollback procedures.

- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements. Structure, best practices, and action item tracking.

### Cross-Cutting Guidance

- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identify, assess, and monitor risks. Includes the Risk Register template, stakeholder communication strategies, and escalation paths.

- **[Project Roles & Personas](./octoacme-roles-and-personas.md)** — Detailed descriptions of typical roles (Developers, Product Managers, Project Managers) and their responsibilities, goals, and communication patterns.

---

## How to Use These Docs

- **For new team members** — Start with [Project Management Overview](./octoacme-project-management-overview.md), then review the persona that matches your role in [Project Roles & Personas](./octoacme-roles-and-personas.md).

- **For a new project** — Follow the phases in order: [Initiation](./octoacme-project-initiation.md) → [Planning](./octoacme-project-planning.md) → [Execution & Tracking](./octoacme-execution-and-tracking.md) → [Release & Deployment](./octoacme-release-and-deployment.md) → [Retrospective](./octoacme-retrospective-and-continuous-improvement.md).

- **For ongoing execution** — Refer to [Execution & Tracking](./octoacme-execution-and-tracking.md) for daily workflows, and [Risk Management & Communication](./octoacme-risks-and-communication.md) for blocker escalation and status reporting.

- **For process improvements** — Use the [Add Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to propose updates or clarifications to these documents.

---

## Contributing to These Docs

Process documents are living artifacts. If you identify gaps, improvements, or want to add new guidance:

1. Open an issue using the [Add Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
2. Describe the gap or improvement, the rationale, and suggested content.
3. Ensure your contribution aligns with existing process docs and has been reviewed with stakeholders.

---

## Questions?

Reach out to your Project Manager or Product Lead with questions about these processes. These docs are maintained as a shared resource and can be refined based on team feedback.
