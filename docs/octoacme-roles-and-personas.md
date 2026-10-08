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

## Product Leads

### Role Summary
Product Leads serve as strategic bridges between Product Managers and stakeholder alignment, ensuring business priorities are reflected in technical delivery. They approve major decisions and escalate competing priorities or risks to sponsors.

### Responsibilities
- Align product strategy with business objectives and stakeholder needs
- Approve scope changes and feature trade-offs
- Escalate critical decisions and priority conflicts to sponsors
- Review and validate acceptance criteria against business goals
- Represent the product voice in cross-functional planning and retrospectives

### Goals
- Ensure product decisions drive measurable business value
- Reduce scope creep and maintain alignment with strategic priorities
- Facilitate fast, informed decision-making across teams
- Bridge product vision with technical execution

### Typical Communication
- Weekly alignment with PM and Project Manager
- Milestone approvals and stakeholder briefings
- Priority escalations and dependency reviews
- Acceptance criteria reviews and release sign-offs

---

## Technical Leads / Engineering Leads

### Role Summary
Technical Leads guide the technical architecture and design of features, mentor developers, and identify technical risks and capacity constraints. They serve as the engineering voice in planning and ensure technical feasibility of business commitments.

### Responsibilities
- Guide technical architecture and design decisions
- Mentor and support developers in their growth
- Identify technical risks, dependencies, and mitigation strategies
- Assess team capacity and technical feasibility during planning
- Conduct technical design reviews and code reviews
- Propose technical improvements and optimization opportunities

### Goals
- Deliver technically sound, scalable solutions
- Build team capability and reduce knowledge silos
- Minimize technical debt and rework
- Ensure sustainable velocity and maintainability

### Typical Communication
- Technical design documents and architecture reviews
- Sprint planning and capacity assessments
- Code reviews and technical mentoring
- Risk register updates for technical blockers
- Weekly sync with Product Manager and Project Manager

---

## QA / Testing Leads

### Role Summary
QA/Testing Leads own quality standards, test strategy, and acceptance criteria validation. They ensure features meet quality gates before release and coordinate comprehensive testing across manual and automated approaches.

### Responsibilities
- Define and maintain test strategy and quality standards
- Validate features against acceptance criteria
- Coordinate manual and automated testing efforts
- Report defect metrics and quality trends
- Identify gaps in test coverage and propose improvements
- Conduct smoke tests and release verification
- Document known issues and workarounds

### Goals
- Deliver high-quality features with minimal defects
- Reduce time-to-quality and testing bottlenecks
- Ensure consistent acceptance criteria validation
- Maintain visibility into product quality metrics

### Typical Communication
- Quality reports and defect metrics
- Test plans and test case documentation
- Daily standups and sprint reviews
- Release verification and smoke test results
- Acceptance criteria reviews with Product Manager

---

## Stakeholders

### Role Summary
Stakeholders represent different organizational perspectives and interests in project outcomes. They provide inputs on priorities, approve budgets/resources, and receive regular updates on progress and risks.

### Subcategories
- **Executives/Sponsors:** Set strategic direction, approve budgets, escalation point for business-impacting decisions
- **Department Leads:** Provide functional guidance (e.g., Sales, Support, Finance), ensure cross-functional alignment
- **End Users:** Provide user research and feedback on usability and customer impact
- **Support/Operations:** Represent customer impact and operational readiness requirements

### Responsibilities (by category)
- **Executives/Sponsors:** Approve go/no-go decisions, allocate resources, remove organizational blockers
- **Department Leads:** Ensure alignment with departmental goals, provide subject-matter expertise, coordinate cross-functional dependencies
- **End Users:** Provide use-case validation and feedback, participate in demos and user testing
- **Support/Operations:** Report customer-facing impact, identify operational gaps, support deployment and rollout

### Goals
- Align project delivery with business strategy and customer needs
- Maintain transparency on progress and risks
- Enable fast decision-making and issue resolution
- Ensure solutions are operationally viable and customer-focused

### Typical Communication
- Monthly stakeholder updates and roadmap briefings
- Milestone approvals and go/no-go gates
- Risk escalations and decision requests
- Demo and feedback sessions
- Incident and blocker escalation

---

## Security

### Role Summary
Security owns security requirements, threat assessment, and incident response. They conduct security reviews of features, ensure compliance with security standards, and lead incident response for security-related issues.

### Responsibilities
- Define and enforce security requirements for features
- Conduct security code reviews and threat assessments
- Configure and monitor security scanning in CI/CD pipelines
- Review acceptance criteria for security-relevant features
- Lead security incident response and post-incident reviews
- Maintain security runbooks and incident playbooks
- Provide security guidance and training to the team

### Goals
- Prevent security vulnerabilities and breaches
- Ensure compliance with security standards and regulations
- Reduce time-to-remediation for security issues
- Build security awareness and practices across the team

### Typical Communication
- Security requirements in feature specifications
- Security review results and scan reports
- Incident alerts and response coordination
- Security trainings and awareness updates
- Post-incident retrospectives and action items

---

## Interaction Map: How Personas Work Together

| Initiator | Primary Collaborators | Key Decision Points |
|-----------|----------------------|-------------------|
| **Product Manager** | Product Lead, Project Manager, Developers | What to build, prioritization, success metrics |
| **Product Lead** | Product Manager, Sponsor/Executives, Project Manager | Priority conflicts, scope changes, business alignment |
| **Technical Lead** | Developers, Project Manager, Product Manager | Technical feasibility, architecture, capacity |
| **Project Manager** | All roles | Timeline, dependencies, risk management, communication |
| **QA Lead** | Developers, Product Manager, Project Manager | Quality gates, test coverage, release readiness |
| **Security** | Developers, Product Manager, QA Lead | Security requirements, vulnerability remediation |
| **Stakeholders** | Project Manager, Product Lead, Project Sponsor | Approvals, resource allocation, escalations |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the interaction map when modeling cross-functional workflows and decision-making.
