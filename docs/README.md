# OctoAcme Project Management Docs

## Overview

OctoAcme uses a structured, phase-based project management approach built on principles of iterative delivery, clear ownership, customer focus, and data-informed decisions. This documentation suite provides guidance for managing projects from initiation through closure.

### Core Principles
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named Product Manager (PdM) and Project Manager (PM)
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Management Processes

OctoAcme follows a five-phase lifecycle with integrated risk management, continuous communication, and quality assurance throughout:

### 1. **Project Initiation** ([octoacme-project-initiation.md](./octoacme-project-initiation.md))
Validate business need, confirm measurable outcomes, identify stakeholders and champions, and create a lightweight Project One-pager to decide go/no-go for planning.

### 2. **Project Planning** ([octoacme-project-planning.md](./octoacme-project-planning.md))
Turn an approved initiative into an actionable backlog and delivery roadmap. Break work into shippable increments, estimate scope, define acceptance criteria and Definition of Done, and identify dependencies and risks.

### 3. **Execution & Tracking** ([octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md))
Manage day-to-day delivery, track progress toward milestones, and maintain quality standards. Use GitHub Projects for visibility, small PRs with automated testing and reviews, and regular demos and standups for alignment.

### 4. **Risk & Communication** ([octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md))
Identify and manage risks through a Risk Register, maintain stakeholder communication via weekly status updates and incident reports, and escalate issues through defined paths (team → PM → Product Lead → Sponsor).

### 5. **Release & Deployment** ([octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md))
Standardize release processes to minimize risk. Define release types (patch, minor, major), validate pre-release requirements including security scans and smoke tests, and implement rollback/incident playbooks.

### 6. **Retrospectives & Continuous Improvement** ([octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md))
Capture learnings after sprints, releases, or milestones. Run structured retrospectives, convert action items into backlog work with clear owners and timelines, and measure the impact of improvements.

## Key Roles & Responsibilities

OctoAcme defines four core roles that enable consistent, cross-functional collaboration:

- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, measures success
- **Project Manager (PM)**: Coordinates delivery, manages schedules, risks, and stakeholder communication
- **Developers**: Implement features, collaborate on design, write tests and documentation
- **QA/Testing**: Validate quality, verify acceptance criteria, identify defects

For detailed persona descriptions, see [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md).

## Communication Cadence

- **Daily**: 15-minute team standups (focus on progress, blockers, dependencies)
- **Twice-weekly**: Delivery standups during execution phase
- **Weekly**: PM + PdM alignment sync
- **Weekly**: Stakeholder updates and risk reviews
- **Monthly**: Stakeholder briefings and roadmap updates
- **Ad-hoc**: Escalations for blockers or business-impacting issues

## Quality & Testing Standards

- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed
- PR reviews with at least one approval required before merge
- Small PRs (≤400 lines) to maintain review quality

## Additional Resources

- **Project Management Overview** ([octoacme-project-management-overview.md](./octoacme-project-management-overview.md)) — High-level framework, core roles, key artifacts, and lifecycle
- **Personas** ([octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md)) — Detailed definitions of Product Manager, Project Manager, Developer, and QA roles

## Getting Started

**New to OctoAcme?** Start with [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) for a high-level understanding of our approach, then dive into the specific phase documents based on where your project is in its lifecycle.

**Starting a new project?** Begin with [octoacme-project-initiation.md](./octoacme-project-initiation.md) to validate your idea and align stakeholders.

**In execution?** Reference [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md) for day-to-day workflows, and [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md) for risk and communication management.

**Planning a release?** See [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md) for standardized release processes.

**Wrapping up?** Use [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md) to capture learnings and drive continuous improvement.
