# OctoAcme Project Management Documentation

## Overview

OctoAcme follows a structured, lifecycle-based approach to project management grounded in customer-first principles and iterative delivery. The methodology spans five core phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Closure & Retrospective**. During Initiation, teams validate business need and align stakeholders around a lightweight Project One-pager that defines the problem, goals, success metrics, and resource needs. Once approved, the Planning phase breaks work into shippable increments, establishes acceptance criteria, estimates scope, and identifies dependencies and risks. This foundation enables the Execution phase, where teams follow a structured rhythm of daily standups, weekly delivery syncs, and sprint-based iterations using GitHub Projects boards with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done). Pull requests are kept small (≤400 lines), require at least one approval, and must pass automated tests and linting before merging.

Quality and testing are embedded throughout execution, with requirements for unit tests on new logic, integration tests where applicable, and end-to-end smoke tests for critical flows. Security scanning runs in CI, and manual QA validates feature acceptance when needed. The Release & Deployment guide standardizes how features move to production through pre-release checklists, staged deployment to staging environments, post-deploy verification, and documented rollback procedures. Throughout all phases, OctoAcme maintains a Risk Register tracking impact, likelihood, ownership, and mitigation plans, reviewed weekly to catch blockers early.

Three primary roles drive project success: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** define outcomes, prioritize backlogs, and measure impact; and **Developers** implement features collaboratively while identifying technical risks. The communication cadence includes weekly syncs between PM and PdM, twice-weekly standups for delivery teams, and monthly stakeholder updates, with escalation paths flowing from team-level triage through PM to Product Lead and Sponsor. Every project concludes with a Retrospective (45–75 minutes) to capture learnings, prioritize 2–3 actionable improvements, and feed insights back into the backlog—ensuring continuous refinement of both process and product.

---

## Core Documents

- **[Project Management Overview](./octoacme-project-management-overview.md)** — Introduction to OctoAcme's approach, core principles, roles, key artifacts, and high-level lifecycle
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Steps to validate business need, align stakeholders, and authorize work with the Project One-pager template
- **[Project Planning](./octoacme-project-planning.md)** — Breaking work into shippable increments, estimating scope, defining Definition of Done, and identifying dependencies
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Day-to-day execution, team rhythm (standups, syncs, demos), PR workflows, quality practices, and blocker escalation
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identifying, managing, and communicating risks and dependencies; maintaining risk registers and escalation paths
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardized release types, pre-release requirements, deployment checklists, and rollback procedures
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capturing learnings, running retrospectives, tracking action items, and driving iterative improvements
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Definitions of core roles (Developers, Product Managers, Project Managers) and their responsibilities, goals, and communication patterns

---

## Quick Start

**New to OctoAcme?** Start here:

1. **Understand the big picture:** Read the [Project Management Overview](./octoacme-project-management-overview.md) for a high-level introduction to our approach, principles, and roles.

2. **Find your phase:** Depending on where you are in your project, explore the relevant guide:
   - Starting a new project? → [Project Initiation Guide](./octoacme-project-initiation.md)
   - Planning the work? → [Project Planning](./octoacme-project-planning.md)
   - Building and shipping? → [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Release & Deployment Guide](./octoacme-release-and-deployment.md)
   - Managing risks? → [Risk Management & Communication](./octoacme-risks-and-communication.md)
   - Wrapping up? → [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

3. **Know the roles:** Check [Roles & Personas](./octoacme-roles-and-personas.md) to understand responsibilities and communication patterns.

---

## How to Use This Documentation

- **Keep it current:** These documents are living guides. Update them as processes evolve and practices improve.
- **Link from your project:** Reference relevant sections in your project charter, README, or issue templates.
- **Share with stakeholders:** Use the overview and relevant guides to onboard new team members and align stakeholders.
- **Suggest improvements:** Found a gap or have a suggestion? Open an issue or pull request to improve our documentation.

---

## Related Resources

- **Issue Templates:** Process-specific issue templates are stored in `.github/ISSUE_TEMPLATE/` to help standardize how process improvements are tracked.
- **Copilot Spaces:** These docs can be added to a Copilot Space to provide context-specific guidance during project execution.
