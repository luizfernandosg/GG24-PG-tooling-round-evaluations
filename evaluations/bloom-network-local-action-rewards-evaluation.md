# Evaluation: Bloom Network — Local Action Rewards: Scaling Ethereum Public Goods Adoption

**Date:** 2025-10-22
**Evaluator:** Luiz Fernando
**Proposal Link:** [Unclear from screenshot]

---

## Key Aspects

### Integration/Development in Question
Design and pilot a Local Action Rewards (LAR) program that incentivizes community‑level impact activities (cleanup, mutual aid, climate resilience, etc.) and connects them to Ethereum primitives for credibility, coordination, and rewards. Work includes an MVP rewards framework, partner pilots with local nodes/communities, and developer assets (APIs/flows) to standardize impact issuance and verification.

### Funding Amount
Small scenario appears to request ~$5,000 (with research/design/engineering/PM split). Totals and exact line items are not fully legible. Please confirm final requested amount and per‑category allocations.

### General Impression
Clear fit for public‑goods adoption at the local level. Strong narrative on bridging offline actions to onchain recognition and funding. Proposal lists concrete deliverables and pilots, but interop specifics (2+ primitives and upstream work), budget totals, and milestone acceptance criteria need to be nailed down for Dec 9.

### Alignment with Round
- Interoperability: Intends to use recognized primitives for attestations/impact; specify exactly which and the artifacts to ship.
- Collaboration: Multi‑stakeholder (local nodes, NGOs, municipalities, partners); provide named partners and evidence.
- UI/UX: Community onboarding and rewards flows; needs explicit UX problem framing and validation.
- Product Maturity: MVP + pilots by Dec 9 looks feasible with focused scope.

---

## Proposal Feedback

### What I Like About the Proposal
- Tackles a key adoption gap: connecting real‑world community actions to onchain recognition/funding
- Pilot‑driven approach with developer assets to generalize beyond a single city/community
- Potential to align with existing impact standards (EAS schemas, Hypercerts) to enhance credibility

### What Can Be Improved or Made More Clear
- Commit to at least two primitives (e.g., EAS + Hypercerts or EAS + OpenGrants/Karma GAP) with concrete artifacts and upstream PRs
- Provide itemized budget with totals and acceptance criteria per milestone
- Name launch partners (cities/NGOs/community nodes) with letters/issues/MOUs; add a simple risk register

### Questions
- Which two+ primitives will be integrated by Dec 9 and what artifacts will ship (schemas, adapters, example issuers, upstream PRs)?
- What is the total funding requested and per‑category breakdown? What are acceptance criteria for each milestone?
- Who are the confirmed pilot partners and what evidence can you share of commitments and timelines?

---

## Rubric-Based Analysis

### Interoperability (25 points)
**Focus:** Concrete plan + credible execution path to adopt at least 2 primitives; evidence of upstream contributions (schemas, PRs).

**Analysis:**
- Primitives being integrated: Karma GAP profile present; EAS/Hypercerts/OpenGrants likely but not explicit in screenshot.
- Execution credibility: Pilots + developer flows are a good path; specify adapters and upstream engagement.
- Upstream contribution evidence: Not shown; propose EAS schema PRs and Hypercerts example templates.
- Strength of interoperability approach: Strong potential with clear artifacts.

**Assessment:** Moderate (conditional)

---

### UX Impact (20 points)
**Focus:** Clear definition of the UX problem (onboarding, account abstraction, safety, gas, dev‑ex, privacy, etc.), severity evidence, and test plan.

**Analysis:**
- UX problem clearly defined: Friction for communities to document/verify impact and access rewards/funding.
- Severity and evidence: Provide baseline data (participation rates, current workflows).
- Test/validation plan: Pilot cohorts with before/after metrics and surveys; define success thresholds.
- Impact potential: High if issuance/verification becomes easy and credible.

**Assessment:** Moderate → Strong (with validation plan)

---

### Product Maturity & Feasibility (15 points)
**Focus:** TRL‑style stage mapping with realistic scope for 4‑6 weeks; risk register & mitigations.

**Analysis:**
- Current maturity stage: Network and programs exist; LAR MVP is new.
- Scope realistic for Dec 9th deadline: Yes, for MVP issuance + 1–2 pilots + reporting.
- Risks identified and mitigated: Add risks (partner bandwidth, data quality, device access) with mitigations.
- Technical feasibility: Reasonable with focused deliverables.

**Assessment:** Moderate

---

### Collaboration (10 points)
**Focus:** Named integration partners; MOUs/issues opened; co‑maintenance or shared roadmaps.

**Analysis:**
- Named partners/collaborators: Several referenced (local nodes/partners) but not fully legible.
- Evidence of partnerships (MOUs, issues, etc.): Not linked; add documents/issues/letters.
- Shared roadmap elements: Propose a simple partner milestone calendar.
- Cross‑project potential: High for replication across cities.

**Assessment:** Moderate (pending evidence)

---

### Team Track Record (10 points)
**Focus:** Repos, releases, audits, shipped infra; Proof‑of‑Ship track record.

**Analysis:**
- Team background and experience: Network with prior local activation programs; add repos and program reports.
- Previous shipped projects: Provide links to past pilots and code.
- Repository activity and quality: Add GitHub links and quality signals.
- Credibility indicators: Letters/references from partners helpful.

**Assessment:** Moderate (needs links)

---

### Measurement Plan (10 points)
**Focus:** Which onchain/offchain metrics will be emitted; EAS schemas; Hypercert minting cadence; reporting via OpenGrants/Karma GAP.

**Analysis:**
- Impact metrics defined: Recommend KPIs—participants, actions verified, attestations/hypercerts issued, repeat participation, partner adoption.
- Karma GAP integration plan: Provide GAP link and weekly cadence aligned to CIDS.
- CIDS framework alignment: Collaboration + UI/UX + Product Growth; Interoperability if EAS/Hypercerts used.
- Reporting frequency and detail: Weekly updates and final report by Dec 9.

**Assessment:** Moderate

---

### Budget & Timeline (10 points)
**Focus:** Value for money; milestone clarity; licenses; acceptance criteria; fallback plan.

**Analysis:**
- Budget reasonableness: Requires confirmed totals and rationale; small scenario appears reasonable.
- Milestone clarity and achievability: Define 3–4 milestones with acceptance criteria (issuance MVP, partner pilot live, metrics collected, reporting).
- Timeline to Dec 9th: Feasible with tight scoping.
- Acceptance criteria defined: To be specified.
- Risk mitigation/fallback: Include alternative pilots and simplified flows if partner delays occur.

**Assessment:** Moderate

---

## Summary

### Standout Strengths
1. Strong local adoption thesis linking offline impact to onchain recognition
2. Pilot‑driven plan with developer assets that can generalize
3. High replication potential across communities and municipalities

### Key Concerns / Red Flags
1. Concrete interop plan (2+ primitives) and upstream contributions not yet linked
2. Budget totals and milestone acceptance criteria unclear
3. Partner commitments and timelines not evidenced

### Critical Questions for Builder
1. Which two+ primitives (e.g., EAS, Hypercerts, OpenGrants/Karma GAP) will be integrated by Dec 9, and what artifacts will ship?
2. What is the total requested amount and itemized budget with acceptance criteria per milestone?
3. Who are the confirmed pilot partners and what commitment evidence can you share?

---

## Final Recommendation

**Conviction Level:** Medium (conditional)

**Rationale:** Strong alignment with Round goals and real‑world adoption focus. Recommend funding contingent on concrete integrations, budget clarity, and partner evidence.

**Conditions/Suggestions:**
- Commit to EAS + Hypercerts (or GAP/OpenGrants) with upstream PRs and example issuers
- Run at least one pilot by Dec 9 with defined KPIs and weekly GAP updates mapped to CIDS
- Publish simple developer docs/templates so other cities can replicate

---

## CIDS Activity Alignment

Which CIDS activity structure(s) does this proposal align with?
- [x] Collaboration
- [x] UI/UX
- [x] Product Growth
- [x] Interoperability (conditional on integrations)

**Notes:** Treat primarily as Collaboration + Product Growth with strong Interoperability potential once primitives are specified and upstreamed.
