# OctoAcme Project Management Docs

## Overview

Welcome to OctoAcme's project management documentation. This guide serves as the central hub for understanding how we plan, execute, and deliver projects across our organization.

OctoAcme follows an **iterative, customer-first approach** to project delivery, emphasizing:
- Clear ownership and accountability
- Data-informed decision making
- Continuous improvement and psychological safety
- Small, testable increments that deliver value early and often

### Core Principles

- **Customer-first**: Prioritize customer value and usability in every decision
- **Iterative delivery**: Ship small, testable increments rather than big-bang releases
- **Clear ownership**: Each project has defined roles with specific responsibilities
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and blameless retrospectives

---

## Project Lifecycle Workflows

OctoAcme projects follow a five-stage lifecycle:

### 1. Initiation
Define the problem, identify stakeholders, and create a lightweight project charter (one-pager) with success metrics and high-level timeline. [Learn more →](octoacme-project-initiation.md)

**Key deliverables**: Project one-pager, stakeholder list, initial timeline, resource needs

### 2. Planning
Break work into shippable increments, identify dependencies and risks, and create a prioritized backlog with clear acceptance criteria. [Learn more →](octoacme-project-planning.md)

**Key deliverables**: Prioritized backlog, release plan, Definition of Done, risk register

### 3. Execution & Tracking
Manage day-to-day delivery with daily standups, weekly syncs, and regular demos. Track progress using project boards and maintain quality through automated testing and code reviews. [Learn more →](octoacme-execution-and-tracking.md)

**Key activities**: Daily standups, PR workflows, quality checks, burndown tracking

### 4. Release & Deployment
Deploy features to production following standardized release processes with proper verification, rollback plans, and stakeholder communication. [Learn more →](octoacme-release-and-deployment.md)

**Key activities**: Pre-release checks, deployment checklists, smoke tests, release notes

### 5. Retrospective & Continuous Improvement
Capture learnings after each sprint, release, or milestone and convert them into actionable improvements. [Learn more →](octoacme-retrospective-and-continuous-improvement.md)

**Key activities**: What went well/what to improve, action items with owners, tracking improvements

---

## Key Roles & Personas

OctoAcme projects involve cross-functional teams with clearly defined responsibilities:

### Project Manager (PM)
Coordinates delivery, manages schedules, risks, and communications. Facilitates meetings and maintains project documentation.
- Weekly status updates and stakeholder reports
- Risk register and decision log maintenance
- Cross-team coordination

### Product Manager (PdM)
Defines what should be built, prioritizes the backlog, and measures outcomes against customer and business value.
- Product vision and roadmap ownership
- Success metrics and acceptance criteria
- Stakeholder alignment and prioritization decisions

### Developers
Design, build, test, and deliver software components that meet acceptance criteria and quality standards.
- Feature implementation and testing
- Code reviews and technical design
- Risk identification and estimation

### Release Manager
Orchestrates release planning, execution, communications, and incident response.
- Release schedules and deployment coordination
- Pre-release readiness reviews
- Incident response and rollback procedures

### QA Lead
Defines and oversees the test strategy, manages test resources, and reports on product quality.
- Test strategy and planning
- Quality gates and test coverage
- Bug triage coordination

### Business Analyst
Gathers, refines, and documents requirements, bridging gaps between business stakeholders and delivery teams.
- Requirements elicitation and documentation
- Stakeholder interviews and validation
- Process flows and functional specifications

### UX Designer
Designs and validates user experiences, creates wireframes and prototypes, and champions usability.
- User research and usability testing
- Wireframes, mockups, and prototypes
- Design systems and UI guidelines

[Full role descriptions →](octoacme-roles-and-personas.md)

---

## Communication Approaches

Clear, consistent communication is essential for project success:

### Regular Cadence
- **Daily standups** (15 min): Progress, blockers, dependencies
- **Weekly PM/PdM sync**: Alignment on priorities, risks, and decisions
- **Twice-weekly team standups**: Delivery coordination (or as agreed)
- **Sprint demos**: Show progress at milestone completion
- **Monthly stakeholder updates**: High-level progress and upcoming milestones

### Status Reporting Template
- Progress this week
- Next steps
- Risks & blockers
- Asks / decisions needed

### Escalation Paths
- **Level 1**: Team-level triage in daily standup
- **Level 2**: PM escalates to Product Lead and dependent teams
- **Level 3**: Sponsor-level escalation for business-impacting issues

[Risk management and communication details →](octoacme-risks-and-communication.md)

---

## Quality Assurance Practices

Quality is built into every stage of the delivery process:

### Testing Strategy
- **Unit tests**: For all new logic and business rules
- **Integration tests**: Where components interact
- **End-to-end smoke tests**: Critical user flows before release
- **Security scanning**: Automated in CI/CD pipeline
- **Manual QA**: Feature acceptance when needed

### Pull Request (PR) Standards
- Small PRs (≤ 400 lines when possible)
- Include issue link and acceptance criteria in description
- Automated tests and linting pass in CI
- At least one approval before merging (or team-defined policy)

### Project Board Workflow
**Backlog → Ready → In Progress → In Review → QA → Done**

Each stage has clear entry/exit criteria to maintain quality and visibility.

### Definition of Done (DoD)
Agreed criteria that must be met before work is considered complete, typically including:
- Code complete and reviewed
- Tests written and passing
- Documentation updated
- Acceptance criteria validated
- Security scans passed

---

## Key Artifacts

OctoAcme projects maintain these core documents:

- **Project Charter / One-pager**: Problem statement, goals, success metrics
- **Roadmap and Release Plan**: Timeline, milestones, dependencies
- **Sprint/Iteration Backlog**: Prioritized work items with acceptance criteria
- **Risk Register**: Identified risks with mitigation plans
- **Retrospective Notes**: Learnings and action items for improvement

[Project management overview →](octoacme-project-management-overview.md)

---

## Complete Process Documentation Index

- [Project Management Overview](octoacme-project-management-overview.md) - High-level principles, roles, and lifecycle
- [Project Initiation Guide](octoacme-project-initiation.md) - How to start a new project
- [Project Planning](octoacme-project-planning.md) - From initiative to actionable backlog
- [Execution & Tracking](octoacme-execution-and-tracking.md) - Day-to-day delivery management
- [Risk Management & Communication](octoacme-risks-and-communication.md) - Identifying and managing risks
- [Release & Deployment Guide](octoacme-release-and-deployment.md) - Production deployment standards
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) - Learning and improving
- [Roles & Personas](octoacme-roles-and-personas.md) - Detailed role descriptions and responsibilities

---

## How to Use These Docs

### For New Team Members
Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand our principles and approach, then review the [Roles & Personas](octoacme-roles-and-personas.md) to understand your responsibilities.

### For Project Managers
Use the lifecycle guides ([Initiation](octoacme-project-initiation.md) → [Planning](octoacme-project-planning.md) → [Execution](octoacme-execution-and-tracking.md) → [Release](octoacme-release-and-deployment.md) → [Retrospective](octoacme-retrospective-and-continuous-improvement.md)) as checklists and templates for your projects.

### For Developers & Contributors
Focus on [Execution & Tracking](octoacme-execution-and-tracking.md) for daily workflows and quality standards.

### For Copilot Spaces
Add relevant process docs to `.copilot/` in your project repository to provide context-specific guidance during development.

---

## Questions or Feedback?

These processes are living documents. If you have suggestions for improvement or need clarification, please open an issue or speak with your Project Manager.
