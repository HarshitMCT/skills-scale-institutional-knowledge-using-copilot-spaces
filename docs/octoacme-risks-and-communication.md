# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Operational Risk Signals from Support and DevOps

Support and engineering operations are key early-warning systems for delivery risk:

- **Customer Support Lead**: Monitors support queues for patterns that may indicate production degradation, scope gaps, or usability failures. Escalates to the Product Manager when recurring issues reach a defined threshold (e.g., >3 similar tickets in a sprint). Support signal summaries should be added to the Risk Register.
- **DevOps Engineer**: Monitors infrastructure metrics, deployment failure rates, and CI pipeline health. Flags environment or pipeline risks during weekly syncs and adds them to the Risk Register with mitigation plans (e.g., rollback scripts, feature flags).

## Risk Ownership Escalation Paths

| Risk Type | First Owner | Escalation Path |
|---|---|---|
| Technical / infrastructure risk | DevOps Engineer | → Developer lead → Project Manager → Sponsor |
| Scope / requirements risk | Business Analyst | → Product Manager → Project Manager → Sponsor |
| Usability / design risk | UX/UI Designer | → Product Manager → Project Manager |
| Customer-impact / operational risk | Customer Support Lead | → Product Manager → Project Manager → Sponsor |
| Cross-team dependency risk | Project Manager | → Product Lead → Sponsor |
| Security incident | DevOps Engineer | → Security on-call → Project Manager → Sponsor |

Escalation should move to the next level when a risk cannot be mitigated within the current sprint or when business impact is High.

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call
