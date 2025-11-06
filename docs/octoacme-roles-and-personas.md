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

### Key Interactions
- **Product Managers**: Clarify requirements, acceptance criteria, and technical feasibility
- **Project Managers**: Report progress, blockers, and estimates
- **UX Designer**: Collaborate on design implementation and provide technical constraints
- **QA Lead**: Partner on test strategy, bug fixes, and code quality
- **DevOps Engineer**: Coordinate on deployment processes and environment issues

### Reporting Line
Reports to Engineering Manager or Technical Lead.

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

### Key Interactions
- **Developers**: Collaborate on trade-offs, technical feasibility, and scope decisions
- **Project Managers**: Align on roadmap, priorities, and resource allocation
- **UX Designer**: Define user needs, validate designs, and prioritize usability improvements
- **Customer Success Manager**: Review feedback themes, prioritize requests, and communicate roadmap
- **QA Lead**: Define acceptance criteria and quality standards

### Reporting Line
Reports to VP of Product or Chief Product Officer.

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

### Key Interactions
- **Product Managers**: Align on priorities, scope changes, and resource constraints
- **Developers**: Track progress, remove blockers, and coordinate deliverables
- **QA Lead**: Monitor quality metrics and testing progress
- **DevOps Engineer**: Coordinate deployment schedules and infrastructure planning
- **Customer Success Manager**: Plan customer communications around releases

### Reporting Line
Reports to PMO Director, Delivery Lead, or Program Manager.

---

## UX Designer

### Role Summary
UX Designers own the usability and design aspects of the product. They translate requirements and user needs into wireframes, prototypes, and design specifications that guide implementation.

### Responsibilities
- Conduct user research and usability testing
- Create design artifacts (wireframes, mockups, prototypes, style guides)
- Run usability tests and incorporate feedback
- Partner with Product Managers and Developers for design handoff
- Ensure design consistency and accessibility standards

### Goals
- Deliver intuitive, accessible user experiences
- Validate designs with real user feedback
- Maintain design system consistency

### Typical Communication
- Weekly sync with Product Managers on requirements
- Design review sessions with Developers
- Usability testing sessions with users
- Design handoff documentation and specifications

### Key Interactions
- **Product Managers**: Collaborate on requirement clarification, user stories, and acceptance criteria
- **Developers**: Partner on design implementation, provide design specifications and assets
- **QA Lead**: Coordinate on usability testing and design validation
- **Customer Success Manager**: Review user feedback to inform design improvements

### Reporting Line
Reports to Design Lead or Product Manager, depending on organization structure.

---

## QA Lead

### Role Summary
QA Leads are accountable for quality strategy, test planning, and test execution. They define quality gates, lead QA efforts, and report on quality metrics to ensure releases meet acceptance criteria.

### Responsibilities
- Create and maintain test plans and test cases
- Oversee manual and automated test execution
- Coordinate bug triage and track defect metrics
- Define quality gates and release criteria
- Mentor team on testing best practices

### Goals
- Ensure product quality meets acceptance criteria
- Reduce production defects and regressions
- Improve test automation coverage

### Typical Communication
- Daily standups for blockers and test status
- Weekly quality reports and metrics reviews
- Bug triage meetings with Developers and Product Managers
- Pre-release quality gate reviews

### Key Interactions
- **Developers**: Clarify acceptance criteria, coordinate bug fixes, review test coverage
- **Product Managers**: Schedule QA activities, validate acceptance criteria, prioritize testing scope
- **DevOps Engineer**: Integrate automated tests into CI/CD pipelines
- **Project Manager**: Report on quality metrics and testing progress

### Reporting Line
Reports to Engineering Manager or Quality Director.

---

## DevOps Engineer

### Role Summary
DevOps Engineers manage and automate CI/CD pipelines, infrastructure provisioning, and release operations. They enable rapid, reliable, and secure software delivery.

### Responsibilities
- Maintain deployment scripts and infrastructure as code
- Monitor production and staging environments
- Respond to incidents and outages
- Enable rapid and reliable releases through automation
- Implement security and compliance controls

### Goals
- Minimize deployment time and risk
- Maximize system reliability and uptime
- Automate manual operational tasks

### Typical Communication
- Daily monitoring and incident response
- Weekly infrastructure and deployment planning
- Post-incident reviews and retrospectives
- Release coordination meetings

### Key Interactions
- **Developers**: Partner on build/deployment automation, troubleshoot environment issues
- **QA Lead**: Integrate automated testing into CI/CD pipelines
- **Project Manager**: Coordinate deployment schedules and communicate infrastructure changes
- **Product Manager**: Align infrastructure capabilities with product requirements

### Reporting Line
Reports to Engineering Manager or DevOps/Infrastructure Lead.

---

## Customer Success Manager

### Role Summary
Customer Success Managers bridge the gap between users and the product team, representing customer interests and ensuring user feedback is incorporated into the product roadmap.

### Responsibilities
- Aggregate and synthesize user feedback and feature requests
- Communicate releases, changes, and product updates to customers
- Track customer satisfaction metrics (NPS, CSAT, etc.)
- Advocate for customer needs in planning and prioritization
- Support customer onboarding and adoption

### Goals
- Maximize customer satisfaction and retention
- Ensure customer voice influences product decisions
- Drive product adoption and engagement

### Typical Communication
- Weekly sync with Product Managers on feedback themes
- Monthly customer business reviews
- Release announcements and change communications
- Escalation of critical customer issues

### Key Interactions
- **Product Managers**: Closely collaborate to communicate feedback, influence roadmap, validate solutions
- **UX Designer**: Share user feedback to inform design improvements
- **QA Lead**: Report customer-found defects and usability issues
- **Project Manager**: Coordinate customer communications around releases

### Reporting Line
Reports to Customer Success Lead or VP of Customer Success.

---

## Reporting Lines & Communication Flows

**Purpose**: Clear reporting structures and communication flows enhance accountability and reduce confusion about escalation paths.

**Gap Addressed**: Issue #4 identified the need for explicit reporting lines to improve accountability and clarify decision-making authority.

### Organizational Structure
```
Executive Sponsor
├── Product Manager (reports to VP Product)
│   └── Customer Success Manager
│   └── UX Designer (may also report to Design Lead)
├── Engineering Manager (reports to VP Engineering)
│   ├── Developers
│   ├── QA Lead
│   └── DevOps Engineer
└── Project Manager (reports to PMO Director or Delivery Lead)
```

### Communication Flows
- **Cross-functional alignment**: Weekly sync between Product Manager, Project Manager, and Engineering Lead
- **Daily execution**: Standups involving Developers, QA Lead, DevOps Engineer, and UX Designer
- **Customer feedback loop**: Customer Success Manager → Product Manager → UX Designer/Developers
- **Quality handoffs**: Developers → QA Lead → DevOps Engineer → Production
- **Escalations**: Team → Project Manager → Sponsor (for business/timeline issues)
- **Technical escalations**: Team → Engineering Manager → CTO (for technical decisions)

---

## Cross-Functional Handoff Checklists

**Purpose**: Standardize handoffs between roles to prevent gaps, missed requirements, and quality issues.

**Gap Addressed**: Issue #4 highlighted unclear cross-functional handoffs, particularly for quality processes and user feedback, leading to potential missed requirements.

### Design to Development Handoff
**Gap Addressed**: Ensures UX designs are fully understood before implementation begins, reducing rework.

- [ ] Design specifications and mockups finalized and approved by Product Manager
- [ ] Design assets (icons, images, style guide) delivered to Developers
- [ ] Accessibility requirements documented (WCAG compliance level, keyboard navigation)
- [ ] Responsive breakpoints and mobile designs provided
- [ ] Design review meeting held with Developers to clarify questions
- [ ] Acceptance criteria updated to include design requirements
- [ ] UX Designer available for questions during implementation

### Development to QA Handoff
**Gap Addressed**: Clarifies when code is ready for testing and what quality standards must be met.

- [ ] All acceptance criteria met and documented in PR/issue
- [ ] Unit tests written and passing
- [ ] Code reviewed and approved by at least one peer
- [ ] Feature deployed to QA/staging environment
- [ ] Test data or test accounts prepared for QA Lead
- [ ] Known limitations or edge cases documented
- [ ] Developer available for bug triage and clarifications

### QA to Release Handoff
**Gap Addressed**: Ensures releases meet quality gates before production deployment.

- [ ] All test cases executed (manual and automated)
- [ ] Critical and high-priority bugs resolved
- [ ] Regression testing completed for existing functionality
- [ ] Performance and security tests passed (if applicable)
- [ ] Release notes reviewed and approved by Product Manager
- [ ] QA sign-off documented with test summary and metrics
- [ ] Rollback plan reviewed with DevOps Engineer

### Customer Feedback to Product Handoff
**Gap Addressed**: Ensures user feedback is systematically captured and influences product decisions.

- [ ] Customer feedback aggregated and categorized by theme
- [ ] Frequency and severity of feedback items documented
- [ ] Supporting data (usage metrics, support tickets) attached
- [ ] Customer Success Manager presents feedback in weekly sync
- [ ] Product Manager prioritizes feedback items in backlog
- [ ] Decision (accept/defer/reject) communicated back to Customer Success Manager
- [ ] Action items tracked in project management system

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

