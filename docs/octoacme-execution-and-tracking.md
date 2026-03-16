# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Agile Facilitation by Scrum Masters
The Scrum Master plays a central role in maintaining healthy sprint execution. Their facilitation responsibilities include:

- **Sprint Planning:** Collaborate with the Project Manager and Product Manager to ensure the sprint goal is clear and the backlog is refined and estimated before planning begins.
- **Daily Standups:** Facilitate the standup, capture impediments, and follow up on blockers outside the meeting to keep the team unblocked.
- **Sprint Reviews:** Coordinate the demo with Developers and Product Managers; capture stakeholder feedback for backlog refinement.
- **Retrospectives:** Facilitate structured retrospectives (e.g., Start/Stop/Continue) and track action items to closure across sprints.
- **Impediment Removal:** Maintain a visible impediment log, escalate blockers to the Project Manager when needed, and track resolution timelines.
- **Metrics & Health:** Share velocity trends and burndown charts with the Project Manager weekly to support delivery forecasting.

## Persona-Driven Coordination in Execution Workflows
Each role contributes to execution in distinct ways. Use the following guidance to coordinate across personas effectively:

| Persona | Key Execution Contribution | Primary Touchpoints |
|---|---|---|
| Scrum Master | Sprint facilitation, impediment removal, metrics | Project Manager, Developers, Product Manager |
| Developer | Feature implementation, code reviews, test coverage | QA Specialist, UX Designer, Scrum Master |
| QA Specialist | Test execution, defect reporting, acceptance validation | Developer, Product Manager, Scrum Master |
| UX Designer | Design handoffs, implementation review, accessibility checks | Developer, Product Manager |
| Business Analyst | Requirements clarity, workflow documentation, UAT support | Product Manager, Developer, QA Specialist |
| Product Manager | Backlog prioritization, acceptance criteria, stakeholder alignment | All roles |
| Project Manager | Schedule management, risk tracking, cross-team coordination | Scrum Master, Product Manager, Stakeholders |

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
- QA Specialists coordinate with Developers on testability during sprint planning to reduce late-cycle defects

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)
- Scrum Master shares sprint health metrics (velocity, impediment count) with Project Manager weekly

## Blocker Escalation
- Level 1: Team-level triage in daily standup (Scrum Master facilitates)
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] Sprint ceremonies (planning, standup, review, retro) scheduled and facilitated by Scrum Master
- [ ] Impediment log maintained and reviewed in each standup
- [ ] QA Specialists involved in sprint planning for acceptance criteria review
- [ ] UX design handoffs completed before development begins for each feature
