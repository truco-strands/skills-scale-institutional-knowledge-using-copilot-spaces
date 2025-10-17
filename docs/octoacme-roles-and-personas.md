# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

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

## Release Manager

### Role Summary
Release Managers coordinate and execute production deployments, ensuring safe and reliable releases. They own the release process, manage deployment schedules, and coordinate release activities across teams.

### Responsibilities
- Plan and schedule release windows and deployment activities
- Coordinate release readiness reviews and go/no-go decisions
- Manage release pipelines, automation, and deployment tooling
- Execute production deployments and monitor post-deployment health
- Maintain release documentation and runbooks
- Coordinate rollback procedures when issues arise
- Track release metrics and continuously improve the release process

### Goals
- Achieve zero-downtime deployments with minimal customer impact
- Reduce time from code complete to production
- Maintain high deployment success rate and minimize rollbacks
- Ensure clear communication and coordination during releases

### Typical Communication
- Pre-release readiness meetings with PM, QA, and development teams
- Release status updates to stakeholders during deployment windows
- Post-deployment reports and retrospectives
- Coordination with on-call and support teams for release monitoring

### Interactions with Other Roles
- **Project Managers**: Align release schedules with project milestones and timelines
- **Developers**: Coordinate merge deadlines, review deployment requirements
- **QA/Testing**: Validate release readiness and coordinate smoke testing
- **Security Lead**: Review security scans and approve security-cleared releases
- **Technical Writer**: Ensure release notes and documentation are ready
- **Customer Success Manager**: Communicate release schedules and feature availability

---

## Customer Success Manager

### Role Summary
Customer Success Managers ensure customers achieve their desired outcomes using OctoAcme's products. They act as the voice of the customer, gathering feedback and advocating for customer needs during project planning and execution.

### Responsibilities
- Onboard new customers and ensure successful product adoption
- Gather and synthesize customer feedback and feature requests
- Advocate for customer needs in prioritization discussions
- Communicate product updates, releases, and changes to customers
- Escalate critical customer issues and coordinate resolution
- Track customer health metrics and identify at-risk accounts
- Create customer-facing documentation and success resources

### Goals
- Maximize customer satisfaction and retention
- Ensure customers achieve value from the product
- Reduce time-to-value for new customers
- Provide actionable customer insights to product and engineering teams

### Typical Communication
- Regular check-ins with key customer accounts
- Monthly customer feedback synthesis reports to Product and PM
- Release impact assessments and customer communication plans
- Escalation updates for high-priority customer issues

### Interactions with Other Roles
- **Product Managers**: Share customer insights to inform roadmap prioritization
- **Project Managers**: Provide customer context for feature requirements
- **Developers**: Escalate and clarify customer-reported issues
- **Release Manager**: Coordinate customer communications for releases
- **Technical Writer**: Collaborate on customer-facing documentation and guides
- **Support/QA**: Partner on issue resolution and quality feedback loops

---

## Security Lead

### Role Summary
Security Leads ensure that security is integrated throughout the project lifecycle. They assess security risks, review code and infrastructure changes, and ensure compliance with security policies and best practices.

### Responsibilities
- Conduct security reviews during project planning and design
- Review and triage security scanning alerts and vulnerabilities
- Define security requirements and acceptance criteria
- Approve security-sensitive changes before production deployment
- Coordinate incident response for security issues
- Maintain security documentation and threat models
- Provide security training and guidance to development teams

### Goals
- Minimize security vulnerabilities in production systems
- Ensure compliance with security policies and regulations
- Enable teams to build secure features without blocking velocity
- Reduce time to detect and respond to security incidents

### Typical Communication
- Security review sessions during project planning and design
- Weekly security scan reviews with development teams
- Security incident updates and post-incident reports
- Security training sessions and best practice guidance

### Interactions with Other Roles
- **Developers**: Provide security guidance during code reviews
- **Project Managers**: Identify security risks and define mitigation timelines
- **Release Manager**: Approve security-cleared releases and coordinate security patches
- **QA/Testing**: Define security test cases and validation procedures
- **Product Managers**: Balance security requirements with feature priorities
- **Technical Writer**: Review security documentation for accuracy and completeness

---

## Technical Writer

### Role Summary
Technical Writers create and maintain clear, accurate, and user-friendly documentation for internal teams and external customers. They ensure that product features, processes, and technical concepts are well-documented and accessible.

### Responsibilities
- Write and maintain user guides, API documentation, and technical references
- Create and update internal process documentation and runbooks
- Collaborate with developers to document new features and APIs
- Review and edit technical content for clarity and accuracy
- Maintain documentation infrastructure and publishing workflows
- Conduct documentation reviews and gather feedback
- Create visual aids, diagrams, and tutorials to enhance understanding

### Goals
- Ensure comprehensive and up-to-date documentation for all features
- Reduce time users spend searching for information
- Improve clarity and accessibility of technical content
- Enable self-service for common tasks and questions

### Typical Communication
- Weekly syncs with Product and Engineering to identify documentation needs
- Reviews with subject matter experts for technical accuracy
- Documentation planning sessions during project kickoffs
- Feedback sessions with customer success teams on documentation gaps

### Interactions with Other Roles
- **Developers**: Collaborate on API docs, code samples, and technical references
- **Product Managers**: Document product requirements and feature specifications
- **Project Managers**: Maintain process documentation and project templates
- **Customer Success Manager**: Address documentation gaps identified by customers
- **Release Manager**: Create release notes and deployment documentation
- **Security Lead**: Document security policies and compliance procedures
- **QA/Testing**: Document test procedures and quality standards

---

## Role Collaboration Matrix

This matrix shows the key touchpoints and collaboration patterns between roles:

| Role | Primary Collaborators | Key Touchpoints | Communication Frequency |
|------|----------------------|-----------------|------------------------|
| **Developer** | PM, PdM, QA, Technical Writer, Security Lead | Standup, code reviews, design discussions, documentation reviews | Daily to weekly |
| **Product Manager** | PM, Developers, Customer Success, Stakeholders | Roadmap planning, prioritization, acceptance criteria | Weekly |
| **Project Manager** | PdM, Developers, Release Manager, All roles | Status updates, risk reviews, milestone planning | Daily to weekly |
| **Release Manager** | PM, Developers, QA, Security Lead, Technical Writer | Release planning, deployment coordination, go/no-go reviews | Per release cycle |
| **Customer Success Manager** | PdM, PM, Technical Writer, Developers | Customer feedback, feature requests, escalations | Weekly to monthly |
| **Security Lead** | Developers, PM, Release Manager, QA | Security reviews, vulnerability triage, incident response | Weekly + ad-hoc |
| **Technical Writer** | Developers, PdM, PM, Customer Success, Release Manager | Documentation planning, reviews, release notes | Weekly |
| **QA/Testing** | Developers, PM, Release Manager, Security Lead | Test planning, acceptance validation, release readiness | Daily to weekly |

## Cross-Role Collaboration Checklists

### Project Kickoff Checklist
- [ ] **Project Manager**: Schedule kickoff meeting with all stakeholders
- [ ] **Product Manager**: Present problem statement, goals, and success metrics
- [ ] **Security Lead**: Identify security requirements and compliance needs
- [ ] **Technical Writer**: Document project overview and initial architecture
- [ ] **Customer Success Manager**: Share customer context and expected impact
- [ ] **Release Manager**: Define release strategy and deployment approach
- [ ] **Developers**: Review technical feasibility and raise concerns
- [ ] **QA/Testing**: Define test strategy and acceptance criteria

### Pre-Release Readiness Checklist
- [ ] **Developers**: All code merged, PRs approved, CI passing
- [ ] **QA/Testing**: All acceptance criteria validated, smoke tests passing
- [ ] **Security Lead**: Security scans reviewed, vulnerabilities addressed or accepted
- [ ] **Technical Writer**: Release notes complete, documentation updated
- [ ] **Release Manager**: Deployment plan reviewed, rollback procedures ready
- [ ] **Project Manager**: Stakeholders informed, risks reviewed
- [ ] **Customer Success Manager**: Customer communication plan ready
- [ ] **Product Manager**: Success metrics and monitoring dashboards configured

### Incident Response Checklist
- [ ] **On-call/Developer**: Triage and assess impact
- [ ] **Project Manager**: Notify stakeholders and coordinate response
- [ ] **Release Manager**: Evaluate rollback options if deployment-related
- [ ] **Security Lead**: Assess if security-related, activate security incident response if needed
- [ ] **Customer Success Manager**: Prepare customer communications if customer-facing
- [ ] **Technical Writer**: Document incident timeline and resolution steps
- [ ] **All**: Participate in post-incident retrospective and action items

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

