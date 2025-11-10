# Evaluation: PiePay: Profit-Sharing and Contribution Tracking System for Small Teams

**Date:** 2025-10-22
**Evaluator:** Luiz Fernando
**Proposal Link:** [To be added]

---

## Key Aspects

### Integration/Development in Question
Development of PiePay profit-sharing system features: (1) Manual contribution uploads for Payroll Manager (serial and CSV upload); (2) QA & bug fixes with real-time indexer updates for GUI; (3) Specification design for external contract managers enabling multi-sig or automated management. Focus on improving contribution tracking and profit distribution UX for small teams.

### Funding Amount
$5,000 requested ($1,000 QA, $2,000 contribution uploads, $1,500 bug fixes/wiring, $500 contract specifications)

### General Impression
Well-scoped incremental improvements to existing PiePay system. Clear focus on UX improvements (manual uploads, real-time updates) and technical enhancements (external contract managers). Compatible with Hats Protocol for permissioning. Realistic scope with clear deliverables. Good technical foundation with verified contracts on Arbitrum Sepolia and Envio indexer. Builds on existing infrastructure.

### Alignment with Round
- **Interoperability:** Moderate - compatible with Hats Protocol, mentions external contract managers but doesn't explicitly commit to multiple primitive integrations
- **Collaboration:** Weak - mentions "none" for collaborations
- **UI/UX:** Good - addresses contribution tracking and profit distribution UX pain points
- **Product Maturity:** Good - has deployed contracts, indexer, frontend; realistic incremental improvements

---

## Proposal Feedback

### What I Like About the Proposal
- Clear, focused scope on incremental improvements
- Addresses real UX pain point: manual contribution tracking
- Good technical foundation with verified contracts and working indexer
- Realistic budget and timeline
- Compatible with Hats Protocol for permissioning

### What Can Be Improved or Made More Clear
- Add explicit interoperability plan: commit to 2+ primitive integrations (Hats Protocol + another)
- Specify measurement plan: KPIs for adoption, usage metrics, reporting cadence
- Add collaboration evidence: partner commitments, pilot teams
- Clarify timeline and milestone schedule
- Risk mitigation strategies not addressed

### Questions
- What specific Hats Protocol integration will be delivered and what are the acceptance criteria?
- What are the expected adoption metrics (number of teams using, contributions processed) and how will progress be tracked?
- Can you provide evidence of pilot team commitments or partnerships?
- What is the reporting cadence to Karma GAP and how will metrics be aligned to CIDS framework?

---

## Rubric-Based Analysis

### Interoperability (25 points)
**Focus:** Concrete plan + credible execution path to adopt at least 2 primitives; evidence of upstream contributions (schemas, PRs).

**Analysis:**
- Primitives being integrated: Hats Protocol (mentioned as compatible), external contract managers (specification design). Doesn't explicitly meet 2+ requirement - needs more specific integration commitments.
- Execution credibility: Moderate - has technical foundation, clear deliverables, but integration plan needs more specificity.
- Upstream contribution evidence: Not mentioned - should specify contributions to Hats Protocol or other primitives.
- Strength of interoperability approach: Moderate - compatible with Hats but integration plan needs more detail and additional primitives.

**Assessment:** Weak → Moderate (with explicit integration plan)

---

### UX Impact (20 points)
**Focus:** Clear definition of the UX problem (onboarding, account abstraction, safety, gas, dev-ex, privacy, etc.), severity evidence, and test plan.

**Analysis:**
- UX problem clearly defined: Small teams struggle with manual spreadsheets for contribution tracking and profit distribution. Need automated, transparent system.
- Severity and evidence: Strong narrative - manual spreadsheets are inefficient, need better UX for payroll managers and recipients.
- Test/validation plan: Mentions testnet playground and whiteglove setup but doesn't specify success metrics or validation approach.
- Impact potential: Good - addresses real UX pain point for small teams, improves contribution tracking and distribution workflows.

**Assessment:** Moderate → Strong (with validation metrics)

---

### Product Maturity & Feasibility (15 points)
**Focus:** TRL-style stage mapping with realistic scope for 4-6 weeks; risk register & mitigations.

**Analysis:**
- Current maturity stage: Early production - has deployed contracts (Arbitrum Sepolia), indexer (Envio), frontend, verified on Arbiscan.
- Scope realistic for Dec 9th deadline: Yes - incremental improvements, clear deliverables, realistic scope.
- Risks identified and mitigated: Not explicitly addressed - should add risk register (indexer reliability, CSV parsing issues, contract manager complexity).
- Technical feasibility: High - builds on existing infrastructure, clear technical approach, realistic scope.

**Assessment:** Strong

---

### Collaboration (10 points)
**Focus:** Named integration partners; MOUs/issues opened; co-maintenance or shared roadmaps.

**Analysis:**
- Named partners/collaborators: Explicitly states "none" - no collaborations mentioned.
- Evidence of partnerships (MOUs, issues, etc.): None provided.
- Shared roadmap elements: Not shown - mentions DAOMasons network but doesn't show partner commitments.
- Cross-project potential: Moderate - could be adopted by small teams but needs ecosystem integration.

**Assessment:** Weak

---

### Team Track Record (10 points)
**Focus:** Repos, releases, audits, shipped infra; Proof-of-Ship track record.

**Analysis:**
- Team background and experience: Limited information - UI369 (Product/Dev Lead), Jord (UX/QA Advisor). Should provide more team background.
- Previous shipped projects: Has deployed PiePay contracts, indexer, frontend. GitHub repos provided.
- Repository activity and quality: GitHub org provided (github.com/DAOmasons/piepay-contracts, piepay-user, piepay-indexer), should verify current activity and quality signals.
- Credibility indicators: Has working infrastructure but limited team track record visibility.

**Assessment:** Moderate (needs more visibility)

---

### Measurement Plan (10 points)
**Focus:** Which onchain/offchain metrics will be emitted; EAS schemas; Hypercert minting cadence; reporting via OpenGrants/Karma GAP.

**Analysis:**
- Impact metrics defined: Not explicit - mentions adoption targets but doesn't specify KPIs (number of teams, contributions processed, profit distributions).
- Karma GAP integration plan: Karma GAP profile linked (https://gap.karmahq.xyz/project/piepay) but doesn't specify reporting cadence or CIDS framework mapping.
- CIDS framework alignment: Likely fits UI/UX and Product Growth categories. Should explicitly map to CIDS.
- Reporting frequency and detail: Not specified - should define weekly updates and final impact report by Dec 9.

**Assessment:** Moderate

---

### Budget & Timeline (10 points)
**Focus:** Value for money; milestone clarity; licenses; acceptance criteria; fallback plan.

**Analysis:**
- Budget reasonableness: $5,000 seems reasonable for scope (QA, uploads, bug fixes, specifications). Good breakdown.
- Milestone clarity and achievability: Clear deliverables (D1, D2, D3) with specific scope. D3 is specification design (not implementation).
- Timeline to Dec 9th: Not explicitly specified - should confirm timeline aligns with Dec 9 deadline.
- Acceptance criteria defined: Not explicitly shown - should add acceptance criteria for each deliverable.
- Risk mitigation/fallback: Not addressed - should add risk register and mitigation strategies.

**Assessment:** Moderate → Strong (with timeline and acceptance criteria)

---

## Summary

### Standout Strengths
1. Clear, focused scope on incremental improvements
2. Addresses real UX pain point for small teams
3. Good technical foundation with deployed infrastructure

### Key Concerns / Red Flags
1. Interoperability plan needs more specificity (only Hats Protocol mentioned, needs 2+ primitives)
2. No collaborations mentioned ("none" explicitly stated)
3. Measurement plan and reporting cadence not specified

### Critical Questions for Builder
1. What specific Hats Protocol integration will be delivered and what are the acceptance criteria?
2. Can you commit to at least one additional primitive integration beyond Hats Protocol?
3. What are the expected adoption metrics and how will progress be tracked via Karma GAP?

---

## Final Recommendation

**Conviction Level:** Low → Medium (conditional)

**Rationale:** Clear scope addressing real UX pain point but lacks interoperability focus and ecosystem integration. No collaborations mentioned limits ecosystem impact. Realistic scope with good technical foundation. Recommend funding contingent on explicit interoperability plan (2+ primitives), collaboration commitments, and measurement plan.

**Conditions/Suggestions:**
- Commit to explicit interoperability plan: Hats Protocol integration with acceptance criteria + at least one additional primitive integration
- Add collaboration commitments: pilot teams, partnerships, ecosystem integration
- Specify measurement plan: KPIs (teams onboarded, contributions processed), weekly Karma GAP updates, CIDS framework mapping, final impact report by Dec 9
- Confirm timeline aligns with Dec 9 deadline and add acceptance criteria for each deliverable

---

## CIDS Activity Alignment

Which CIDS activity structure(s) does this proposal align with?
- [ ] Interoperability (conditional on explicit plan)
- [ ] Collaboration (none mentioned)
- [x] UI/UX
- [x] Product Growth

**Notes:** Primarily UI/UX improvements with Product Growth potential. Interoperability and Collaboration need strengthening to align with round goals.
