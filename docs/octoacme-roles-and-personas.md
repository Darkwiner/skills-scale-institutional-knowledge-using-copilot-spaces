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

## Quality Assurance Lead

### Role Summary
QA Leads own quality strategy and acceptance validation for projects. They define testing approaches, coordinate QA resources, and ensure features meet acceptance criteria and quality standards before release.

### Responsibilities
- Define and maintain test plans and QA strategies per project
- Coordinate manual and automated testing efforts
- Validate acceptance criteria for user stories and features
- Identify quality risks and propose mitigations
- Coordinate with developers on test coverage and CI validation
- Participate in release readiness reviews

### Goals
- Deliver high-quality, defect-free releases
- Reduce rework and production incidents
- Enable fast feedback loops during development

### Typical Communication
- Weekly QA sync with development and PM teams
- Test plan reviews during sprint planning
- Defect triage during daily standups
- Release readiness sign-off before deployment

### Interaction with Existing Roles
- **With Developers:** Collaborate on test coverage, automation strategies, and defect resolution in daily standups and code reviews
- **With Product Managers:** Review acceptance criteria, validate feature alignment with requirements, and participate in backlog refinement
- **With Project Managers:** Coordinate testing timelines, report quality metrics and risks, and participate in release planning

---

## Stakeholder / Sponsor

### Role Summary
Sponsors and key stakeholders provide business context, approve investments, and receive status updates. They represent customer needs and business priorities to the project team.

### Responsibilities
- Define business objectives and success metrics
- Approve project charter and resource allocation
- Participate in kickoff and key decision gates
- Receive regular status updates and escalations
- Provide feedback on priorities and trade-offs
- Sign off on releases and business outcomes

### Goals
- Align project delivery with business strategy
- Ensure customer value and ROI
- Enable rapid escalation and decision-making

### Typical Communication
- Monthly stakeholder status updates
- Ad-hoc escalations for blockers and decisions
- Milestone reviews and gate approvals
- Post-release outcome reviews

### Interaction with Existing Roles
- **With Project Managers:** Receive and approve milestone updates, escalations, and key decisions; provide business context and priorities
- **With Product Managers:** Align on business objectives, success metrics, and priorities; provide customer/market feedback
- **With Development Team:** Participate in gate reviews and release sign-offs; provide business rationale for trade-offs

---

## Technical Lead / Architect

### Role Summary
Technical Leads provide architecture guidance, technical strategy, and design reviews. They ensure solutions are scalable, maintainable, and aligned with system standards.

### Responsibilities
- Review and guide technical design and architecture
- Identify technical risks and propose mitigations
- Mentor developers on best practices and standards
- Coordinate integration across components and teams
- Participate in design and code reviews
- Assist in estimating technical complexity

### Goals
- Ensure technical excellence and maintainability
- Minimize rework and technical debt
- Accelerate feature delivery through good design

### Typical Communication
- Technical design reviews during planning
- Architecture discussions during kickoff
- Code and design review comments
- Ad-hoc technical guidance

### Interaction with Existing Roles
- **With Developers:** Mentor on best practices, review code and design decisions, guide technical problem-solving
- **With Project Managers:** Assess technical complexity and risks, participate in planning to identify dependencies and timeline implications
- **With Product Managers:** Discuss technical trade-offs, feasibility of requirements, and long-term system health vs. feature velocity

---

## Security Officer

### Role Summary
Security Officers ensure projects meet security standards and compliance requirements. They conduct security reviews, coordinate vulnerability scanning, and guide secure development practices.

### Responsibilities
- Review security requirements and threat models
- Coordinate security scanning and penetration testing
- Validate secure coding practices in code reviews
- Manage security incidents and disclosures
- Provide guidance on compliance and data protection
- Participate in release security sign-off

### Goals
- Prevent security vulnerabilities and breaches
- Ensure compliance with organizational and regulatory standards
- Build security awareness across teams

### Typical Communication
- Security requirements review during planning
- Security scanning results in CI/CD pipeline
- Incident response and post-mortems
- Quarterly security training and updates

### Interaction with Existing Roles
- **With Developers:** Review code for security practices, guide threat modeling, participate in security-focused code reviews
- **With Project Managers:** Identify security risks and compliance requirements, participate in release security sign-off
- **With QA Leads:** Coordinate security testing strategies, validate security test coverage, and defect triage for security issues

---

## Operations / Release Engineer

### Role Summary
Operations/Release Engineers manage deployment infrastructure, release pipelines, and production monitoring. They enable reliable, repeatable deployments and rapid incident response.

### Responsibilities
- Maintain and optimize CI/CD pipelines
- Coordinate and execute production deployments
- Set up monitoring, logging, and alerting
- Manage rollbacks and incident response
- Document runbooks and operational procedures
- Validate release readiness and post-deploy verification

### Goals
- Enable fast, reliable deployments with minimal downtime
- Provide visibility into production health
- Reduce incident mean time to resolution (MTTR)

### Typical Communication
- Release planning and deployment window scheduling
- Post-deploy verification and status updates
- Incident response coordination
- Monitoring and observability dashboards

### Interaction with Existing Roles
- **With Developers:** Coordinate on release procedures, runbooks, and post-deployment troubleshooting
- **With Project Managers:** Participate in release planning, provide deployment readiness assessments, communicate deployment status
- **With QA Leads:** Validate release readiness, coordinate smoke testing, provide production environment verification

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Review the "Interaction with Existing Roles" sections to understand cross-functional collaboration patterns and communication expectations.
