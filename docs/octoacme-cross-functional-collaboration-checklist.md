# OctoAcme — Cross-Functional Collaboration Checklist

This checklist provides a phase-by-phase reference for key handoffs, questions, and ownership across all personas. Use it during planning, execution, and release to reduce ambiguity and ensure nothing falls through the cracks.

For full persona definitions, see [Roles & Personas](octoacme-roles-and-personas.md).

---

## Phase 1: Initiation

| Question / Handoff | Owner | Contributors |
|---|---|---|
| Is the problem statement and success metric defined? | Product Manager | Business Analyst |
| Are key stakeholder groups identified and communication cadence agreed? | Project Manager | Product Manager |
| Are there any known UX or usability research needs? | UX/UI Designer | Product Manager |
| Are environment or infrastructure constraints known? | DevOps Engineer | Project Manager |
| Are support or operational readiness requirements understood? | Customer Support Lead | Project Manager |

**Checklist**
- [ ] Project One-pager or brief approved
- [ ] Stakeholder list and communication plan drafted
- [ ] Initial risk register seeded (technical, scope, operational)
- [ ] Roles and DRIs (Directly Responsible Individuals) assigned

---

## Phase 2: Planning

| Question / Handoff | Owner | Contributors |
|---|---|---|
| Are user stories elaborated with clear, testable acceptance criteria? | Business Analyst | Product Manager, Developers |
| Are design dependencies identified and wireframes/specs scheduled? | UX/UI Designer | Product Manager |
| Are CI/CD pipeline and environment requirements included in the Definition of Done? | DevOps Engineer | Developers |
| Is the support-readiness checklist for each feature identified? | Customer Support Lead | Product Manager |
| Are cross-team dependencies captured in the Risk Register? | Project Manager | All |

**Checklist**
- [ ] Backlog refined with acceptance criteria reviewed by BA and UX
- [ ] Definition of Done includes deployment, monitoring, and support gates
- [ ] Design tasks estimated and included in sprint capacity
- [ ] Infrastructure/environment dependencies documented
- [ ] Release milestones and deployment windows agreed with DevOps

---

## Phase 3: Execution

| Question / Handoff | Owner | Contributors |
|---|---|---|
| Are design specs available before development starts on user-facing stories? | UX/UI Designer | Developers |
| Are acceptance criteria edge cases clarified before stories move to QA? | Business Analyst | Developers |
| Are CI pipelines passing and security scans clean? | DevOps Engineer | Developers |
| Are any customer-impacting issues or support signals elevated to the backlog? | Customer Support Lead | Product Manager |
| Are blockers escalated promptly using the defined escalation path? | Project Manager | All |

**Checklist**
- [ ] Design review completed for all user-facing stories before merge
- [ ] BA sign-off on acceptance criteria prior to QA
- [ ] CI green; no suppressed security alerts without documented justification
- [ ] Risk Register reviewed and updated at weekly sync
- [ ] Incident triage loop defined (channel, DRI, escalation contact)

---

## Phase 4: Release

| Question / Handoff | Owner | Contributors |
|---|---|---|
| Is the deployment plan and rollback procedure documented and tested? | DevOps Engineer | Project Manager |
| Are release notes complete and reviewed? | Product Manager | Business Analyst, Customer Support Lead |
| Are monitoring dashboards and alerts configured for the new release? | DevOps Engineer | Developers |
| Is the support team briefed with a runbook and FAQ updates? | Customer Support Lead | Product Manager, DevOps Engineer |
| Is the stakeholder release communication drafted and approved? | Project Manager | Customer Support Lead |

**Checklist**
- [ ] Release readiness review completed (DevOps, PM, Support)
- [ ] Rollback plan documented and verified
- [ ] Monitoring and alerting thresholds set for new features
- [ ] Support runbook and escalation contacts updated
- [ ] Release notes published and stakeholder announcement sent

---

## Phase 5: Retrospective

| Question / Handoff | Owner | Contributors |
|---|---|---|
| Were design handoffs clear and timely? | UX/UI Designer | Developers |
| Were acceptance criteria unambiguous and complete? | Business Analyst | Product Manager |
| Were deployments smooth? Any pipeline or environment issues to address? | DevOps Engineer | Project Manager |
| Were there recurring customer-reported issues that indicate process gaps? | Customer Support Lead | Product Manager |
| Were risks identified and mitigated in time? | Project Manager | All |

**Checklist**
- [ ] Retrospective facilitated with all personas represented (or async input collected)
- [ ] Action items documented with owners and due dates
- [ ] Process improvements fed back into relevant docs (planning, execution, release)
- [ ] Risk Register reviewed for items to carry forward

---

## Quick Reference: Who to Involve and When

| Activity | Always Involve | Optionally Involve |
|---|---|---|
| Backlog refinement | Product Manager, Business Analyst | UX/UI Designer, Customer Support Lead |
| Sprint planning | Project Manager, Developers | DevOps Engineer (for infra stories) |
| Design review | UX/UI Designer, Developers | Product Manager |
| Release readiness review | DevOps Engineer, Project Manager | Customer Support Lead |
| Incident triage | DevOps Engineer, Developers | Customer Support Lead, Project Manager |
| Retrospective | Project Manager, all Developers | All personas |

---

*See also: [Project Planning](octoacme-project-planning.md) · [Execution & Tracking](octoacme-execution-and-tracking.md) · [Release & Deployment](octoacme-release-and-deployment.md) · [Risk Management & Communication](octoacme-risks-and-communication.md) · [Roles & Personas](octoacme-roles-and-personas.md)*
