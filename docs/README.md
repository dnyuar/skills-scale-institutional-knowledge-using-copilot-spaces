# OctoAcme Project Management Documentation

This directory contains OctoAcme's standardized project management process docs and serves as the entry point for planning, executing, and delivering work. The project lifecycle is artifact-driven and moves from Initiation (one‑pager and stakeholder alignment) through Planning (prioritized backlog, Definition of Done, and release mapping), Execution (work tracked on the project board and delivered via PRs), Release (pre‑release checks and rollbacks), and Retrospective (action items and continuous improvement).

OctoAcme emphasizes clear roles and ownership: Product Managers define outcomes and measures of success, Project Managers coordinate delivery and risks, Developers implement features and tests, and QA validates acceptance criteria. Each project maintains core artifacts — Project One‑pager, Roadmap, Backlog with acceptance criteria, Risk Register, and Retrospective notes — to make responsibilities and expectations visible across the team.

Workflows prioritize iterative delivery and low-risk integration. Teams use a project board with columns like Backlog → Ready → In Progress → In Review → QA → Done. Pull requests should be small, reference the related issue and acceptance criteria, and run CI (tests, linting, security scanning) before review. Releases are categorized (patch, minor, major) and require pre‑release smoke tests, release notes, and a rollback/mitigation plan.

Communication is structured and regular: daily standups for progress and blockers, weekly delivery syncs for progress and risks, PM–PdM alignment meetings, and stakeholder updates tied to milestones. Quality assurance mixes automated unit, integration, and smoke tests with manual QA where needed. After releases or incidents, retrospectives capture learnings and convert them into tracked action items.

## Quick Navigation
- Starting a project: [Project Initiation Guide](./octoacme-project-initiation.md)
- Planning work: [Project Planning](./octoacme-project-planning.md)
- Day-to-day execution: [Execution & Tracking](./octoacme-execution-and-tracking.md)
- Risk & communications: [Risk Management & Communication](./octoacme-risks-and-communication.md)
- Releasing to production: [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- Learning & improvement: [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- Roles & personas: [Roles & Personas](./octoacme-roles-and-personas.md)

## Index of Documents
- octoacme-project-management-overview.md — Overview, principles, lifecycle
- octoacme-project-initiation.md — One‑pager and decision gate
- octoacme-project-planning.md — Backlog, estimation, DoD, release plan
- octoacme-execution-and-tracking.md — Board, PR workflow, daily rhythm
- octoacme-risks-and-communication.md — Risk register and stakeholder templates
- octoacme-release-and-deployment.md — Release types, checklists, rollback playbook
- octoacme-retrospective-and-continuous-improvement.md — Retrospectives and action tracking
- octoacme-roles-and-personas.md — Role definitions and responsibilities

## Getting started
1. New to OctoAcme? Read the [Project Management Overview](./octoacme-project-management-overview.md).
2. Starting a new initiative? Complete the Project One‑pager in [Project Initiation](./octoacme-project-initiation.md).
3. In flight? Use [Execution & Tracking](./octoacme-execution-and-tracking.md) for day‑to‑day guidance and the project board.
