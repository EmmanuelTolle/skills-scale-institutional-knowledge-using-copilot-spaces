# OctoAcme Project Management Processes

Welcome to the OctoAcme project management documentation. This guide provides a concise entry point to how OctoAcme runs projects, from initiation through retrospective and continuous improvement, and links to the detailed process documents maintained in this folder.

OctoAcme runs projects with an iterative, customer‑focused approach that moves work through a clear lifecycle: initiation (one‑pager, stakeholders, success metrics), planning (prioritized backlog, estimates, Definition of Done), execution (build, test, review), release (staged deployment and verifications), and close (retrospective and follow‑ups). Key artifacts — Project One‑pager, roadmap/release plan, backlog items with acceptance criteria, and a living risk register — form the single source of truth for project status and decisions.

Day‑to‑day execution uses a project board with columns (Backlog, Ready, In Progress, In Review, QA, Done) and a disciplined pull request workflow: keep PRs small, include the related issue and acceptance criteria, run automated tests and security scans in CI, and require review approvals before merging. Sprint planning pulls items that meet the Definition of Done and respects team capacity; risks and dependencies are tracked in the risk register and escalated according to the documented paths.

Roles and responsibilities are explicit: Product Managers define outcomes and measure success, Project Managers coordinate delivery and communications, Developers implement and test features, and QA validates acceptance criteria and runs test plans. Communication cadence includes daily standups, weekly delivery syncs, regular demos at sprint or milestone close, and monthly stakeholder updates. Quality practices require unit and integration tests, end‑to‑end smoke tests for critical flows, CI security scanning, and documented rollback/incident procedures for releases.

## Process Documentation

- [Project Management Overview](./octoacme-project-management-overview.md)  
  A concise introduction to OctoAcme's approach, core roles, key artifacts, and the high-level project lifecycle.

- [Project Initiation](./octoacme-project-initiation.md)  
  Guidance for validating and authorizing work, aligning stakeholders, and creating a lightweight plan (one-pager).

- [Project Planning](./octoacme-project-planning.md)  
  Turn approved initiatives into actionable plans: backlog creation, estimation, dependency and risk management, and release planning.

- [Execution & Tracking](./octoacme-execution-and-tracking.md)  
  Day-to-day execution guidance including team rhythm, workflows, PR standards, quality checks, and blocker escalation.

- [Risk Management & Communication](./octoacme-risks-and-communication.md)  
  How to identify, assess, mitigate, and communicate risks and dependencies, plus templates for status and incident updates.

- [Release & Deployment](./octoacme-release-and-deployment.md)  
  Release types, pre-release requirements, deployment checklist, rollback procedures, and release notes template.

- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)  
  Running retros, tracking action items, and closing the loop on continuous improvement.

- [Roles & Personas](./octoacme-roles-and-personas.md)  
  Definitions of common roles (Developers, Product Managers, Project Managers) and expectations used across our docs.

## How to use these docs
- New to OctoAcme? Start with the Project Management Overview.
- Starting a new project? Follow: Initiation → Planning → Execution → Release → Retrospective.
- Need role or responsibility clarification? See Roles & Personas.
- Managing risk or stakeholder comms? See Risk Management & Communication.

## Communication cadence (summary)
- Daily standups (team)
- Weekly delivery sync (progress & risks)
- Regular demo/review at sprint or milestone close
- Monthly stakeholder updates and ad-hoc escalations as needed

## Acceptance criteria for this README
- Links to all existing process docs are present and correct
- Includes a clear summary of processes, roles, communication, and quality practices
- Adds a single entry point for onboarding and navigation of OctoAcme process docs
