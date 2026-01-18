# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
  - Include Developers, QA Lead, DevOps Engineer, and PM
- Weekly delivery sync — show progress, updates, and flagged risks
  - Include core team plus UX Designer, Business Analyst, and Stakeholder Representatives as needed
- Demo/Review at the end of each sprint or milestone
  - Include full team and Stakeholder Representatives to validate deliverables

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic (Developers)
- Integration tests where applicable (Developers with DevOps support)
- End-to-end smoke tests for critical flows before release (QA Lead coordinates)
- Security scanning in CI (DevOps Engineer maintains)
- Manual QA for feature acceptance when needed (QA Lead)
- UX validation against design specifications (UX Designer reviews with QA)

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup (Developers, QA, DevOps)
- Level 2: PM escalates to Product Lead and dependent teams; BA or Stakeholder Rep may assist with business-side blockers
- Level 3: Sponsor-level escalation for business-impacting issues (via Stakeholder Representatives)

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint (DevOps Engineer)
- [ ] Test strategy and quality gates defined (QA Lead)
- [ ] Design handoff process established (UX Designer)
- [ ] Regular demos scheduled (with Stakeholder Representatives)
- [ ] Risk register updated weekly (PM with input from all roles)
