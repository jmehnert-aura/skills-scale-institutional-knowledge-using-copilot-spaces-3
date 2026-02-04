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

## Release Manager

### Role Summary
Release Managers own the release planning, schedules, and coordinate handoff between development, QA, and operations. They ensure releases are properly scoped, communicated, and deployed with minimal risk.

### Responsibilities
- Plan and schedule releases based on product roadmap and team capacity
- Coordinate handoffs between development, QA Lead, and operations teams
- Ensure all pre-release requirements are met (CI passing, docs updated, approvals)
- Manage release notes and changelog documentation
- Monitor deployment health and coordinate rollback if needed
- Facilitate release retrospectives to improve the process

### Goals
- Deliver reliable, predictable releases on schedule
- Minimize production incidents and deployment risks
- Maintain clear communication with all stakeholders during releases
- Continuously improve release process efficiency

### Typical Communication
- Weekly release planning meetings with Project Manager and QA Lead
- Release status updates to stakeholders and support teams
- Deployment coordination with operations and developers
- Post-release retrospectives and incident debriefs

### Key Collaboration Points
- **Project Manager**: Aligns release schedules with project milestones and dependencies
- **QA Lead**: Coordinates testing completion and sign-off before releases
- **Developers**: Ensures code is ready, tested, and documented for release
- **Product Manager**: Validates feature completeness and business readiness
- **Technical Writer**: Confirms documentation is updated before release

---

## Stakeholder Liaison

### Role Summary
Stakeholder Liaisons serve as the main communication bridge between the project team and executive leadership, external partners, and key stakeholders. They ensure feedback flows in both directions and progress is clearly reported.

### Responsibilities
- Facilitate regular stakeholder updates and executive briefings
- Collect and synthesize stakeholder feedback for the project team
- Escalate concerns and risks to appropriate leadership levels
- Ensure stakeholder expectations are aligned with project reality
- Coordinate stakeholder participation in key milestones and reviews
- Manage external partner communications and expectations

### Goals
- Maintain stakeholder satisfaction and trust
- Ensure timely, transparent communication of project status
- Minimize surprises and misaligned expectations
- Build and maintain strong relationships with key partners

### Typical Communication
- Monthly executive briefings and stakeholder reports
- Weekly check-ins with Project Manager for status updates
- Ad-hoc escalations and decision requests
- Stakeholder feedback synthesis and sharing

### Key Collaboration Points
- **Project Manager**: Primary source for project status, risks, and decisions needed
- **Product Manager**: Aligns stakeholder feedback with product vision and priorities
- **Release Manager**: Communicates release schedules and impacts to stakeholders
- **All roles**: Gathers input for status reports and shares stakeholder feedback

---

## QA Lead

### Role Summary
QA Leads champion quality throughout sprints and releases, managing test plans, coordinating bug triage, and ensuring acceptance criteria are met. They work closely with developers and product managers to maintain quality standards.

### Responsibilities
- Develop and maintain test strategies and plans for each release
- Coordinate testing activities across functional and regression test suites
- Lead bug triage sessions with developers and Product Manager
- Define and track quality metrics and testing coverage
- Ensure acceptance criteria are testable and validated
- Provide release sign-off based on quality gates

### Goals
- Maintain high product quality and minimize production defects
- Ensure comprehensive test coverage across features
- Foster a culture of quality ownership across the team
- Reduce time-to-detection and time-to-fix for bugs

### Typical Communication
- Daily coordination with developers during sprint testing
- Weekly test status updates to Project Manager
- Bug triage meetings with dev team and Product Manager
- Pre-release sign-off meetings with Release Manager

### Key Collaboration Points
- **Developers**: Coordinates bug fixes, test automation, and quality improvements
- **Product Manager**: Validates acceptance criteria and prioritizes quality issues
- **Release Manager**: Provides quality sign-off and coordinates testing schedules
- **Project Manager**: Reports testing progress and identifies quality risks

---

## Technical Writer

### Role Summary
Technical Writers ensure process documentation, user guides, and API documentation are accurate, up-to-date, and accessible. They interface with all teams to collect requirements and maintain documentation quality.

### Responsibilities
- Create and maintain user-facing documentation and guides
- Update process and project documentation as workflows evolve
- Collaborate with developers to document APIs, features, and technical details
- Review and edit documentation for clarity and consistency
- Maintain documentation standards and style guides
- Ensure documentation is released alongside features

### Goals
- Provide clear, accurate documentation that enables users and teams
- Reduce support burden through comprehensive self-service docs
- Maintain documentation freshness and relevance
- Establish consistent documentation standards

### Typical Communication
- Weekly syncs with developers and Product Manager for feature docs
- Documentation review sessions with subject matter experts
- Collaboration with Release Manager for release documentation
- Feedback collection from users and support teams

### Key Collaboration Points
- **Developers**: Gathers technical details, reviews code comments and API docs
- **Product Manager**: Understands feature goals and user scenarios for documentation
- **Release Manager**: Ensures documentation is ready before each release
- **Project Manager**: Updates process documentation and project artifacts
- **All roles**: Collects input to keep institutional knowledge documented

---

## Handoff Points and Collaboration Requirements

### Planning Phase
- **Product Manager → Project Manager**: Product requirements, priorities, and success metrics
- **Project Manager → All roles**: Project charter, timeline, and resource allocation
- **Technical Writer**: Begins documentation planning based on project scope

### Development Phase
- **Developers → QA Lead**: Feature completion notifications and test requirements
- **QA Lead → Developers**: Bug reports and quality feedback
- **Technical Writer → Developers**: Technical documentation reviews and updates

### Pre-Release Phase
- **QA Lead → Release Manager**: Quality sign-off and test results
- **Developers → Release Manager**: Code freeze confirmation and deployment artifacts
- **Technical Writer → Release Manager**: Documentation readiness confirmation
- **Release Manager → Stakeholder Liaison**: Release schedule and impact summary

### Release Phase
- **Release Manager → All teams**: Deployment status and go/no-go decisions
- **Release Manager → Stakeholder Liaison**: Release announcement and stakeholder notifications

### Post-Release Phase
- **All roles → Project Manager**: Retrospective feedback and lessons learned
- **Stakeholder Liaison → Product Manager**: Stakeholder feedback and impact assessment
- **Technical Writer**: Updates documentation based on release outcomes

### Ongoing Collaboration
- **Stakeholder Liaison ↔ Project Manager**: Weekly status and escalation alignment
- **QA Lead ↔ Developers**: Daily testing coordination and bug resolution
- **Release Manager ↔ QA Lead**: Continuous release readiness assessment
- **Technical Writer ↔ All roles**: Ongoing documentation maintenance and updates

### Communication Best Practices
- Use clear handoff notifications (e.g., "Ready for QA", "Approved for Release")
- Document decisions and action items in shared systems
- Escalate blockers immediately to appropriate stakeholders
- Maintain accountability through explicit ownership assignments
- Follow up on handoffs to ensure nothing is dropped

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

