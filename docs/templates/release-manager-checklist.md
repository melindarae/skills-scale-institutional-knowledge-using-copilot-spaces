# Release Manager Checklist

Use this checklist to coordinate and verify each release from code-freeze to post-deploy confirmation. Adapt sections for patch, minor, or major releases as needed.

---

## Release Details

- **Release name / version:**
- **Release type:** (Patch / Minor / Major)
- **Planned deployment window:**
- **Release Manager:**
- **QA Sign-off owner:**
- **Product Manager sign-off:**

---

## Pre-Release: Code & Quality Gates

- [ ] Code-freeze date confirmed and communicated to the team
- [ ] All planned PRs merged; no unreviewed or draft PRs in scope
- [ ] CI pipeline passing (tests, lint, security scans)
- [ ] QA sign-off received (manual and/or automated acceptance tests)
- [ ] No open P0/P1 bugs targeting this release
- [ ] Dependency and license checks complete

---

## Pre-Release: Documentation & Communication

- [ ] Release notes drafted and reviewed (see [Release & Deployment Guide](../octoacme-release-and-deployment.md))
- [ ] User-facing documentation updated by Technical Writer
- [ ] Stakeholder Champion and support teams notified of upcoming release
- [ ] Deployment window communicated to on-call and operations teams
- [ ] Rollback / mitigation plan documented and shared

---

## Deployment

- [ ] Deployment window confirmed with operations / on-call
- [ ] Backup or snapshot taken (if applicable)
- [ ] Deploy to staging environment
- [ ] Smoke tests passed on staging
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Post-deploy smoke tests / verification complete
- [ ] Monitoring dashboards reviewed for anomalies (error rate, latency, usage)

---

## Post-Release

- [ ] Release announcement sent to stakeholders and support teams
- [ ] Release notes published / linked from the project repo
- [ ] Any post-deploy issues triaged and tickets created
- [ ] Rollback triggered? (if yes, fill in Incident section below)
- [ ] Release retrospective or hot-wash scheduled (for major releases)

---

## Incident Section *(complete only if rollback or incident occurred)*

- **Incident summary:**
- **Rollback triggered:** Yes / No
- **Time to detection:**
- **Time to rollback / mitigation:**
- **Root cause (preliminary):**
- **Follow-up action items:**

---

## Sign-off

| Role | Name | Date | Approved |
|---|---|---|---|
| QA / Testing | | | ☐ |
| Product Manager | | | ☐ |
| Release Manager | | | ☐ |

---

> **Related docs:** [Release & Deployment Guide](../octoacme-release-and-deployment.md) · [Roles & Personas](../octoacme-roles-and-personas.md) · [Risk Management & Communication](../octoacme-risks-and-communication.md)
