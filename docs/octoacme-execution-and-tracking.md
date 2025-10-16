# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
### Project Board
Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done

**Column Definitions:**
- **Backlog**: Prioritized items not yet ready for development
- **Ready**: Items with clear acceptance criteria, no blockers, ready to be picked up
- **In Progress**: Actively being worked on by a developer
- **In Review**: PR open and awaiting code review
- **QA**: Code merged, awaiting QA validation
- **Done**: All quality gates passed, feature deployed or ready for release

### Pull Request Workflow
**Developer responsibilities:**
- Small PRs (<= 400 lines when possible) for easier review
- Include issue link and acceptance criteria in PR description
- Run automated tests and linting in CI before requesting review
- Tag appropriate reviewers (code owner, Security Lead for security-sensitive changes)

**Reviewer responsibilities:**
- Review within 24 hours (or team-agreed SLA)
- Provide constructive feedback focused on code quality, security, and maintainability
- Approve when quality standards are met
- At least one approval required before merging (or team-defined policy)

**Technical Writer involvement:**
- Tag Technical Writer on PRs that introduce new APIs or user-facing features
- Technical Writer reviews for documentation completeness and clarity

**Security Lead involvement:**
- Tag Security Lead on PRs touching authentication, authorization, data handling, or external integrations
- Security Lead reviews for security best practices and vulnerabilities

## Quality & Testing
**Quality is a shared responsibility across all roles**

### Code Quality
- **Developers**: Unit tests for new logic, integration tests where applicable
- **Developers**: Code review checklist includes test coverage and maintainability
- **Security Lead**: Security scanning in CI with vulnerability reviews

### Testing Strategy
- **QA/Testing**: End-to-end smoke tests for critical flows before release
- **QA/Testing**: Manual QA for feature acceptance when needed
- **QA/Testing**: Regression testing for bug fixes
- **Developers**: Performance testing for high-traffic features

### Documentation Quality
- **Technical Writer**: Documentation created or updated for all user-facing features
- **Technical Writer**: API documentation validated against implementation
- **Technical Writer**: Code examples tested and verified
- **Developers**: Inline code comments for complex logic
- **Product Manager**: Acceptance criteria include documentation requirements
- **Customer Success Manager**: Review documentation for customer clarity and completeness

### Quality Gates
Before marking work as "Done":
- [ ] All acceptance criteria met and verified
- [ ] Test coverage meets team standards (typically 80%+)
- [ ] Code review approved by at least one team member
- [ ] Security scan passing or vulnerabilities accepted by Security Lead
- [ ] Documentation updated (user guides, API docs, or runbooks as applicable)
- [ ] No high-priority bugs or blockers remaining

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
