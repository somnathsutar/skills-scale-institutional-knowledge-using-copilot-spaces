```markdown
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

## QA / Testing

### Role Summary
QA and testing validate product quality and acceptance criteria across unit, integration, and end-to-end flows.

### Responsibilities
- Define and execute test plans
- Automate tests where feasible
- Collaborate on acceptance criteria and DoD
- Validate releases via smoke and regression testing

### Typical Communication
- Test results in PRs and release notes
- QA status at delivery syncs

---

## Stakeholders

### Role Summary
Stakeholders provide domain context, approvals, and access to business resources needed to deliver outcomes.

### Responsibilities
- Provide inputs and approvals
- Review business/marketing impacts
- Participate in milestone reviews as needed

---

## Additional Personas (Proposed additions)

To reduce ambiguity and improve accountability as projects scale, consider adding the following personas to the roles doc.

### UX Designer
- Role summary: Owns user experience research and design, ensuring features meet usability and accessibility goals.
- Responsibilities:
  - Conduct user research, interviews, and usability tests.
  - Produce wireframes, prototypes, and design specs.
  - Validate designs with users and measure usability before wide release.
  - Provide acceptance criteria for UX/usability aspects of features.
- Interaction with existing roles:
  - Works with Product Managers to refine problem statements and acceptance criteria.
  - Collaborates with Developers to ensure designs are feasible and testable.
  - Coordinates with QA on usability acceptance tests and edge-case flows.

### Business Analyst (BA)
- Role summary: Bridges business stakeholders and the delivery team by clarifying requirements, mapping processes, and minimizing scope ambiguity.
- Responsibilities:
  - Elicit and document business requirements and workflows.
  - Create user journeys, process maps, and data requirements.
  - Break down high-level requirements into clear backlog items with acceptance criteria.
  - Track scope changes and their impact on timeline and dependencies.
- Interaction with existing roles:
  - Partners with Product Managers to convert objectives into detailed requirements.
  - Works with Project Managers to flag risks and dependencies discovered during analysis.
  - Collaborates with Developers and QA to ensure acceptance criteria are implementable and testable.

### Release Manager
- Role summary: Coordinates release planning and execution to minimize production risk and ensure smooth deployments.
- Responsibilities:
  - Own the release calendar and coordinate deployment windows.
  - Maintain rollback and mitigation plans for releases.
  - Validate that pre-release checks (CI, security scans, smoke tests) are complete.
  - Communicate release status to stakeholders and support teams.
- Interaction with existing roles:
  - Works closely with Project Managers and Product Managers to schedule releases.
  - Coordinates with Developers and QA to verify deployment readiness.
  - Engages Support Lead and on-call engineers for post-deploy monitoring and rollback if needed.

### Support Lead
- Role summary: Primary contact for post-release support and the feedback loop from customers to the project team.
- Responsibilities:
  - Triage incoming incidents and user-reported issues; escalate per incident playbook.
  - Maintain runbooks and knowledge base articles for common issues.
  - Aggregate support trends and feed them back to Product and Engineering.
  - Coordinate knowledge transfer and training for support staff before releases.
- Interaction with existing roles:
  - Receives release notes and runbooks from the Release Manager and PM.
  - Escalates recurring or high-impact issues to Project Managers and Product Managers.
  - Works with Developers and QA to reproduce and validate fixes.

---

## How to use these personas
- Add the primary personas to the Project One-pager and team rosters for each project.
- Use the roles to define clear ownership for artifacts (e.g., BA owns process maps, UX owns prototypes, Release Manager owns release checklist).
- Link role-specific checklists and templates from the docs/templates folder.

```
