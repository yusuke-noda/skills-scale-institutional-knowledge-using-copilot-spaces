# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged (Dev + QA)
- Passing CI and security scans (DevOps)
- Release notes drafted (Documentation/Technical Writer)
- Rollback / mitigation plan documented (DevOps)
- Smoke tests prepared (QA)
- User-facing documentation updated (Documentation/Technical Writer)

Use the **Release Readiness Checklist** in [`octoacme-templates-and-checklists.md`](./octoacme-templates-and-checklists.md) for the full sign-off process.

## Deployment Checklist
- [ ] Deployment window scheduled (PM + DevOps)
- [ ] Backup or snapshot (if applicable) (DevOps)
- [ ] Deploy to staging and run smoke tests (DevOps + QA)
- [ ] Deploy to production (automated pipeline preferred) (DevOps)
- [ ] Run post-deploy verifications (DevOps + QA)
- [ ] Announce release to stakeholders and support (PM + Documentation/Technical Writer)

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
