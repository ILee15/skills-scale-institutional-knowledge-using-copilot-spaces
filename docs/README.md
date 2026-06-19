# OctoAcme Project Management Docs

Welcome to the OctoAcme project management process documentation. This README provides a centralized index and brief overview of all process documents used to manage projects at OctoAcme.

## Quick Navigation

- **[Project Management Overview](#project-management-overview)** — Core principles, roles, and key artifacts
- **[Project Initiation](#project-initiation)** — One-pager, stakeholder alignment, decision gate
- **[Project Planning](#project-planning)** — Backlog, estimation, Definition of Done, release planning
- **[Execution & Tracking](#execution--tracking)** — Team rhythm, workflows, quality assurance, reporting
- **[Risks & Communication](#risks--communication)** — Risk register, stakeholder updates, escalation paths
- **[Release & Deployment](#release--deployment)** — Release types, deployment checklist, rollback playbook
- **[Retrospective & Continuous Improvement](#retrospective--continuous-improvement)** — Running retrospectives, tracking action items
- **[Roles & Personas](#roles--personas)** — Responsibilities and communication norms for common roles

---

## Project Management Overview

**[octoacme-project-management-overview.md](./octoacme-project-management-overview.md)**

Provides a concise, shareable introduction to how OctoAcme runs projects. Covers core principles (customer-first, iterative delivery, clear ownership, data-informed decisions, psychological safety), defines key roles (Project Manager, Product Manager, Developers, QA/Testing), describes key artifacts, and outlines the high-level project lifecycle and communication cadence.

---

## Project Initiation

**[octoacme-project-initiation.md](./octoacme-project-initiation.md)**

Guidance for validating and authorizing new work, aligning stakeholders, and creating a lightweight initial plan. Includes the Project One-pager template, stakeholder identification, success criteria definition, and the decision gate for moving into detailed planning.

---

## Project Planning

**[octoacme-project-planning.md](./octoacme-project-planning.md)**

Turns an approved initiative into an actionable plan and backlog for delivery. Covers backlog creation with acceptance criteria, scope estimation (T-shirt sizing or story points), Definition of Done, sprint/iteration planning, risk and dependency management, and the release plan and milestone map.

---

## Execution & Tracking

**[octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md)**

Guidance for managing day-to-day execution and tracking progress toward project milestones. Defines team rhythm (daily standups, weekly delivery syncs, demos/reviews), pull request workflows, quality assurance practices (unit tests, integration tests, smoke tests, security scanning), reporting and metrics, blocker escalation, and an execution checklist.

---

## Risks & Communication

**[octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md)**

Explains how to identify, manage, and communicate risks and dependencies. Includes the Risk Register format, risk lifecycle (identify, assess, mitigate, monitor), stakeholder communication strategies, communication templates (weekly status, incident communication), and escalation paths (team-level → PM → Product Lead → Sponsor).

---

## Release & Deployment

**[octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md)**

Standardizes how OctoAcme releases features to production to reduce risk and improve observability. Covers release types (Patch, Minor, Major), pre-release requirements, deployment checklist (staging verification, production deployment, post-deploy checks), rollback and incident playbook, and release notes template.

---

## Retrospective & Continuous Improvement

**[octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md)**

Guidance for capturing learnings and converting them into actionable improvements. Describes retrospective structure (what went well, improvements, action items), how to run a retrospective, tracking improvements in the backlog, action item template, and fostering a continuous improvement culture.

---

## Roles & Personas

**[octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md)**

Defines typical roles and responsibilities used in OctoAcme project work. Includes detailed persona definitions for Developers, Product Managers, and Project Managers, with their responsibilities, goals, and typical communication patterns.

---

## OctoAcme Project Management Approach

### Overview & Core Philosophy

OctoAcme follows a structured, customer-centric project lifecycle that emphasizes iterative delivery, clear ownership, and data-informed decision-making. The approach spans five key phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. At its foundation, OctoAcme operates on five core principles: prioritizing customer value and usability, delivering small testable increments, establishing clear ownership through named Project Managers and Product Leads, making decisions based on measurable evidence, and fostering psychological safety for continuous feedback and learning. This structured yet flexible framework ensures that all cross-functional projects—whether delivering product features, services, or integrations—maintain alignment and transparency from conception through deployment.

### Key Roles, Responsibilities & Communication Cadence

The OctoAcme operating model defines three primary personas: **Developers** (who implement features, write tests, and identify technical risks), **Product Managers** (who define what to build, prioritize the backlog, and measure outcomes), and **Project Managers** (who coordinate delivery, manage risks, and maintain stakeholder alignment). Complementing these are QA/Testing and stakeholder groups. Communication happens through a deliberate cadence: daily standups (15 minutes focused on progress and blockers), weekly PM–PdM syncs, twice-weekly delivery standups, monthly stakeholder updates, and ad-hoc escalations for critical issues. Risk escalation follows a three-level model: Level 1 (team-level triage in standups), Level 2 (PM escalates to Product Lead and dependent teams), and Level 3 (sponsor-level escalation for business-impacting issues). This rhythm ensures transparency and rapid resolution of dependencies and blockers.

### Execution, Quality & Release Standards

Execution is managed through a project board with defined columns—Backlog, Ready, In Progress, In Review, QA, Done—and a strict pull request discipline: PRs should stay under 400 lines, include issue links and acceptance criteria, run automated tests and linting in CI, and require at least one approval before merging. Quality assurance is built into every stage: unit and integration tests for new logic, end-to-end smoke tests before release, security scanning in CI, and manual QA for feature acceptance where needed. Before any release, teams must confirm all acceptance criteria are met, passing CI and security scans, have release notes drafted, and a documented rollback plan. Releases are categorized as Patch (hotfixes), Minor (incremental features), or Major (significant functionality), and deployment includes staging verification, post-deploy checks, and stakeholder announcements. This rigor, combined with retrospectives held after each sprint or milestone to capture learnings and drive continuous improvement, ensures OctoAcme maintains both velocity and reliability.

---

## How to Use These Docs

- **New to OctoAcme projects?** Start with the [Project Management Overview](#project-management-overview) and [Roles & Personas](#roles--personas) to understand the framework and who does what.
- **Starting a new project?** Follow the sequence: [Project Initiation](#project-initiation) → [Project Planning](#project-planning) → [Execution & Tracking](#execution--tracking).
- **Managing a live project?** Refer to [Execution & Tracking](#execution--tracking), [Risks & Communication](#risks--communication), and [Release & Deployment](#release--deployment).
- **At project end?** Use [Retrospective & Continuous Improvement](#retrospective--continuous-improvement) to capture learnings.

For process improvements or updates to these docs, see the [process documentation update issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml).
