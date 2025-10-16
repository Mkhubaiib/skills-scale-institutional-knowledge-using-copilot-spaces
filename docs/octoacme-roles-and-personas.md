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

## Agile Coach

### Role Summary
Agile Coaches guide teams in adopting and improving agile practices, facilitate ceremonies, and foster continuous improvement. They help teams become more effective and self-organizing.

### Responsibilities
- Facilitate sprint ceremonies (planning, standups, reviews, retrospectives)
- Coach teams on agile principles and best practices
- Identify and help remove organizational impediments
- Mentor Project Managers and team leads on process improvements
- Foster psychological safety and team collaboration

### Goals
- Increase team velocity and predictability
- Improve team collaboration and communication
- Build self-organizing, high-performing teams
- Drive adoption of agile and lean practices

### Typical Communication
- Sprint ceremony facilitation
- One-on-one coaching sessions with team members
- Process improvement workshops
- Collaboration with Project Managers on team dynamics

### Interactions with Other Roles
- **Project Managers**: Partner to improve team processes, provide coaching on agile practices, help resolve team dynamics issues
- **Developers**: Coach on agile engineering practices, facilitate better collaboration and self-organization
- **Product Managers**: Assist with backlog refinement and stakeholder management techniques

---

## Release Manager

### Role Summary
Release Managers coordinate and oversee the release process, ensuring deployments are executed smoothly, risks are managed, and releases meet quality standards.

### Responsibilities
- Plan and coordinate release schedules across teams
- Manage release artifacts, versioning, and documentation
- Ensure deployment checklists and gates are completed
- Coordinate go/no-go decisions with stakeholders
- Track and communicate release status
- Maintain release calendar and dependency tracking

### Goals
- Deliver reliable, on-time releases
- Minimize production incidents and rollbacks
- Ensure smooth coordination across teams during releases
- Maintain clear release documentation and audit trails

### Typical Communication
- Release planning meetings with engineering and product teams
- Go/no-go meetings before major releases
- Release status updates to stakeholders
- Post-release retrospectives

### Interactions with Other Roles
- **Project Managers**: Coordinate release timelines, dependencies, and resource allocation
- **Developers**: Review deployment plans, coordinate code freeze and release branches
- **DevOps Engineers**: Collaborate on deployment automation, rollback procedures, and environment readiness
- **Product Managers**: Align on release priorities, feature readiness, and communication to customers
- **QA/Testing**: Verify acceptance criteria are met and sign-off on release readiness

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and technical teams. They gather requirements, document processes, and ensure solutions align with business needs.

### Responsibilities
- Gather and document business requirements
- Create process flows, use cases, and functional specifications
- Facilitate requirements workshops with stakeholders
- Validate that delivered solutions meet business needs
- Analyze data to support business decisions

### Goals
- Ensure clear, actionable requirements
- Reduce rework by catching requirement gaps early
- Bridge communication between business and technical teams
- Support data-driven decision making

### Typical Communication
- Requirements workshops and stakeholder interviews
- Documentation reviews with technical teams
- User acceptance testing coordination
- Business case presentations

### Interactions with Other Roles
- **Product Managers**: Collaborate on defining requirements, validate solutions align with product vision
- **Developers**: Clarify requirements, provide functional specifications, answer business logic questions
- **Project Managers**: Support scope definition, help identify risks and dependencies
- **UX/UI Designers**: Provide user journey insights and functional requirements for design work

---

## UX/UI Designer

### Role Summary
UX/UI Designers create user-centered designs that are intuitive, accessible, and aligned with business goals. They conduct user research and design interfaces that enhance user experience.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and prototypes
- Design user interfaces following accessibility standards
- Collaborate with developers on implementation feasibility
- Maintain design systems and style guides

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and improve satisfaction
- Ensure design consistency across products
- Validate designs through user testing

### Typical Communication
- Design reviews and critique sessions
- User research presentations
- Design handoff meetings with developers
- Feedback sessions with Product Managers and stakeholders

### Interactions with Other Roles
- **Product Managers**: Align designs with product vision, validate user needs and priorities
- **Business Analysts**: Review user flows and functional requirements to inform design
- **Developers**: Collaborate on design feasibility, provide design specifications and assets
- **QA/Testing**: Define expected UI behavior for testing, review visual acceptance criteria

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain the infrastructure, tooling, and automation that enable reliable and efficient software delivery. They bridge development and operations.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure as code (IaC) and configuration management
- Implement monitoring, logging, and alerting systems
- Ensure security best practices in deployment pipelines
- Automate deployment and operational tasks
- Support incident response and troubleshooting

### Goals
- Maximize deployment frequency and reliability
- Minimize lead time for changes and recovery time
- Ensure infrastructure scalability and security
- Enable developer productivity through automation

### Typical Communication
- Infrastructure planning and architecture discussions
- Incident response and post-mortems
- CI/CD pipeline reviews with development teams
- Security and compliance discussions

### Interactions with Other Roles
- **Developers**: Provide tooling and automation for build, test, and deployment; support debugging production issues
- **Release Managers**: Implement deployment automation, coordinate release windows, provide deployment metrics
- **Project Managers**: Communicate infrastructure readiness, capacity planning, and technical dependencies
- **QA/Testing**: Provide test environments and automation infrastructure

---

## Role Interaction Matrix

This matrix shows key collaboration points and handoffs between roles:

| From → To | Developers | Product Managers | Project Managers | Agile Coach | Release Manager | Business Analyst | UX/UI Designer | DevOps Engineer |
|-----------|-----------|------------------|------------------|-------------|-----------------|------------------|----------------|-----------------|
| **Developers** | Code reviews | Feature demos | Status updates | Process feedback | Deployment plans | Requirement clarifications | Design questions | Pipeline issues |
| **Product Managers** | Backlog items | - | Roadmap alignment | Product strategy | Feature priorities | Requirements | User needs | Product metrics |
| **Project Managers** | Task assignments | Timeline reviews | - | Process improvements | Release schedules | Scope validation | Resource planning | Infrastructure needs |
| **Agile Coach** | Practice coaching | Backlog refinement | Team dynamics | - | Ceremony facilitation | Requirements workshops | Design thinking | Process automation |
| **Release Manager** | Code freeze notices | Release updates | Dependency tracking | Release retrospectives | - | Release requirements | UI sign-off | Deployment coordination |
| **Business Analyst** | Specifications | Requirement validation | Scope documentation | User stories | Business requirements | - | User flows | Data requirements |
| **UX/UI Designer** | Design specs | Design proposals | Timeline estimates | Design sprints | UI acceptance criteria | Design validation | - | UI monitoring needs |
| **DevOps Engineer** | CI/CD support | Deployment metrics | Infrastructure status | Automation demos | Deployment tooling | Data pipelines | Performance metrics | - |

---

## Communication and Handoff Points

### Key Handoff Scenarios

#### 1. Requirements to Design
- **From**: Business Analyst → **To**: UX/UI Designer
- **Handoff**: User stories, functional requirements, business rules
- **Validation**: Design review meeting with BA and Product Manager
- **Documentation**: Requirements document, user journey maps

#### 2. Design to Development
- **From**: UX/UI Designer → **To**: Developers
- **Handoff**: Design specs, mockups, assets, accessibility requirements
- **Validation**: Design handoff meeting, developer Q&A session
- **Documentation**: Design system documentation, Figma/Sketch files with annotations

#### 3. Development to QA
- **From**: Developers → **To**: QA/Testing
- **Handoff**: Completed feature in test environment, PR with acceptance criteria
- **Validation**: Smoke tests pass, feature meets Definition of Done
- **Documentation**: Test cases, acceptance criteria checklist

#### 4. QA to Release
- **From**: QA/Testing → **To**: Release Manager
- **Handoff**: Sign-off on acceptance criteria, test results
- **Validation**: All release criteria met, no blocking issues
- **Documentation**: Test report, known issues list

#### 5. Release to Production
- **From**: Release Manager → **To**: DevOps Engineer
- **Handoff**: Deployment approval, release artifacts
- **Validation**: Pre-deployment checklist completed, rollback plan ready
- **Documentation**: Deployment runbook, release notes

#### 6. Sprint Planning
- **From**: Product Manager + Business Analyst → **To**: Team (via Agile Coach/Project Manager)
- **Handoff**: Prioritized backlog, refined user stories
- **Validation**: Team understands requirements, estimates provided
- **Documentation**: Sprint backlog, capacity planning

### Communication Cadence by Role

- **Daily**: Developers, DevOps Engineers (standups)
- **2-3x per week**: Project Managers, Release Managers (status syncs)
- **Weekly**: Product Managers, Business Analysts (backlog refinement)
- **Bi-weekly/Sprint**: All roles (sprint planning, review, retrospective)
- **As needed**: Agile Coach (coaching sessions), UX/UI Designer (design reviews)

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The Role Interaction Matrix helps identify who needs to communicate with whom and when.
- Communication and handoff points ensure smooth transitions between project phases and team members.

