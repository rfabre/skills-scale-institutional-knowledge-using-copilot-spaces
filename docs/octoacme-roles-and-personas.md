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

## QA / Quality Assurance Lead

### Role Summary
QA leads define and execute testing strategies, validate acceptance criteria, and ensure quality standards are met before release. They work closely with developers and product managers to maintain high quality throughout the delivery lifecycle.

### Responsibilities
- Design test plans and QA approach for features
- Execute manual and automated testing
- Validate acceptance criteria before merging PRs
- Identify and track quality issues and regressions
- Report quality metrics and recommend release readiness
- Collaborate with developers on testability and test coverage
- Define and maintain QA standards and best practices

### Goals
- Deliver high-quality, user-tested software
- Reduce production defects and regressions
- Maintain high test coverage and observability
- Enable confident, risk-managed releases

### Typical Communication
- Test plans and QA approach during sprint planning
- QA status updates in daily standups
- Bug reports and test results in code reviews
- Release verification sign-off and quality metrics reporting
- Participation in retrospectives on quality issues

### Interaction with Existing Roles
- **Developers**: Reviews code for testability; provides feedback on test coverage; collaborates on bug triage
- **Product Managers**: Validates acceptance criteria; flags quality risks that impact release readiness
- **Project Managers**: Reports quality metrics and readiness status; escalates blockers
- **Technical Leads**: Advises on testing strategies for complex technical solutions

---

## Sponsor / Stakeholder

### Role Summary
Sponsors provide business context, set strategic priorities, and authorize resource allocation. They represent business needs and ensure project alignment with organizational goals. Sponsors make go/no-go decisions and remove cross-organizational blockers.

### Responsibilities
- Provide business problem statement and success metrics
- Prioritize initiatives relative to other work
- Approve scope changes and resource trade-offs
- Receive regular status updates and escalation notifications
- Make go/no-go decisions at key project gates
- Communicate project outcomes to broader leadership
- Remove organizational blockers and dependencies

### Goals
- Maximize ROI and business value
- Ensure projects align with business strategy
- Minimize project risk and delays
- Enable data-driven business decisions

### Typical Communication
- Project kickoff and alignment sessions
- Milestone reviews and gate approvals
- Escalation notifications for critical issues
- Stakeholder briefings and executive updates
- Risk and issue escalation paths

### Interaction with Existing Roles
- **Product Managers**: Collaborates on business requirements and success metrics
- **Project Managers**: Receives status updates; approves scope and resource changes
- **Developers**: Provides business context for features; reviews high-level progress
- **All Roles**: Ultimate decision authority for trade-offs and go/no-go decisions

---

## Technical Lead / Architect

### Role Summary
Technical Leads provide architectural guidance, technical mentoring, and design review. They ensure solutions are scalable, maintainable, and align with platform standards. They enable team growth and reduce technical risk.

### Responsibilities
- Review and validate technical design and architecture
- Mentor developers on technical standards and best practices
- Identify technical risks and propose mitigations
- Guide decisions on frameworks, libraries, and technology choices
- Participate in code reviews for complex or risky changes
- Drive technical excellence and reduce technical debt
- Ensure solutions align with platform standards and long-term vision

### Goals
- Maintain technical quality and consistency
- Reduce technical debt and system complexity
- Enable team growth and knowledge sharing
- Ensure scalability and maintainability of solutions

### Typical Communication
- Design review sessions during planning
- Code review comments on complex changes
- Technical documentation and architecture decision records (ADRs)
- Mentoring sessions and technical guidance
- Risk identification and mitigation planning

### Interaction with Existing Roles
- **Developers**: Provides technical guidance; reviews code; mentors on best practices
- **Product Managers**: Collaborates on feasibility; advises on technical trade-offs
- **Project Managers**: Identifies technical risks; estimates impact on timeline
- **QA Leads**: Advises on testability and test strategy for complex solutions

---

## DevOps / Release Engineer

### Role Summary
DevOps engineers manage infrastructure, CI/CD pipelines, and release processes. They enable reliable, automated deployments and operational excellence. They ensure systems are observable, scalable, and recoverable.

### Responsibilities
- Maintain and improve CI/CD pipelines
- Manage infrastructure and deployment environments
- Coordinate release planning and deployment execution
- Monitor production systems and respond to incidents
- Document and automate operational runbooks
- Ensure system observability and incident response capabilities
- Manage environment parity and configuration management

### Goals
- Enable fast, reliable releases
- Maintain high system availability and performance
- Reduce manual toil and operational overhead
- Minimize deployment risk and incident impact

### Typical Communication
- Deployment checklists and runbooks
- CI/CD status updates and pipeline health reports
- Incident coordination and response
- Infrastructure change notifications
- Release verification and post-deployment monitoring

### Interaction with Existing Roles
- **Developers**: Collaborates on CI/CD pipeline improvements; supports deployment troubleshooting
- **Project Managers**: Coordinates release timing and deployment windows
- **QA Leads**: Collaborates on pre-release verification and smoke testing
- **Technical Leads**: Advises on infrastructure design and operational standards

---

## Design / User Experience Lead

### Role Summary
Design leads define user-centered solutions, create design specifications, and validate usability. They ensure features are intuitive, accessible, and meet user needs. They bridge the gap between user research and implementation.

### Responsibilities
- Conduct user research and define user requirements
- Create wireframes, prototypes, and design specifications
- Validate design decisions through user testing
- Collaborate with engineering on implementation feasibility
- Provide design review and feedback on features
- Ensure design consistency and accessibility standards
- Guide design decisions based on user research and metrics

### Goals
- Deliver intuitive, user-centric solutions
- Improve user satisfaction and adoption
- Maintain design consistency across products
- Reduce user friction and support burden

### Typical Communication
- Design specs and prototypes during planning
- Design reviews during development
- User research findings in roadmap discussions
- Feedback on feature implementations and QA sign-off
- Design system and pattern library maintenance

### Interaction with Existing Roles
- **Product Managers**: Collaborates on user needs and feature prioritization
- **Developers**: Reviews implementation for design fidelity; iterates on UX issues
- **QA Leads**: Validates design against user research and acceptance criteria
- **Project Managers**: Advises on design timeline and resource needs
- **Technical Leads**: Collaborates on feasibility of design solutions

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When resolving conflicts or trade-offs, reference the goals and responsibilities of each persona to guide decision-making.
