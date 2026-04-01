# OctoAcme Project Management Docs

This directory is the central hub for OctoAcme's project management process documentation. It is intended for team members, contributors, and stakeholders who want to understand how OctoAcme plans, executes, releases, and continuously improves its projects.

---

## Overview

OctoAcme follows a structured project lifecycle—Initiation, Planning, Execution, Release, and Close/Retrospective—designed to move an idea from initial validation through a prioritized backlog and iterative delivery. Key artifacts include the Project One-pager, release and milestone plans, a prioritized backlog with acceptance criteria, and a Risk Register. These serve as the single source of truth for status, dependencies, and scope decisions throughout the project.

Workflows emphasize small, incremental delivery and explicit handoffs. Teams use a project board with standard columns (Backlog, Ready, In Progress, In Review, QA, Done) and a Pull Request workflow that encourages small PRs (≤ 400 lines), inclusion of issue links and acceptance criteria, CI-driven testing and linting before review, and at least one approval prior to merge. Planning artifacts and templates—backlog item template, release notes template, deployment checklist—standardize sprint planning, release readiness, and post-deploy verification. The release process includes pre-release checks, staged deployments, smoke tests, rollback plans, and a documented incident playbook.

Roles and communication are explicit. Product Managers define outcomes and success metrics, Project Managers coordinate delivery and risks, Developers implement and test, QA validates acceptance criteria, and Stakeholders provide approvals and inputs. The cadence includes daily standups for blockers and progress, weekly delivery syncs and PM–PdM alignment, sprint/milestone demos, and monthly stakeholder updates. Escalation paths are defined (team → PM → Product Lead → Sponsor), and specific communication templates are provided for weekly status and incident reporting to keep stakeholders informed and aligned.

Quality assurance and continuous improvement are integral to OctoAcme's approach. Development is supported by unit, integration, and end-to-end smoke tests, automated security scanning in CI, and manual QA for feature acceptance when needed. The process mandates documenting a Definition of Done, running CI checks before requesting review, and capturing retrospective action items as issues or backlog entries so improvements are tracked and measured. The repository also includes an issue template for proposing updates to process docs, which helps keep program guidance living, reviewed, and aligned with team feedback.

---

## Process Documents

- [OctoAcme Project Management Overview](octoacme-project-management-overview.md) — A concise introduction to how OctoAcme runs projects, covering approach, roles, and key artifacts.
- [OctoAcme — Project Initiation Guide](octoacme-project-initiation.md) — Initial steps to validate and authorize work, align stakeholders, and create a lightweight plan.
- [OctoAcme — Project Planning](octoacme-project-planning.md) — Turn an approved initiative into an actionable plan and backlog for delivery.
- [OctoAcme — Execution & Tracking](octoacme-execution-and-tracking.md) — Guidance for managing day-to-day execution and tracking progress toward project milestones.
- [OctoAcme — Risk Management & Communication](octoacme-risks-and-communication.md) — How to identify, manage, and communicate risks and dependencies.
- [OctoAcme — Release & Deployment Guide](octoacme-release-and-deployment.md) — Standardized process for releasing features to production to reduce risk and improve observability.
- [OctoAcme — Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into actionable improvements.
- [OctoAcme Personas](octoacme-roles-and-personas.md) — Defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## How to Contribute

To propose additions or updates to any process document in this directory, please open an issue using the [Add/Update Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template. This ensures all changes are reviewed, discussed, and aligned with team feedback before being merged.

---

## Acceptance Criteria

- [ ] Content aligns with existing docs in the `docs/` folder.
- [ ] README improves clarity or addresses a gap in the current documentation.
- [ ] Changes have been reviewed with stakeholders (if needed).
