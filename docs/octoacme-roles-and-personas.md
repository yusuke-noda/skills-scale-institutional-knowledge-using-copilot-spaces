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

## UX/UI Designer

### Role Summary
UX/UI Designers craft intuitive user experiences by translating requirements and user research into wireframes, mockups, and final design assets. They ensure usability and visual consistency across the product.

### Responsibilities
- Conduct user research and usability testing to inform design decisions
- Create wireframes, prototypes, and high-fidelity design assets
- Define and maintain the product's design system and style guide
- Review implemented UI to verify design fidelity
- Iterate on designs based on user feedback and QA findings

### Goals
- Deliver user experiences that are intuitive, accessible, and visually consistent
- Reduce design-to-development rework through clear handoff artifacts
- Validate designs with real users before full implementation

### Typical Communication
- Design reviews and critique sessions with Developers and Product Managers
- Figma/design tool links shared in issues and PRs
- Usability testing reports shared with Product Managers

### Interactions with Existing Roles
- **Developers**: Hand off design assets and specs; review implemented UI for fidelity; discuss technical feasibility of proposed designs.
- **Product Managers**: Align on user needs and success criteria; incorporate product strategy into design decisions; present design options for prioritization.
- **Project Managers**: Provide design milestone estimates; flag dependency on content or copy; alert when design reviews are blocking development.

---

## QA/Test Engineer

### Role Summary
QA/Test Engineers own quality assurance across the delivery lifecycle. They develop test strategies, execute test plans, identify defects, and maintain test automation to ensure product reliability and acceptance criteria are met.

### Responsibilities
- Author and maintain test plans, test cases, and acceptance test suites
- Execute manual and automated tests across functional and non-functional requirements
- Report, track, and verify resolution of defects
- Maintain and extend test automation frameworks and CI test suites
- Define and uphold the Definition of Done quality gates

### Goals
- Prevent defects from reaching production through early and continuous testing
- Increase automation coverage to reduce manual regression effort
- Ensure acceptance criteria are objectively verified before release

### Typical Communication
- Bug reports and defect tickets linked to development issues
- Test summary reports shared with Project Manager and Product Manager before release
- Participation in sprint planning to flag testability gaps in acceptance criteria

### Interactions with Existing Roles
- **Developers**: Collaborate on testability and test automation; report and triage defects; review acceptance criteria and edge cases during sprint planning.
- **Product Managers**: Clarify acceptance criteria and priority of defects; report test coverage and quality metrics to support release decisions.
- **Project Managers**: Align on release readiness based on test results; raise risks when quality gates are not met; update task status on the project board.

---

## DevOps Engineer

### Role Summary
DevOps Engineers design and maintain the CI/CD pipelines, infrastructure, and operational tooling that enable reliable, repeatable software delivery. They bridge development and operations to improve deployment frequency and system reliability.

### Responsibilities
- Design, build, and maintain CI/CD pipelines for build, test, and deployment automation
- Manage infrastructure as code (IaC) for development, staging, and production environments
- Monitor production systems for reliability, performance, and security
- Automate operational tasks such as scaling, alerting, and incident response
- Establish and maintain deployment, rollback, and incident response playbooks

### Goals
- Enable fast, safe, and repeatable deployments with minimal manual intervention
- Maximize system uptime and observability
- Reduce time-to-recover from incidents

### Typical Communication
- Pipeline status notifications and deployment logs shared with the delivery team
- Infrastructure change reviews in PRs
- On-call runbooks and incident postmortems shared with Project Managers and stakeholders

### Interactions with Existing Roles
- **Developers**: Support build and deployment needs; review infrastructure-related code changes; provide environment access and tooling.
- **Product Managers**: Communicate deployment windows and infrastructure constraints that affect feature delivery timelines.
- **Project Managers**: Coordinate deployment scheduling and change windows; report infrastructure risks and outage impacts on project milestones.

---

## Documentation/Technical Writer

### Role Summary
Documentation/Technical Writers create and maintain user-facing and internal documentation that makes products and processes understandable and usable. They work across teams to gather accurate information and ensure docs stay current.

### Responsibilities
- Author and update user guides, API references, and developer documentation
- Maintain process and runbook documentation in coordination with engineering and operations
- Review release notes and changelogs for clarity and completeness
- Identify and close documentation gaps reported by support, QA, or end users
- Establish and enforce documentation standards and templates

### Goals
- Ensure users and contributors can quickly find accurate, up-to-date documentation
- Reduce support burden by proactively documenting common questions and procedures
- Improve onboarding efficiency through clear role and process documentation

### Typical Communication
- Doc review requests in PRs or issues linked to features or bug fixes
- Documentation status updates in release checklists
- Collaboration via shared docs and wikis with Product Managers and Developers

### Interactions with Existing Roles
- **Developers**: Gather technical details for API references and developer guides; review technical accuracy of documentation; align on code examples and sample outputs.
- **Product Managers**: Obtain feature context and user-facing messaging; coordinate timing of doc releases with product launches.
- **Project Managers**: Flag documentation tasks in the project plan; report documentation readiness as part of release criteria.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [`octoacme-templates-and-checklists.md`](./octoacme-templates-and-checklists.md) for a RACI ownership matrix mapping these roles to key ceremonies and artifacts.

