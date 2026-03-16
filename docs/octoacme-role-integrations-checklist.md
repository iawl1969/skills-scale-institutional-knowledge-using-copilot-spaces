# OctoAcme — Role Integrations Checklist

## Purpose
This checklist ensures that cross-role collaboration is effective at each phase of the project lifecycle. Use it to confirm that handoffs, communication touchpoints, and shared responsibilities between personas are properly established before, during, and after delivery.

> **Reference:** See [OctoAcme Personas](./octoacme-roles-and-personas.md) for full role descriptions.

---

## Project Initiation

### Product Manager ↔ Business Analyst
- [ ] Business Analyst has conducted stakeholder interviews to gather initial requirements
- [ ] Product Manager and Business Analyst have aligned on problem statement and success metrics
- [ ] Initial user stories or epics drafted collaboratively and reviewed by Product Manager

### Product Manager ↔ UX Designer
- [ ] UX Designer has been briefed on product goals and target users
- [ ] Discovery research plan agreed upon between Product Manager and UX Designer
- [ ] Initial design exploration (mood boards, sketches, or personas) shared with Product Manager

### Project Manager ↔ Scrum Master
- [ ] Scrum Master is identified and onboarded to the project
- [ ] Delivery cadence (sprint length, ceremony schedule) agreed between Project Manager and Scrum Master
- [ ] Project Manager and Scrum Master have aligned on escalation paths for blockers

---

## Planning & Backlog Refinement

### Product Manager ↔ QA Specialist
- [ ] QA Specialist has reviewed acceptance criteria for upcoming stories and flagged ambiguities
- [ ] Testability requirements incorporated into stories before sprint planning
- [ ] Test scope and risk assessment shared with Product Manager for prioritization decisions

### Product Manager ↔ Business Analyst
- [ ] Requirements traceability matrix initiated and shared with Product Manager
- [ ] Business rules and edge cases documented by Business Analyst and reviewed by Product Manager
- [ ] UAT plan drafted and stakeholders identified for upcoming features

### Scrum Master ↔ Project Manager
- [ ] Sprint goals aligned with project milestones maintained by Project Manager
- [ ] Capacity planning reviewed jointly before each sprint planning session
- [ ] Risk register updated to reflect sprint-level blockers and dependencies

### UX Designer ↔ Developers
- [ ] Design handoff package (specs, assets, interaction notes) delivered before sprint starts
- [ ] Developers have reviewed designs and raised feasibility questions; UX Designer has responded
- [ ] Accessibility annotations included in design handoff

---

## Execution & Development

### Scrum Master ↔ Developers
- [ ] Scrum Master facilitating daily standups; blockers captured and actioned same day
- [ ] Sprint burndown shared with team; Scrum Master addressing pace concerns proactively
- [ ] Retrospective action items from prior sprint tracked and in progress

### QA Specialist ↔ Developers
- [ ] QA Specialist involved in refinement of stories in the current sprint
- [ ] Test environment available and stable for QA Specialist use
- [ ] Defects reported by QA Specialist triaged within one business day by Developers
- [ ] Developers notifying QA Specialist of PRs ready for testing

### UX Designer ↔ QA Specialist
- [ ] UX Designer has provided QA Specialist with design specifications for visual and interaction validation
- [ ] QA Specialist verifying delivered UI against approved designs as part of acceptance testing
- [ ] Discrepancies between design intent and implementation logged and reviewed with UX Designer

### Business Analyst ↔ Developers
- [ ] Business Analyst available to clarify requirements questions raised by Developers
- [ ] Any in-sprint scope changes reviewed by Business Analyst and Product Manager before acceptance
- [ ] Business Analyst maintaining updated workflow documentation as implementation decisions are made

---

## Release & Deployment

### QA Specialist ↔ Project Manager
- [ ] Test summary report delivered to Project Manager at least 48 hours before planned release
- [ ] Open defect status communicated clearly with severity, impact, and mitigation plan
- [ ] QA Specialist confirming release readiness sign-off (or documenting known-risk exceptions)

### UX Designer ↔ Project Manager
- [ ] UX Designer confirming design QA sign-off for all user-facing changes in the release
- [ ] Accessibility audit results shared with Project Manager; critical issues resolved
- [ ] UX Designer available during release window for rapid feedback on user-facing issues

### Business Analyst ↔ QA Specialist
- [ ] UAT scenarios reviewed and approved by Business Analyst before UAT begins
- [ ] Business Analyst coordinating stakeholder participation in UAT sessions
- [ ] UAT defects logged and communicated to QA Specialist and Developers for resolution

### Scrum Master ↔ Project Manager
- [ ] Sprint velocity and delivery forecast updated before release planning meeting
- [ ] Outstanding impediments resolved or formally accepted before release date
- [ ] Retrospective scheduled for post-release learnings

---

## Post-Release & Retrospective

### All Roles
- [ ] Post-release monitoring review conducted within 24–48 hours of deployment
- [ ] Incidents or post-deploy defects triaged with QA Specialist and Developers
- [ ] Stakeholder release communication sent by Project Manager (or Product Manager)
- [ ] Retrospective held; action items documented and assigned with owners and due dates

### Scrum Master ↔ All Roles
- [ ] Retrospective facilitated by Scrum Master using a structured format
- [ ] Action items from retrospective added to next sprint backlog or process documentation
- [ ] Team health check conducted; concerns escalated to Project Manager if needed

### Product Manager ↔ Business Analyst
- [ ] Post-release metrics reviewed against success criteria defined during initiation
- [ ] Business Analyst updating requirements documentation to reflect delivered state
- [ ] Next prioritization cycle initiated based on user feedback and performance data

---

## Cross-Role Collaboration Health Indicators

Use the following signals to assess whether cross-role collaboration is working effectively:

| Indicator | Healthy Signal | Warning Signal |
|---|---|---|
| Defect escape rate | Low defects found in UAT or production | High volume of late-cycle defects |
| Design rework | Minimal implementation changes after design handoff | Frequent redesigns during development |
| Requirements churn | Stable stories within a sprint | Stories frequently reopened or revised mid-sprint |
| Impediment resolution | Blockers cleared within 1–2 days | Impediments persisting across multiple sprints |
| Retrospective action follow-through | Actions closed before next retro | Same issues recurring across retrospectives |
| UAT pass rate | High first-pass UAT acceptance | Significant UAT defect volume requiring re-testing |
