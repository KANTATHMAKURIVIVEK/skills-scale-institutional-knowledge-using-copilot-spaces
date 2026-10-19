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

## Delivery Lead

### Role Summary
The Delivery Lead focuses on sprint-level coordination and removing execution blockers to keep teams on track toward milestones.

### Responsibilities
- Coordinate sprint planning, standups, and delivery ceremonies
- Track milestones, risks, and cross-team dependencies
- Facilitate day-to-day execution and unblock teams
- Maintain sprint-level artifacts (burn-down, scope tracking)

### Interactions / Handoffs
- Works with Project Manager to align on timelines and risk communications
- Partners with Product Manager to ensure priorities are clear and stories are ready
- Coordinates with Developers and QA to resolve blockers and validate acceptance criteria
- Escalates unresolved blockers to PM or Product Lead when needed

---

## Engineering Manager

### Role Summary
Engineering Managers own team capacity, technical delivery quality, and people development for engineering teams aligned to a project.

### Responsibilities
- Commit to realistic capacity and delivery timelines
- Drive technical standards, code quality, and engineering best practices
- Support hiring, onboarding, and career development for engineers
- Participate in architecture and design reviews

### Interactions / Handoffs
- Communicates team capacity and resourcing to Project Manager and Product Manager
- Works with Developers on implementation approach and technical debt decisions
- Collaborates with QA on testability and automation requirements

---

## UX / Design Lead or Researcher

### Role Summary
Design leads or researchers ensure solutions meet user needs and define usable interaction patterns and acceptance criteria.

### Responsibilities
- Conduct user research and usability testing
- Produce interaction designs, prototypes, and design specs
- Define UX acceptance criteria and accessibility requirements
- Collaborate on content and microcopy as needed

### Interactions / Handoffs
- Works with Product Manager to translate user needs into requirements and success criteria
- Hands off designs and assets to Developers with clear specs
- Coordinates with QA to include UX validation in acceptance tests

---

## Data / Analytics Owner

### Role Summary
The Data / Analytics Owner defines success metrics, instrumentation requirements, and validates data quality for feature launches.

### Responsibilities
- Define metrics, dashboards, and instrumentation needs for features
- Specify event schemas and data contracts
- Validate data post-release and troubleshoot data quality issues
- Support experiments and A/B testing requirements

### Interactions / Handoffs
- Works with Product Manager to align on success metrics and definitions
- Provides implementation details to Developers for telemetry/event tracking
- Collaborates with Release Manager to verify data rollout and post-release monitoring

---

## Security / Privacy Engineer

### Role Summary
Security and Privacy Engineers assess risks, perform security reviews, and ensure compliance with policies and standards.

### Responsibilities
- Conduct threat modeling and security reviews for designs and implementations
- Identify and track security risks and remediation plans
- Review third-party dependencies and data handling practices
- Ensure privacy and compliance requirements are met

### Interactions / Handoffs
- Works with Developers to implement secure design and fixes
- Notifies Project Manager of security risks that affect timelines or scope
- Coordinates with Release Manager to ensure security gates are satisfied before production rollout

---

## DevOps / Platform Engineer

### Role Summary
Platform engineers maintain CI/CD, environments, and observability to enable reliable deployments and operations.

### Responsibilities
- Maintain and improve CI/CD pipelines and deployment tooling
- Manage staging and production environments and configuration
- Implement monitoring, alerting, and rollback procedures
- Support scalability and performance tuning

### Interactions / Handoffs
- Works with Developers to onboard deployment and environment needs
- Coordinates with QA to provide environments for testing
- Partners with Release Manager on deployment plans and runbooks

---

## Release Manager

### Role Summary
The Release Manager coordinates release planning, communication, and risk controls across teams for production rollouts.

### Responsibilities
- Schedule release windows and coordinate cross-team readiness
- Maintain release notes, migration steps, and rollback plans
- Run pre-release checklists and post-release verifications
- Drive go/no-go decisions with stakeholders

### Interactions / Handoffs
- Aligns release timing with Project Manager and Delivery Lead
- Works with DevOps and QA to confirm deployment readiness
- Notifies Support, Product Marketing, and Stakeholders about release details and impacts

---

## Support / Ops Lead

### Role Summary
Support and Ops leads handle incoming production issues, triage, and ensure issues are routed and resolved efficiently.

### Responsibilities
- Triage incidents and create reproducible problem reports
- Collect logs, steps to reproduce, and customer impact details
- Coordinate with engineering teams for timely fixes and mitigations
- Capture post-incident actions and feed into retrospectives

### Interactions / Handoffs
- Escalates critical incidents to Project Manager and relevant engineering owners
- Works with Developers to reproduce and prioritize fixes
- Communicates status to Stakeholders and affected customers

---

## Product Marketing / Launch Lead

### Role Summary
Product Marketing or Launch Leads prepare messaging, launch materials, and coordinate cross-functional launch activities.

### Responsibilities
- Create launch plans, messaging, and customer-facing materials
- Coordinate go-to-market timing and readiness checks
- Prepare internal and external communications and training materials
- Track launch KPIs and support post-launch feedback

### Interactions / Handoffs
- Works with Product Manager on feature positioning and success metrics
- Coordinates with Release Manager on launch timing and go/no-go
- Communicates with Sales, Support, and Stakeholders about customer impacts

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
