# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles
- Project Manager (PM): coordinates delivery, schedules, risk, communications.
- Product Manager (PdM): defines outcomes, prioritizes backlog, and measures success.
- Developers: implement features, collaborate on design and testability.
- Agile Coach: facilitates ceremonies, coaches teams on agile practices, drives continuous improvement.
- Release Manager: coordinates release schedules, manages deployment process, ensures release quality.
- Business Analyst: gathers requirements, documents processes, bridges business and technical teams.
- UX/UI Designer: conducts user research, creates designs, ensures accessible and intuitive interfaces.
- DevOps Engineer: builds CI/CD pipelines, manages infrastructure, ensures reliable deployments.
- QA/Testing: validate quality and acceptance criteria.
- Stakeholders: provide inputs and approvals.

For detailed role descriptions, responsibilities, and interaction patterns, see [Roles and Personas](octoacme-roles-and-personas.md).

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Lifecycle (high-level)
1. Initiation: problem statement, stakeholders, high-level timeline.
2. Planning: scope, resources, milestones, dependencies.
3. Execution: build, test, review, iterate.
4. Release: deploy, verify, announce.
5. Close & Retrospective: capture learnings and next steps.

## Communication Cadence
- Daily: Standup meetings for development team (Developers, DevOps Engineers)
- Twice-weekly: Delivery syncs and progress reviews
- Weekly sync between PM + PdM
- Weekly: Backlog refinement sessions (Product Manager, Business Analyst, team representatives)
- Bi-weekly or per sprint: Sprint planning, review, retrospective (facilitated by Agile Coach)
- As needed: Design reviews (UX/UI Designer with Product Manager and stakeholders)
- Release planning: Regular coordination between Release Manager, DevOps, and delivery teams
- Monthly stakeholder updates
- Ad-hoc escalations as needed

For detailed communication strategies and handoff points, see [Communication & Handoff Checklist](octoacme-communication-and-handoff-checklist.md).

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
