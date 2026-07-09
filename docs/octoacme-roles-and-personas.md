# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Expanded Personas

Below are additional personas commonly involved in cross-functional projects. Each entry includes a short summary, key responsibilities, and how they typically interact with existing roles.

### Technical Program Manager (TPM)
- Summary: Coordinates complex technical efforts across multiple teams; focuses on scheduling, technical dependencies, and delivery risks.
- Responsibilities:
  - Track cross-team dependencies and milestones
  - Drive technical milestones and integrate engineering inputs
  - Maintain RAID (Risks, Assumptions, Issues, Decisions)
- Interactions:
  - Works with PM/PdM on timelines and scope
  - Coordinates with Engineering Managers and architects
  - Escalates cross-team blockers to Project Manager or Product Lead

### Delivery Lead
- Summary: Day-to-day owner of delivery for a release or milestone; ensures work items meet Definition of Done and are progressing.
- Responsibilities:
  - Facilitate standups for multi-team deliveries
  - Validate readiness criteria and track release-readiness checklist
  - Coordinate cross-team verification and cutover tasks
- Interactions:
  - Reports progress to PM
  - Coordinates with QA and Developers for verification
  - Partners with Release Manager for deployment timing

### Release Manager
- Summary: Owns release coordination and deployment activities across environments.
- Responsibilities:
  - Schedule deployment windows and maintain release checklist
  - Ensure backups/rollback plans and smoke tests are in place
  - Communicate release notes and stakeholder notifications
- Interactions:
  - Works with Delivery Lead and PM for timing
  - Coordinates with SRE/DevOps for pipelines and cutover
  - Notifies Support/Customer Success for customer impact

### Site Reliability Engineer (SRE) / DevOps Owner
- Summary: Responsible for service reliability, observability, and runbook ownership.
- Responsibilities:
  - Define and monitor SLOs and alerts
  - Support incident response and post-incident actions
  - Manage infra changes and deployment safety
- Interactions:
  - Collaborates with Developers on architecture and deployability
  - Advises PM/Delivery Lead on operational risk
  - Coordinates with Release Manager for production changes

### UX Researcher / Designer
- Summary: Owns user research, UX validation, and design handoff for features.
- Responsibilities:
  - Run usability studies and validate UX hypotheses
  - Produce wireframes, prototypes, and design specs
  - Ensure acceptance criteria include UX validation
- Interactions:
  - Works with PdM on product decisions and success metrics
  - Hands off designs to Developers and QA for implementation
  - Participates in demos to validate UX outcomes

### Data Analyst / Data Product Owner
- Summary: Ensures features have measurable metrics and proper instrumentation.
- Responsibilities:
  - Define key metrics and success criteria
  - Validate telemetry and dashboarding for releases
  - Support A/B test design and analysis
- Interactions:
  - Works with PdM on success metrics and measurement plans
  - Coordinates with Developers to implement telemetry
  - Provides reports to PM for status and retrospectives

### Security Owner / Security Reviewer
- Summary: Ensures security requirements are considered and validated for the project.
- Responsibilities:
  - Perform threat modeling and security reviews when needed
  - Review security scans and sign off on remediation
  - Coordinate vulnerability triage and fixes
- Interactions:
  - Engages with Developers and SRE on remediation
  - Escalates critical security issues to Product Lead or Security on-call

### Customer Success / Support Liaison
- Summary: Bridges product teams and customer-facing support functions.
- Responsibilities:
  - Provide product context to Support and prepare playbooks
  - Collect feedback and customer-reported issues
  - Assist in post-release validation and customer communications
- Interactions:
  - Works with PM for communications and runbooks
  - Coordinates with Release Manager for customer notices
  - Works with QA to reproduce and prioritize customer issues

---

## How to add more personas
- Use the Process Doc Update issue template to propose additions or edits.
- Keep entries short (3–5 bullets) and include interactions to reduce handoff ambiguity.
