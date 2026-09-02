# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Stakeholders / Sponsors

### Role Summary
Stakeholders and Sponsors provide business context, strategic direction, and executive oversight for projects. They approve scope, budget, and major decisions, and serve as the escalation point for business-impacting issues.

### Responsibilities
- Define business objectives and success metrics for projects
- Approve project scope, timeline, and resource allocation
- Review and approve major milestone deliverables
- Serve as escalation point for Level 3 issues and business risks
- Communicate project status to leadership and other stakeholders
- Provide feedback and approval on key decisions

### Goals
- Ensure projects deliver measurable business value
- Maintain budget and timeline commitments
- Minimize business-impacting risks and delays
- Enable cross-organizational alignment

### Typical Communication
- Monthly stakeholder updates and reviews
- Escalation notifications for high-impact issues
- Go/no-go decision meetings at key gates
- Executive dashboards and risk summaries

### Interaction with Other Roles
- **Product Managers**: Approve strategic direction and resource allocation; align on business objectives
- **Project Managers**: Receive escalations for Level 3 issues; provide go/no-go decisions at key gates
- **Developers & Technical Leads**: Understand business priorities and constraints; receive architectural guidance on solutions

---

## QA / Testing Lead

### Role Summary
QA leads and testing professionals ensure product quality by developing test strategies, defining acceptance criteria, and validating that features meet quality standards before release.

### Responsibilities
- Develop and maintain test plans and QA strategy
- Define acceptance criteria with Product and Development teams
- Execute manual and automated testing
- Identify and triage defects
- Validate that quality standards are met before release
- Track test coverage and quality metrics
- Recommend process improvements based on defect patterns

### Goals
- Ensure high-quality releases that meet customer expectations
- Reduce production defects and support burden
- Provide clear, actionable feedback to development teams
- Enable confident deployment with reduced rollback risk

### Typical Communication
- Sprint planning and acceptance criteria reviews
- Daily standup updates on testing progress
- Defect reports and quality dashboards
- Pre-release QA sign-offs

### Interaction with Other Roles
- **Developers**: Collaborate on acceptance criteria; receive timely feedback on defects
- **Product Managers**: Validate feature acceptance; ensure quality metrics align with business expectations
- **Project Managers**: Report QA status and blockers; coordinate pre-release sign-offs
- **Operations/DevOps**: Coordinate smoke testing and post-deployment verification

---

## Technical Lead / Architect

### Role Summary
Technical Leads provide architectural guidance, oversee technical quality, and help teams make sound engineering decisions that balance short-term delivery with long-term maintainability.

### Responsibilities
- Define technical architecture and design patterns
- Review code and provide technical feedback
- Identify technical risks and propose mitigations
- Mentor developers and facilitate knowledge sharing
- Ensure compliance with coding standards and best practices
- Guide technology selection and dependency decisions

### Goals
- Deliver technically sound, maintainable solutions
- Reduce technical debt and future rework
- Improve team capability and code quality
- Minimize technical risks to release timelines

### Typical Communication
- Technical design reviews and architecture discussions
- Code review feedback and guidance
- Planning estimations and risk assessment
- Technical documentation and knowledge sharing

### Interaction with Other Roles
- **Developers**: Provide technical guidance and code review feedback; mentor on best practices
- **Project Managers**: Assess technical risks and effort estimates; communicate blockers and trade-offs
- **QA/Testing Lead**: Discuss testability and quality standards; recommend testing strategies
- **Operations/DevOps**: Ensure operational concerns are considered in design; coordinate on monitoring and logging

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate sprint ceremonies, remove impediments, and help teams follow agile practices and principles. They enable team velocity and continuous improvement.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Remove impediments and blockers that hinder team progress
- Coach team members on agile practices and collaboration
- Track sprint metrics and burndown progress
- Foster psychological safety and team engagement
- Help teams adopt and improve agile processes

### Goals
- Enable consistent, predictable team velocity
- Improve team collaboration and communication
- Reduce cycle time and time-to-delivery
- Build a high-performing, self-organizing team

### Typical Communication
- Facilitation of all sprint ceremonies
- One-on-one coaching conversations
- Sprint metrics and velocity dashboards
- Process improvement recommendations

### Interaction with Other Roles
- **Project Managers**: Coordinate on timelines and milestones; escalate business-impacting blockers
- **Developers**: Remove technical and process impediments; coach on agile practices
- **Product Managers**: Help communicate backlog priorities and acceptance criteria clarity
- **All Roles**: Foster collaboration and ensure team ceremonies are effective

---

## Operations / DevOps

### Role Summary
Operations and DevOps professionals ensure reliable infrastructure, streamlined deployments, and production monitoring. They enable rapid, safe delivery and minimize operational risks.

### Responsibilities
- Maintain and optimize infrastructure and deployment pipelines
- Implement automated testing, deployment, and monitoring
- Manage production environments and incident response
- Define rollback procedures and disaster recovery plans
- Monitor application performance, errors, and availability
- Collaborate with development teams on operational concerns
- Support post-deployment verification and smoke testing

### Goals
- Enable fast, reliable deployments with minimal risk
- Maintain high availability and performance standards
- Reduce mean time to recovery (MTTR) for incidents
- Improve deployment frequency and reliability

### Typical Communication
- Pre-release deployment planning and checklists
- Incident escalation and response coordination
- Infrastructure and monitoring dashboards
- Post-deployment verification and rollout communication

### Interaction with Other Roles
- **Developers**: Collaborate on operational requirements and logging; provide deployment support
- **QA/Testing Lead**: Coordinate smoke testing and post-deployment verification
- **Project Managers**: Communicate deployment readiness and risk; coordinate release schedules
- **Technical Leads**: Ensure architectural decisions support operational requirements

---

## UX / Design

### Role Summary
UX and Design professionals collaborate on user experience, design systems, and usability validation. They ensure products are intuitive, accessible, and meet user needs.

### Responsibilities
- Define user experience strategy and design principles
- Create wireframes, prototypes, and design specifications
- Conduct user research and usability testing
- Maintain design systems and component libraries
- Collaborate with developers on implementation quality
- Advocate for accessibility and inclusive design
- Validate that delivered features match design intent

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce user friction and support burden
- Ensure consistent design and brand experience
- Drive user satisfaction and retention

### Typical Communication
- Design reviews and feedback sessions
- User research and usability testing results
- Design specifications and component documentation
- Collaboration with developers during implementation

### Interaction with Other Roles
- **Product Managers**: Define user needs and validate solutions; align on roadmap priorities
- **Developers**: Collaborate on implementation quality and design fidelity; provide design feedback
- **QA/Testing Lead**: Define usability acceptance criteria; participate in user testing
- **Project Managers**: Communicate design timeline and dependencies

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Consider how multiple personas interact and communicate to achieve project goals.
