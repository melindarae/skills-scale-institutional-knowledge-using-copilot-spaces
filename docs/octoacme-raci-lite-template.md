# OctoAcme RACI-Lite Template

Use this template to assign role ownership for each lifecycle phase on your project. Copy and fill in for each new project or release.

> **Reference:** Full role definitions are in [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md).

---

## How to use this template

1. List the roles involved in your project in the columns.
2. For each lifecycle phase, assign ownership using the key below.
3. Ensure every phase has exactly one **Accountable (A)** owner.
4. Share with the full team at project kickoff.

**Key:**
- **R** — Responsible: does the work
- **A** — Accountable: owns the outcome and decision (one per row)
- **C** — Consulted: provides input before or during
- **I** — Informed: notified of outcomes

---

## RACI Table

| Phase / Activity | Project Manager | Product Manager | Developers | QA/Testing | UX Designer | Technical Writer | Release Manager | Stakeholder Champion | Eng Manager / Tech Lead | Support Liaison | Security Partner | Data Partner |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| **INITIATION** | | | | | | | | | | | | |
| Problem statement & success metrics | C | A | C | | C | | | I | C | I | C | C |
| Stakeholder identification | A | R | | | | | | R | | | | |
| Project one-pager | R | A | C | | C | | | C | C | | C | C |
| Go/no-go decision | I | A | I | | | | | C | C | | | |
| **PLANNING** | | | | | | | | | | | | |
| Scope and backlog definition | C | A | C | C | C | C | C | C | C | | | |
| Capacity and milestone planning | A | C | C | | | | C | I | R | | | |
| Risk register creation | A | C | C | C | | | C | C | C | | C | |
| Definition of Done alignment | C | C | R | R | C | C | C | | A | | C | |
| **EXECUTION / TRACKING** | | | | | | | | | | | | |
| Feature development | C | C | R | C | C | | | | A | | | |
| UX design and prototyping | C | C | C | C | A | | | C | C | | | |
| Test plan and execution | C | C | C | A | | C | | | C | | | |
| Documentation updates | C | C | C | C | | A | | | | | | |
| Risk register updates (weekly) | A | C | I | | | | | I | C | | I | |
| Analytics instrumentation | C | C | R | | | | | | C | | | A |
| **RELEASE / DEPLOYMENT** | | | | | | | | | | | | |
| Release readiness sign-off | C | C | C | R | | C | A | C | C | | C | |
| Deployment execution | I | I | R | C | | | A | I | R | | | |
| Release notes | I | C | C | C | | R | A | I | | C | | |
| Stakeholder/support notification | C | C | | | | | R | A | | R | | |
| Post-deploy verification | I | I | R | A | | | R | | C | | | |
| **RETROSPECTIVE** | | | | | | | | | | | | |
| Retrospective facilitation | A | C | C | C | C | C | C | C | C | | | |
| Action item capture | R | C | C | C | C | C | C | C | C | | | |
| Metrics & outcome review | C | A | C | | | | | C | C | | | R |

---

## Project-Specific RACI

Copy this blank table for your project and fill in as needed.

**Project:** _[Project Name]_
**Date:** _[Date]_

| Phase / Activity | [Role 1] | [Role 2] | [Role 3] | [Role 4] | [Role 5] |
|---|---|---|---|---|---|
| [Activity] | | | | | |
| [Activity] | | | | | |
| [Activity] | | | | | |

---

## Checklist: Role Coverage Verification

Before kickoff, confirm the following to reduce accountability gaps:

- [ ] Every lifecycle phase has an identified Accountable (A) owner
- [ ] All roles listed in this project's RACI are staffed or have a named backup
- [ ] UX Designer is engaged before development begins on user-facing features
- [ ] Technical Writer is included in sprint planning for features with documentation needs
- [ ] Release Manager is identified and has reviewed the release checklist
- [ ] Stakeholder Champion has confirmed stakeholder availability for review gates
- [ ] Security/Compliance Partner has reviewed security requirements for the release
- [ ] Data/Analytics Partner has confirmed success metrics are instrumented
- [ ] Support/Customer Success Liaison has been briefed on upcoming release scope
