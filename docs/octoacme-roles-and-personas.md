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

## UX Designer

### Role Summary
UX Designers create user experiences, interaction designs, and prototypes that ensure the product is usable, accessible, and meets user needs. They serve as the user's advocate throughout the project lifecycle.

### Responsibilities
- Conduct user research, usability testing, and synthesize findings
- Produce wireframes, prototypes, and design specifications
- Ensure designs meet accessibility standards
- Review acceptance criteria for usability completeness
- Collaborate with Developers on feasibility and implementation fidelity

### Goals
- Deliver designs that are intuitive, accessible, and aligned with user needs
- Reduce rework by validating designs early and iteratively
- Ensure user feedback informs every iteration

### Typical Communication
- Design reviews and critique sessions with Product Managers and Developers
- Usability test readouts shared with stakeholders
- Annotated design files or specs in shared design tooling (e.g., Figma)

### Interactions & handoffs
- **With Product Managers:** Receive feature requirements and success metrics; collaborate on problem framing and user stories; present design concepts for product alignment before development begins.
- **With Developers:** Hand off finalized design specs and assets; answer questions on interaction details during implementation; review built UI against design for fidelity.
- **With Project Managers:** Flag design scope changes or delays; confirm design milestones align with release plan.
- **With QA/Testing:** Provide acceptance criteria for usability and visual accuracy; participate in acceptance testing when UX quality is in scope.

---

## Technical Writer

### Role Summary
Technical Writers create and maintain user-facing documentation, internal guides, API references, and release notes. They ensure that knowledge is accurate, discoverable, and useful to all audiences.

### Responsibilities
- Author and update user guides, API docs, and internal process documentation
- Draft release notes in collaboration with Developers and Product Managers
- Validate documentation completeness as part of the Definition of Done
- Maintain a documentation style guide and ensure consistency
- Coordinate with QA to verify that documentation accurately reflects shipped functionality

### Goals
- Ensure every feature ships with clear, accurate documentation
- Reduce support burden by providing self-service documentation
- Keep documentation in sync with the product as it evolves

### Typical Communication
- Regular check-ins with Developers to review technical accuracy
- Collaboration with Product Managers on documentation scope and priority
- Pull requests or review cycles for doc changes
- Documentation updates included in sprint demos and release checklists

### Interactions & handoffs
- **With Developers:** Review implementation details and changelog entries; request technical review of drafted docs; receive API or config changes that require documentation updates.
- **With Product Managers:** Align on documentation scope per release; receive feature specs to inform user-facing content.
- **With Project Managers:** Confirm that documentation tasks are reflected in the sprint backlog and release checklist; escalate documentation gaps that could block release.
- **With Release Manager:** Deliver final release notes and documentation updates as a release gate requirement.

---

## Release Manager

### Role Summary
Release Managers plan, coordinate, and oversee the release process from code-freeze to production deployment. They own the deployment checklist, coordinate sign-offs, and ensure rollback plans are in place.

### Responsibilities
- Define and maintain the release calendar and deployment windows
- Coordinate pre-release sign-offs from QA, Development, and Product Management
- Own the deployment checklist and rollback/mitigation plan
- Communicate release status to stakeholders and support teams
- Conduct post-release verification and escalate incidents if needed

### Goals
- Release reliably and predictably with minimal production incidents
- Maintain clear audit trails of what shipped, when, and who approved
- Reduce time-to-rollback when issues are detected post-deployment

### Typical Communication
- Release readiness meetings prior to each deployment window
- Release announcements to stakeholders and support teams
- Post-deploy status updates and incident reports when applicable
- Coordination with Developers and QA via the deployment checklist

### Interactions & handoffs
- **With Developers:** Confirm all PRs are merged and CI is passing; review code-freeze requirements; ensure hotfix processes are followed for patch releases.
- **With QA/Testing:** Obtain final QA sign-off before deployment; review smoke test results post-deploy.
- **With Product Managers:** Align on release scope and timing; confirm acceptance criteria are met.
- **With Project Managers:** Report release status and blockers; ensure release milestones are reflected in the project plan.
- **With Technical Writers:** Confirm release notes and updated documentation are ready before announcement.

---

## Stakeholder Champion

### Role Summary
Stakeholder Champions represent the interests of a major stakeholder group (e.g., customers, business units, or external partners). They surface requirements and concerns early, gather feedback, and communicate project decisions back to their stakeholder group.

### Responsibilities
- Represent stakeholder requirements and priorities in project planning
- Gather and consolidate stakeholder feedback at key milestones
- Communicate project decisions and updates back to the stakeholder group
- Participate in decision gates (initiation, planning, release) to provide approval or raise concerns
- Escalate unresolved stakeholder concerns to the Project Manager

### Goals
- Ensure stakeholder needs are understood and addressed throughout the project
- Reduce late-stage surprises by surfacing concerns early
- Maintain stakeholder trust and confidence in the project team

### Typical Communication
- Attendance at key milestone reviews and decision gates
- Stakeholder group newsletters or briefings after major decisions
- Feedback sessions or surveys at design and pre-release stages
- Direct communication with Project Manager and Product Manager for escalations

### Interactions & handoffs
- **With Product Managers:** Provide stakeholder requirements and validate prioritization decisions; review product roadmap for alignment with stakeholder expectations.
- **With Project Managers:** Raise concerns, risks, or blockers visible from the stakeholder side; participate in status reporting and milestone reviews.
- **With Developers:** Offer clarifications on stakeholder use cases and business rules during implementation; review demos or prototypes for stakeholder fit.
- **With UX Designers:** Provide user feedback and business context to inform design decisions; review prototypes on behalf of the stakeholder group.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Role-to-Workflow Mapping

The table below maps each role to key workflows and artifacts across the project lifecycle. Use it to quickly identify ownership, contributors, approvers, and who should be kept informed (RACI-lite: **O** = Owner, **C** = Contributor, **A** = Approver, **I** = Informed).

| Workflow / Artifact | Developer | Product Manager | Project Manager | UX Designer | Technical Writer | Release Manager | Stakeholder Champion |
|---|---|---|---|---|---|---|---|
| **Initiation** | | | | | | | |
| One-pager / Project Charter | C | O | C | I | I | I | C |
| Stakeholder list & comms plan | I | C | O | I | I | I | C |
| Decision gate (go/no-go) | I | A | O | I | I | I | A |
| **Planning** | | | | | | | |
| Backlog with acceptance criteria | C | O | C | C | I | I | I |
| Definition of Done | C | C | O | C | C | C | I |
| Release plan & milestone map | C | C | O | I | I | O | I |
| Initial test plan / QA approach | C | C | O | I | I | C | I |
| **Execution & Tracking** | | | | | | | |
| Project board / sprint workflow | O | I | O | C | I | I | I |
| PR / CI pipeline | O | I | C | I | I | I | I |
| QA & acceptance testing | C | A | C | C | C | C | I |
| Blocker escalation | C | C | O | I | I | C | C |
| **Risk & Communication** | | | | | | | |
| Risk register updates | C | C | O | I | I | C | C |
| Weekly status report | I | C | O | I | I | C | I |
| Incident / escalation comms | C | I | C | I | I | O | I |
| **Release & Deployment** | | | | | | | |
| Pre-release requirements sign-off | C | A | C | I | C | O | I |
| Deployment checklist | C | I | C | I | I | O | I |
| Release notes | C | C | I | I | O | C | I |
| Rollback plan | O | I | C | I | I | O | I |
| **Retrospective** | | | | | | | |
| Retro facilitation | C | C | O | C | C | C | I |
| Action items tracking | C | C | O | I | I | I | I |

> **Key:** O = Owner (accountable, drives completion) · C = Contributor (actively participates) · A = Approver (formal sign-off required) · I = Informed (receives updates)

