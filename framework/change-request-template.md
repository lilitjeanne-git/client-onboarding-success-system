# Change Request Log
<!--
  HOW TO USE THIS FILE
  ─────────────────────────────────────────────────────────────────────────────
  Every time something changes from what was agreed in the Project Charter,
  a Change Request (CR) must be raised here BEFORE the change is implemented.

  WHO raises a CR:  Anyone — client, PM, technical team, sponsor.
  WHEN to raise it: As soon as a change is identified. Never after the fact.
  HOW to use it:    Add a new entry to the Change Log table (Section 2),
                    then fill in a full Change Request block (Section 3)
                    using the template provided.

  WHAT counts as a change:
    ✅ Adding a deliverable or feature not in the original scope
    ✅ Removing or replacing a deliverable
    ✅ Moving a milestone date
    ✅ Changing a named team member or SPOC
    ✅ Budget modification
    ✅ Changing a technical requirement or test environment spec
    ✅ Any decision that contradicts something in the Project Charter

  WHAT does NOT need a CR:
    ❌ Routine meeting reschedules (within the same week)
    ❌ Minor wording clarifications in documentation
    ❌ Internal team task reassignments with no client impact

  Once a CR is approved, update the Project Charter and RAID Log accordingly.
  ─────────────────────────────────────────────────────────────────────────────
-->

| Field            | Value                                      |
|------------------|--------------------------------------------|
| **Project Name** | [CLIENT NAME] — Crypto-Agility Pilot       |
| **Project ID**   | [e.g. CNS-2025-001]                        |
| **Document owner** | [Project Manager Name]                   |
| **Last updated** | [DD/MM/YYYY]                               |

---

## 1. What Is a Change Request and Why It Matters

A Change Request (CR) is the formal way to propose, evaluate, and approve
any modification to what was agreed in the Project Charter — whether that
affects scope, timeline, budget, quality, or risk.

**Why this process exists:**

Without it, changes happen informally — verbally, by email, or assumed —
and the project slowly drifts away from what was contracted. This creates
disputes at closure, unexpected costs, missed deadlines, and damaged client
relationships.

With it, every change is visible, evaluated for impact, and approved by
the right person before any work changes course.

**The golden rule:**
> *No change is implemented without an approved Change Request.*
> If it was not in the Project Charter and it is happening — it needs a CR.

---

## 2. Change Log (Summary Table)

<!--
  Add one row per Change Request as soon as it is raised.
  This table gives a quick overview of all changes across the project lifecycle.
  Full details for each CR are in Section 3 below.
-->

| CR ID | Date Raised | Raised By | Short Description | Impact | Status | Decision Date | Approved By |
|-------|-------------|-----------|-------------------|--------|--------|---------------|-------------|
| CR-001 | [DD/MM/YYYY] | [Name / Role] | [One-line summary of the change] | Scope + Time | Approved | [DD/MM/YYYY] | [Name] |
| CR-002 | [DD/MM/YYYY] | [Name / Role] | [One-line summary of the change] | Time | Pending | — | — |
| CR-003 | [DD/MM/YYYY] | [Name / Role] | [One-line summary of the change] | Cost + Scope | Rejected | [DD/MM/YYYY] | [Name] |
| CR-004 | | | | | | | |
| CR-005 | | | | | | | |

**Status values:** `Draft` · `Under Review` · `Approved` · `Rejected` · `Deferred`

---

## 3. Change Request Entries

<!--
  Copy the template block below for each new Change Request.
  Keep all CRs in this file in chronological order.
  Do not delete rejected or deferred CRs — they are part of the audit trail.
-->

---

### CR-001 — [Short Title of Change]

| Field | Value |
|-------|-------|
| **Change ID** | CR-001 |
| **Raised by** | [Name — Role — Organisation] |
| **Date raised** | [DD/MM/YYYY] |
| **Priority** | 🔴 High / 🟡 Medium / 🟢 Low |
| **Status** | Draft / Under Review / Approved / Rejected / Deferred |

#### Description of Change

<!--
  Describe clearly and specifically what is being proposed.
  What would change compared to what was agreed in the Project Charter?
-->

[Describe the change. Be precise. Example: "The client has requested that
Phase 5 (COMPASS Analytics) be included in the main delivery scope rather
than treated as optional, and that it be completed before T4a (Jan 15, 2026)."]

#### Reason / Business Justification

<!--
  Why is this change being requested?
  What would happen if the change is NOT made?
-->

[Explain why this change is needed. Example: "The client's CISO has mandated
a full cryptographic asset inventory as part of their 2025 compliance
programme. Without COMPASS Analytics, the PoC results will be incomplete
for their internal audit report."]

#### Impact Analysis

<!--
  Evaluate the effect of this change on each project dimension.
  Be honest — this section is how the decision-maker understands the trade-offs.
-->

| Dimension | Impact | Details |
|-----------|--------|---------|
| **Scope** | 🔴 High / 🟡 Medium / 🟢 Low / ⚪ None | [What is added, removed, or changed in scope] |
| **Timeline** | 🔴 High / 🟡 Medium / 🟢 Low / ⚪ None | [Days/weeks added or lost. Which milestones are affected] |
| **Cost / Budget** | 🔴 High / 🟡 Medium / 🟢 Low / ⚪ None | [Additional cost, if any. Who bears it] |
| **Risk** | 🔴 High / 🟡 Medium / 🟢 Low / ⚪ None | [New risks introduced or existing risks changed] |
| **Quality** | 🔴 High / 🟡 Medium / 🟢 Low / ⚪ None | [Effect on deliverable quality or test coverage] |
| **Resources** | 🔴 High / 🟡 Medium / 🟢 Low / ⚪ None | [Additional team effort required — CNS and/or client] |

**Overall impact assessment:**
[Write 2–3 sentences summarising the net effect of this change on the project.]

#### Options

<!--
  Present the decision-maker with clear choices.
  Always include at least Accept and Reject.
  Add Defer if timing is the main concern, not the change itself.
-->

| Option | Description | Consequence |
|--------|-------------|-------------|
| ✅ **Accept** | Implement the change as described | [What happens if approved — timeline shift, cost, effort] |
| ❌ **Reject** | Do not implement the change | [What happens if rejected — client impact, workaround needed] |
| ⏸ **Defer** | Revisit at [milestone / date] | [Conditions under which it could be approved later] |

**Recommendation from PM:**
[State which option the PM recommends and briefly why.]

#### Decision

<!--
  Completed by the approver after review.
  The decision must be recorded here before any action is taken.
-->

| Field | Value |
|-------|-------|
| **Decision** | Approved / Rejected / Deferred |
| **Decision date** | [DD/MM/YYYY] |
| **Approved by** | [Name — Role] |
| **Notes** | [Any conditions attached to the decision, e.g. "Approved subject to budget amendment being signed by [date]"] |

#### Implementation Plan

<!--
  Completed only if the CR is Approved.
  Define who does what, and by when.
-->

| Step | Action | Owner | Target Date |
|------|--------|-------|-------------|
| 1 | [First action required to implement the change] | [Name] | [DD/MM/YYYY] |
| 2 | [Update Project Charter section X.X] | [PM] | [DD/MM/YYYY] |
| 3 | [Update RAID Log — new risks or closed assumptions] | [PM] | [DD/MM/YYYY] |
| 4 | [Update Onboarding Tracker milestones] | [PM] | [DD/MM/YYYY] |
| 5 | [Notify all stakeholders via email] | [PM] | [DD/MM/YYYY] |

**Target completion date:** [DD/MM/YYYY]

---

### CR-002 — [Short Title of Change]

| Field | Value |
|-------|-------|
| **Change ID** | CR-002 |
| **Raised by** | [Name — Role — Organisation] |
| **Date raised** | [DD/MM/YYYY] |
| **Priority** | 🔴 High / 🟡 Medium / 🟢 Low |
| **Status** | Draft |

#### Description of Change

[Describe the change.]

#### Reason / Business Justification

[Explain why this change is needed.]

#### Impact Analysis

| Dimension | Impact | Details |
|-----------|--------|---------|
| **Scope** | ⚪ None | |
| **Timeline** | 🟡 Medium | |
| **Cost / Budget** | ⚪ None | |
| **Risk** | 🟢 Low | |
| **Quality** | ⚪ None | |
| **Resources** | 🟢 Low | |

**Overall impact assessment:**
[Summary.]

#### Options

| Option | Description | Consequence |
|--------|-------------|-------------|
| ✅ **Accept** | | |
| ❌ **Reject** | | |
| ⏸ **Defer** | | |

**Recommendation from PM:** [Recommendation.]

#### Decision

| Field | Value |
|-------|-------|
| **Decision** | Pending |
| **Decision date** | — |
| **Approved by** | — |
| **Notes** | |

#### Implementation Plan

*To be completed upon approval.*

---

<!--
  ─────────────────────────────────────────────────────────────────────────────
  ADD NEW CHANGE REQUESTS BELOW THIS LINE
  Copy the full CR block from CR-001, increment the ID, and fill in the fields.
  ─────────────────────────────────────────────────────────────────────────────
-->

---

## 4. Governance & Process

### Who can raise a Change Request?

Anyone involved in the project — client team, CNS team, or executive sponsor.
The PM is responsible for logging it formally and facilitating the review.

### Who approves a Change Request?

| Change Type | Approver |
|-------------|----------|
| Scope change (minor — no cost impact) | Project Manager + Client SPOC |
| Scope change (major) or any cost impact | Steering Committee (STC) |
| Timeline shift ≤ 2 weeks | Project Manager both sides |
| Timeline shift > 2 weeks | Steering Committee (STC) |
| Budget change | Executive Sponsors both sides |
| Technical requirement change | Technical Directors both sides |

### How long does review take?

- **Standard CR**: decision within 5 business days of submission.
- **Urgent CR** (blocking project progress): decision within 48 hours.
  Flag as 🔴 High priority and notify PM and sponsor immediately.

### What happens after approval?

1. PM updates this document (status → Approved, decision date, approver).
2. PM updates the **Project Charter** to reflect the change.
3. PM updates the **RAID Log** (new risks, closed assumptions if any).
4. PM updates the **Onboarding Tracker** (milestone dates if affected).
5. PM sends a change notification email to all stakeholders within 24 hours.

### What happens after rejection?

The CR remains in this log with status `Rejected`. The original project
plan remains in force. The reason for rejection is recorded so it can be
referenced if the same request is raised again.

---

📎 **Related documents**
- Project Charter: [`/framework/project-charter-template.md`](project-charter-template.md)
- RAID Log: [`/templates/raid-log-template.xlsx`](../templates/raid-log-template.xlsx)
- Onboarding Tracker: [`/templates/onboarding-tracker.xlsx`](../templates/onboarding-tracker.xlsx)
- Meeting Notes: [`/templates/meeting-notes-template.xlsx`](../templates/meeting-notes-template.xlsx)

---

*This document is Restricted Use — Confidential.*
*CryptoNext Security © [YEAR] — Client Onboarding System*
