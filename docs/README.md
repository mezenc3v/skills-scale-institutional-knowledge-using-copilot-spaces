# OctoAcme Project Management Docs

Welcome to OctoAcme's project management practices documentation! This collection provides practical guidance, templates, and roles to help teams deliver projects consistently and transparently.

## Project Management Processes Summary

OctoAcme follows a structured, five-phase project lifecycle designed to balance rigor with iterative delivery. The process begins with **Initiation**, where new ideas are validated through a lightweight Project One-pager that captures the business need, success metrics, and stakeholder alignment. Once approved, projects move into **Planning**, where work is broken into shippable increments with clear acceptance criteria, dependencies are identified, and a release timeline is established. The **Execution & Tracking** phase emphasizes daily standups, weekly delivery syncs, and a GitHub Projects-based workflow with small PRs (≤400 lines), automated CI/CD checks, and quality gates including unit tests, integration tests, and security scanning. Finally, projects conclude with **Release & Deployment** (following patch/minor/major versioning) and **Retrospective & Continuous Improvement**, where learnings are captured and converted into actionable improvements.

### Core Principles

- **Customer-first:** Focus on customer value and usability
- **Iterative delivery:** Ship small, testable increments
- **Clear ownership:** Defined Project Manager (PM) and Product Lead roles
- **Data-informed:** Use metrics and success criteria to drive decisions
- **Psychological safety:** Encourage feedback, learning, and continuous improvement

### Key Organizational Roles

OctoAcme's structure emphasizes clear role separation and accountability:

- **Project Managers** coordinate delivery, manage schedules, risks, and communications, ensuring transparency across stakeholders
- **Product Managers** define what should be built, prioritize the backlog, and measure outcomes through success metrics
- **Developers** design, implement, and test features while collaborating on design reviews and risk identification
- **QA/Testing** validate quality and acceptance criteria

This separation of concerns is supported by a **Communication Cadence** that includes weekly PM-PdM syncs, twice-weekly standups for delivery teams, and monthly stakeholder updates, with escalation paths flowing from team-level triage through the PM, Product Lead, and Sponsor as needed.

### Quality & Risk Management

Quality and risk management are embedded throughout the entire lifecycle:

- All code changes require at least one approval, pass automated tests and linting, and are subject to security scanning before merge
- A formal **Risk Register** tracks identified risks with ID, description, impact, likelihood, mitigation plans, and status, reviewed weekly during syncs
- **Blocker Escalation** follows a three-level protocol: team-level triage in standups, PM escalation to Product Leadership and dependent teams, and sponsor-level involvement for business-impacting issues
- Definition of Done checklists and acceptance criteria templates ensure consistent execution

## Documentation Index

### Overview & Roles
- [Project Management Overview](./octoacme-project-management-overview.md) — Introduction to OctoAcme's approach, core roles, key artifacts, and high-level lifecycle
- [Roles & Personas](./octoacme-roles-and-personas.md) — Detailed responsibilities and communication patterns for Project Managers, Product Managers, Developers, and QA

### Project Lifecycle Phases
- [Project Initiation Guide](./octoacme-project-initiation.md) — Validate business need, align stakeholders, and create a lightweight plan
- [Project Planning](./octoacme-project-planning.md) — Break work into shippable increments, identify dependencies, and establish release timelines
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Day-to-day execution, team rhythm, PR workflows, quality gates, and blocker escalation
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Standardize releases to production, manage rollbacks, and verify deployments
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into actionable improvements

### Cross-Cutting Concerns
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Risk identification, lifecycle management, stakeholder communication, and escalation paths

## How to Use These Docs

1. **New to OctoAcme?** Start with [Project Management Overview](./octoacme-project-management-overview.md) for a high-level introduction
2. **Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md) and proceed through each phase
3. **Need a template or checklist?** Each phase document includes practical templates and checklists
4. **Managing risks or escalations?** Refer to [Risk Management & Communication](./octoacme-risks-and-communication.md)
5. **Contributing updates?** Use the issue template in `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` to suggest improvements

---

**Last updated:** June 2026

For questions or contributions, please open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
