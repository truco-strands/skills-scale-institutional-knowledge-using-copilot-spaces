# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management documentation hub! This README serves as your entry point to understanding how OctoAcme manages projects, from initiation through delivery and continuous improvement.

> 📋 **Related:** This documentation addresses [Issue #2](https://github.com/truco-strands/skills-scale-institutional-knowledge-using-copilot-spaces/issues/2)

## Overview

OctoAcme follows a structured, iterative approach to project management that emphasizes:

- **Customer-first delivery**: Prioritizing customer value and usability in every decision
- **Iterative increments**: Building and shipping small, testable features frequently
- **Clear ownership**: Defined roles and responsibilities for every project
- **Data-informed decisions**: Measuring impact and iterating based on evidence
- **Psychological safety**: Fostering a culture of feedback and continuous learning

## Key Workflows

OctoAcme's project lifecycle follows five core phases:

1. **Initiation**: Define the problem, identify stakeholders, and create a high-level timeline
2. **Planning**: Break work into actionable items, estimate effort, and manage dependencies
3. **Execution**: Build, test, review, and iterate with regular team syncs and demos
4. **Release**: Deploy to production with proper verification and stakeholder communication
5. **Retrospective**: Capture learnings and convert them into actionable improvements

## Core Roles & Personas

OctoAcme projects involve collaboration across multiple roles:

- **Project Manager (PM)**: Coordinates delivery, schedules, risk management, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success
- **Developers**: Implement features, write tests, and participate in design reviews
- **QA/Testing**: Validate quality standards and acceptance criteria
- **Release Manager**: Coordinates production deployments, ensures safe releases, and manages rollbacks
- **Customer Success Manager**: Ensures customer satisfaction, gathers feedback, and advocates for customer needs
- **Security Lead**: Integrates security throughout the lifecycle, reviews vulnerabilities, and coordinates incident response
- **Technical Writer**: Creates and maintains user guides, API documentation, and process documentation
- **Stakeholders**: Provide inputs, approvals, and strategic direction

Each role has specific responsibilities and communication patterns to ensure effective collaboration. See the [Roles and Personas](./octoacme-roles-and-personas.md) document for detailed definitions and interaction patterns.

## Communication Strategy

Effective communication is central to OctoAcme's project success:

- **Daily standups** (15 min): Progress updates, blockers, and dependencies
- **Weekly PM + PdM sync**: Alignment on priorities and risk review
- **Weekly delivery sync**: Team progress, demos, and flagged risks
- **Monthly stakeholder updates**: High-level status and milestone progress
- **Ad-hoc escalations**: Multi-level escalation path for critical issues

All communication follows a structured approach with templates for status updates, risk reporting, and incident communication.

## Quality Assurance Practices

OctoAcme maintains high quality standards through:

- **Test-driven development**: Unit tests for new logic, integration tests where applicable
- **Code review process**: Small PRs with at least one approval before merging
- **Automated CI/CD**: Automated tests, linting, and security scanning
- **Definition of Done**: Clear acceptance criteria for all backlog items
- **Smoke testing**: End-to-end tests for critical flows before each release
- **Post-deployment verification**: Monitoring and validation after every production deploy

## Documentation Index

### Core Process Documents

1. **[Project Management Overview](./octoacme-project-management-overview.md)**  
   High-level introduction to OctoAcme's project management principles, roles, artifacts, and lifecycle

2. **[Project Initiation Guide](./octoacme-project-initiation.md)**  
   Define and validate new projects, create one-pagers, and align stakeholders

3. **[Project Planning](./octoacme-project-planning.md)**  
   Turn approved initiatives into actionable plans with prioritized backlogs and release timelines

4. **[Execution & Tracking](./octoacme-execution-and-tracking.md)**  
   Day-to-day execution guidance, team rhythms, workflows, and quality practices

5. **[Risk Management & Communication](./octoacme-risks-and-communication.md)**  
   Identify, assess, and mitigate risks while maintaining effective stakeholder communication

6. **[Release & Deployment Guide](./octoacme-release-and-deployment.md)**  
   Standardized release processes, deployment checklists, and rollback procedures

7. **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)**  
   Capture learnings and convert them into actionable improvements after each milestone

8. **[Roles and Personas](./octoacme-roles-and-personas.md)**  
   Detailed definitions of team roles, responsibilities, goals, and communication patterns

## Getting Started

### For New Team Members

1. Start with the **[Project Management Overview](./octoacme-project-management-overview.md)** to understand our core principles
2. Review the **[Roles and Personas](./octoacme-roles-and-personas.md)** to understand your role and how you collaborate with others
3. Familiarize yourself with the phase-specific guides relevant to your current project stage

### For Project Managers

1. Use the **[Project Initiation Guide](./octoacme-project-initiation.md)** to kick off new projects
2. Follow the **[Project Planning](./octoacme-project-planning.md)** process to create actionable backlogs
3. Reference **[Execution & Tracking](./octoacme-execution-and-tracking.md)** for daily operations
4. Use **[Risk Management & Communication](./octoacme-risks-and-communication.md)** for stakeholder alignment

### For Product & Engineering Teams

1. Review **[Execution & Tracking](./octoacme-execution-and-tracking.md)** for workflows and quality standards
2. Use **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** for production deployments
3. Participate in **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** activities

## Key Artifacts

Throughout the project lifecycle, OctoAcme teams maintain these essential artifacts:

- **Project Charter / One-pager**: Problem statement, goals, success metrics, and timeline
- **Roadmap and Release Plan**: Milestone map with delivery dates
- **Sprint/Iteration Backlog**: Prioritized work items with acceptance criteria
- **Risk Register**: Identified risks with impact, likelihood, and mitigation plans
- **Definition of Done**: Quality standards and completion criteria
- **Retrospective Notes**: Learnings and action items from each milestone

## Using These Docs with Copilot Spaces

To leverage these documents with GitHub Copilot Spaces:

1. **Add relevant process documents** to your `.copilot/` directory for context-aware assistance:
   - Copy process documents most relevant to your current project phase (e.g., Planning, Execution)
   - Include the Roles and Personas document to help Copilot understand team structure
   - Maintain the same filenames for consistency
2. **Reference the Project Charter** in your project repository for AI-powered suggestions
3. **Use persona definitions** to shape role-specific guidance from Copilot

## Contributing

These process documents are living artifacts. If you identify improvements or gaps:

1. Open an issue in this repository describing the proposed change
2. Follow the standard PR process with clear documentation of updates
3. Ensure changes maintain consistency with OctoAcme's core principles

---

**Questions or feedback?** Reach out to your Project Manager or Product Lead for guidance on using these processes effectively.
