# OctoAcme Project Management Documentation Hub

Welcome to the OctoAcme Project Management Documentation Hub. This repository contains comprehensive guides for running projects at OctoAcme, covering everything from initial concept through retrospectives and continuous improvement.

## Quick Overview: How OctoAcme Manages Projects

OctoAcme operates on a structured lifecycle approach that guides projects from initial conception through closure and continuous improvement. The organization follows five distinct phases: **Initiation** (validating business need and stakeholder alignment), **Planning** (breaking work into shippable increments with clear acceptance criteria), **Execution** (day-to-day delivery with regular standups and tracking), **Release** (standardized deployment with pre-release verification and rollback planning), and **Close & Retrospective** (capturing learnings and driving improvements). This iterative, customer-first approach emphasizes delivering small, testable increments while maintaining psychological safety and data-informed decision-making.

Communication and transparency are central to OctoAcme's execution model. Teams operate on a regular cadence including **daily standups** (15 minutes) focused on progress and blockers, **weekly delivery syncs** for status updates and risk review, and **monthly stakeholder updates** for broader visibility. Cross-functional teams collaborate through a project board workflow with standardized columns (Backlog → Ready → In Progress → In Review → QA → Done), and all pull requests must be smaller than 400 lines when possible, include issue links and acceptance criteria, pass CI/automated tests, and receive at least one approval before merging.

Quality assurance and continuous improvement are non-negotiable practices at OctoAcme. Before any release, teams must confirm acceptance criteria are met, pass security scanning and CI checks, and complete smoke tests in staging environments; deployments follow standardized checklists and include post-deploy verification and rollback mitigation planning. The organization prioritizes **test coverage** through unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, and security scanning in CI pipelines. Finally, OctoAcme institutionalizes learning through **retrospectives** held after each sprint, release, or milestone—using 45–75 minute timeboxed sessions to identify what went well, areas for improvement, and 2–3 prioritized action items with clear owners and due dates.

---

## Core Documentation

Navigate to the guides below based on your project phase or role:

### 1. [Project Management Overview](octoacme-project-management-overview.md)
**Start here to understand OctoAcme's approach.**
- Core principles and values (customer-first, iterative delivery, clear ownership, data-informed, psychological safety)
- Key roles: Project Manager, Product Manager, Developers, QA/Testing
- High-level project lifecycle (Initiation → Planning → Execution → Release → Close & Retrospective)
- Key artifacts and communication cadence

### 2. [Project Initiation Guide](octoacme-project-initiation.md)
**Define and validate a new project idea.**
- Confirm business need and measurable outcomes
- Identify stakeholders and champions
- Define success criteria and initial timeline
- Complete the Project One-pager template
- Move to planning when success metrics are clear and stakeholders align

### 3. [Project Planning Guide](octoacme-project-planning.md)
**Turn an approved initiative into an actionable plan.**
- Break work into shippable increments
- Create prioritized backlog with acceptance criteria
- Estimate scope using T-shirt sizing or story points
- Define Definition of Done (DoD)
- Identify dependencies and integration points
- Create release plan and milestone map

### 4. [Execution & Tracking](octoacme-execution-and-tracking.md)
**Manage day-to-day execution and track progress.**
- Team rhythm: daily standups, weekly delivery syncs, sprint/milestone reviews
- Project board workflow and pull request conventions
- Quality and testing standards
- Reporting metrics and blocker escalation procedures
- Execution checklist for CI, demos, and risk management

### 5. [Risk Management & Communication](octoacme-risks-and-communication.md)
**Identify, manage, and communicate risks effectively.**
- Risk Register structure and lifecycle
- Stakeholder communication strategies
- Weekly status templates and incident communication
- Escalation paths (team-level → PM → Product Lead → Sponsor)
- Security incident procedures

### 6. [Release & Deployment Guide](octoacme-release-and-deployment.md)
**Standardize release processes and reduce deployment risk.**
- Release types: Patch, Minor, Major
- Pre-release requirements and deployment checklist
- Rollback and incident playbook
- Release notes template
- Post-deploy verification procedures

### 7. [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
**Capture learnings and drive process improvements.**
- Structure: what went well, what could improve, action items
- How to run a retrospective (45–75 minutes, anonymous ideas)
- Tracking and measuring improvements
- Action item template with owners and due dates
- Building a continuous improvement culture

### 8. [Roles & Personas](octoacme-roles-and-personas.md)
**Understand key roles and responsibilities.**
- **Developers**: implement features, write tests, participate in design and code reviews
- **Product Managers**: define outcomes, prioritize backlog, measure success
- **Project Managers**: coordinate delivery, manage schedules and risks, facilitate communications
- Typical communication patterns for each role

---

## Key Principles at a Glance

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named PM and Product Lead roles
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and blameless retrospectives

---

## How to Use These Docs

1. **During Project Phases**: Reference the guide that matches your current phase (initiation → planning → execution → release → close)
2. **For Role-Specific Guidance**: Check the Roles & Personas document to understand responsibilities and communication patterns
3. **For Risk & Communication**: Use the Risk Management guide to maintain visibility and escalate appropriately
4. **For Continuous Improvement**: Review retrospective notes and action items to refine team processes
5. **In Your Project Repository**: Keep your Project Charter updated in your repo's README or `.github/` folder
6. **For Copilot Spaces**: Add process-specific customizations to `.copilot/` to ground Copilot's knowledge in your team's practices

---

## Quick Reference: Project Lifecycle at OctoAcme

```
Initiation → Planning → Execution → Release → Close & Retrospective
     ↓            ↓          ↓          ↓              ↓
  One-pager   Backlog    Standups   Deploy      Learnings &
  & approval  & DoD      & PRs      & verify     improvements
```

---

## Questions?

If you have questions about OctoAcme's project management approach:
- Check the relevant process document from the links above
- Reach out to your Project Manager or Product Lead
- Review retrospective notes and lessons learned from similar projects
