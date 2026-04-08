# OctoAcme — Role Interaction Matrix

## Purpose
Clarify how each role collaborates with the others across the project lifecycle. Use this matrix to reduce ambiguity about ownership and handoffs, especially during initiation, planning, execution, and release.

---

## Interaction Matrix

The table below summarizes key touchpoints between roles. **✔** indicates a regular, expected interaction; **→** indicates one role is the primary initiator or owner of that interaction.

| Role | Project Manager | Product Manager | Developers | QA Engineer | Scrum Master | Technical Writer | UX Designer | DevOps Engineer | Business Analyst | Stakeholders |
|---|---|---|---|---|---|---|---|---|---|---|
| **Project Manager** | — | ✔ Weekly sync | ✔ Daily standups | ✔ Pre-release sign-off | ✔ Impediment escalation | ✔ Release coordination | ✔ Design milestones | ✔ Deployment windows | ✔ Requirements status | → Status updates |
| **Product Manager** | ✔ Weekly sync | — | ✔ Backlog refinement | ✔ Acceptance testing | ✔ Sprint planning | ✔ Docs milestones | ✔ Research readouts | ✔ Infrastructure needs | ✔ Requirements backlog | → Roadmap briefings |
| **Developers** | ✔ Daily standups | ✔ Backlog refinement | — | ✔ Defect triage | ✔ Sprint ceremonies | ✔ Technical accuracy | ✔ Design handoff | ✔ Deployment & pipeline | ✔ Backlog refinement | — |
| **QA Engineer** | → Pre-release sign-off | ✔ Acceptance testing | ✔ Defect triage | — | ✔ Sprint ceremonies | ✔ Doc validation | ✔ Usability findings | ✔ Incident triage | ✔ Requirements validation | — |
| **Scrum Master** | ✔ Team health & risks | ✔ Sprint planning | ✔ Sprint ceremonies | ✔ Sprint ceremonies | — | — | — | — | — | — |
| **Technical Writer** | ✔ Release coordination | ✔ Docs milestones | ✔ Technical accuracy | ✔ Doc validation | — | — | — | — | — | — |
| **UX Designer** | ✔ Design milestones | ✔ Research readouts | ✔ Design handoff | ✔ Usability findings | ✔ Sprint planning | — | — | — | — | ✔ User research |
| **DevOps Engineer** | ✔ Deployment windows | ✔ Infrastructure needs | ✔ Deployment & pipeline | ✔ Incident triage | — | — | — | — | — | — |
| **Business Analyst** | ✔ Requirements status | ✔ Requirements backlog | ✔ Backlog refinement | ✔ Requirements validation | — | — | — | — | — | ✔ Requirements workshops |
| **Stakeholders** | ✔ Status updates | ✔ Roadmap briefings | — | — | — | — | ✔ User research | — | ✔ Requirements workshops | — |

---

## Key Handoffs by Phase

### Initiation
| Handoff | From | To | Artifact |
|---|---|---|---|
| Business need and initial requirements | Business Analyst / Stakeholders | Product Manager | Problem statement, requirement notes |
| Project One-pager approval | Project Manager | Stakeholders | Signed-off One-pager |
| Role assignment confirmation | Project Manager | All roles | Role Assignment Checklist |

### Planning
| Handoff | From | To | Artifact |
|---|---|---|---|
| Prioritised backlog | Product Manager + Business Analyst | Developers, QA | Sprint backlog with acceptance criteria |
| Design specifications | UX Designer | Developers | Annotated wireframes / component specs |
| Infrastructure needs | Developers + Product Manager | DevOps Engineer | Environment requirements doc |
| Documentation plan | Product Manager | Technical Writer | Feature list, milestone dates |

### Execution
| Handoff | From | To | Artifact |
|---|---|---|---|
| Completed feature (ready for QA) | Developers | QA Engineer | Merged PR, acceptance criteria |
| Defect report | QA Engineer | Developers | Bug ticket with steps to reproduce |
| Impediment escalation | Scrum Master | Project Manager | Blocker log |
| Documentation draft review | Technical Writer | Developers / QA | Draft doc for accuracy review |

### Release
| Handoff | From | To | Artifact |
|---|---|---|---|
| Release sign-off | QA Engineer | Project Manager | Test results / sign-off note |
| Deployment coordination | DevOps Engineer | Project Manager | Deployment plan, rollback procedure |
| Release notes | Technical Writer | Product Manager / PM | Final release notes |
| Stakeholder announcement | Project Manager | Stakeholders | Release announcement email or post |

---

## Related Docs
- [Roles and Personas](./octoacme-roles-and-personas.md)
- [Role Assignment Checklist](./octoacme-role-assignment-checklist.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
