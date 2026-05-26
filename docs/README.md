# OctoAcme Project Management Docs

## Project Management Process Summary

OctoAcme follows a structured, iterative project lifecycle that emphasizes customer value, clear ownership, and data-informed decision-making. The approach is organized around five key phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During Initiation, teams validate business need and align stakeholders around a lightweight Project One-pager that defines the problem, success metrics, and resource needs. Once approved by the Product Lead and sponsor, the project moves into Planning, where the scope is broken into shippable increments, backlog items are prioritized with acceptance criteria, and dependencies are mapped.

Execution and day-to-day tracking are governed by a consistent team rhythm: daily 15-minute standups focused on progress and blockers, weekly delivery syncs with the PM and Product Manager, and regular demos at sprint or milestone boundaries. Work flows through a project board with columns—Backlog, Ready, In Progress, In Review, QA, Done—to maintain visibility. Pull Request workflow is lightweight but rigorous: PRs are kept small (≤400 lines where possible), include issue links and acceptance criteria, run automated tests and linting in CI, and require at least one approval before merging. Quality is embedded throughout execution via unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance.

OctoAcme defines clear roles to ensure accountability and smooth collaboration. The **Project Manager** coordinates delivery, manages schedules, risks, and communications; the **Product Manager** owns the product vision, prioritizes the backlog, and measures outcomes; **Developers** implement features, write tests, and identify technical risks; and **QA/Testing** validates quality and acceptance criteria. Communication is formalized through weekly syncs between PM and Product Manager, twice-weekly standups for the delivery team, monthly stakeholder updates, and a three-level escalation path (team → PM → Product Lead → Sponsor) for blockers. Risk management is continuous—identified during planning and execution, assessed for impact and likelihood, mitigated through specific actions, and reviewed weekly.

Release and deployment follow a standardized approach to reduce risk: pre-release requirements include all acceptance criteria met, passing CI and security scans, and a documented rollback plan. Releases are announced to stakeholders and support, with rollback playbooks ready if needed. After each sprint, release, or milestone, teams conduct retrospectives to capture learnings and convert them into action items tracked in the backlog. This cycle of continuous improvement, combined with consistent measurement of velocity, burndown, and success metrics, ensures OctoAcme teams deliver reliable outcomes while building institutional knowledge and reducing single-person dependency risk.

---

## Process Documentation

Navigate to the specific process guides below:

- **[Project Management Overview](./octoacme-project-management-overview.md)** — Concise introduction to OctoAcme's approach, core roles, key artifacts, and high-level lifecycle.

- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Steps to validate business need, align stakeholders, and authorize work through a Project One-pager and decision gate.

- **[Project Planning](./octoacme-project-planning.md)** — Break work into shippable increments, prioritize the backlog, estimate scope, and plan releases and milestones.

- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Manage day-to-day execution, team rhythm, pull request workflow, quality assurance, reporting, and blocker escalation.

- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identify and manage risks, maintain a risk register, and communicate status and incidents to stakeholders.

- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardize how OctoAcme releases features to production, including pre-release requirements, deployment checklist, and rollback procedures.

- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings after sprints, releases, or milestones and convert them into actionable improvements.

- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Define typical roles (Project Managers, Product Managers, Developers, QA) and their responsibilities, goals, and communication patterns.

---

## How to Use These Docs

- **For Onboarding:** Start with [Project Management Overview](./octoacme-project-management-overview.md) to understand OctoAcme's approach, then explore individual guides as needed.
- **For Reference:** Use the navigation above to jump to the specific phase or process you're working on.
- **For Updates:** Submit process document updates or new content using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.
- **For Copilot Spaces:** Add this folder to your Copilot Space context to receive process-informed guidance.

---

## Key Principles

All OctoAcme processes are grounded in these principles:

- **Customer-first:** Prioritize customer value and usability.
- **Iterative delivery:** Deliver small, testable increments.
- **Clear ownership:** Each project has a named Project Manager and Product Lead.
- **Data-informed decisions:** Measure impact and iterate based on evidence.
- **Psychological safety:** Encourage feedback and learning.
