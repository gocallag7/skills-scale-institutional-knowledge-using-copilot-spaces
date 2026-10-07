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

## QA / Testing Lead

### Role Summary
QA / Testing Leads own the quality strategy, test execution, and acceptance validation across the project lifecycle. They ensure delivery meets quality standards, acceptance criteria, and readiness expectations before release.

### Responsibilities
- Define the QA and testing strategy for each project or release
- Create and maintain test plans, test cases, and quality checklists
- Validate functionality against acceptance criteria before signoff
- Triage and document defects with clear priority and reproduction details
- Coordinate regression, integration, and smoke testing activities
- Partner with developers and PMs to confirm release readiness
- Escalate quality or risk issues when delivery confidence is low

### Goals
- Reduce defects and production issues
- Improve confidence in release quality and readiness
- Make quality progress visible to stakeholders and delivery teams

### Typical Communication
- Daily standups and planning sessions for defect triage and testing status
- QA signoff in PR review and release readiness check-ins
- Quality reports in weekly project updates and milestones
- Clear escalation to PMs and stakeholders when critical issues block delivery

### Interaction with Existing Roles
- Works with Developers to clarify acceptance criteria and validate fixes
- Partners with Product Managers to confirm customer-facing quality expectations
- Supports Project Managers by identifying delivery risks and release readiness gaps

---

## Technical Lead / Architect

### Role Summary
Technical Leads provide architectural direction, technical decision-making, and design oversight. They help the team build solutions that are scalable, maintainable, and aligned with technical standards.

### Responsibilities
- Lead technical design and architecture decisions
- Review solutions for scalability, maintainability, and security
- Guide implementation trade-offs and technical feasibility discussions
- Provide design feedback during planning and code review
- Identify technical risks and propose mitigation strategies
- Mentor engineers and help align the team around standards and practices

### Goals
- Deliver robust, maintainable solutions
- Reduce technical debt and avoid architectural drift
- Support informed, consistent decision-making across the team

### Typical Communication
- Technical design discussions and architecture reviews
- Decision logs, code review feedback, and planning conversations
- Risk updates in cross-functional meetings and PM syncs
- Guidance during implementation tradeoff discussions

### Interaction with Existing Roles
- Advises Developers on architecture, technical constraints, and implementation choices
- Aligns with Product Managers to assess feasibility and trade-offs against roadmap goals
- Works with Project Managers to surface technical dependencies, risk, and timeline impact

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors are business or executive owners who provide strategic direction, funding, and decision-making support. They ensure the initiative aligns with business priorities and organizational objectives.

### Responsibilities
- Define strategic goals and funding priorities for the initiative
- Review progress against business outcomes and milestones
- Remove organizational blockers or approve escalated decisions
- Confirm priority, trade-offs, and high-level scope changes
- Support cross-functional alignment across business and delivery teams

### Goals
- Ensure the project delivers business value and strategic alignment
- Support timely decisions and strategic sponsorship
- Create clarity on priorities and organizational commitment

### Typical Communication
- Milestone reviews and steering meetings
- Executive updates and business status reports
- Decision-making on scope, priority, and resource support

### Interaction with Existing Roles
- Provides direction to Product Managers and Project Managers on business priorities
- Reviews and supports the work of delivery teams through sponsorship and escalation paths
- Balances strategic outcomes with operational realities surfaced by the project team

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters or Agile Coaches help teams work effectively, improve collaboration, and remove obstacles that slow delivery. They support healthy team practices and continuous improvement without replacing the accountability of delivery roles.

### Responsibilities
- Facilitate agile ceremonies such as standups, planning, reviews, and retrospectives
- Help the team identify and remove impediments and blockers
- Coach the team on agile practices and delivery habits
- Improve team flow, collaboration, and transparency
- Support continuous improvement and learning across iterations

### Goals
- Increase team effectiveness and delivery throughput
- Improve predictability and quality of delivery
- Create a healthier, more collaborative working environment

### Typical Communication
- Team ceremonies and working agreement discussions
- Retrospective facilitation and improvement planning
- Supportive conversations with PMs and Product Managers about flow and dependencies

### Interaction with Existing Roles
- Works with Project Managers to keep delivery cadence and communication aligned
- Partners with Product Managers to improve backlog clarity and prioritization flow
- Supports Developers by reducing friction and encouraging sustainable team practices

---

## Security Champion

### Role Summary
Security Champions embed security considerations into project planning and execution. They help the team reduce risk by identifying threats, ensuring secure design, and aligning with security standards.

### Responsibilities
- Identify security requirements and risk areas during planning
- Review solutions for security vulnerabilities and compliance risks
- Partner with engineering on secure design and testing practices
- Support mitigation planning for identified issues and incidents
- Help ensure release readiness accounts for security controls

### Goals
- Reduce security exposure in projects and releases
- Strengthen secure-by-default practices across the team
- Support compliance and operational confidence

### Typical Communication
- Security reviews in planning, design, and pre-release discussions
- Security issue tracking and escalation with engineering and leadership
- Security readiness checks in release and incident workflows

### Interaction with Existing Roles
- Advises Developers and Technical Leads on secure implementation patterns
- Provides PMs and Product Managers with risk information and release gating decisions
- Coordinates with incident responders and operational owners during critical issues

---

## Support / Operations Lead

### Role Summary
Support and Operations Leads represent the post-launch operational reality of the product or service. They ensure the team considers support readiness, service reliability, and customer impact throughout the lifecycle.

### Responsibilities
- Define support requirements, runbooks, and operational readiness criteria
- Represent customer support scenarios and incident handling needs
- Coordinate monitoring, observability, and response expectations
- Help plan for rollout, rollback, and post-deployment validation
- Ensure product changes are operationally sustainable

### Goals
- Reduce production disruption and support burden
- Improve operational readiness and incident response effectiveness
- Create smoother transitions from delivery to ongoing service ownership

### Typical Communication
- Release and deployment reviews
- Post-launch support check-ins and incident follow-up
- Operational readiness discussions with PMs, developers, and stakeholders

### Interaction with Existing Roles
- Works with Developers and Technical Leads to ensure the product is observable and supportable
- Supports Project Managers and Product Managers in release planning and risk communication
- Provides feedback to stakeholders on operational impact and sustainability

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Together, these roles support clearer accountability, stronger cross-functional communication, and more consistent project outcomes.

