# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Roles

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

## Additional Personas

The following personas represent cross-functional and accountability-focused roles that enhance coordination, risk management, and project outcomes. Not all projects require all personas; teams should adopt based on project complexity and organizational needs.

---

## Delivery Lead

### Role Summary
The Delivery Lead owns day-to-day execution of the delivery plan, coordinates cross-functional dependencies, and removes blockers to keep the project on track.

### Responsibilities
- Execute and adapt the project delivery plan
- Coordinate work across engineering, QA, design, and other teams
- Identify and escalate blockers in real time
- Track milestones and flag schedule risks weekly
- Drive daily standups and maintain project visibility

### Goals
- Keep projects moving toward on-time delivery
- Reduce context switching and dependency delays
- Ensure clear, achievable weekly commitments

### Key Interactions
- **Project Manager**: Escalates blockers and requests plan adjustments
- **Product Manager**: Communicates scope decisions and prioritization changes
- **Developers & QA**: Coordinates work, removes impediments
- **Stakeholders**: Provides milestone progress updates

### Typical Communication
- Daily standups and blockers list
- Weekly delivery status to PM and stakeholders
- Ad-hoc escalations for critical blockers

---

## Technical Program Manager (TPM)

### Role Summary
The TPM drives technical dependency management, sequences infrastructure and platform work, and ensures integration across multiple technical teams.

### Responsibilities
- Map technical dependencies between teams and milestones
- Sequence infrastructure, platform, and feature work to minimize rework
- Facilitate architectural trade-offs and design decisions
- Coordinate cross-team integration points and testing
- Identify technical risk and propose mitigation strategies

### Goals
- Enable parallel execution while respecting technical constraints
- Reduce cycle time by optimizing team sequencing and handoffs
- Prevent technical surprises by surfacing risks early

### Key Interactions
- **Engineering Managers & Architects**: Validate dependency maps and sequencing
- **Project Manager**: Aligns technical sequencing with project plan
- **Developers**: Coordinates work across teams and resolves blockers
- **Release Engineer**: Coordinates integration and deployment sequencing

### Typical Communication
- Dependency maps and sequencing documents
- Weekly technical risk review
- Design docs and decision logs

---

## Release Engineer / Release Lead

### Role Summary
The Release Engineer owns release pipelines, deployment automation, and rollback strategies. They ensure every release is safe, repeatable, and observable.

### Responsibilities
- Maintain and improve release and deployment pipelines
- Automate build, test, staging, and production deployments
- Define rollback and incident response playbooks
- Verify pre-release requirements (tests, security scans, documentation)
- Coordinate deployment windows and communicate release status
- Monitor deployments and triage production issues post-release

### Goals
- Enable frequent, safe releases with minimal manual intervention
- Reduce deployment risk and time-to-rollback
- Maintain deployment observability and traceability

### Key Interactions
- **Developers**: Verifies PR quality gates and deployment requirements
- **QA**: Coordinates smoke tests and acceptance criteria validation
- **Security Champion**: Ensures security scanning and sign-off before deploy
- **Support/On-call**: Collaborates on post-deploy verification and incident response

### Typical Communication
- Release notes and deployment checklists
- Pipeline status and incident playbooks
- Post-release retrospectives and action items

---

## UX Researcher / Designer (project-dedicated)

### Role Summary
The UX Researcher or Designer (assigned to the project) conducts user research, validates product design, and defines usability acceptance criteria to ensure features meet user needs.

### Responsibilities
- Conduct user research and usability testing
- Validate product and feature design with users
- Define usability acceptance criteria and test scenarios
- Collaborate on design iterations and edge cases
- Ensure accessibility and user experience standards are met

### Goals
- Validate that features solve real user problems
- Reduce rework due to design or usability misalignment
- Ensure inclusive, accessible user experiences

### Key Interactions
- **Product Manager**: Partners on requirements and feature definition
- **Developers**: Collaborates on design feasibility and implementation
- **QA**: Works together on usability test scenarios and acceptance criteria
- **Stakeholders**: Presents research findings and design validation

### Typical Communication
- User research summaries and findings
- Design specs and prototypes
- Usability test results and acceptance criteria

---

## Data Analyst / Data Owner

### Role Summary
The Data Analyst (or Data Owner) defines success metrics, instruments code for observability, and creates dashboards that drive decisions about feature impact and product direction.

### Responsibilities
- Define and validate success metrics for features and releases
- Ensure proper instrumentation and data collection in code
- Create and maintain dashboards for key signals (errors, latency, usage, adoption)
- Analyze feature impact and recommend optimizations
- Ensure data quality and privacy compliance

### Goals
- Enable data-driven decision-making on feature impact and priorities
- Reduce guessing and improve product iteration speed
- Provide early signals of quality or adoption issues

### Key Interactions
- **Product Manager**: Aligns on success metrics and interprets findings
- **Developers**: Coordinates instrumentation and logging strategy
- **Project Manager**: Provides progress signals and milestone tracking
- **Stakeholders**: Presents impact reports and dashboards

### Typical Communication
- Metrics definitions and instrumentation specs
- Weekly dashboard updates and impact reports
- Data quality and privacy sign-offs

---

## Security Champion

### Role Summary
The Security Champion advocates for security best practices, triages security scan findings, and ensures security requirements are integrated into the delivery process.

### Responsibilities
- Review code and design for security risks
- Triage and prioritize security scanning findings
- Coordinate security fixes and patches
- Ensure compliance with security standards and policies
- Escalate critical security issues to Product Lead and Security team

### Goals
- Reduce security risk in delivery without blocking progress
- Shift security left by catching issues early in development
- Ensure compliance and maintain customer trust

### Key Interactions
- **Developers**: Reviews code and design for security; assists with fixes
- **Release Engineer**: Signs off on security scans before deployment
- **QA**: Includes security test scenarios in acceptance criteria
- **Security on-call & PM**: Escalates critical issues; coordinates response

### Typical Communication
- Security scan reports and findings
- Security design reviews and approval sign-offs
- Incident response and post-incident retrospectives

---

## Support Liaison

### Role Summary
The Support Liaison bridges customer support and operations with the delivery team, ensuring customer-impacting issues are surfaced early and factored into prioritization.

### Responsibilities
- Capture customer-facing issues and pain points from support
- Prioritize and escalate high-impact or frequently reported issues
- Provide early feedback to the delivery team on user problems
- Coordinate workarounds and communication for known issues
- Help QA and developers reproduce and validate fixes

### Goals
- Reduce support load and customer frustration through better prioritization
- Catch user experience issues early in development
- Improve communication between customer-facing and product teams

### Key Interactions
- **Project Manager**: Escalates customer-impacting issues for prioritization
- **Product Manager**: Provides input on customer needs and pain points
- **Developers**: Helps reproduce issues and validate fixes
- **Stakeholders**: Communicates known issues and workarounds to customers

### Typical Communication
- Weekly customer issue summaries and trends
- High-priority customer escalations and workarounds
- Customer feedback and impact reports

---

## Business Analyst / Requirements Owner

### Role Summary
The Business Analyst captures detailed requirements, maps business processes to technical solutions, and ensures acceptance criteria are complete and testable.

### Responsibilities
- Gather and document detailed business requirements
- Map business processes and workflows to technical design
- Define and validate acceptance criteria with stakeholders
- Clarify ambiguities and edge cases before development
- Ensure test scenarios cover business requirements

### Goals
- Reduce rework and misalignment by capturing requirements accurately
- Accelerate development by providing clear, testable criteria
- Improve quality by ensuring acceptance criteria are comprehensive

### Key Interactions
- **Product Manager**: Aligns on business priorities and requirements
- **Project Manager**: Incorporates requirements planning into schedule
- **Developers**: Clarifies technical feasibility and implementation approach
- **QA**: Works together to define and validate acceptance criteria

### Typical Communication
- Detailed requirements documents and specs
- Acceptance criteria and test scenario documents
- Requirement clarifications and issue resolution

---

## Role Interaction Matrix

The matrix below shows primary interactions between roles:

| Role | Works closely with | Key handoffs | Frequency |
|------|--------------------|--------------|----------|
| **Developers** | QA, Product Manager, Technical Lead | Code reviews, PRs, test results | Daily |
| **Product Manager** | Project Manager, Developers, Business Analyst | Requirements, prioritization, metrics | Weekly+ |
| **Project Manager** | All roles | Status, risks, decisions | Weekly |
| **Delivery Lead** | Developers, QA, Project Manager | Blockers, progress, scope changes | Daily |
| **Technical Program Manager** | Engineering Managers, Developers, Release Engineer | Dependency maps, sequencing | Weekly |
| **Release Engineer** | Developers, QA, Security Champion, Support | Deployments, rollback plans, incidents | Per release |
| **UX Researcher** | Product Manager, Developers, QA | Design specs, research findings, acceptance criteria | Weekly |
| **Data Analyst** | Product Manager, Developers, Project Manager | Metrics, dashboards, success signals | Weekly |
| **Security Champion** | Developers, Release Engineer, Security on-call | Security scans, fixes, sign-offs | Per sprint |
| **Support Liaison** | Project Manager, Developers, Product Manager | Customer issues, workarounds, impact reports | Weekly+ |
| **Business Analyst** | Product Manager, Developers, QA | Requirements, acceptance criteria, specs | Weekly |

---

## How to use these personas

- **Project staffing**: Identify which personas are needed for your project based on complexity, team size, and stakeholder needs.
- **Role assignment**: Assign team members or external partners to personas; note that one person can hold multiple personas.
- **Communication planning**: Use the interaction matrix to plan handoffs and sync meetings.
- **Accountability**: Use personas to clarify ownership of key activities (e.g., "Who owns success metrics?" → Data Analyst).
- **Scenarios & exercises**: Use persona definitions to frame hypothetical scenarios and shape role-specific guidance.

See `octoacme-roles-interaction-checklist.md` for detailed guidance on project staffing, interaction planning, and handoff templates.
