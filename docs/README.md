# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management framework. This README serves as a central index and entry point for all project management process documentation. Whether you're starting a new project, managing execution, or closing out work, you'll find comprehensive guidance organized by lifecycle phase and role.

## Table of Contents

- [Quick Navigation](#quick-navigation)
- [OctoAcme Principles](#octoacme-principles)
- [Project Lifecycle Overview](#project-lifecycle-overview)
- [Role Quick-Reference Guide](#role-quick-reference-guide)
- [How to Use These Docs](#how-to-use-these-docs)
- [Key Artifacts](#key-artifacts)

---

## Quick Navigation

### By Project Lifecycle Phase

| Phase | Document | Purpose |
|-------|----------|---------|
| **1. Initiation** | [Project Initiation Guide](./octoacme-project-initiation.md) | Validate business need, align stakeholders, create initial plan, make go/no-go decision |
| **2. Planning** | [Project Planning](./octoacme-project-planning.md) | Break work into shippable increments, define milestones, identify dependencies and risks |
| **3. Execution** | [Execution & Tracking](./octoacme-execution-and-tracking.md) | Day-to-day execution, team rhythm, quality standards, blocker escalation |
| **4. Release** | [Release & Deployment Guide](./octoacme-release-and-deployment.md) | Pre-release requirements, deployment checklists, rollback playbook, incident response |
| **5. Close & Learn** | [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Capture learnings, drive continuous improvement, track action items |

### Core References

| Document | Purpose |
|----------|---------|
| [Project Management Overview](./octoacme-project-management-overview.md) | Comprehensive introduction to OctoAcme's PM approach: principles, core roles, key artifacts, and high-level lifecycle |
| [Risk Management & Communication](./octoacme-risks-and-communication.md) | How to identify, manage, and communicate risks; stakeholder communication templates; escalation paths |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Detailed responsibilities, goals, and typical communication patterns for Project Managers, Product Managers, Developers, and QA |

---

## OctoAcme Principles

These five principles guide how OctoAcme runs all projects:

- **Customer-first**: Prioritize customer value and usability in every decision
- **Iterative delivery**: Deliver small, testable increments rather than monolithic releases
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead with defined responsibilities
- **Data-informed**: Measure impact, collect evidence, and iterate based on what you learn
- **Psychological safety**: Encourage feedback, learning, and blameless problem-solving

---

## Project Lifecycle Overview

OctoAcme projects follow a five-stage lifecycle:

### 1. Initiation
**Goal**: Validate the business need and decide whether to proceed to planning.

**Key Activities**:
- Confirm problem statement and measurable success metrics
- Identify stakeholders and champions
- Create a Project One-pager
- Make go/no-go decision

**Artifacts**: Project One-pager, stakeholder list, initial risk list

**Reference**: [Project Initiation Guide](./octoacme-project-initiation.md)

---

### 2. Planning
**Goal**: Convert an approved initiative into an actionable plan and prioritized backlog.

**Key Activities**:
- Hold project kickoff with stakeholders and delivery team
- Create prioritized backlog with acceptance criteria
- Estimate scope and define Definition of Done
- Identify dependencies and integration points
- Create release plan and milestone map

**Artifacts**: Prioritized backlog, release timeline, risk register, test plan

**Reference**: [Project Planning](./octoacme-project-planning.md)

---

### 3. Execution
**Goal**: Build and iterate toward milestones with predictable team rhythm and quality standards.

**Key Activities**:
- Daily standups (15 min) focused on progress, blockers, dependencies
- Weekly delivery sync to show progress and flag risks
- Pull requests with code review and testing
- Ongoing risk monitoring and escalation
- Demo/review at sprint end or milestone

**Artifacts**: Sprint/iteration backlog, project board, CI/CD pipeline, risk register updates

**Reference**: [Execution & Tracking](./octoacme-execution-and-tracking.md)

---

### 4. Release
**Goal**: Deploy features to production safely and with full observability.

**Key Activities**:
- Verify all acceptance criteria met and tests passing
- Run smoke tests on staging
- Execute deployment to production
- Post-deploy verification and monitoring
- Announce release to stakeholders

**Artifacts**: Release notes, deployment checklist, rollback plan, incident playbook

**Reference**: [Release & Deployment Guide](./octoacme-release-and-deployment.md)

---

### 5. Close & Retrospective
**Goal**: Capture learnings and convert them into actionable improvements.

**Key Activities**:
- Run retrospective meeting (45–75 minutes)
- Identify what went well and what could improve
- Document action items with clear owners and due dates
- Track improvements and measure impact

**Artifacts**: Retrospective notes, action items, learnings documentation

**Reference**: [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

---

## Role Quick-Reference Guide

### Project Manager (PM)
**Primary Focus**: Coordinate delivery, manage schedule, risks, and communications

**Key Responsibilities**:
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings and maintain project documentation
- Ensure consistent status reporting and stakeholder alignment
- Escalate blockers and cross-team issues

**When to Reference**: [Roles & Personas](./octoacme-roles-and-personas.md#project-managers), [Execution & Tracking](./octoacme-execution-and-tracking.md), [Risk Management & Communication](./octoacme-risks-and-communication.md)

---

### Product Manager (PdM)
**Primary Focus**: Define what to build and measure outcomes

**Key Responsibilities**:
- Define problem statements and success metrics
- Prioritize roadmap and backlog
- Collaborate with engineering on trade-offs
- Validate solutions through user research and metrics
- Accept features against acceptance criteria

**When to Reference**: [Roles & Personas](./octoacme-roles-and-personas.md#product-managers), [Project Initiation Guide](./octoacme-project-initiation.md), [Project Planning](./octoacme-project-planning.md)

---

### Developers
**Primary Focus**: Design, build, test, and deliver software components

**Key Responsibilities**:
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and identifying technical risks
- Collaborate on defining Definition of Done

**When to Reference**: [Roles & Personas](./octoacme-roles-and-personas.md#developers), [Execution & Tracking](./octoacme-execution-and-tracking.md), [Project Planning](./octoacme-project-planning.md#definition-of-done)

---

### QA / Testing
**Primary Focus**: Validate quality and ensure acceptance criteria are met

**Key Responsibilities**:
- Design test plans and test cases
- Execute manual and automated testing
- Validate acceptance criteria before marking work done
- Identify and triage defects
- Participate in quality standards definition

**When to Reference**: [Execution & Tracking](./octoacme-execution-and-tracking.md#quality--testing), [Project Planning](./octoacme-project-planning.md), [Release & Deployment Guide](./octoacme-release-and-deployment.md#pre-release-requirements)

---

## How to Use These Docs

### For New Team Members
1. Start with [Project Management Overview](./octoacme-project-management-overview.md) to understand the big picture
2. Read [Roles & Personas](./octoacme-roles-and-personas.md) to understand your role and others
3. Bookmark this README as your reference guide

### For Project Initiation
1. Review [Project Initiation Guide](./octoacme-project-initiation.md)
2. Use the Project One-pager template to document the business case
3. Reference [Roles & Personas](./octoacme-roles-and-personas.md) to assign ownership

### For Project Planning
1. Read [Project Planning](./octoacme-project-planning.md)
2. Set up your project board and create your initial backlog
3. Reference [Risk Management & Communication](./octoacme-risks-and-communication.md) to create your risk register

### For Day-to-Day Execution
1. Follow the guidance in [Execution & Tracking](./octoacme-execution-and-tracking.md)
2. Use [Risk Management & Communication](./octoacme-risks-and-communication.md) for escalation paths
3. Reference [Release & Deployment Guide](./octoacme-release-and-deployment.md) as you approach milestones

### For Release
1. Review the pre-release checklist in [Release & Deployment Guide](./octoacme-release-and-deployment.md)
2. Prepare rollback and incident playbooks
3. Follow the deployment checklist to the letter

### For Learning & Improvement
1. Schedule a retrospective using [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
2. Track action items in your project backlog or issues
3. Review outstanding action items in weekly syncs

---

## Key Artifacts

OctoAcme projects produce and maintain these key artifacts:

| Artifact | Used When | Reference |
|----------|-----------|-----------|
| **Project One-pager** | Initiation & Planning | [Project Initiation Guide](./octoacme-project-initiation.md#project-one-pager-template) |
| **Prioritized Backlog** | Planning & Execution | [Project Planning](./octoacme-project-planning.md#backlog-item-template) |
| **Definition of Done** | Planning & Execution | [Project Planning](./octoacme-project-planning.md#sprint--iteration-planning) |
| **Risk Register** | Planning, Execution & Release | [Risk Management & Communication](./octoacme-risks-and-communication.md#risk-register) |
| **Project Board** | Execution | [Execution & Tracking](./octoacme-execution-and-tracking.md#workflows) |
| **Release Notes** | Release | [Release & Deployment Guide](./octoacme-release-and-deployment.md#release-notes-template) |
| **Retrospective Notes** | Close & Learn | [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md#structure) |

---

## Communication Cadence

| Cadence | Attendees | Purpose |
|---------|-----------|---------|
| **Daily standup** | Delivery team | Progress, blockers, dependencies (15 min) |
| **Weekly PM–PdM sync** | PM + Product Manager | Alignment on roadmap and execution (30–45 min) |
| **Weekly delivery sync** | PM + delivery team | Progress update, flagged risks (30–45 min) |
| **Sprint planning** | Delivery team | Pull backlog items, estimate, commit (depends on sprint length) |
| **Demo / Review** | Team + stakeholders | Show progress, gather feedback (45–60 min) |
| **Retrospective** | Team | Capture learnings, identify improvements (45–75 min) |
| **Monthly stakeholder update** | Stakeholders + PM + PdM | Status, metrics, risks (30 min) |

---

## Support & Questions

For questions about OctoAcme processes:
1. Consult the relevant document linked above
2. Check the templates and checklists in each guide
3. Reach out to your Project Manager or Product Lead
4. Propose improvements by creating an issue using the [Process Doc Update template](./../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)

---

## Document Version History

| Date | Version | Summary |
|------|---------|---------|
| 2026-07-01 | 1.0 | Initial comprehensive README created, consolidating OctoAcme PM framework documentation |

---

**Last Updated**: 2026-07-01

For the latest updates, always check this README and the individual process documents in the `docs/` folder.
