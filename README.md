[README.md](https://github.com/user-attachments/files/26835038/README.md)
# Siemens Healthineers — Teamplay Platform Strategy

**Boston University × Siemens Healthineers · MBA Strategy Consulting · April 2026**

---

## Overview

This repository contains interactive strategy artifacts developed as part of an MBA consulting engagement analyzing why Siemens Healthineers' Teamplay Digital Marketplace has near-zero hospital adoption — and a structured recommendation for how to fix it.

The core argument: Teamplay is underperforming not because the idea is wrong, but because Siemens built a marketplace layer before building the workflow, governance, and service architecture required for platform network effects. The fix is not more app listings. It is repositioning Fleet as the marketplace entry point, separating the sponsor and provider layers, and standardizing the end-to-end app lifecycle across a governed three-lane partner model.

**Live site:** [caitlinyu98.github.io/Siemens-Teamplay-Platform-Strategy](https://caitlinyu98.github.io/Siemens-Teamplay-Platform-Strategy/)

---

## Research Methodology

**Internal:** 6 Siemens stakeholder surveys across Portfolio Management, Product Management, Business Development, and MR leadership. Questions covered adoption rates, governance, developer friction, KPIs, and strategic objectives.

**External:** 3 independent hospital interviews:
- Diana Fullerton — Physical Therapist, NYU Langone / Mass General Hospital
- Stephanie McMains & Shruthi Chakrapani — Assistant Directors, BU Cognitive Neuroimaging Center
- Cheryl Whyte — Advanced Imaging Regional Manager, Atrius Health

**Framework:** Marshall Van Alstyne's platform theory — cross-side network effects, governance design, interaction layer ownership.

**Key external finding:** An active Siemens fleet customer (Atrius Health) had never heard of the Teamplay marketplace — confirming that the problem is not adoption friction but awareness at the point-of-care.

---

## Key Findings

| Finding | Evidence |
|---|---|
| Marketplace adoption rate | Less than 1% (internal survey) |
| Hospital awareness | 0 of 3 external interviewees aware of marketplace |
| Primary complaint | Each app is its own IT project — different T&Cs, deployment models, data rights, service paths |
| Structural gap | Fleet (trusted, active) and Marketplace (unknown) are two disconnected products under one brand |
| Governance state | No clear vision, no validated value requirements, ad hoc partner negotiations |
| Cannibalization fear | Blocking third-party apps to protect syngo — but protecting the wrong layer |

---

## Strategic Framework

### The Three-Layer Separation

| Layer | What it is | Siemens' role |
|---|---|---|
| Layer 1 — Substrate | Scanner HW, Fleet data, teamplay platform, DICOM/PACS connectivity | Own forever. Non-negotiable moat. |
| Layer 2 — Sponsor | Scanner-native syngo (dose mgmt, fleet analytics) vs. commodity syngo (post-proc, worklist, reporting) | Keep what requires scanner access. Open the rest to third parties. |
| Layer 3 — Provider | Clinical AI, image quality, reporting, specialty apps | Fully open. Siemens certifies, governs, and bills — but does not build. |

### The Three-Lane Governance Model

- **Lane A — Core:** Siemens-built, scanner-native apps. Deepest integration, full SLA ownership.
- **Lane B — Complementary:** Co-promoted partners. Shared SLA, managed cloud deployment, co-marketing.
- **Lane C — Competitive-allowed:** Vetted third parties. API-only integration, vendor-led support.

---

## Artifacts

| File | Type | Description |
|---|---|---|
| `index.html` | Landing page | Project overview, research snapshot, links to all four prototypes |
| `teamplay_fleet_dashboard_mockup.html` | Interactive | What the hospital Fleet experience should look like — app cards, scanner fleet, support tickets, recommendations |
| `lane_b_partner_priority_matrix.html` | Interactive | Priority partner shortlist — Aidoc, Nuance PowerScribe, Subtle Medical, Cerebriu, Blackford watch, Intelerad avoid |
| `teamplay_workflow_diagram.html` | Static diagram | 7-stage app lifecycle across three governance lanes |
| `siemens_platform_layer_separation.html` | Static diagram | Substrate / sponsor / provider layer separation with syngo split |

---

## Lane B Partner Priorities

| Partner | Status | Fleet hook |
|---|---|---|
| Aidoc (aiOS) | Priority now | Scanner-level alert volume + triage time = ROI in Fleet dashboard |
| Nuance PowerScribe | Priority now | Reporting turnaround per modality as a Fleet KPI |
| Subtle Medical | Add Q2 | Before/after throughput per MAGNETOM — data already in Fleet |
| Cerebriu | Add Q2 | Protocol compliance rate per site across MR fleet |
| Blackford Analysis | Strategic watch | Partner only if Siemens accepts them as the orchestration layer |
| Intelerad | Avoid | Acquired by GE HealthCare Nov 2025 — now a competitor asset |

---

## Pilot Program

**Who:** 3 enterprise fleet customers, 5+ scanner sites, US or Europe

**What:** 2 Lane A apps + Aidoc as Lane B, surfaced through Fleet dashboard — not standalone marketplace

**How long:** 90 days

**Success threshold:** 70%+ app activation, measurable throughput improvement, all support tickets resolved within SLA

**Timeline:** Pilot Q3 2026 → readout Q4 2026 → full governance rollout 2027

---

## The Core Recommendation

> Siemens does not need a bigger marketplace. It needs a stronger platform operating model.

Three decisions Siemens leadership must make:
1. Commit to Fleet as the marketplace entry point
2. Draw the internal line on syngo — keeper vs. open
3. Fund the pilot — three customers, 90 days, dedicated team

---

## Notes

All research has been anonymized. This project was conducted as part of the Boston University MBA program in partnership with Siemens Healthineers. Artifacts are for academic and strategic communication purposes.

(Built with Claude, 2026) 
