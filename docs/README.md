# OctoAcme Project Management Documentation

## Overview
OctoAcme follows a structured, iterative approach to project management focused on delivering customer value, reducing risk, and enabling fast learning. These documents are the playbooks, checklists, and working guidance that help teams initiate work, plan effectively, execute and track progress, and continuously improve.

Core principles:
- Customer-first: prioritize customer value and usability
- Iterative delivery: deliver small, testable increments
- Clear ownership: each project has a named PM and Product Lead
- Data-informed: measure impact and iterate based on evidence
- Psychological safety: encourage feedback and learning

## Table of Contents
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)

## Brief overview of OctoAcme project management processes
1. Initiation
   - Validate the business need and define measurable success.
   - Produce a Project One-pager, identify stakeholders, and confirm go/no-go.
2. Planning
   - Break approved initiatives into shippable backlog items with clear acceptance criteria.
   - Estimate scope, define Definition of Done, identify dependencies and risks, and create a release/milestone plan.
3. Execution & Tracking
   - Use a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done).
   - Small PRs, CI and automated checks, daily standups, weekly delivery syncs, and regular demos.
   - Track velocity, burndown, and success metrics.
4. Release & Deployment
   - Ensure all acceptance criteria and CI checks pass, draft release notes, run staging smoke tests, and deploy via automated pipelines where possible.
   - Have rollback and incident playbooks ready.
5. Retrospective & Continuous Improvement
   - Capture what went well and what to improve; create prioritized action items and track their impact.

Cross-cutting areas:
- Risk management: maintain a lightweight Risk Register and escalate via the defined paths.
- Communication: weekly PM+PdM sync, twice-weekly standups (or team cadence), and monthly stakeholder updates.
- Quality: unit/integration tests, security scanning in CI, manual QA for acceptance when needed.

## Quick start
- New to OctoAcme? Start with the [Project Management Overview](./octoacme-project-management-overview.md).
- Starting a new project? Follow the [Initiation Guide](./octoacme-project-initiation.md).
- In active delivery? See [Execution & Tracking](./octoacme-execution-and-tracking.md) and the checklists in [Release & Deployment](./octoacme-release-and-deployment.md).

## How to use these docs
- Keep process artifacts updated in the repo under docs/.
- Add project-specific process guidance into `.copilot/` if you want them to be included as Copilot Spaces context.
- Suggest edits using the Process Doc Update issue template: `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`.

## Governance & contribution
- Propose updates through the Process Doc Update issue template.
- Small editorial updates can be merged by the PM; substantive process changes should be reviewed by stakeholders.
- Maintain clear acceptance criteria and link decisions to issue PRs for traceability.
