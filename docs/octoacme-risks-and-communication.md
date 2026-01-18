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
  - All roles contribute: technical risks (Developers, DevOps), quality risks (QA Lead), design risks (UX Designer), business risks (Business Analyst, Stakeholder Representatives)
- Assess: estimate impact and likelihood
  - PM coordinates assessment with input from relevant specialists
- Mitigate: reduced via actions, contingency plans
  - Assign mitigation owners based on risk domain (e.g., DevOps for infrastructure risks, QA for quality risks)
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
  - Stakeholder Representatives help identify their group's needs and preferred channels
  - Business Analyst may facilitate requirements gathering sessions
- Provide regular updates (weekly or milestone-based)
  - PM coordinates, with contributions from UX Designer (design progress), QA Lead (quality status), DevOps Engineer (deployment readiness)
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

## Escalation Paths
- Team-level (Developers, QA, DevOps, UX) -> PM -> Product Lead -> Sponsor
- Business concerns: Stakeholder Representative -> PM -> Product Lead
- For security incidents, follow the security incident runbook and notify Security on-call (DevOps Engineer coordinates)
