# Release Manager Checklist

## Purpose
This checklist provides a comprehensive guide for Release Managers to plan, coordinate, and execute releases successfully while minimizing risk and maintaining clear communication.

---

## Pre-Release Planning (1-2 weeks before release)

### Release Scoping
- [ ] Review product roadmap with Product Manager to identify features for release
- [ ] Confirm release type (Patch, Minor, or Major)
- [ ] Set release date and deployment window
- [ ] Identify dependencies and blockers
- [ ] Create release branch (if using branch-based workflow)

### Team Coordination
- [ ] Schedule release planning meeting with Project Manager, QA Lead, and key developers
- [ ] Communicate release timeline to all stakeholders
- [ ] Confirm team availability during deployment window
- [ ] Identify on-call coverage for release day

### Documentation & Communication
- [ ] Create release tracking ticket or project board
- [ ] Draft initial release notes template
- [ ] Schedule stakeholder communication via Stakeholder Liaison
- [ ] Update release calendar

---

## Development & Testing Phase (During sprint/iteration)

### Quality Assurance Coordination
- [ ] Coordinate with QA Lead on test plan and coverage
- [ ] Track testing progress and quality metrics
- [ ] Monitor bug triage and resolution progress
- [ ] Ensure acceptance criteria are met for all features

### Documentation Review
- [ ] Confirm with Technical Writer that documentation is on track
- [ ] Review API documentation updates (if applicable)
- [ ] Verify migration guides are prepared (for breaking changes)

### Pre-Release Requirements
- [ ] Verify all PRs are merged to release branch
- [ ] Confirm CI/CD pipeline is passing
- [ ] Ensure security scans are complete and issues addressed
- [ ] Validate rollback plan is documented
- [ ] Prepare smoke test scenarios

---

## Final Pre-Release (1-3 days before release)

### Release Sign-Offs
- [ ] Obtain QA Lead sign-off on quality gates
- [ ] Get Technical Writer confirmation that docs are ready
- [ ] Confirm with developers that code freeze is in effect
- [ ] Review final release notes with Product Manager

### Deployment Preparation
- [ ] Schedule deployment window with operations team
- [ ] Create backup or snapshot (if applicable)
- [ ] Deploy to staging environment
- [ ] Execute smoke tests on staging
- [ ] Verify monitoring and alerting are configured
- [ ] Prepare rollback procedure

### Communication
- [ ] Send release reminder to stakeholders via Stakeholder Liaison
- [ ] Notify support team of upcoming release and changes
- [ ] Brief on-call team on potential issues and rollback plan
- [ ] Update status page or maintenance banner (if applicable)

---

## Release Day

### Deployment Execution
- [ ] Conduct go/no-go check with Project Manager and QA Lead
- [ ] Execute deployment to production (manual or automated)
- [ ] Monitor deployment progress and logs
- [ ] Run post-deploy smoke tests
- [ ] Verify critical paths and integrations

### Validation & Monitoring
- [ ] Check error rates and performance metrics
- [ ] Validate new features are functioning as expected
- [ ] Monitor customer feedback and support tickets
- [ ] Confirm database migrations completed (if applicable)

### Communication
- [ ] Announce successful deployment to stakeholders
- [ ] Update status page or remove maintenance banner
- [ ] Send release notes to users and support team
- [ ] Document any issues encountered during deployment

---

## Post-Release (1-7 days after release)

### Monitoring & Support
- [ ] Continue monitoring metrics for 24-48 hours
- [ ] Track and triage any production issues
- [ ] Coordinate hotfix deployment if critical issues arise
- [ ] Communicate status updates to stakeholders

### Documentation
- [ ] Finalize release notes with any post-release updates
- [ ] Document lessons learned and improvement opportunities
- [ ] Update runbooks or deployment procedures based on learnings

### Retrospective
- [ ] Schedule release retrospective with team
- [ ] Gather feedback from QA Lead, developers, and operations
- [ ] Identify process improvements for next release
- [ ] Create action items for continuous improvement
- [ ] Share retrospective summary with Project Manager

---

## Emergency Rollback Procedure

### If Critical Issues Arise
- [ ] Assess severity and impact with Project Manager and QA Lead
- [ ] Initiate incident response and notify on-call team
- [ ] Execute rollback to last known-good release
- [ ] Verify rollback success and system stability
- [ ] Communicate rollback to stakeholders immediately
- [ ] Schedule root cause analysis and fix planning

---

## Best Practices

### Communication
- Use clear, consistent status updates (e.g., "Deploying", "Deployed", "Verified")
- Over-communicate during high-risk deployments
- Maintain a single source of truth for release status

### Risk Management
- Never skip smoke tests or quality gates
- Always have a tested rollback plan
- Deploy during low-traffic windows when possible

### Continuous Improvement
- Document what went well and what didn't after each release
- Share learnings across teams
- Automate repetitive tasks to reduce human error
