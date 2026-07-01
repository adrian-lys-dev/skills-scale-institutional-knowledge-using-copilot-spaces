# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management framework. This README provides a comprehensive guide to our processes, roles, and best practices for managing projects from initiation through closure.

## OctoAcme Project Management Overview

OctoAcme operates on a customer-first, iterative delivery model grounded in five key principles: customer value prioritization, iterative delivery of small testable increments, clear ownership through named Project Managers and Product Leads, data-informed decision-making, and psychological safety. The project lifecycle spans five phases—Initiation, Planning, Execution, Release, and Close & Retrospective—each with defined deliverables and decision gates.

During Initiation, teams validate business need through a Project One-pager that captures problem statements, success metrics, stakeholders, and timeline. This moves into Planning, where work is broken into shippable increments with prioritized backlogs, acceptance criteria, and release milestones. Once approved, the team enters Execution, where daily standups and weekly delivery syncs track progress against a project board using standardized columns (Backlog, Ready, In Progress, In Review, QA, Done).

OctoAcme defines four core personas with distinct responsibilities: Developers implement features, write tests, and collaborate on design reviews; Product Managers define what to build by owning the vision and prioritizing backlogs; Project Managers coordinate delivery and manage schedules; and QA/Testing validates quality and acceptance criteria. Each project has clear ownership—a named PM handles coordination while a Product Lead owns outcomes.

Quality, communication, and risk management are formalized throughout the lifecycle. Teams enforce rigorous quality standards through unit tests, integration tests, end-to-end smoke tests, security scanning, and manual QA. Pull requests are kept small (≤400 lines) with acceptance criteria and require at least one approval. Communication follows a consistent cadence: daily standups (15 min), weekly delivery syncs, and monthly stakeholder updates. Risk management uses a formalized Risk Register reviewed weekly, with escalation paths from team level to PM to Product Lead to Sponsor when needed.

## Quick Navigation

### By Project Lifecycle Phase

- **[Project Initiation](octoacme-project-initiation.md)** - Validate business need, align stakeholders, create initial plan
  - When: For new project ideas or feature proposals
  - Deliverables: Project One-pager, stakeholder list, timeline, risk list
  - Decision gate: Success metrics clear, stakeholders aligned, team availability confirmed

- **[Project Planning](octoacme-project-planning.md)** - Break work into shippable increments, define milestones
  - When: After initiation approval
  - Activities: Kickoff meeting, prioritized backlog, estimation, Definition of Done
  - Outputs: Release plan, milestone map, risk and dependency documentation

- **[Execution & Tracking](octoacme-execution-and-tracking.md)** - Day-to-day execution, team rhythm, quality standards
  - Team rhythm: Daily standups (15 min), weekly delivery sync, sprint/milestone demos
  - Workflows: Project board columns, PR workflow (≤400 lines, issue link, approval required)
  - Quality: Unit tests, integration tests, E2E smoke tests, security scanning, manual QA

- **[Release & Deployment](octoacme-release-and-deployment.md)** - Pre-release requirements, deployment checklists, rollback playbook
  - Release types: Patch, Minor, Major
  - Pre-release: All acceptance criteria met, passing CI/security scans, release notes, rollback plan
  - Post-release: Run verifications, announce to stakeholders, prepare incident playbook

- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** - Capture learnings, drive continuous improvement
  - When: After each sprint, release, or important milestone
  - Structure: What went well, what could improve, action items with owners and due dates
  - Focus: 2–3 top action items, measure impact, celebrate improvements

### Core References

- **[Project Management Overview](octoacme-project-management-overview.md)** - Principles, roles, artifacts, and high-level lifecycle
  - Core roles: PM, Product Manager, Developers, QA/Testing, Stakeholders
  - Key artifacts: Project Charter, Roadmap, Sprint Backlog, Risk Register, Retrospective notes
  - Communication cadence: Weekly PM + PdM sync, twice-weekly standups, monthly stakeholder updates

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** - Risk register, stakeholder communication, escalation paths
  - Risk lifecycle: Identify → Assess → Mitigate → Monitor
  - Escalation: Team-level → PM → Product Lead → Sponsor
  - Communication templates: Weekly status, incident communication, blameless retrospectives

- **[Roles & Personas](octoacme-roles-and-personas.md)** - Responsibilities and typical communication for each role
  - Developers: Implement features, write tests, participate in design/code reviews, identify technical risks
  - Product Managers: Define problem statements, prioritize backlog, validate solutions, measure outcomes
  - Project Managers: Create/maintain plans, manage risks/dependencies, facilitate meetings, ensure documentation
  - QA/Testing: Validate quality, confirm acceptance criteria, execute test plans

## Quick-Reference by Role

### For Developers
Start with [Execution & Tracking](octoacme-execution-and-tracking.md) for PR workflow and quality standards, then review [Project Planning](octoacme-project-planning.md) for acceptance criteria and Definition of Done. Reference [Roles & Personas](octoacme-roles-and-personas.md) for developer responsibilities and communication patterns.

### For Product Managers
Begin with [Project Initiation](octoacme-project-initiation.md) to validate business need, move to [Project Planning](octoacme-project-planning.md) to prioritize the backlog, and use [Risk Management & Communication](octoacme-risks-and-communication.md) for stakeholder updates. Refer to [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) to measure outcomes and iterate.

### For Project Managers
Review [Project Management Overview](octoacme-project-management-overview.md) for foundational principles, then use [Project Planning](octoacme-project-planning.md) to structure your plan. Reference [Risk Management & Communication](octoacme-risks-and-communication.md) for escalation paths and stakeholder communication templates. Use [Execution & Tracking](octoacme-execution-and-tracking.md) for day-to-day cadence and [Release & Deployment](octoacme-release-and-deployment.md) for release planning.

### For QA/Testing
Review [Execution & Tracking](octoacme-execution-and-tracking.md) for quality standards and test requirements, and [Release & Deployment](octoacme-release-and-deployment.md) for pre-release and smoke test requirements. Reference [Project Planning](octoacme-project-planning.md) for Definition of Done and acceptance criteria.

## How to Use These Docs

1. **New to OctoAcme?** Start with [Project Management Overview](octoacme-project-management-overview.md) for a high-level introduction, then review the Quick-Reference section above for your role.

2. **Starting a new project?** Follow the phases in order: [Initiation](octoacme-project-initiation.md) → [Planning](octoacme-project-planning.md) → [Execution & Tracking](octoacme-execution-and-tracking.md) → [Release & Deployment](octoacme-release-and-deployment.md) → [Retrospective](octoacme-retrospective-and-continuous-improvement.md).

3. **Need a template or checklist?** Each process doc includes templates (One-pager, Backlog Item, Release Notes, etc.) and checklists to guide your work.

4. **Managing risks or communicating with stakeholders?** Reference [Risk Management & Communication](octoacme-risks-and-communication.md) for templates and escalation paths.

5. **Want to understand team roles?** See [Roles & Personas](octoacme-roles-and-personas.md) for responsibility definitions and typical communication patterns.

## Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named PM and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Contributing to These Docs

To propose updates, improvements, or new content to the OctoAcme process documentation, use the ["Add Content to Project Management Process Docs" issue template](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml). This ensures your proposed changes are reviewed for alignment with existing processes and team feedback is incorporated before publication.
