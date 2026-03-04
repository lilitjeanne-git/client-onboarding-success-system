# Project Charter
<!-- 
  HOW TO USE THIS TEMPLATE
  ─────────────────────────────────────────────────────────────────────────────
  Replace every [placeholder] with real content before the Kick-Off Meeting.
  This document should be reviewed and approved by the Project Sponsor
  before work begins. Once approved, treat it as the master reference for
  the entire project — link to it from your tracker, RAID log, and meeting notes.

  For AI-assisted use: paste this file as context before asking an AI to
  generate a project plan, status report, stakeholder email, or risk assessment.
  ─────────────────────────────────────────────────────────────────────────────
-->

| Field            | Value                                      |
|------------------|--------------------------------------------|
| **Project Name** | [CLIENT NAME] — Product X Pilot       |
| **Project ID**   | [e.g. ID-2026-001]                        |
| **Version**      | v1.0                                       |
| **Status**       | Draft / Under Review / Approved            |
| **Created by**   | [Project Manager Name]                     |
| **Created on**   | [DD/MM/YYYY]                               |
| **Last updated** | [DD/MM/YYYY]                               |
| **Sponsor**      | [Executive Sponsor Name]                   |

---

## 1. Project Overview

### 1.1 Context

<!--
  Explain WHY this project is happening. What is the background?
  What triggered the need for it? 1–3 short paragraphs.
-->

[CLIENT NAME] has initiated a Crypto-Agility Pilot Project in collaboration
with X Company to experiment with post-quantum cryptography
(PQC) management within its strategic products and services roadmap.

The project responds to the growing threat of quantum computing, which is
expected to render current public-key cryptographic algorithms (RSA, ECC,
Diffie-Hellman) obsolete within the next 10–15 years. The "Harvest Now,
Decrypt Later" attack vector makes migration urgent — sensitive data
intercepted today can be decrypted once quantum computers become available.

[Add any additional client-specific context here — regulatory pressure,
internal mandate, previous PoC results, etc.]

### 1.2 Business Problem

<!--
  State the core problem in 1–2 sentences. Be specific. Avoid jargon.
-->

[CLIENT NAME]'s current cryptographic infrastructure relies entirely on
classical algorithms that are vulnerable to quantum attacks. The organisation
lacks visibility into its cryptographic asset inventory and has no mechanism
to update cryptographic schemes without disrupting existing systems.

### 1.3 Project Goals

<!--
  List 3–5 clear goals. Each goal should be achievable within this project.
  Goals answer "what do we want to achieve?" — not how.
-->

1. Experiment with and validate Company X's Crypto-Agility framework
   in [CLIENT NAME]'s technical environment.
2. Demonstrate quantum-safe key exchange and digital signatures across
   REST and gRPC APIs using NIST-standardised PQC algorithms.
3. Assess the impact of PQC migration on [CLIENT NAME]'s existing
   application portfolio and infrastructure.
4. Produce a results analysis report to support internal decision-making
   on a production-level deployment.
5. [Add goal specific to client's use case, e.g. Quantum-Safe VPN, TLS, etc.]

---

## 2. Scope

### 2.1 In Scope

<!--
  List everything this project WILL deliver or cover.
  Be precise — vague scope is the most common cause of project problems.
-->

- Delivery of Company software modules...
- 5 pilot phases as defined in the contract:
  - **Phase 1** — 
  - **Phase 2** — 
  - **Phase 3** — 
  - **Phase 4** — 
- 3 workshops: 
- Monthly Technical Coordination Meetings (TCMs) throughout the project.
- Technical support with 48-hour acknowledgement SLA.
- Final results analysis report and project closure debriefing.

### 2.2 Out of Scope

<!--
  Explicitly state what this project will NOT cover.
  This protects both parties from scope creep.
-->

- Production deployment of any Company X software.
- Integration with [CLIENT NAME]'s live systems or production infrastructure.
- Migration of existing certificates or cryptographic keys.
- Security audit or penetration testing of [CLIENT NAME]'s environment.
- Training of [CLIENT NAME]'s end users beyond the defined workshops.
- Support for operating systems or environments not specified in the
  technical requirements (Linux RHEL 9.4 / Intel CPU / Docker).
- [Add any other items explicitly excluded from this project.]

---

## 3. Success Criteria & KPIs

<!--
  Success criteria answer: "How will we know the project succeeded?"
  Make them measurable. Link to Phase completion where possible.
-->

| # | Success Criterion | Measurement | Target |
|---|-------------------|-------------|--------|
| 1 | All contracted SW deliverables accepted by client | Signed acceptance per delivery batch | 100% accepted |
| 2 | Phase 1–3 tests completed and results documented | Test report covering all defined crypto services | All phases signed off |
| 3 | Phase 4 Product Y integration demonstrated | Successful crypto-policy distribution to test application | Functional demo |
| 4 | Results Analysis Report produced | Report delivered and reviewed in WS #3 | Delivered by T4 |
| 5 | Project delivered on time | All Tn milestones met or rescheduled by Steering Committee only | ≤ 2 milestone delays |
| 6 | Client satisfaction | Informal feedback or satisfaction check at closure | Positive assessment |
| 7 | [Add client-specific KPI, e.g. latency benchmark, algorithm coverage] | [Measurement method] | [Target value] |

---

## 4. High-Level Timeline & Milestones

<!--
  Use the milestone dates from your project calendar.
  These should match the RAID Log and Onboarding Tracker.
-->

| Milestone | Description | Target Date | Status |
|-----------|-------------|-------------|--------|
| **T0** | Signed agreement & initial invoice | Jun 30, 2025 | ✅ Done |
| **Kick-Off** | Kick-Off Meeting (STC #1) + WS #1 | [DD/MM/YYYY] | 🔄 Upcoming |
| **T1** | SW Delivery #1 + Phase 1 setup begins | Sep 1, 2025 | ⬜ Planned |
| **T2** | Software setup complete + Phase 1–3 tests start | Sep 30, 2025 | ⬜ Planned |
| **T3** | SW Deliveries #2–4 + Phase 4–5 tests | Nov 15, 2025 | ⬜ Planned |
| **T4a** | WS #3 Results Analysis | Jan 15, 2026 | ⬜ Planned |
| **T4b** | Final SW delivery + Phase 5 tests | Feb 15, 2026 | ⬜ Planned |
| **End** | Project Closure Meeting + Debrief | Mar 30, 2026 | ⬜ Planned |

> ⚠️ All dates are estimates based on T0 = June 30, 2025.
> Consecutive dates are subject to prerequisites completion and
> Steering Committee approval.

---

## 5. Budget & Constraints

### 5.1 Budget

<!--
  Fill in or reference the contract value. Keep financial detail
  at a high level in this document.
-->

| Item | Details |
|------|---------|
| **Contract value** | [EUR / per contract] |
| **Invoicing schedule** | Initial invoice at T0 · Milestone-based thereafter |
| **Budget owner** | [Name / Department] |
| **Approved by** | [Executive Sponsor] |

### 5.2 Constraints

<!--
  List anything that limits how the project can be delivered —
  time, resources, technology, regulatory, etc.
-->

- **Time**: Project must close by [Mar 30, 2026] per contractual agreement.
- **Technology**: Client environment must run Linux RHEL 9.4 / Intel (AVX2).
  No exceptions to the Docker delivery format.
- **Resources**: Client must provide a dedicated SPOC and technical engineer
  throughout the project.  cannot proceed without client-side availability.
- **Legal**: All CryptoNext software must be erased from client systems
  at project closure, per contractual obligation.
- **Confidentiality**: All project materials are Restricted Use — Confidential.
  Not to be shared outside the named project teams.
- [Add any budget cap, regulatory deadline, or technical constraint specific
  to this client.]

---

## 6. Key Stakeholders & Roles

<!--
  Keep this section high-level. Full details are in the Stakeholder Register.
  Link to it below.
-->

| Name | Organisation | Role | Responsibility |
|------|-------------|------|----------------|
| [Name] | [CLIENT NAME] | Project Sponsor | Final approval authority, escalation point |
| [Name] | [CLIENT NAME] | SPOC / Project Lead | Day-to-day coordination, client-side decisions |
| [Name] | [CLIENT NAME] | Technical Lead | Test environment, infrastructure, technical validation |
| [Project Manager] | Company X | Project Manager | Delivery management, meeting facilitation, reporting |
| [Tech Director] | Company X | Technical Director | Architecture, workshops, technical support |
| [CRO] | Company X  | Executive Sponsor | Commercial relationship, escalation |

📎 **Full stakeholder details**: see
[`/templates/stakeholder-register.xlsx`](../templates/stakeholder-register.xlsx)

---

## 7. Assumptions & Dependencies

<!--
  List the top assumptions and dependencies for this project.
  Full details are tracked in the RAID Log.
-->

### Key Assumptions

- The client will provide a dedicated SPOC and named technical resource
  for the full duration of the project.
- The client's test environment (Linux RHEL 9.4, Docker, 8 GB RAM,
  2 vCPU, 30 GB disk) will be provisioned before T1.
- The contract is signed and the initial invoice is paid before
  the Kick-Off Meeting (T0 confirmed).
- Workshop and TCM attendees have sufficient availability and authority
  to make technical and operational decisions.
- [Add any assumption specific to this client.]

### Key Dependencies

- Client must open port 443 on their test environment before Phase 2
  REST API testing can begin.
- Phase 3  cannot start until Phase 2 results are validated
  and signed off by the client.
- Phase 4  requires Phase 3 infrastructure to be stable.
- Client must provide test data sets for signature validation
  testing before T2.

📎 **Full RAID log**: see
[`/templates/raid-log.xlsx`](../templates/raid-log.xlsx)

---

## 8. Top 5 Risks

<!--
  Summarise the most critical risks here for executive visibility.
  Full risk tracking is in the RAID Log.
-->

| # | Risk | Impact | Probability | Mitigation |
|---|------|--------|-------------|------------|
| 1 | Client infrastructure not ready in time for SW deployment | High | Medium | Infrastructure checklist agreed at Kick-Off. Readiness gate before each SW delivery. |
| 2 | Key client contact (SPOC) changes during project | High | Low | All contacts documented in Stakeholder Register. Knowledge transfer protocol if change occurs. |
| 3 | Client team unfamiliar with Docker — slow setup | Medium | High | 1h Docker onboarding call scheduled before Phase 1 testing. CNS provides setup guide. |
| 4 | Phase delivery delayed if client does not validate deliverables on time | High | Medium | Acceptance SLA defined in contract. Escalate to Steering Committee if > 2 weeks overdue. |
| 5 | PQC algorithms not natively supported by client's existing PKI | Medium | High | PKI compatibility assessed in WS #2. Hybrid certificate deployment planned as fallback. |

📎 **Full RAID log**: see
[`/templates/raid-log.xlsx`](../templates/raid-log.xlsx)

---

## 9. Approval

<!--
  This section makes the charter official.
  All named approvers should confirm by email, signature, or
  a comment on this file in GitHub before the project starts.
-->

By approving this document, the signatories confirm that they have read,
understood, and agreed to the project objectives, scope, constraints,
and governance structure described above.

| Role | Name | Organisation | Date | Signature / Confirmation |
|------|------|-------------|------|--------------------------|
| Project Sponsor (Client) | [Name] | [CLIENT NAME] | [DD/MM/YYYY] | _________________ |
| Project Lead / SPOC (Client) | [Name] | [CLIENT NAME] | [DD/MM/YYYY] | _________________ |
| Project Manager (CNS) | [Name] | Company X  | [DD/MM/YYYY] | _________________ |
| Executive Sponsor (CNS) | [Name] | Company X | [DD/MM/YYYY] | _________________ |

---

## Change Log

<!--
  Every time this document is updated after approval, log the change here.
  This keeps a clear audit trail.
-->

| Version | Date | Author | Change Description |
|---------|------|--------|-------------------|
| v1.0 | [DD/MM/YYYY] | [Name] | Initial draft |
| v1.1 | | | |

---

*This document is Restricted Use — Confidential.*
*Company X  © [YEAR] — Client Onboarding System*
