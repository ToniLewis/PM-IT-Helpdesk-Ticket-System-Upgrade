# Risk Log: IT Helpdesk Ticket System Upgrade

**Project Lead:** Toni Lewis
**Last Updated:** July 2026

---

| ID | Risk | Likelihood | Impact | Mitigation | Owner | Status |
|---|---|---|---|---|---|---|
| R1 | Data migration errors could result in lost or corrupted historical ticket records | Medium | High | Run a full test migration in a staging environment before the live migration; validate record counts and spot-check ticket details against the legacy system before cutover | Backend Team | Open |
| R2 | Staff resistance to the new tool may slow adoption during the training window | Medium | Medium | Involve helpdesk staff early in UAT so they have input before rollout; provide a quick-start guide and recorded training sessions for reference | Project Manager | Open |
| R3 | Vendor onboarding delays could compress the testing phase | Low | High | Confirm vendor implementation timeline in writing before Week 1; build a 3-5 day buffer into the testing phase schedule | Project Manager | Open |
| R4 | SLA automation rules may be misconfigured, causing incorrect ticket routing or missed escalations | Medium | High | Test all SLA and escalation rules against sample ticket scenarios during the Development phase, before UAT begins | Frontend Team | Open |
| R5 | Parallel-run period may reveal discrepancies between old and new systems that require rework | Medium | Medium | Monitor both systems daily during the 2-week parallel run; log all discrepancies and address before full cutover | Backend Team | Open |
| R6 | Mobile access setup may not work consistently across all staff devices | Low | Medium | Test mobile login and core functions on at least 2 different device types before staff-wide rollout | UX | Open |

---

## Risk rating guide

**Likelihood:** Low / Medium / High — how probable the risk is to occur during the project
**Impact:** Low / Medium / High — how much the risk would affect timeline, quality, or stakeholder trust if it occurred

## Notes
This log is reviewed and updated weekly during project status meetings. New risks identified during any phase are added here with an assigned owner and mitigation plan before moving forward.
