# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
**Coordinated by: Project Manager**

### Stakeholder Mapping
Identify stakeholder groups and their communication needs:

| Stakeholder Group | Key Information Needs | Frequency | Owner |
|-------------------|----------------------|-----------|-------|
| Engineering Team | Technical decisions, blockers, dependencies | Daily | PM, Developers |
| Product Leadership | Progress, risks, milestone status | Weekly | PM, Product Manager |
| Customer Success | Feature availability, customer impact, known issues | Per release | Customer Success Manager |
| Sales | Roadmap updates, competitive features | Monthly | Product Manager |
| Support | Known issues, workarounds, documentation | Per release | Technical Writer, Customer Success |
| Security & Compliance | Vulnerabilities, security patches, compliance status | Weekly | Security Lead |
| Executive Sponsors | High-level status, major risks, budget/timeline | Monthly | PM, Product Manager |

### Communication Best Practices
- **Single source of truth**: Use project README or release doc for status
- **Tiered updates**: Provide appropriate detail level for each audience
- **Proactive communication**: Share risks and blockers early
- **Two-way feedback**: Encourage questions and input from stakeholders

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Security Risk Management
**Led by: Security Lead**

Security risks require special handling and rapid escalation:

### Security Risk Categories
- **Critical**: Immediate threat to data confidentiality, integrity, or availability
- **High**: Significant vulnerability requiring mitigation before next release
- **Medium**: Vulnerability that should be addressed in upcoming sprints
- **Low**: Minor security improvement or hardening opportunity

### Security Incident Response
When a security issue is identified:
1. **Immediate notification** to Security Lead (within 1 hour)
2. **Security Lead assessment** of severity and scope
3. **Incident response activation** if critical or high severity
4. **Security patch planning** coordinated with Release Manager
5. **Post-incident review** to prevent recurrence

### Security Communication Protocol
- **Internal**: Security Lead notifies PM, Release Manager, and affected teams
- **External**: Customer Success Manager coordinates customer communications (if customer-facing)
- **Compliance**: Security Lead ensures regulatory reporting if required
- **Transparency**: Blameless approach focused on learning and improvement

## Escalation Paths
- **Standard issues**: Team-level -> PM -> Product Lead -> Sponsor
- **Security incidents**: Security Lead -> PM -> Product Lead + Security on-call (parallel notification)
- **Customer escalations**: Customer Success Manager -> PM -> Product Lead
- **Release blockers**: Release Manager -> PM -> Product Lead (with go/no-go decision framework)
