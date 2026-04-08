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

## QA / Testing Engineer

### Role Summary
QA Engineers validate that features meet acceptance criteria and quality standards before release. They design test plans, execute manual and automated tests, and act as the quality gate for the team.

### Responsibilities
- Review acceptance criteria and define test cases
- Execute functional, regression, and exploratory testing
- Report, triage, and track defects through resolution
- Maintain and extend automated test suites
- Participate in sprint planning to ensure testability

### Goals
- Prevent critical defects from reaching production
- Improve test coverage and reduce time to detect bugs
- Enable fast, reliable releases through automation

### Typical Communication
- Daily standup: surface blockers or test failures
- Sprint planning and backlog refinement with PM and Developers
- Defect reports and test results shared with the full team
- Pre-release sign-off to PM and Product Manager

---

## Scrum Master

### Role Summary
The Scrum Master enables the team to follow Agile/Scrum practices, facilitates ceremonies, removes impediments, and protects the team from distractions. They serve as a coach for continuous improvement and delivery rhythm.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Identify and remove blockers and impediments
- Coach the team on Agile/Scrum practices and principles
- Shield the team from external interruptions during a sprint
- Track team velocity and highlight trends for planning
- Escalate systemic issues to the Project Manager or leadership

### Goals
- Sustain a healthy, predictable delivery cadence
- Foster a culture of continuous improvement and psychological safety
- Reduce cycle time and eliminate recurring blockers

### Typical Communication
- Daily standup facilitation with Developers and QA
- Weekly sync with Project Manager to align on team health and risks
- Retrospective action items tracked with the full team
- Impediment escalations to PM and Product Manager as needed

---

## Technical Writer

### Role Summary
The Technical Writer owns the creation and maintenance of technical documentation, user guides, release notes, and internal process write-ups. They ensure information is accurate, consistent, and accessible to both technical and non-technical audiences.

### Responsibilities
- Draft and maintain user-facing documentation, API references, and internal guides
- Review and edit content contributed by Developers, QA, and Product Managers
- Align documentation releases with product releases
- Establish and enforce documentation standards and templates
- Collaborate with Product Manager to document feature specifications and changelogs

### Goals
- Ensure all shipped features have clear, accurate documentation
- Reduce support burden by making self-service information discoverable
- Maintain a consistent voice and style across all project docs

### Typical Communication
- Sprint review attendance to capture feature details
- Direct collaboration with Developers and QA to validate technical accuracy
- Weekly sync with Product Manager to plan documentation milestones
- Release coordination with PM to publish docs alongside deployments

---

## UX Designer

### Role Summary
The UX Designer is responsible for user experience research, interaction design, and UI design. They translate user needs and business goals into intuitive workflows and interfaces, ensuring the product is usable and valuable.

### Responsibilities
- Conduct user research, interviews, and usability testing
- Create wireframes, prototypes, and high-fidelity designs
- Define user flows and interaction patterns
- Collaborate with Developers on feasibility and implementation of designs
- Maintain a design system and ensure visual consistency

### Goals
- Deliver designs that meet user needs and align with business objectives
- Reduce usability issues identified post-launch
- Enable Developers to implement designs accurately with minimal rework

### Typical Communication
- Sprint planning with Product Manager and Developers to scope design work
- Design reviews and critiques with Developers and QA
- User research readouts shared with Product Manager and stakeholders
- Handoff documentation (annotated designs, component specs) to Developers

---

## DevOps Engineer

### Role Summary
DevOps Engineers automate code deployments, manage environments, ensure CI/CD reliability, and monitor operational health. They bridge the gap between development and operations to enable fast, stable releases.

### Responsibilities
- Design, implement, and maintain CI/CD pipelines
- Manage cloud infrastructure, environments (dev, staging, production), and access controls
- Monitor system health, alerts, and on-call response
- Automate repetitive operational tasks and infrastructure provisioning
- Coordinate deployment windows and rollback procedures with PM and Developers
- Implement and maintain security scanning and compliance checks in pipelines

### Goals
- Enable frequent, low-risk deployments
- Minimize environment downtime and mean time to recovery (MTTR)
- Provide reliable observability for all production systems

### Typical Communication
- Sprint planning with PM and Developers to plan infrastructure work
- Pre-release coordination with PM to schedule deployment windows
- Incident triage and post-mortems with Developers and QA
- Regular pipeline and infrastructure health updates at weekly delivery syncs

---

## Business Analyst

### Role Summary
The Business Analyst elicits, analyzes, and documents requirements, bridging business stakeholders and the technical delivery team. They translate business needs into clear, actionable requirements and ensure solutions deliver expected outcomes.

### Responsibilities
- Facilitate requirements workshops and stakeholder interviews
- Document functional and non-functional requirements, user stories, and acceptance criteria
- Maintain and prioritize the requirements backlog in partnership with the Product Manager
- Analyze current-state processes and identify improvement opportunities
- Validate delivered solutions against documented requirements
- Manage scope change requests and assess impact

### Goals
- Ensure development work directly addresses validated business needs
- Reduce rework caused by unclear or missing requirements
- Enable traceable links between business goals and delivered features

### Typical Communication
- Requirements workshops with stakeholders and Product Manager
- Backlog refinement sessions with Developers and QA
- Weekly status updates with PM on requirements completeness
- Acceptance testing coordination with QA and Product Manager before release

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [Role Interaction Matrix](./octoacme-role-interaction-matrix.md) for a summary of how roles collaborate across the project lifecycle.
- See [Role Assignment Checklist](./octoacme-role-assignment-checklist.md) for guidance on confirming role owners at project initiation and planning.

