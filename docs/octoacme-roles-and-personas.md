# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

> **See also:** [RACI-Lite Template](./octoacme-raci-lite-template.md) for a lifecycle phase ownership reference.

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
QA/Testing is responsible for validating that features meet acceptance criteria and quality standards before release. They act as the final quality gate and advocate for the end user's experience.

### Responsibilities
- Write and execute test plans, test cases, and regression suites
- Validate acceptance criteria and Definition of Done for each feature
- Perform exploratory, functional, and smoke testing
- Report, triage, and track defects through resolution
- Contribute to CI/CD quality gates and security scan reviews

### Goals
- Prevent regressions and defects from reaching production
- Improve test coverage and testing efficiency over time
- Ensure releases are stable and meet stakeholder expectations

### Typical Communication
- Participates in sprint planning to assess testability of stories
- Collaborates with Developers on test environments and bug triage
- Coordinates with Release Manager on release sign-off
- Reports quality status to Project Managers and Product Managers

---

## Stakeholders

### Role Summary
Stakeholders are individuals or groups with a vested interest in the project outcome. They provide requirements, review progress, and grant approvals at key decision points.

### Responsibilities
- Define and communicate business requirements and constraints
- Review and approve deliverables at initiation, planning, and release gates
- Provide timely feedback on prototypes, demos, and release candidates
- Escalate concerns or changing priorities to the Project Manager or Product Manager

### Goals
- Ensure the project delivers measurable business or customer value
- Maintain visibility into project progress and risk
- Make timely decisions to keep the project on track

### Typical Communication
- Monthly stakeholder updates and milestone demos
- Decision and approval requests from Project Managers
- Briefings from Product Managers on roadmap and trade-offs
- Release announcements from Release Manager or Project Manager

---

## UX Designer

### Role Summary
UX Designers craft user experiences, interaction models, and visual designs that meet usability and accessibility requirements. They bridge the gap between user needs and technical implementation.

### Responsibilities
- Conduct user research and synthesize findings into design requirements
- Create wireframes, prototypes, and high-fidelity mockups
- Define interaction patterns and ensure accessibility compliance
- Collaborate in design reviews and usability tests
- Maintain a design system or component library as applicable

### Goals
- Deliver intuitive, accessible, and consistent user experiences
- Reduce rework by validating designs before development begins
- Ensure usability requirements are captured in acceptance criteria

### Typical Communication
- Works with Product Managers to translate requirements into design specs
- Partners with Developers to assess technical feasibility and implementation fidelity
- Shares prototypes and findings with Stakeholders for early feedback
- Coordinates with QA/Testing to ensure usability is part of acceptance criteria

---

## Technical Writer

### Role Summary
Technical Writers produce and maintain user-facing and internal documentation, API references, release notes, and onboarding guides. They ensure that knowledge is accessible, accurate, and up to date.

### Responsibilities
- Author and maintain product documentation, user guides, and API specs
- Draft release notes for each release in collaboration with the Release Manager
- Validate documentation accuracy with Developers and QA
- Incorporate documentation review into the Definition of Done
- Keep the `docs/` folder organized and well-linked

### Goals
- Reduce support burden by providing clear, searchable documentation
- Ensure release notes are complete and published with every release
- Embed documentation as a first-class deliverable in the project lifecycle

### Typical Communication
- Collaborates with Developers to verify technical accuracy
- Works with Product Managers to understand scope and user impact
- Coordinates with Release Manager on release note timelines
- Partners with QA/Testing to confirm documentation aligns with validated behavior

---

## Release Manager

### Role Summary
Release Managers plan, coordinate, and supervise deployments. They own the release checklist, communicate deployment windows, and manage rollback plans to minimize risk to production.

### Responsibilities
- Maintain and execute the release checklist for each deployment
- Schedule deployment windows and communicate timelines to all stakeholders
- Coordinate code-freeze and readiness sign-off with Developers and QA
- Manage rollback plans and incident escalation if a deployment fails
- Publish release announcements and coordinate with Support post-release

### Goals
- Deliver releases safely, reliably, and on schedule
- Minimize downtime and production incidents from deployments
- Improve release velocity through process automation and documentation

### Typical Communication
- Works with Developers to confirm code readiness and merged PRs
- Coordinates release sign-off with QA/Testing
- Aligns on release timing and scope with Product Managers and Project Managers
- Notifies Stakeholders and Support before and after each release
- Engages Technical Writers for release note delivery

---

## Stakeholder Champion

### Role Summary
The Stakeholder Champion is an embedded advocate for key stakeholder groups within the project team. They ensure that stakeholder interests, concerns, and feedback are represented throughout the project lifecycle—not just at formal review gates.

### Responsibilities
- Gather, consolidate, and communicate stakeholder requirements and feedback
- Surface changing priorities or concerns to the Project Manager and Product Manager early
- Represent stakeholder approval or escalation at key decision points
- Bridge communication between the project team and the broader stakeholder community
- Ensure that stakeholder communication commitments from the project plan are met

### Goals
- Prevent late-stage surprises by surfacing stakeholder feedback continuously
- Reduce miscommunication between delivery team and business stakeholders
- Strengthen trust and transparency between the project team and stakeholders

### Typical Communication
- Acts as a liaison between Stakeholders and the Project Manager/Product Manager
- Participates in sprint demos and review sessions on behalf of stakeholders
- Channels feedback to Developers and UX Designers in a timely manner
- Collaborates with Release Manager on stakeholder release communications

---

## Engineering Manager / Tech Lead

### Role Summary
The Engineering Manager or Tech Lead provides technical leadership, owns architectural decisions, and ensures the team has the capacity and direction to deliver quality software. They are the primary decision-maker for technical standards and Definition of Done alignment.

### Responsibilities
- Own technical architecture and design decisions
- Define and uphold coding standards, branching strategy, and CI/CD practices
- Align team capacity to sprint commitments in partnership with the Project Manager
- Represent engineering in cross-functional discussions on scope and timelines
- Mentor Developers and facilitate technical knowledge sharing

### Goals
- Maintain a healthy, scalable codebase and sustainable engineering pace
- Reduce technical debt without blocking delivery
- Ensure Definition of Done reflects meaningful quality standards

### Typical Communication
- Partners with Project Managers on capacity and scheduling
- Collaborates with Product Managers on feasibility and trade-offs
- Advises the Security/Compliance Partner on technical risk
- Engages with Release Manager on deployment readiness

---

## Support / Customer Success Liaison

### Role Summary
The Support/Customer Success Liaison connects the project team with the customer support function. They ensure that support teams are prepared for releases and that customer-reported issues are fed back into the project backlog.

### Responsibilities
- Brief support teams before releases on new features and known issues
- Relay customer feedback and reported defects to the Product Manager and QA
- Coordinate incident response communications for customer-facing issues
- Contribute to release note drafts by highlighting customer-impacting changes
- Track support volume trends as a signal for product and quality improvements

### Goals
- Minimize customer disruption from releases and incidents
- Ensure support teams are equipped and informed ahead of every deployment
- Close the feedback loop between customers and the product team

### Typical Communication
- Coordinates with Release Manager on pre-release briefings and announcements
- Works with QA/Testing and Developers during incident triage
- Shares customer feedback summaries with Product Managers
- Partners with Technical Writers on user-facing documentation accuracy

---

## Security / Compliance Partner

### Role Summary
The Security/Compliance Partner ensures that security and compliance requirements are integrated into the project lifecycle. They own security scanning, vulnerability triage, and escalation for compliance-blocking issues.

### Responsibilities
- Define and enforce security requirements and compliance constraints
- Review CI/CD pipelines for security scanning coverage (e.g., SAST, dependency scanning)
- Triage security scan results and advise Developers on remediation
- Escalate compliance-blocking issues to the Project Manager or Sponsor
- Conduct or coordinate security reviews for high-risk releases

### Goals
- Prevent security vulnerabilities from reaching production
- Embed security into the Definition of Done and release checklist
- Maintain compliance with relevant regulatory or organizational standards

### Typical Communication
- Partners with Engineering Manager/Tech Lead to set security standards
- Advises Developers on secure coding practices and vulnerability fixes
- Collaborates with Release Manager to validate security gate on release checklist
- Reports compliance status to Project Managers and Stakeholders

---

## Data / Analytics Partner

### Role Summary
The Data/Analytics Partner ensures that success metrics are defined, instrumented, and monitored. They support data-driven decision-making by maintaining dashboards and interpreting usage and performance signals.

### Responsibilities
- Collaborate with Product Managers to define measurable success metrics
- Instrument new features with appropriate analytics and observability
- Maintain dashboards tracking key signals (errors, latency, usage, conversion)
- Analyze post-release data and surface insights for retrospectives
- Identify data quality or instrumentation gaps and recommend improvements

### Goals
- Ensure every project has clear, measurable success criteria with corresponding tracking
- Provide timely, accurate data to support prioritization and retrospectives
- Reduce reliance on anecdote by embedding metrics into the delivery process

### Typical Communication
- Works with Product Managers to finalize success metrics at project initiation
- Coordinates with Developers to implement analytics and observability instrumentation
- Shares dashboards and analysis with Project Managers for status reporting
- Presents post-release data summaries at retrospectives

---

## Lifecycle Phase Ownership (RACI-Lite)

The table below maps each lifecycle phase to primary (**P**) and supporting (**S**) role ownership. Use this as a quick reference to reduce ambiguity on who leads each phase.

> Full RACI detail: see [octoacme-raci-lite-template.md](./octoacme-raci-lite-template.md).

| Phase | Project Manager | Product Manager | Developers | QA/Testing | UX Designer | Technical Writer | Release Manager | Stakeholder Champion | Eng Manager/Tech Lead |
|---|---|---|---|---|---|---|---|---|---|
| **Initiation** | P | P | S | | S | | | S | S |
| **Planning** | P | P | S | S | S | S | S | S | S |
| **Execution / Tracking** | P | S | P | P | S | S | | S | P |
| **Release / Deployment** | S | S | S | P | | S | P | S | S |
| **Retrospective** | P | S | S | S | S | S | S | S | S |

**Key:** P = Primary owner / accountable · S = Supporting / consulted · (blank) = not typically involved in this phase

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

