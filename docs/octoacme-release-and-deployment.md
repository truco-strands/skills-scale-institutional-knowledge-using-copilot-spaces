# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Manager Ownership
The **Release Manager** coordinates all production deployments and is accountable for:
- Planning release windows and coordinating deployment activities
- Facilitating release readiness reviews and go/no-go decisions
- Executing deployments and monitoring post-deployment health
- Managing rollback procedures when needed
- Continuously improving the release process

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release Requirements
These requirements must be validated before any production deployment:

| Requirement | Owner | Validation |
|-------------|-------|------------|
| All acceptance criteria met and PRs merged | Developers, PM | Project board shows all items in "Done" |
| Passing CI and security scans | Developers, Security Lead | CI green, no blocking vulnerabilities |
| Release notes drafted | Technical Writer | Release notes reviewed and approved |
| Rollback / mitigation plan documented | Release Manager | Rollback procedure tested in staging |
| Smoke tests prepared and passing | QA/Testing | Critical paths validated in staging |
| Customer communication plan ready | Customer Success Manager | Communication drafted and scheduled |

## Deployment Checklist
**Led by: Release Manager**

- [ ] Deployment window scheduled and communicated (if needed)
- [ ] Release readiness meeting completed with go/no-go decision
- [ ] Backup or snapshot taken (if applicable)
- [ ] Deploy to staging and run smoke tests (QA/Testing validates)
- [ ] Security Lead approval obtained for security-sensitive changes
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications (Release Manager + on-call)
- [ ] Monitor key metrics and error rates for 30 minutes post-deploy
- [ ] Announce release to stakeholders and support (Customer Success Manager coordinates customer comms)
- [ ] Update release documentation and close release ticket

## Rollback & Incident Playbook
**Coordinator: Release Manager**

If a deployment fails or causes a critical issue:
1. **Assess Impact** (Release Manager + on-call)
   - Determine severity and customer impact
   - Check if issue is deployment-related or pre-existing
2. **Trigger Incident Response** (Project Manager)
   - Notify on-call and incident response team
   - Create incident tracking issue
   - If security-related, notify Security Lead immediately
3. **Decide: Fix Forward vs. Rollback** (Release Manager + PM + on-call)
   - Rollback if: High customer impact, no quick fix available
   - Fix forward if: Low impact, fix can be deployed within 30 minutes
4. **Execute Rollback** (Release Manager)
   - Follow documented rollback procedure
   - Validate rollback success with smoke tests
   - Monitor for 15 minutes to confirm stability
5. **Post-Incident** (Project Manager + Technical Writer)
   - Triage root cause and capture action items
   - Update incident documentation
   - Schedule blameless retrospective within 48 hours

## Release Notes Template
**Author: Technical Writer** | **Reviewer: Product Manager, Release Manager**

- Release name / number:
- Date:
- Summary:
- Notable changes:
  - New features:
  - Improvements:
  - Bug fixes:
- Migration steps (if any):
- Breaking changes (if any):
- Known issues:
- Customer impact assessment (from Customer Success Manager)
- Rollback procedure (if different from standard)
