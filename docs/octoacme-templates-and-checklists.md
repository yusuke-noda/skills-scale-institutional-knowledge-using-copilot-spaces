# OctoAcme — Templates & Checklists

This document provides a RACI-style ownership matrix and cross-functional handoff checklists to reduce ambiguity and improve accountability across OctoAcme project ceremonies and artifacts.

---

## Role Abbreviations

| Abbreviation | Role |
|---|---|
| PM | Project Manager |
| PdM | Product Manager |
| Dev | Developer |
| UX | UX/UI Designer |
| QA | QA/Test Engineer |
| DO | DevOps Engineer |
| TW | Documentation/Technical Writer |

**RACI key:** **R** = Responsible (does the work) · **A** = Accountable (final decision/sign-off) · **C** = Consulted · **I** = Informed

---

## RACI Ownership Matrix

| Ceremony / Artifact | PM | PdM | Dev | UX | QA | DO | TW |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Project Charter / One-pager | A | R | C | C | I | I | C |
| Backlog creation & prioritization | C | A | C | C | C | I | I |
| Sprint/Iteration planning | A | R | R | C | C | I | I |
| Definition of Done (DoD) | A | C | R | C | R | C | I |
| UX designs & prototypes | I | C | C | A/R | I | I | I |
| Feature Ready for Dev checklist | C | A | C | R | C | I | I |
| Test plan & test cases | I | C | C | C | A/R | C | I |
| CI/CD pipeline & environments | I | I | C | I | C | A/R | I |
| Risk Register | A/R | C | C | I | C | C | I |
| Release Plan | A | C | C | I | C | R | C |
| Release Readiness checklist | A | C | C | I | R | R | C |
| Release Notes / Changelog | C | C | C | I | C | I | A/R |
| Retrospective facilitation | A/R | C | C | I | I | I | I |
| User / developer documentation | I | C | C | I | C | I | A/R |
| Stakeholder status updates | A/R | C | I | I | I | I | I |

---

## Feature Ready for Development Checklist

Use this checklist before moving a backlog item to **In Progress** to reduce ambiguity and late-stage rework.

**Owned by:** Product Manager (accountable) · UX/UI Designer (design sign-off) · QA/Test Engineer (testability review)

- [ ] Problem statement and user story written (PdM)
- [ ] Acceptance criteria defined and reviewed with QA (PdM + QA)
- [ ] UX designs or wireframes attached or linked (UX)
- [ ] Design reviewed and approved by PdM (PdM)
- [ ] Technical feasibility confirmed with at least one Developer (Dev)
- [ ] Definition of Done criteria applicable to this item confirmed (QA)
- [ ] Dependencies and integration points identified (PM)
- [ ] Item estimated (Dev)
- [ ] Item prioritized in sprint backlog (PM + PdM)

---

## Release Readiness Checklist

Use this checklist before any production deployment to confirm the release is safe and complete.

**Owned by:** Project Manager (accountable) · QA/Test Engineer · DevOps Engineer

### Quality Gates
- [ ] All acceptance criteria met and verified by QA (QA)
- [ ] All blocking and critical defects resolved or risk-accepted (QA + PdM)
- [ ] Automated test suite passing in CI (QA + DO)
- [ ] Security scan passing (DO)

### Deployment Preparation
- [ ] Deployment window scheduled and communicated (PM + DO)
- [ ] Staging deployment successful with smoke tests passing (DO + QA)
- [ ] Rollback plan documented and verified (DO)
- [ ] On-call/support team notified (PM)

### Documentation & Communication
- [ ] Release notes drafted and reviewed (TW + PdM)
- [ ] User-facing documentation updated for new or changed features (TW)
- [ ] Internal runbooks updated if infrastructure changed (DO + TW)
- [ ] Stakeholder announcement prepared (PM + PdM)

### Sign-off
- [ ] QA sign-off obtained (QA)
- [ ] PdM accepts release (PdM)
- [ ] PM confirms schedule (PM)
