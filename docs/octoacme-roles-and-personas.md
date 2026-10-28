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

## Engineering Manager

### Role Summary
Engineering Managers support the execution of delivery plans by aligning engineering capacity, technical prioritization, and team health with business needs. They act as the operational partner to the Product Manager and Project Manager inside the engineering organization.

### Responsibilities
- Own engineering team planning, capacity, and workload balancing
- Support delivery forecasting, sprint planning, and technical prioritization
- Help remove blockers that prevent teams from delivering committed work
- Align engineering dependencies and sequencing with project milestones
- Partner with engineering leads to improve execution quality and team sustainability

### Interaction with Other Roles
- Works with Product Managers on prioritization trade-offs and roadmap feasibility
- Coordinates with Project Managers on schedules, dependencies, and risk tracking
- Collaborates with Developers on planning, team practices, and technical execution
- Escalates cross-team engineering issues to PM or sponsor when needed
- Participates in retrospectives to surface process and delivery improvements

### Typical Communication
- Sprint planning and engineering capacity review
- Delivery status updates to PM and leadership
- Technical dependency escalations and trade-off discussions

---

## QA Lead / Quality Manager

### Role Summary
The QA Lead defines the quality strategy and validates that work meets acceptance criteria, release readiness, and operational stability requirements before handoff to production.

### Responsibilities
- Define test strategy, release quality gates, and validation approach
- Review user stories and acceptance criteria for testability
- Coordinate manual and automated validation across features and integrations
- Triage defects, prioritize fixes, and assess release risk
- Certify that critical workflows have appropriate test coverage and smoke validation

### Interaction with Other Roles
- Works with Developers on test design, defect triage, and quality feedback loops
- Partners with Product Managers to validate that the delivered solution meets business intent
- Provides release readiness signals to the Project Manager and Release Manager
- Escalates quality issues that threaten milestone or launch success
- Contributes to retrospectives by identifying gaps in testing or process discipline

### Typical Communication
- Acceptance review, defect triage, release readiness check-ins
- Quality metrics and risk flags during planning and execution

---

## Release Manager / Delivery Coordinator

### Role Summary
The Release Manager coordinates release readiness, deployment windows, communication, and operational continuity so product changes are delivered with clear ownership and rollback awareness.

### Responsibilities
- Manage release readiness checklists and milestone dependencies
- Coordinate deployment timing, rollback planning, and stakeholder communication
- Confirm required approvals, change documentation, and operational handoff
- Monitor release health before, during, and after rollout
- Support incident triage and post-release follow-up when production issues occur

### Interaction with Other Roles
- Works with Project Managers to align release timing with schedule and dependencies
- Partners with QA and Engineering to confirm release readiness and smoke-test completion
- Coordinates with Product Managers on stakeholder messaging and launch impact
- Informs Security and Operations partners when risk or compliance checks apply
- Participates in retrospectives to improve release practices and reduce deployment friction

### Typical Communication
- Release readiness reviews and deployment checklists
- Stakeholder updates during planned rollouts and rollback scenarios

---

## Security / Compliance Partner

### Role Summary
The Security / Compliance Partner helps the team design, review, and deliver work in a way that meets security, privacy, and compliance requirements without slowing delivery unnecessarily.

### Responsibilities
- Review risks, controls, and compliance needs during planning and implementation
- Help ensure secure design patterns, sensitive-data handling, and access controls
- Support security testing, threat review, and remediation prioritization
- Escalate issues that require broader risk ownership or policy decisions
- Advise on documentation needed for audits, reviews, or incident response

### Interaction with Other Roles
- Partners with Developers on secure architecture, threat awareness, and remediation
- Supports Product Managers and Project Managers in understanding risk trade-offs and approval needs
- Works with Release Manager to assess launch risk and release conditions
- Coordinates with stakeholders when compliance impacts timeline, scope, or operational controls
- Contributes to retrospectives by capturing recurring security and compliance lessons

### Typical Communication
- Security review meetings, risk assessments, and incident escalation paths
- Compliance checkpoints tied to project milestones and release gates

---

## Customer Success / Stakeholder Liaison

### Role Summary
The Customer Success or Stakeholder Liaison connects project execution to customer impact, stakeholder expectations, and communication needs. This role ensures the team remains aware of adoption, usability, and relationship context as work progresses.

### Responsibilities
- Translate customer feedback, adoption signals, and stakeholder concerns into product priorities
- Maintain stakeholder communication and update cadence for key groups
- Surface customer-impact risks and dependencies to the team early
- Coordinate feedback loops from pilot users, champions, and internal stakeholders
- Support readiness for launch communications and adoption follow-through

### Interaction with Other Roles
- Works with Product Managers to prioritize issues based on customer impact and adoption goals
- Coordinates with Project Managers on stakeholder updates and escalation paths
- Shares customer insights with Developers and QA to improve feature quality and usability
- Helps Release Manager and leadership communicate rollout impact and readiness
- Participates in retrospectives to capture customer feedback and service improvements

### Typical Communication
- Stakeholder updates, customer readiness reviews, and feedback summaries
- Milestone and release communication to impacted groups

---

## Data / Analytics Lead

### Role Summary
The Data / Analytics Lead helps the team track whether the initiative is creating the intended value by measuring adoption, quality signals, and operational outcomes.

### Responsibilities
- Define success metrics, dashboards, and operational signals for the project
- Validate that tracking is in place before release and during adoption
- Analyze usage, quality, and performance data to inform decisions
- Partner with Product and Stakeholder groups on outcome measurement
- Highlight gaps in instrumentation, reporting, or attribution that affect decision-making

### Interaction with Other Roles
- Works with Product Managers to define measurable success criteria and progress thresholds
- Supports Project Managers and Release Manager with business impact data during rollout
- Provides technical partners with instrumentation needs and reporting definitions
- Helps Customer Success teams understand adoption and change impact
- Contributes to retrospectives by evaluating whether outcomes met expectations and where to improve

### Typical Communication
- Metric reviews, instrumentation planning, and adoption reporting
- Outcome and performance updates tied to sprint and release milestones

---

## Role Interaction Summary

Across OctoAcme projects, these supporting roles help clarify ownership without replacing the core team. Developers implement the work, Product Managers define value, and Project Managers coordinate delivery. Engineering Managers, QA Leads, Release Managers, Security partners, Customer Success stakeholders, and Data Leads add specialized accountability for execution quality, readiness, risk, communication, and measurable outcomes.

This creates a clearer operating model in which each role:
- contributes at the right point in planning, execution, and release
- escalates issues through the correct path
- maintains accountability for the decision areas it owns
- provides feedback into retrospectives and continuous improvement

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- These roles can be combined with the core project roles to model cross-functional delivery, risk management, and stakeholder communication.


