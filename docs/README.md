# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management processes guide. This documentation captures the standard practices and workflows used to deliver projects successfully across OctoAcme.

## Quick Start

New to OctoAcme projects? Start with our [Project Management Overview](./octoacme-project-management-overview.md) to understand our principles, roles, and artifacts.

## Project Lifecycle

OctoAcme projects follow a structured lifecycle from initiation through retrospective. Navigate each phase:

### Phase 1: Initiation
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Validate business need, identify stakeholders, create a lightweight project one-pager, and make a go/no-go decision.

### Phase 2: Planning
- **[Project Planning](./octoacme-project-planning.md)** — Break work into shippable increments, estimate scope, identify dependencies, and create a release plan.

### Phase 3: Execution & Tracking
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Manage day-to-day delivery, use project boards, run standups, and escalate blockers.
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Maintain a risk register, monitor dependencies, and keep stakeholders informed.

### Phase 4: Release & Deployment
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardize releases, manage pre-release requirements, and prepare rollback plans.

### Phase 5: Retrospective & Continuous Improvement
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings, track action items, and drive iterative improvements.

## Reference

- **[OctoAcme Roles & Personas](./octoacme-roles-and-personas.md)** — Understanding Project Managers, Product Managers, Developers, QA, and Stakeholder responsibilities.

## OctoAcme Project Management Overview

OctoAcme's project management approach is built around a clear lifecycle: start with initiation, move into planning, execute in iterative delivery increments, release with verification, and close with a retrospective. The approach emphasizes customer value, clear ownership, and data-informed decision-making, with each project expected to define a project charter or one-pager, a high-level timeline, and measurable success metrics before work begins. This gives teams a shared definition of scope and outcomes while creating a lightweight structure that can be adapted across different initiatives. The overall intent is to keep work aligned to business impact while reducing uncertainty through visible milestones, backlog prioritization, and dependency tracking.

The operating model relies on a set of core personas with distinct responsibilities. Product managers define the problem, prioritize the roadmap, and measure outcomes, while project managers coordinate schedules, risks, communications, and project documentation. Developers own implementation, testing, and technical quality, and QA/testing focuses on validating acceptance criteria and release readiness. Stakeholders provide input, approvals, and strategic alignment. This complementary structure minimizes ambiguity and creates accountability across cross-functional work.

Key workflows include backlog creation, sprint planning, risk tracking, and milestone-based execution. Projects use a board with columns such as Backlog, Ready, In Progress, In Review, QA, and Done, and work is broken into small, testable increments with defined acceptance criteria. Planning activities include kickoff meetings, estimation, dependencies mapping, Definition of Done, and release planning, while execution guidance includes daily standups, weekly delivery syncs, demos, and escalation paths for blockers. Communication is intentionally regular and structured: PM + Product Lead alignment, team standups, stakeholder updates, and clear owner assignments for risks and action items.

Quality assurance is a central part of the process. Requirements include unit tests, integration tests, smoke tests for critical flows, CI validation, security scans, and manual QA where appropriate. Acceptance criteria and the Definition of Done are used as gates before work is considered ready for review or release, and pull requests are expected to be small, linked to issues, and include criteria for validation. Before release, teams complete pre-deployment checks, smoke tests, rollback planning, and stakeholder notifications. The retrospective and continuous improvement guidance closes the loop by capturing lessons learned, assigning action items, and reviewing those improvements regularly to drive better team performance over time.

## Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named leads
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## How to Use This Documentation

1. **New team members**: Start with the Quick Start and Project Management Overview to get oriented.
2. **Project leads**: Use the Initiation Guide to kick off a new project, then move through Planning and Execution phases as work progresses.
3. **Delivery teams**: Reference Execution & Tracking and Risk Management docs during daily work; use Release & Deployment when preparing for production.
4. **Retrospectives**: Use the Retrospective & Continuous Improvement guide to capture learnings and track action items.
5. **Questions about roles**: Consult the Roles & Personas reference.
