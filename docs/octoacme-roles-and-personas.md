# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Roles describe areas of accountability, not necessarily separate people. Assign or combine them according to project size and team structure, while keeping decision ownership and handoffs explicit.

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

## UX / Product Designer

### Role Summary
The UX / Product Designer researches user needs and shapes accessible, usable workflows and experiences. The role may be shared with a Product Manager or another design contributor on smaller teams.

### Responsibilities
- Conduct or synthesize user research and translate findings into design opportunities
- Create user flows, prototypes, and design specifications
- Define usability, accessibility, and design acceptance considerations
- Validate designs with users and incorporate feedback
- Communicate design constraints and open questions early

### Decision Authority and Deliverables
- Owns the interaction and visual design recommendations within agreed product goals and design standards
- Produces research findings, user flows, prototypes, and design specifications
- Partners with the Product Manager when user evidence suggests revisiting scope or priorities; product priority remains with the Product Manager

### Interactions and Handoffs
- Partners with the Product Manager to connect user needs, product outcomes, and backlog acceptance criteria
- Works with Developers and the Tech Lead / Architect to assess feasibility and preserve design intent during implementation
- Collaborates with QA / Testing to turn usability and accessibility considerations into test scenarios
- Shares research and design decisions with stakeholders, who provide domain input and feedback

---

## Tech Lead / Architect

### Role Summary
The Tech Lead / Architect guides technical design and helps ensure the solution is secure, maintainable, testable, and aligned with system architecture. On smaller teams, this accountability may be held by a senior Developer.

### Responsibilities
- Guide technical design, integration choices, and architecture decisions
- Identify and communicate technical risks, dependencies, and non-functional requirements
- Support estimation and decomposition of technically complex work
- Promote maintainable engineering practices, security, reliability, and testability
- Document consequential technical decisions and trade-offs

### Decision Authority and Deliverables
- Owns technical recommendations and decisions within the team's agreed architecture and engineering standards
- Produces or reviews design notes, interface and integration plans, and technical risk mitigations
- Escalates decisions with product, schedule, or cross-team impact to the Product Manager and Project Manager as appropriate

### Interactions and Handoffs
- Collaborates with Developers on implementation approach, code review, and technical problem-solving
- Advises the Product Manager on feasibility and technical trade-offs without taking ownership of product priorities
- Works with the Project Manager to surface dependencies, sequencing needs, and technical risks for the plan and risk register
- Partners with QA / Testing to make work testable and clarify technical coverage; supports the UX / Product Designer on feasibility and implementation constraints
- Provides technical context to reviewers and stakeholders when decisions affect interfaces, reliability, or future work

---

## Delivery / Iteration Lead

### Role Summary
The Delivery / Iteration Lead helps the team run effective iteration ceremonies and maintain a clear flow of work. This facilitation responsibility may be performed by the Project Manager or another team member; it does not confer product-priority ownership.

### Responsibilities
- Facilitate iteration planning, standups, reviews, and retrospectives as agreed by the team
- Help keep work visible and surface blockers, dependencies, and risks early
- Support the team in clarifying readiness, work-in-progress, and completion expectations
- Capture decisions and improvement actions and help follow up on them
- Encourage continuous improvement and balanced team participation

### Decision Authority and Deliverables
- Owns facilitation and team-workflow practices agreed for the iteration, not scope or product-priority decisions
- Produces or maintains ceremony notes, blocker follow-ups, and retrospective action tracking
- Helps the team make progress visible on the project board and escalates unresolved impediments

### Interactions and Handoffs
- Coordinates with the Project Manager on milestones, dependencies, risks, and escalations; either may facilitate ceremonies, with responsibilities agreed explicitly
- Works with the Product Manager to ensure prioritized work and acceptance criteria are understood before iteration commitments
- Partners with Developers, QA / Testing, and the Tech Lead / Architect to identify capacity or technical blockers and clarify readiness
- Shares review outcomes and retrospective actions with the Product Manager, Project Manager, and relevant stakeholders

---

## Operations / SRE or Release Manager

### Role Summary
Operations / SRE or Release Manager provides operational readiness and release coordination so changes can be deployed, observed, and recovered safely. The role may be an operations specialist, a rotating team responsibility, or shared with a Developer on smaller teams.

### Responsibilities
- Advise on reliability, service-level expectations, observability, and operational risks
- Define or coordinate deployment readiness checks, runbooks, and release verification
- Ensure rollback or mitigation plans are clear and practical
- Coordinate deployment timing and operational communications with affected teams
- Support incident response, post-release monitoring, and follow-up learning

### Decision Authority and Deliverables
- Owns operational readiness recommendations and release coordination within the team's release policy; production approval authority follows the organization's defined policy
- Produces or maintains deployment checklists, operational runbooks, monitoring/alerting requirements, and rollback plans
- Can raise a readiness concern and request appropriate review or escalation; product scope and project priority remain with the Product Manager and Project Manager respectively

### Interactions and Handoffs
- Works with Developers and the Tech Lead / Architect to ensure services are deployable, observable, and recoverable
- Partners with QA / Testing on release checks and smoke-test results, and with the Project Manager on deployment windows, dependencies, and stakeholder communications
- Advises the Product Manager on release risks that could affect customer outcomes or rollout decisions
- Coordinates with support and stakeholders during release communications and incident response, then contributes operational findings to the retrospective

---

## QA / Testing

### Role Summary
QA / Testing validates that delivered work meets acceptance criteria and expected quality. Testing may be performed by dedicated QA personnel, Developers, or a shared team depending on the project.

### Responsibilities
- Develop and execute test approaches for functional and critical end-to-end flows
- Validate work against acceptance criteria and report defects with clear reproduction details
- Identify quality risks and recommend suitable test coverage
- Coordinate manual, integration, and automated testing as appropriate

### Interactions and Handoffs
- Works with the Product Manager to clarify acceptance criteria and with Developers and the Tech Lead / Architect to improve testability
- Partners with the UX / Product Designer on usability and accessibility scenarios
- Shares test status, defects, and release risks with the Project Manager and Operations / SRE or Release Manager
- Provides evidence and outstanding quality concerns to stakeholders at review or release gates

---

## Stakeholders

### Role Summary
Stakeholders represent the business, customer, support, or partner perspectives affected by the project. They provide input and decisions when their expertise or authority is needed; they do not replace the named owners of product, delivery, or technical decisions.

### Responsibilities
- Share goals, constraints, domain knowledge, and feedback
- Review proposed outcomes and deliverables at agreed checkpoints
- Make or obtain business decisions and approvals within their authority
- Raise impact, readiness, or dependency concerns through agreed communication paths

### Interactions and Handoffs
- Work with the Product Manager to provide context and feedback that informs outcomes and priorities
- Coordinate with the Project Manager on updates, dependencies, decisions, and escalations
- Provide domain input to the UX / Product Designer, Developers, QA / Testing, and Operations / SRE or Release Manager as relevant
- Receive release and incident communications from the Project Manager or designated operational contact

---

## Role Assignment Guidance

- Assign roles based on project scope, risk, and team structure; not every project needs a separate person for every role.
- A person may hold more than one role, but document who owns each decision and deliverable, especially product priority, delivery coordination, technical design, quality validation, and operational readiness.
- When responsibilities are combined, protect appropriate review and escalation paths so that critical decisions and quality checks are not silently skipped.
- Confirm role assignments and handoffs during initiation and planning, and revisit them when scope, team composition, or release risk changes.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
