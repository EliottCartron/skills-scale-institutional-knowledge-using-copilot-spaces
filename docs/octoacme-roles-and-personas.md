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
QA/Testing Leads ensure product quality through comprehensive testing strategies, test automation, and acceptance validation. They collaborate with developers and product managers to define testability requirements and quality standards.

### Responsibilities
- Define and maintain test plans and test case libraries
- Collaborate on acceptance criteria and Definition of Done
- Execute manual and automated testing during sprints and pre-release phases
- Identify and triage defects with clear severity and reproduction steps
- Validate that acceptance criteria are met before feature handoff
- Support smoke tests and post-deployment verification

### Goals
- Deliver high-quality software with minimal production defects
- Enable fast feedback cycles through efficient testing
- Prevent quality regressions through automation and strategic testing

### Typical Communication
- Sprint planning and backlog refinement
- QA status updates during standups
- Defect reports and test result summaries
- Release readiness sign-off

### Interactions with Other Roles
- Works closely with **Developers** to understand implementation details and define test strategies
- Collaborates with **Product Managers** to validate acceptance criteria align with user expectations
- Partners with **Project Managers** on release timelines and quality gates
- Supports **Technical Architects** in planning testability requirements during design reviews

---

## Security / Compliance Officer

### Role Summary
Security and Compliance Officers ensure that projects meet security, privacy, and regulatory requirements. They provide guidance on secure design, review code and architecture for vulnerabilities, and manage security incident response.

### Responsibilities
- Review security and privacy requirements during project planning
- Participate in design reviews to identify security risks
- Define and monitor security testing and scanning requirements in CI
- Review and approve security mitigations and remediation timelines
- Manage security incident escalation and response
- Ensure compliance with regulatory and organizational policies

### Goals
- Prevent security incidents and data breaches
- Maintain compliance with regulatory frameworks
- Build security into the development lifecycle

### Typical Communication
- Security reviews during project planning and design phases
- CI/CD security scan results and remediation tracking
- Incident response and escalation communication
- Compliance audit reports and evidence collection

### Interactions with Other Roles
- Advises **Technical Architects** on secure design patterns and architectural security considerations
- Partners with **Developers** on secure coding practices and vulnerability remediation
- Reviews project scope with **Product Managers** to identify security and privacy implications
- Escalates critical security issues to **Sponsors** and **Project Managers** for priority and resource decisions

---

## Technical Architect

### Role Summary
Technical Architects define the system design, technical strategy, and integration patterns. They guide engineering teams on technology choices and ensure scalability, reliability, and maintainability of solutions.

### Responsibilities
- Design system architecture and integration points
- Evaluate technology trade-offs and recommend solutions
- Review technical designs for scalability and reliability
- Identify technical risks and propose mitigations
- Support cross-team dependency mapping and integration planning
- Mentor engineers on architectural patterns and best practices

### Goals
- Enable rapid, reliable delivery through sound technical design
- Minimize technical debt and rework
- Support scalability and long-term maintainability

### Typical Communication
- Technical design reviews and architecture decision records
- Integration planning and dependency coordination
- Risk assessments and mitigation strategies
- Mentoring during code review and design discussions

### Interactions with Other Roles
- Collaborates with **Product Managers** to understand scope and requirements early in planning
- Guides **Developers** on implementation approaches and technical best practices
- Works with **QA/Testing Leads** to design systems with testability and observability in mind
- Partners with **Security/Compliance Officers** on secure design principles and regulatory considerations
- Communicates technical risks and dependencies to **Project Managers** and **Sponsors**

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, remove impediments, and help teams optimize their delivery processes. They serve as process guides and enablers rather than task managers.

### Responsibilities
- Facilitate sprint planning, daily standups, retrospectives, and sprint reviews
- Identify and escalate team impediments and blockers
- Coach the team on agile principles and ceremonies
- Track sprint velocity and burndown metrics
- Support continuous improvement initiatives from retrospectives
- Protect the team from scope creep and external distractions

### Goals
- Maximize team efficiency and delivery predictability
- Foster continuous improvement and psychological safety
- Remove obstacles to flow and reduce cycle time

### Typical Communication
- Sprint ceremony facilitation and notes
- Impediment escalation and resolution tracking
- Retrospective action item follow-up
- Metrics and velocity trending reports

### Interactions with Other Roles
- Facilitates communication between **Developers**, **Product Managers**, and **Project Managers** during sprint planning and reviews
- Escalates blockers raised by any team member to **Project Managers** and **Sponsors** when needed
- Supports **Team Members** in identifying and removing impediments to delivery
- Tracks action items from retrospectives and ensures accountability across all roles

---

## Sponsor / Executive Stakeholder

### Role Summary
Sponsors and executive stakeholders provide business context, funding, and strategic direction for projects. They approve scope and priority decisions and serve as escalation points for business-level risks.

### Responsibilities
- Define business goals and success metrics for the project
- Provide budget and resource approval
- Make priority and scope trade-off decisions
- Serve as escalation point for business and organizational blockers
- Review milestone and release readiness from a business perspective
- Communicate project status and outcomes to executive leadership

### Goals
- Ensure projects deliver measurable business value
- Minimize business risk and maximize ROI
- Enable strategic alignment across the organization

### Typical Communication
- Monthly stakeholder status briefings
- Milestone approval and go/no-go decisions
- Risk and issue escalation
- Post-release outcome and success metrics reporting

### Interactions with Other Roles
- Works with **Product Managers** to align project goals with business strategy and success metrics
- Reviews **Project Manager** status reports and escalations to make go/no-go decisions at key milestones
- Receives **Technical Architect** risk assessments and technology trade-off recommendations
- Approves security and compliance decisions from **Security/Compliance Officers** based on business impact
- Supports **Project Managers** in removing organizational blockers and enabling resource allocation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
