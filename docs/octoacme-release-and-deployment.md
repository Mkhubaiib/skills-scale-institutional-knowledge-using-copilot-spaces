# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans (verified by DevOps Engineer)
- QA sign-off obtained with test results documented
- Release notes drafted (Release Manager with Product Manager input)
- Rollback / mitigation plan documented (DevOps Engineer)
- Smoke tests prepared and reviewed
- UX/UI verification completed for user-facing changes
- Infrastructure and capacity readiness confirmed (DevOps Engineer)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) and communicated by Release Manager
- [ ] Backup or snapshot (if applicable) - DevOps Engineer
- [ ] Deploy to staging and run smoke tests - DevOps Engineer with QA
- [ ] Deploy to production (automated pipeline preferred) - DevOps Engineer
- [ ] Run post-deploy verifications - QA and DevOps Engineer
- [ ] Announce release to stakeholders and support - Release Manager and Product Manager
- [ ] Monitor key metrics and alerts - DevOps Engineer
- [ ] Confirm user-facing changes display correctly - UX/UI Designer verification

For detailed handoff from QA to Release Manager and deployment procedures, see [Communication & Handoff Checklist](octoacme-communication-and-handoff-checklist.md).

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (DevOps Engineer initiates)
  - Rollback to last known-good release if necessary (executed by DevOps Engineer, approved by Release Manager)
  - Triage root cause and capture action items (cross-functional team)
  - Communicate status to stakeholders (Release Manager and Project Manager)
  - Schedule post-incident review (facilitated by Agile Coach or Project Manager)

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
