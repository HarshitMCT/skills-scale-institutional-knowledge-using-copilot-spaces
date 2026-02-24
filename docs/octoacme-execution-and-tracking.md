# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Cross-Functional Collaboration Touchpoints

During execution, the following interactions keep delivery aligned across roles:

- **Design Reviews**: UX/UI Designers and Developers hold mid-sprint design reviews to verify implementation matches approved designs; unresolved gaps are flagged as blockers before the story moves to QA
- **Release Readiness Checks**: DevOps Engineers confirm pipeline health, environment parity, and monitoring coverage before each deployment; this check is a required step in the Definition of Done for release-tagged items
- **Incident Triage Loops**: When production incidents are detected, DevOps Engineers and Developers triage the issue in a dedicated channel; the Customer Support Lead is notified immediately to manage user-facing communications while engineering investigates
- **BA Clarification Sessions**: Business Analysts are available during execution to clarify acceptance criteria edge cases; unresolved ambiguities should be raised in the daily standup or via a linked issue comment rather than resolved independently

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
