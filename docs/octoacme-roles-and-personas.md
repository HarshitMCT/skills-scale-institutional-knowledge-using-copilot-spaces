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
UX/UI Designers are responsible for crafting intuitive user experiences and visual interfaces. They translate user needs and business requirements into actionable designs, ensuring that what gets built is usable, accessible, and aligned with product goals.

### Responsibilities
- Conduct user research and usability testing to validate design decisions
- Create wireframes, prototypes, and final design assets
- Define and maintain design system components and standards
- Collaborate on acceptance criteria to include usability and accessibility requirements
- Participate in sprint reviews to provide design feedback on implemented features

### Goals
- Deliver experiences that are intuitive, accessible, and delightful for users
- Reduce rework by aligning design intent with implementation early
- Maintain consistency across product surfaces through a shared design system

### Typical Communication / Interactions
- Partner with **Product Managers** during backlog refinement to ensure user needs are reflected in stories and acceptance criteria
- Work with **Developers** in design-review sessions and implementation walkthroughs; provide redlines and design assets via the agreed handoff process
- Coordinate with **Project Managers** during planning to estimate design tasks and flag dependencies on research or stakeholder approvals
- Participate in sprint planning and demos to review implemented designs against specifications
- Contribute to retrospectives with usability observations and design-debt items
- Reference the [Cross-Functional Collaboration Checklist](octoacme-cross-functional-collaboration-checklist.md) for phase-by-phase design handoff checkpoints

---

## DevOps Engineer

### Role Summary
DevOps Engineers own the infrastructure, CI/CD pipelines, deployment automation, and observability platforms that enable reliable software delivery. They bridge the gap between development and operations, ensuring code can be shipped safely, quickly, and with full visibility.

### Responsibilities
- Design, build, and maintain CI/CD pipelines and deployment automation
- Manage environment configuration, infrastructure as code, and secrets management
- Establish and monitor observability tooling (logs, metrics, alerts)
- Collaborate on release readiness checks and deployment windows
- Lead incident response during production issues, including rollback procedures
- Define and enforce release gates (test coverage thresholds, security scans, etc.)

### Goals
- Achieve fast, reliable, and repeatable deployments with minimal manual intervention
- Maintain high availability and observability in production environments
- Reduce mean time to recovery (MTTR) through automation and runbooks

### Typical Communication / Interactions
- Partner with **Developers** to integrate automated tests, linting, and security scans into CI; review branching strategies and merge policies
- Coordinate with **Project Managers** on deployment windows, release schedules, and rollback decision criteria
- Support **Product Managers** in understanding environment constraints and release risk for roadmap planning
- Collaborate with **Customer Support Lead** during and after releases to monitor for incident signals and manage communication runbooks
- Participate in release planning and post-release reviews; feed incident signals into the Risk Register (see [Risk Management & Communication](octoacme-risks-and-communication.md))
- Reference the [Cross-Functional Collaboration Checklist](octoacme-cross-functional-collaboration-checklist.md) for release and incident handoff checkpoints

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and the delivery team. They clarify requirements, document processes, and ensure the team builds the right thing by translating business objectives into well-defined acceptance criteria and test scenarios.

### Responsibilities
- Elicit, document, and validate business requirements and process flows
- Collaborate with Product Managers on backlog refinement and story elaboration
- Define clear, testable acceptance criteria for backlog items
- Support test planning by identifying edge cases and business rule coverage
- Facilitate workshops to align stakeholders on scope and priorities
- Maintain requirement traceability from business goal to delivered feature

### Goals
- Ensure delivered features meet stated business objectives and user needs
- Reduce ambiguity and rework by providing clear, agreed-upon acceptance criteria
- Improve cross-team alignment through well-documented requirements and decision logs

### Typical Communication / Interactions
- Work closely with **Product Managers** during backlog refinement to elaborate stories and validate that acceptance criteria reflect business intent
- Partner with **Developers** to answer questions about business rules and edge cases during implementation
- Support **Project Managers** in scope discussions, change control, and requirements traceability
- Participate in sprint planning, backlog grooming, and sprint reviews to validate delivered functionality
- Contribute requirement insights to the risk register when scope changes introduce delivery risk (see [Risk Management & Communication](octoacme-risks-and-communication.md))
- Reference the [Cross-Functional Collaboration Checklist](octoacme-cross-functional-collaboration-checklist.md) for planning and execution handoff checkpoints

---

## Customer Support Lead

### Role Summary
The Customer Support Lead monitors user feedback, incoming incidents, and support queues post-release. They represent the voice of the customer in the delivery process, providing actionable insight on recurring issues and facilitating smooth support handoffs for major releases.

### Responsibilities
- Monitor support channels and surface recurring issues and user pain points to the product team
- Collaborate on bug prioritization by providing severity and frequency data from the support queue
- Review and contribute to release notes and support documentation before each release
- Own support handoff communications for major releases (runbooks, FAQs, escalation contacts)
- Participate in post-release reviews and retrospectives with customer-impact observations
- Escalate critical user-impacting incidents to the appropriate on-call or engineering contact

### Goals
- Minimize user impact from bugs and regressions by ensuring rapid triage and communication
- Improve time-to-resolution by building strong handoff processes with engineering and DevOps
- Feed continuous improvement loops with real-world usage and issue data

### Typical Communication / Interactions
- Collaborate with **Product Managers** on bug prioritization and customer-driven feature requests; provide support data to inform roadmap decisions
- Coordinate with **DevOps Engineers** during and after releases to monitor incident signals, manage user-facing communications, and execute rollback communications when needed
- Work with **Project Managers** on release communication plans and support-readiness checklists
- Partner with **Developers** on reproducing and triaging user-reported issues
- Participate in retrospectives to share customer feedback trends and support burden data (see [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md))
- Reference the [Cross-Functional Collaboration Checklist](octoacme-cross-functional-collaboration-checklist.md) for release and post-release support handoff checkpoints

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See the [Cross-Functional Collaboration Checklist](octoacme-cross-functional-collaboration-checklist.md) for a phase-by-phase view of how all personas interact across the project lifecycle.

