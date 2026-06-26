# OctoAcme Project Management Documentation

Welcome to the central hub for OctoAcme's project management processes and guidance. This documentation is designed to help team members understand our approach, navigate the project lifecycle, and apply best practices across all phases of delivery.

## Overview

OctoAcme operates on a structured, customer-first approach to project management that emphasizes iterative delivery, clear ownership, and data-informed decision-making. Our core principles guide everything we do:

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## OctoAcme Project Lifecycle

OctoAcme follows a five-phase project lifecycle designed to ensure alignment, quality, and continuous improvement:

1. **Initiation**: Validate business need, identify stakeholders, confirm success metrics, and create a lightweight initial plan
2. **Planning**: Break work into shippable increments, define timelines, identify dependencies, and establish Definition of Done
3. **Execution**: Build, test, review, and iterate toward milestones using structured workflows and daily rhythms
4. **Release**: Deploy to production with verification, stakeholder communication, and rollback plans
5. **Retrospective**: Capture learnings and convert them into actionable improvements

## How OctoAcme Runs Projects

### Key Workflows & Execution Model

At the heart of OctoAcme's execution is a structured workflow built around small, reviewable pull requests (≤400 lines), automated testing in CI/CD pipelines, and a project board with standardized columns (Backlog → Ready → In Progress → In Review → QA → Done). The team operates on a consistent rhythm: daily standups (15 min) focused on progress and blockers, weekly delivery syncs for status updates and risk review, and sprint-based planning using acceptance criteria and Definition of Done. Work is estimated using T-shirt sizing or story points, and dependencies are explicitly captured in a risk register. This systematic approach enables the team to maintain velocity, surface blockers early, and reduce unplanned work through clear handoffs and communication gates.

### Roles & Responsibilities

Every OctoAcme project is led by clearly defined roles that ensure both operational discipline and strategic alignment:

- **Project Manager (PM)**: Coordinates delivery, manages schedules, risks, and communications. Facilitates meetings and maintains project documentation.
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success. Owns the product vision and validates solutions.
- **Developers**: Implement features, write tests, participate in reviews, and help identify technical risks.
- **QA/Testing**: Validate quality and acceptance criteria through manual and automated testing.
- **Stakeholders**: Provide inputs, approvals, and business context.

For detailed role definitions and responsibilities, see [Personas & Roles](./octoacme-roles-and-personas.md).

### Risk Management & Communication

OctoAcme maintains a formal risk management process where potential issues are identified during planning and ongoing execution, then assessed for impact (High/Med/Low) and likelihood. Each risk has an assigned owner and documented mitigation plan, reviewed weekly during syncs. Communication is structured around stakeholder groups with tailored cadences: weekly PM/PdM syncs, twice-weekly delivery standups, and monthly stakeholder updates. Escalation follows a clear three-level path—team triage → PM escalation to Product Lead and dependent teams → sponsor-level escalation for business-impacting issues. Status updates use a consistent template, and incident communication follows a blameless retrospective model to drive learning rather than blame.

### Quality Assurance & Continuous Improvement

Quality is embedded throughout OctoAcme's lifecycle through multiple checkpoints: unit and integration tests written by developers, end-to-end smoke tests for critical flows before release, security scanning in CI, and manual QA for feature acceptance when needed. Pre-release requirements include passing CI/security scans, drafted release notes, and a documented rollback plan. Retrospectives are held after each sprint, release, or milestone to discuss what went well, what could improve, and to prioritize 2–3 actionable items. These action items are tracked in the backlog with clear owners and due dates, reviewed weekly in PM syncs, and their impact is measured to ensure continuous improvement is tangible and tied to team outcomes.

## Documentation

Navigate to the process document that matches your current project phase:

| Document | Purpose |
|----------|---------|
| [Project Management Overview](./octoacme-project-management-overview.md) | Concise introduction to OctoAcme approach, roles, and key artifacts |
| [Project Initiation Guide](./octoacme-project-initiation.md) | Initial steps to validate and authorize work, align stakeholders, and create a lightweight plan |
| [Project Planning](./octoacme-project-planning.md) | Turn an approved initiative into an actionable plan and backlog for delivery |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Guidance for managing day-to-day execution and tracking progress toward milestones |
| [Risk Management & Communication](./octoacme-risks-and-communication.md) | How to identify, manage, and communicate risks and dependencies |
| [Release & Deployment Guide](./octoacme-release-and-deployment.md) | Standardize how OctoAcme releases features to production to reduce risk |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and convert them into actionable improvements |
| [Personas & Roles](./octoacme-roles-and-personas.md) | Typical roles and responsibilities in OctoAcme projects |

## Quick Links

- **[Add Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** — Request updates or additions to process documentation
- **Key Artifacts**: Project One-pagers, Risk Registers, Release Notes, Retrospective Notes

## Getting Started

**New to OctoAcme?**
Start with the [Project Management Overview](./octoacme-project-management-overview.md) for a high-level introduction to our approach, roles, and artifacts.

**Starting a new project?**
Follow the [Project Initiation Guide](./octoacme-project-initiation.md) to validate business need, identify stakeholders, and create your project one-pager.

**Currently executing a project?**
Check the [Execution & Tracking](./octoacme-execution-and-tracking.md) document for guidance on daily rhythms, workflows, quality standards, and blocker escalation.

**Need guidance on a specific topic?**
Use the documentation table above to navigate to the relevant lifecycle phase or process area.

## How to Use These Docs

- **Keep process docs updated**: As OctoAcme evolves, keep these documents current to reflect current practices and learnings.
- **Reference in project repos**: Link to relevant process docs in project READMEs and planning artifacts.
- **Use with Copilot Spaces**: Add process-specific docs to `.copilot/` if you want Copilot Spaces to use them as context for role-specific guidance.
- **Contribute improvements**: Use the [Add Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to propose updates based on team feedback and learnings.

---

**Questions?** Refer to the relevant process document or reach out to your Project Manager or Product Lead.
