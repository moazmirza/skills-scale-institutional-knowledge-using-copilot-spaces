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

## Project Sponsor / Executive Sponsor

### Role Summary
Project Sponsors provide strategic sponsorship, secure funding and resources, and make or escalate decisions that exceed the delivery team's authority.

### Responsibilities
- Confirm the initiative's strategic outcomes, scope boundaries, and success measures
- Secure sponsorship, budget, capacity, and cross-team support
- Review milestone status, major risks, and changes to scope or benefits
- Resolve escalated business decisions and validate outcomes at decision gates

### Interactions
- Receives status, risk, and escalation updates from the Project Manager
- Aligns value, priority, and trade-offs with the Product Manager
- Reviews feasibility and material technical risks with the Delivery Lead
- Confirms release, rollout, or scope decisions with affected stakeholders

---

## Delivery Lead / Engineering Lead

### Role Summary
Delivery or Engineering Leads guide technical execution, coordinate engineering work, and make delivery risks and dependencies visible.

### Responsibilities
- Coordinate implementation, estimation, sequencing, and technical design
- Support Developers with technical decisions, reviews, and dependency management
- Identify technical risks and propose mitigations or trade-offs
- Confirm that work is ready for testing and meets the Definition of Done

### Interactions
- Works with Developers on implementation, code quality, and technical blockers
- Partners with the Product Manager on feasibility, scope, and trade-offs
- Partners with the Project Manager on milestones, capacity, dependencies, and risks
- Coordinates with QA, DevOps, and Security on testability, release, and controls

---

## UX / Design Lead

### Role Summary
UX or Design Leads guide user research, experience design, usability validation, and design decisions.

### Responsibilities
- Translate user needs into journeys, flows, prototypes, and design requirements
- Facilitate usability research and validate designs with representative users
- Maintain accessible, consistent, and implementable design decisions
- Define experience acceptance criteria and design handoff materials

### Interactions
- Partners with the Product Manager on user outcomes, discovery, and acceptance criteria
- Works with Developers and the Delivery Lead on feasibility and implementation details
- Works with QA on testable experience, accessibility, and usability requirements
- Updates the Project Manager on design milestones, decisions, and unresolved issues

---

## QA / Test Lead

### Role Summary
QA or Test Leads define the quality approach, coordinate testing, and provide evidence for release readiness.

### Responsibilities
- Define the test strategy, coverage, environments, and regression approach
- Coordinate functional, integration, accessibility, and regression testing
- Track defects and quality risks through resolution or an agreed exception
- Confirm readiness against acceptance criteria and the Definition of Done

### Interactions
- Works with Developers on testability, defects, and automation
- Partners with the Product Manager on acceptance and known quality trade-offs
- Reports quality status, risks, and release recommendations to the Project Manager
- Coordinates with UX, Security, Data, and DevOps on specialist validation

---

## DevOps / Release Engineer

### Role Summary
DevOps or Release Engineers make delivery repeatable and safe through automation, reliable environments, observability, and rollback readiness.

### Responsibilities
- Maintain CI/CD pipelines, environments, deployment automation, and configuration
- Coordinate release execution, smoke checks, monitoring, and rollback plans
- Confirm operational readiness, observability, and access requirements
- Record release outcomes and support incident response when needed

### Interactions
- Coordinates with Developers and the Delivery Lead on build, deployment, and infrastructure changes
- Works with QA on environments, test data, smoke testing, and release evidence
- Works with the Project Manager on release timing, dependencies, and operational risks
- Supports the Product Manager, Customer/Support Representative, and Change/Adoption Lead with release communications

---

## Security / Privacy Representative

### Role Summary
Security or Privacy Representatives advise on threats, controls, data protection, and required reviews, and help escalate security or privacy incidents.

### Responsibilities
- Identify security, privacy, and compliance requirements during discovery and planning
- Facilitate threat modeling and review designs, data flows, and access controls
- Track remediation and verify that required controls are implemented
- Advise on incident escalation and security or privacy approval for release

### Interactions
- Works with Developers and the Delivery Lead on secure design and remediation
- Partners with the Product Manager on risk-based trade-offs and user trust
- Reports material risks and review status to the Project Manager and Sponsor
- Coordinates with QA, Data, and DevOps on verification, data handling, and operational controls

---

## Data / Analytics Lead

### Role Summary
Data or Analytics Leads define measurement plans and ensure that instrumentation and reporting support product and project decisions.

### Responsibilities
- Define success metrics, event tracking, dashboards, and measurement baselines
- Specify data quality, ownership, retention, and interpretation requirements
- Validate instrumentation and report outcomes after release
- Provide evidence for prioritization, retrospectives, and sponsor decisions

### Interactions
- Partners with the Product Manager on outcomes, metrics, and prioritization
- Works with Developers and the Delivery Lead on telemetry and data implementation
- Works with the Project Manager on progress evidence, risks, and stakeholder reporting
- Coordinates with Security/Privacy on appropriate data collection and with Customer/Support on feedback signals

---

## Customer / Support Representative

### Role Summary
Customer or Support Representatives bring customer needs, support trends, operational feedback, and readiness concerns into delivery and release decisions.

### Responsibilities
- Represent customer workflows, support insights, and known pain points
- Validate communication, support procedures, and customer-facing readiness
- Coordinate feedback collection after release and surface emerging issues
- Help define support impact, service expectations, and escalation needs

### Interactions
- Collaborates with the Product Manager on needs, prioritization, and acceptance
- Works with the Project Manager on stakeholder communications and readiness tracking
- Coordinates with QA and DevOps on validation, monitoring, and support plans
- Partners with the Change/Adoption Lead on enablement and with the Sponsor on material customer impact

---

## Change / Adoption Lead

### Role Summary
Change or Adoption Leads prepare affected users and teams for change through enablement, communications, rollout support, and adoption measurement.

### Responsibilities
- Identify impacted audiences, adoption risks, training needs, and rollout dependencies
- Create enablement materials, communications, and feedback channels
- Coordinate pilots, phased rollout, and reinforcement activities where appropriate
- Measure adoption and recommend follow-up actions after release

### Interactions
- Partners with the Product Manager on value messaging and intended user outcomes
- Works with the Project Manager on rollout plans, milestones, risks, and communications
- Coordinates with Customer/Support on readiness, training, and feedback
- Works with UX, QA, and DevOps on usability evidence, release timing, and operational support

---

## Responsibility and Interaction Guidance

The role accountable for an outcome owns the decision and confirms completion; consulted roles provide input before that decision. The Project Manager records the owner, decision, due date, and escalation in the project board, risk register, or decision log.

| Lifecycle stage | Accountable role(s) | Consulted roles and key interaction |
| --- | --- | --- |
| Initiation and success definition | Sponsor and Product Manager | Project Manager coordinates; Data/Analytics defines measures; Customer/Support and UX provide needs; Security/Privacy flags constraints |
| Planning and design | Project Manager and Product Manager | Delivery Lead, Developers, UX, QA, Security/Privacy, Data, and Change/Adoption identify dependencies, acceptance criteria, risks, and readiness work |
| Build and validation | Delivery Lead and Developers | Product Manager confirms scope; UX reviews experience; QA leads test evidence; Security/Privacy verifies controls; Data validates instrumentation |
| Release decision and execution | Project Manager for coordination; Product Manager for product acceptance; DevOps for execution | QA recommends quality readiness; Security/Privacy confirms required reviews; Delivery Lead confirms technical readiness; Customer/Support and Change/Adoption confirm readiness |
| Adoption, outcomes, and improvement | Product Manager and Project Manager | Data/Analytics measures outcomes; Customer/Support reports feedback; Change/Adoption measures uptake; Sponsor reviews benefits and unresolved escalations |

### Communication Touchpoints and Escalation
- Hold a kickoff to confirm sponsor, accountable owners, success measures, dependencies, and communication cadence.
- Review delivery progress, risks, decisions, and cross-team dependencies in the weekly project sync; circulate a status update with asks and decisions needed.
- Use design reviews, backlog refinement, and technical reviews to involve consulted roles before scope or implementation decisions are finalized.
- Before release, hold a readiness review covering acceptance, quality, security/privacy, operations, support, communications, and adoption; record exceptions and owners.
- After release, review monitoring, customer feedback, adoption, and success metrics, then capture actions in the retrospective or improvement backlog.
- Escalate team blockers to the Delivery Lead or Project Manager, unresolved product or scope trade-offs to the Product Manager, and material schedule, funding, business, security, or privacy decisions to the Sponsor or the applicable incident owner. Follow the security incident runbook for security incidents.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
