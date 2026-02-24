# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

## Cross-Functional Ownership at Release

| Activity | Owner | Contributors |
|---|---|---|
| Deployment execution and pipeline management | DevOps Engineer | Developers |
| Release notes and changelog | Product Manager | Business Analyst, Customer Support Lead |
| Monitoring and alerting setup | DevOps Engineer | Developers |
| Support runbook and FAQ updates | Customer Support Lead | Product Manager |
| Rollback decision and execution | DevOps Engineer | Project Manager, Product Manager |
| Stakeholder release communication | Project Manager | Customer Support Lead |
| Post-release smoke tests | DevOps Engineer | Developers, QA |

**Support Readiness**: Before any major release, the Customer Support Lead confirms that support documentation, escalation contacts, and FAQ pages are updated. This is a required gate before the release announcement is sent.

**Monitoring and Rollback**: DevOps Engineers own the monitoring dashboards and alert thresholds for each release. If post-deploy error rates exceed agreed thresholds, DevOps triggers the rollback procedure and notifies the Project Manager and Customer Support Lead immediately.

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
