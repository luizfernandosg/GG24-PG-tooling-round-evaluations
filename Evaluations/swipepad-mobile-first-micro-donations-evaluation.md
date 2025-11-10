# Evaluation: SwipePad: Mobile-First Micro-Donations for Verified Global South Climate Projects + Regen Eliza AI

**Date:** 2025-10-22
**Evaluator:** Luiz Fernando
**Proposal Link:** [To be added]

---

## Key Aspects

### Integration/Development in Question
Production-ready SwipePad Web DApp on Celo Mainnet enabling gasless micro-donations to climate projects via social login (Thirdweb Wallet), integrated with Regen Eliza AI agent. Deliverables include: (1) Production DApp with 50+ vetted projects, social login, gasless donations (cUSD, cEUR, GLO); (2) EAS Schema for "Verified Climate Project" for ecosystem-wide adoption.

### Funding Amount
$7,000 requested ($3,000 engineering, $1,000 AI/hosting, $500 monitoring/analytics, $1,000 project research/curation, $1,000 business dev/comms, $500 project management)

### General Impression
Strong UX-focused proposal addressing real adoption barriers for Global South communities. Clear mobile-first approach with social login removes wallet friction. Good integration with Celo ecosystem and recognized primitives (EAS, Karma GAP, OpenGrants). Regen Eliza AI adds value for project discovery and content generation. Demonstrated execution capability with active demo and 6 Proof of Shipping programs. Realistic scope focused on web DApp (not MiniApps which are in separate proposal).

### Alignment with Round
- **Interoperability:** Strong - integrates EAS, Karma GAP, OpenGrants, Self Protocol, Celo stablecoins
- **Collaboration:** Good - mentions Celo Devs, Mento, Regen Network, ReFi DAO, Regens Unite, GLO Dollar
- **UI/UX:** Very Strong - addresses onboarding friction for non-crypto users, mobile-first design, social login
- **Product Maturity:** Good - has active demo, proven track record, realistic scope

---

## Proposal Feedback

### What I Like About the Proposal
- Addresses critical UX barrier: onboarding friction for Global South non-crypto users
- Mobile-first design with social login removes wallet requirement
- Clear focus on verified, vetted climate projects with SDG alignment
- Strong integration plan: EAS + Karma GAP + OpenGrants + Celo ecosystem
- Regen Eliza AI adds value for project discovery and content generation
- Demonstrated execution: active demo, 6 Proof of Shipping programs completed
- Realistic scope: web DApp (separate from MiniApps proposal)

### What Can Be Improved or Made More Clear
- Explicit upstream contribution plan (EAS schema proposals, Celo ecosystem PRs, documentation)
- More specific measurement plan: KPIs for adoption (users, donations, project endorsements), reporting cadence
- Risk mitigation strategies for AI hallucination (mentioned but could be more detailed), Celo deployment, project curation
- Clarify collaboration evidence (MOUs, GitHub issues, roadmap coordination)
- Specify exact EAS schema fields and validation approach

### Questions
- What specific EAS schema will be proposed/contributed upstream, and what is the timeline for schema registration?
- What are the expected adoption metrics (number of users, donations processed, projects vetted) and how will progress be tracked?
- Can you provide evidence of collaboration commitments (MOUs, GitHub issues) from Celo Devs, Mento, and other partners?
- How will Regen Eliza AI be constrained to verified data sources and what validation mechanisms ensure accuracy?
- What is the reporting cadence to Karma GAP and how will metrics be aligned to CIDS framework?

---

## Rubric-Based Analysis

### Interoperability (25 points)
**Focus:** Concrete plan + credible execution path to adopt at least 2 primitives; evidence of upstream contributions (schemas, PRs).

**Analysis:**
- Primitives being integrated: EAS (explicit schema), Karma GAP (impact tracking), OpenGrants (metadata), Self Protocol (optional attestation), Celo stablecoins (cUSD, cEUR, GLO). Meets 2+ requirement with 5+ primitives.
- Execution credibility: High - has active demo, proven execution track record, clear technical stack, specific integration approach.
- Upstream contribution evidence: Explicitly commits to EAS schema registration and documentation. Could specify PRs to EAS schemas repo or Celo ecosystem documentation.
- Strength of interoperability approach: Very strong - multiple primitives, clear schema design for ecosystem reuse, addresses composability needs.

**Assessment:** Strong

---

### UX Impact (20 points)
**Focus:** Clear definition of the UX problem (onboarding, account abstraction, safety, gas, dev-ex, privacy, etc.), severity evidence, and test plan.

**Analysis:**
- UX problem clearly defined: High friction for Global South communities in discovering, trusting, and funding climate public goods onchain. Fragmentation: no mobile-native discovery, no user-friendly verification, no unified flow.
- Severity and evidence: Strong narrative - Global South focus, mobile-first design, social login removing wallet requirement. Mentions 1st-place win in Stablecoin Hackathon.
- Test/validation plan: Mentions pilot campaigns, localized micro-campaigns in 8 countries, CPG Passport integration (1,000+ users), ReFi Starter waitlist (1,200+ signups). Could specify success metrics.
- Impact potential: Very high - addresses mass adoption barrier, enables non-crypto users to participate, mobile-first approach aligns with Global South usage patterns.

**Assessment:** Strong

---

### Product Maturity & Feasibility (15 points)
**Focus:** TRL-style stage mapping with realistic scope for 4-6 weeks; risk register & mitigations.

**Analysis:**
- Current maturity stage: Production-ready - has active demo (swipepad.xyz), proven track record with 6 Proof of Shipping programs, existing codebase.
- Scope realistic for Dec 9th deadline: Yes - scope is focused on web DApp (not MiniApps), builds on existing infrastructure, realistic deliverables.
- Risks identified and mitigated: Mentions AI hallucination risk with mitigation (constrain to verified data + disclaimer), mobile app store delays (mitigation: TestFlight/APK). Could add more risks.
- Technical feasibility: High - has working demo, proven execution capability, realistic scope, clear technical approach.

**Assessment:** Strong

---

### Collaboration (10 points)
**Focus:** Named integration partners; MOUs/issues opened; co-maintenance or shared roadmaps.

**Analysis:**
- Named partners/collaborators: Celo Devs, Mento, Regen Network, Akiba, ReFi DAO, Regens Unite, GLO Dollar. Mentions joint campaigns with multiple communities.
- Evidence of partnerships (MOUs, issues, etc.): Not provided - should add links to MOUs, GitHub issues, or evidence of collaboration commitments.
- Shared roadmap elements: Mentions joint "Swipe for Climate" campaign, CPG Passport integration, but doesn't show detailed milestone coordination.
- Cross-project potential: Very high - EAS schema designed for ecosystem reuse, addresses many climate/ReFi projects.

**Assessment:** Moderate (pending evidence)

---

### Team Track Record (10 points)
**Focus:** Repos, releases, audits, shipped infra; Proof-of-Ship track record.

**Analysis:**
- Team background and experience: Strong - Otto has multi-dollar grant experience (Aragon Foundation), Visa-audited smart contracts, ranked #4 Global Talent Builders. Oscar ranked #271, products deployed on multiple chains. Tabata has ecosystem growth experience.
- Previous shipped projects: SwipePad demo live, Regen Eliza AI agent, 6 Proof of Shipping programs completed, GitHub repos provided.
- Repository activity and quality: GitHub org provided (github.com/ReFi-Starter/swipe-pad), should verify current activity and quality signals.
- Credibility indicators: Strong - hackathon wins, proof of shipping track record, Talent Protocol rankings, deployed products.

**Assessment:** Strong

---

### Measurement Plan (10 points)
**Focus:** Which onchain/offchain metrics will be emitted; EAS schemas; Hypercert minting cadence; reporting via OpenGrants/Karma GAP.

**Analysis:**
- Impact metrics defined: Mentions project monitoring, analytics implementation, but doesn't specify exact KPIs (number of users, donations processed, projects vetted, attestations issued). Should define quantitative metrics.
- Karma GAP integration plan: Karma GAP profile linked (https://gap.karmahq.xyz/project/swipe-pad) but doesn't specify reporting cadence or CIDS framework mapping.
- CIDS framework alignment: Explicitly mentions UI/UX, Interoperability, Collaboration, Product Growth alignment. Should specify how metrics map to CIDS.
- Reporting frequency and detail: Not specified - should define weekly updates and final impact report by Dec 9.

**Assessment:** Moderate

---

### Budget & Timeline (10 points)
**Focus:** Value for money; milestone clarity; licenses; acceptance criteria; fallback plan.

**Analysis:**
- Budget reasonableness: $7,000 seems reasonable for scope (engineering, AI/hosting, research, business dev, PM). Good breakdown.
- Milestone clarity and achievability: Clear deliverables (D1: DApp, D2: EAS schema) with specific acceptance criteria (50+ projects, onchain attestations, EAS Scan URL).
- Timeline to Dec 9th: Not explicitly specified - should confirm timeline aligns with Dec 9 deadline.
- Acceptance criteria defined: Excellent - specific criteria (live URL, demo video, onchain transactions, EAS schema deployed, 10+ attestations, documentation).
- Risk mitigation/fallback: Present (AI hallucination, app store delays) but could expand.

**Assessment:** Strong (with timeline confirmation)

---

## Rubric Scores

- **Interoperability:** 22/25
- **UX Impact:** 18/20
- **Product Maturity & Feasibility:** 13/15
- **Collaboration:** 6/10
- **Team Track Record:** 9/10
- **Measurement Plan:** 6/10
- **Budget & Timeline:** 9/10

**Total Score:** 83/100

---

## Summary

### Standout Strengths
1. Addresses critical UX barrier for Global South adoption with mobile-first design and social login
2. Strong interoperability with 5+ primitives (EAS, Karma GAP, OpenGrants, Self Protocol, Celo)
3. Demonstrated execution capability with active demo and 6 Proof of Shipping programs

### Key Concerns / Red Flags
1. Collaboration evidence not provided (MOUs, GitHub issues, roadmap coordination)
2. Measurement plan needs more specificity (KPIs, reporting cadence, CIDS alignment)
3. Timeline not explicitly confirmed to align with Dec 9 deadline

### Critical Questions for Builder
1. What specific EAS schema will be proposed/contributed upstream, and what is the timeline for schema registration and documentation?
2. Can you provide evidence of collaboration commitments (MOUs, GitHub issues) from Celo Devs, Mento, Regen Network, and other partners?
3. What are the expected adoption metrics (users, donations, projects) and how will progress be tracked via Karma GAP with weekly updates?

---

## Final Recommendation

**Conviction Level:** Medium-High (conditional)

**Rationale:** Strong alignment with round goals addressing critical UX barrier for Global South communities. Excellent interoperability with multiple primitives and clear EAS schema commitment. Proven execution capability. Recommend funding contingent on collaboration evidence, specific measurement plan, and timeline confirmation.

**Conditions/Suggestions:**
- Provide evidence of collaboration commitments (MOUs, GitHub issues, roadmap coordination) from named partners
- Specify measurement plan: KPIs (users onboarded, donations processed, projects vetted, attestations issued), weekly Karma GAP updates, CIDS framework mapping, final impact report by Dec 9
- Confirm timeline aligns with Dec 9 deadline and provide milestone schedule
- Commit to upstream EAS schema contributions with specific timeline and documentation plan

---

## CIDS Activity Alignment

Which CIDS activity structure(s) does this proposal align with?
- [x] Interoperability
- [x] UI/UX
- [x] Collaboration
- [x] Product Growth

**Notes:** Strong fit across all categories - removes onboarding friction (UI/UX), integrates multiple primitives (Interoperability), involves multiple ecosystem partners (Collaboration), moves from demo to production (Product Growth).
