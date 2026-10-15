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

## Additional Personas (proposed additions)

The following personas are proposed additions to improve clarity, accountability, and operational ownership across delivery lifecycles. Each entry includes a short role summary, responsibilities, and how the persona typically interacts with existing roles (Developers, Product Managers (PdM), Project Managers (PM), QA/Testing, Stakeholders).

### Release Manager

Role Summary
- Coordinates deployments and release activities to reduce risk and ensure smooth rollouts.

Responsibilities
- Own the release checklist and verification steps
- Schedule deployment windows and coordinate cross-team timing
- Ensure rollback and mitigation plans are documented and tested
- Coordinate post-release monitoring and validation

Interactions
- PM: Aligns on release timing and communications
- Developers / DevOps: Coordinates deployment execution and automation
- QA: Confirms pre-release verification and smoke tests
- Support / Customer Success: Communicates known issues and monitors customer impact

---

### Technical Lead

Role Summary
- Provides technical direction, architecture guidance, and ensures technical quality across the codebase.

Responsibilities
- Lead technical design and architecture reviews
- Mentor developers and guide implementation patterns
- Identify technical debt and propose refactoring plans
- Help estimate complex technical work and flag technical risks

Interactions
- Developers: Daily mentorship, design handoffs, and code review participation
- PM / PdM: Advise on feasibility, technical trade-offs, and effort
- QA: Define testability and provide guidance for integration testing

---

### UX Researcher / Designer

Role Summary
- Owns user research, usability validation, and interaction design to ensure the product meets user needs.

Responsibilities
- Conduct user research and usability testing
- Produce prototypes, wireframes, and design specs
- Define usability acceptance criteria and accessibility considerations
- Collaborate on design handoffs and QA of UX requirements

Interactions
- PdM: Validate product direction and success metrics with user insights
- Developers: Provide design artifacts and clarify interaction details
- QA: Plan and execute usability checks and accessibility tests

---

### Data Analyst / Insights Lead

Role Summary
- Defines measurable success, builds dashboards, and validates experiments to inform product decisions.

Responsibilities
- Define metrics and instrumentation requirements
- Build dashboards and reports for monitoring product health
- Analyze experiments and surface insights to the team
- Work with engineers to ensure accurate data collection

Interactions
- PdM: Align on success metrics and hypotheses
- PM: Provide reporting cadence and support status updates
- Developers: Specify instrumentation and event requirements

---

### Support Lead / Customer Success Liaison

Role Summary
- Represents customer-facing teams, consolidates feedback, and leads incident follow-ups and knowledge base updates.

Responsibilities
- Triage customer reports and provide context to engineering
- Own post-incident communication and follow-up actions
- Maintain FAQs and knowledge articles for common issues
- Prioritize customer-impacting bugs with PM and PdM

Interactions
- PM / PdM: Communicate customer impact and help prioritize fixes
- Developers: Provide reproducible reports and user scenarios
- QA: Collaborate on acceptance criteria for fixes that address customer issues

---

### Change Manager (for larger releases)

Role Summary
- Manages stakeholder communications, adoption planning, and training materials for significant changes.

Responsibilities
- Draft communication plans and stakeholder briefs
- Coordinate training, rollout guides, and adoption metrics
- Ensure stakeholders receive necessary materials and timelines

Interactions
- PM: Coordinate rollout plans and stakeholder engagement
- PdM: Align on messaging and feature framing
- Stakeholders: Drive adoption and feedback loops

---

### Security Champion

Role Summary
- Promotes security best practices within the delivery team and coordinates security reviews and remediation tracking.

Responsibilities
- Lead threat modeling and security risk discussions
- Coordinate security scans and ensure findings are tracked
- Work with security teams to prioritize and remediate issues
- Advocate for secure coding practices and dependency hygiene

Interactions
- Developers: Share remediation guidance and participate in code review for security-sensitive changes
- QA: Ensure security test coverage and validation steps are included
- Security on-call / Security team: Escalate and coordinate critical issues

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

