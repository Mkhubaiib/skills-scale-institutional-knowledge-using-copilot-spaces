# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support, customers)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status
- Tailor communication format and frequency to stakeholder needs:
  - **Executive stakeholders**: Monthly high-level summaries with key metrics and decisions needed
  - **Product stakeholders**: Weekly progress updates with feature status and risks
  - **Technical stakeholders**: Detailed sprint reviews and technical decision logs
  - **Cross-team dependencies**: Proactive updates on changes affecting their work

### Communication Roles and Responsibilities
- **Project Manager**: Coordinates overall communication, sends weekly status updates, manages stakeholder expectations
- **Product Manager**: Communicates product vision, roadmap changes, and customer impact
- **Release Manager**: Provides release schedules, deployment status, and go-live communications
- **Business Analyst**: Documents requirements changes and business impact assessments
- **Agile Coach**: Facilitates team communication and retrospectives
- **DevOps Engineer**: Communicates infrastructure changes, incidents, and system status

For detailed handoff and communication templates, see [Communication & Handoff Checklist](octoacme-communication-and-handoff-checklist.md).

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call

## Cross-Functional Collaboration Guidelines

### Effective Collaboration Practices
1. **Clear Ownership**: Every initiative has a designated DRI (Directly Responsible Individual)
2. **Shared Context**: Use documentation and knowledge sharing to ensure everyone has necessary context
3. **Respect Boundaries**: Understand each role's expertise and decision-making authority
4. **Proactive Communication**: Don't wait for scheduled meetings to raise blockers or concerns
5. **Document Decisions**: Capture key decisions and their rationale in a decision log

### Collaboration Channels
- **Synchronous**: Daily standups, planning meetings, design reviews, pair programming
- **Asynchronous**: Pull request comments, project board updates, documentation, recorded demos
- **Formal**: Sprint ceremonies, stakeholder reviews, go/no-go meetings
- **Informal**: Slack discussions, office hours, ad-hoc working sessions

### Handling Disagreements
1. Assume positive intent and focus on outcomes
2. Escalate to appropriate DRI when consensus cannot be reached
3. Document decision and move forward once resolved
4. Revisit decisions in retrospectives if new information emerges
