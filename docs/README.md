# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation. This README provides a quick overview of how we run projects and links to detailed process docs.

## Overview of Our Process
OctoAcme delivers work through a lightweight, iterative lifecycle grounded in customer value, clear ownership, and data‑informed decisions. Each project names a Project Manager (PM) to coordinate delivery and a Product Manager (PdM) to own outcomes and prioritization. Core artifacts anchor the work: a Project One‑pager/Charter, a prioritized backlog with acceptance criteria and a documented Definition of Done, a roadmap and release plan, a risk register, and retrospective notes. The lifecycle moves from Initiation and Planning (validate need, scope, success metrics, dependencies) through Execution (build, test, review), Release (deploy, verify, announce), and Close/Retrospective (capture learnings and next steps).

Roles are clearly defined and collaborative. Product Managers articulate problem statements, success metrics, and backlog priorities while aligning stakeholders and measuring outcomes. Project Managers create plans, manage schedules, risks, dependencies, and cross‑team communications, facilitating key ceremonies (kickoff, planning, demos, retrospectives). Developers implement features, write tests and documentation, participate in design and code reviews, and surface technical risks. QA/Testing validates acceptance criteria and overall quality, partnering across roles to uphold the Definition of Done. Stakeholders provide inputs and approvals, with transparency maintained via status reports and shared docs.

Execution relies on disciplined workflows and predictable communication. Teams work from a project board (e.g., GitHub Projects) with stages from Backlog to Done, and follow a PR workflow that favors small, reviewable changes linked to issues and acceptance criteria. CI runs tests and linting prior to review, and merges require at least one approval (per team policy). The cadence includes daily standups for progress and blockers, a weekly delivery sync to review progress and risks, end‑of‑sprint/milestone demos, and monthly stakeholder updates. Risk management is continuous: items are tracked in a risk register, reviewed weekly, and escalated along clear paths (team → PM → Product Lead → sponsor), with incident communication templates ready when needed.

Quality assurance is embedded from planning through release and beyond. The team documents a Definition of Done, drafts an initial test/QA approach during planning, and enforces layered testing (unit, integration, and end‑to‑end smoke tests), plus security scanning in CI. Pre‑release gates require all acceptance criteria to pass, CI/security to be green, release notes and rollback plans prepared, and smoke tests ready. Deployments follow a checklist (stage, verify, production, post‑deploy checks, announcements), with a rollback and incident playbook if issues arise. Continuous improvement is formalized via retrospectives after sprints, releases, and incidents, emphasizing psychological safety, prioritized action items with owners/dates, and follow‑through tracked in the backlog.

## Process Documentation
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)
