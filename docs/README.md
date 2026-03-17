# OctoAcme Project Management Docs

## Welcome

Welcome to OctoAcme's project management documentation. This README is your single entry point to all program management guidance, processes, templates, and best practices. These docs help teams deliver value reliably and minimize single-person dependency risk.

---

## OctoAcme Project Management Processes

OctoAcme follows a five-phase project lifecycle: **Initiation, Planning, Execution, Release, and Close & Retrospective**. Each project starts with business need validation and a lightweight "Project One-pager" that captures the problem statement, goals, success metrics, stakeholders, and initial timeline. The team then moves into Planning, where work is broken into shippable increments with prioritized backlogs, clear acceptance criteria, and a Definition of Done.

During **Execution**, the team uses GitHub Projects boards and follows a consistent rhythm: daily standups (15 min), weekly delivery syncs, and demos at each milestone. Pull requests are kept small (≤400 lines when possible) with automated testing and code review before merge. Quality assurance is embedded throughout—unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical paths. Security scanning in CI and manual QA for feature acceptance are standard. Risks are captured in a register with clear owners, mitigation plans, and weekly reviews; blockers follow a three-level escalation path: team-level → PM → sponsor.

At **Release**, the team stages deployment with pre-release checks (CI passing, security scans, smoke tests), then deploys to production with post-deployment verification and announcements. Following each release and significant milestone, **Retrospectives** are held to capture learnings and convert them into tracked action items with clear owners and due dates. This continuous improvement culture, combined with transparent documentation and role clarity, enables consistent, repeatable project success.

**Key Roles:** Project Manager (coordinates delivery, schedules, risks, communications), Product Manager (defines outcomes, prioritizes backlog, measures success), Developers (implement, test, identify technical risks), and QA/Testing (validate quality). **Communication Cadence:** Weekly PM + PdM sync, twice-weekly delivery standups, monthly stakeholder updates, and ad-hoc escalations as needed. All key artifacts—charters, backlogs, risk registers, retrospective notes—are stored in the project repository to ensure transparency and accessibility.

---

## Process Documentation

Select a document below for detailed guidance on each phase and function:

### Foundational Docs
- **[Project Management Overview](octoacme-project-management-overview.md)**  
  Concise introduction to OctoAcme's approach, core roles, key artifacts, and communication cadence.

- **[Roles & Personas](octoacme-roles-and-personas.md)**  
  Detailed responsibilities, goals, and typical communication patterns for each role.

### Lifecycle Phases

#### Phase 1: Initiation
- **[Project Initiation Guide](octoacme-project-initiation.md)**  
  Steps to validate business need, align stakeholders, create a Project One-pager, and make go/no-go decisions.

#### Phase 2: Planning
- **[Project Planning](octoacme-project-planning.md)**  
  Break work into shippable increments, define Definition of Done, estimate scope, identify dependencies, and create release plans.

#### Phase 3: Execution
- **[Execution & Tracking](octoacme-execution-and-tracking.md)**  
  Day-to-day workflows: standups, syncs, PR standards, quality & testing, metrics tracking, and blocker escalation.

#### Phase 4: Release
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)**  
  Standardized release processes, pre-release requirements, deployment checklists, rollback playbooks, and release notes.

#### Phase 5: Continuous Improvement
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)**  
  How to run effective retrospectives, track action items, and build a culture of continuous improvement.

### Cross-Cutting Guidance
- **[Risk Management & Communication](octoacme-risks-and-communication.md)**  
  Risk register structure, escalation paths, stakeholder communication templates, and incident protocols.

---

## Quick Reference

### Communication Cadence
- **Weekly PM + PdM sync** — Strategy, roadmap, risks
- **Twice-weekly delivery standups** — Progress, blockers, dependencies
- **Monthly stakeholder updates** — High-level milestones and decisions
- **Ad-hoc escalations** — Business-impacting issues

### Key Artifacts
| Artifact | Purpose |
|----------|---------|
| **Project One-pager** | Problem, goal, success metrics, stakeholders, timeline |
| **Backlog** | Prioritized work with acceptance criteria |
| **Risk Register** | Track risks, impact, likelihood, mitigation, status |
| **Definition of Done** | Standards for what "done" means |
| **Retrospective Notes** | Learnings and tracked action items |

### Core Roles at a Glance
- **Project Manager:** Coordinates delivery, schedules, risks, communications
- **Product Manager:** Defines outcomes, prioritizes backlog, measures success
- **Developers:** Implement features, test, identify technical risks
- **QA/Testing:** Validate quality and acceptance criteria

---

## How to Use These Docs

1. **New to OctoAcme?** Start with [Project Management Overview](octoacme-project-management-overview.md) and [Roles & Personas](octoacme-roles-and-personas.md).

2. **Starting a new project?** Follow [Project Initiation Guide](octoacme-project-initiation.md) → [Project Planning](octoacme-project-planning.md).

3. **Managing execution?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risk Management & Communication](octoacme-risks-and-communication.md).

4. **Releasing?** See [Release & Deployment Guide](octoacme-release-and-deployment.md).

5. **Improving processes?** Check [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md).

---

## Proposing Improvements

OctoAcme's project management docs are living artifacts. To propose additions, clarifications, or improvements:

1. Use the [Process Docs Update template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)
2. Describe the gap or improvement
3. Include suggested content if possible
4. Discuss with stakeholders for feedback

All proposals are reviewed and tracked for transparency and continuous improvement.

---

## About This Copilot Space

- **Source:** Program management docs live in `docs/`
- **Templates:** Issue templates for updates live in `.github/ISSUE_TEMPLATE/`
- **Purpose:** Centralize knowledge, make processes searchable, accelerate onboarding, and enable consistent, repeatable project execution across all teams.

---

**Last updated:** 2026-03-17  
**Document version:** 1.0
