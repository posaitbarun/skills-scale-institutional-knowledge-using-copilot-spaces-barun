# OctoAcme Project Management Process Documentation

Welcome — this folder is the central entry point for OctoAcme’s project management processes. The guidance here is designed to help teams run initiatives consistently and efficiently: start with a concise Project One-pager, plan in small, shippable increments, execute with clear acceptance criteria and CI gates, and capture learnings during retrospectives. Our approach emphasizes customer-first priorities, iterative delivery, clear ownership (named PM and Product Lead), and data-informed decision making.

Key workflows include a lightweight initiation and planning process (one-pager, kickoff, prioritized backlog), an execution workflow driven from the project board (Backlog → Ready → In Progress → In Review → QA → Done), and a PR policy that favors small, testable changes with CI and required approvals. Releases follow a checklist-driven process with pre-release verification, smoke tests, rollback plans, and post-deploy checks to reduce risk.

Roles and communication are explicit: Product Managers own outcomes and success metrics, Project Managers coordinate delivery, Developers implement and test, and QA validates acceptance. Regular rhythms — daily standups, weekly delivery syncs, sprint demos/reviews, and monthly stakeholder updates — keep progress visible. Risks are tracked in a register with owners and mitigation plans; escalation moves from team → PM → Product Lead → Sponsor when needed.

Quality assurance is layered: unit and integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA where required. Release and deployment guidance includes deployment checklists, verification steps, and incident/rollback playbooks so teams can deploy safely and respond to issues.

## Table of Contents
- 📋 [Project Management Overview](./octoacme-project-management-overview.md)
- 📝 [Project Initiation Guide](./octoacme-project-initiation.md)
- 🗂️ [Project Planning](./octoacme-project-planning.md)
- 🚀 [Execution & Tracking](./octoacme-execution-and-tracking.md)
- ⚠️ [Risk Management & Communication](./octoacme-risks-and-communication.md)
- 📦 [Release & Deployment](./octoacme-release-and-deployment.md)
- 🔁 [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- 👥 [Roles & Personas](./octoacme-roles-and-personas.md)

## Quick Reference
- Starting a new project: read the Project Initiation Guide.
- Planning work: use Project Planning and the Backlog Item Template.
- Day-to-day delivery: follow the Execution & Tracking board flow and PR rules.
- Releasing: use the Release & Deployment checklist and smoke tests.
- Learning: capture action items from Retrospectives and track in the backlog.

## How to contribute
Use the repository’s process-doc update issue template (.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose changes or additions to these documents.
