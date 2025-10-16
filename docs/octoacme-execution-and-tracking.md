# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies (Developers, DevOps Engineers, QA)
- Weekly delivery sync — show progress, updates, and flagged risks (Project Manager with team leads)
- Weekly backlog refinement — prepare upcoming work (Product Manager, Business Analyst, team representatives)
- Design reviews — validate UX/UI designs and gather feedback (UX/UI Designer with stakeholders)
- Demo/Review at the end of each sprint or milestone (whole team, facilitated by Agile Coach or Project Manager)
- Retrospectives — capture learnings and improvement actions (facilitated by Agile Coach)

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint (DevOps Engineer)
- [ ] Regular demos scheduled with stakeholders
- [ ] Risk register updated weekly (Project Manager)
- [ ] Design handoffs completed when UI work is ready (UX/UI Designer to Developers)
- [ ] QA signoff process established and followed
- [ ] Release Manager informed of deployment readiness
- [ ] Team velocity and metrics tracked for continuous improvement

For detailed handoff procedures between phases, see [Communication & Handoff Checklist](octoacme-communication-and-handoff-checklist.md).
