# Evaluation: PiePay: Profit-Sharing and Contribution Tracking System for Small Teams

---

## 📊 Evaluation Scores & Rationale

| **Rubric Category** | **Score** |
| --- | --- |
| Interoperability | 11/25 |
| UX Impact | 15/20 |
| Product Maturity & Feasibility | 13/15 |
| Collaboration | 3/10 |
| Team Track Record | 6/10 |
| Measurement Plan | 6/10 |
| Budget & Timeline | 7/10 |

### **📊 Average Score: 6.9/10**

### **🔢 Total Score: 61/100**

---

## Key Aspects

### Integration/Development in Question
Development of PiePay profit-sharing system features: (1) Manual contribution uploads for Payroll Manager (serial and CSV upload); (2) QA & bug fixes with real-time indexer updates for GUI ensuring GUI always represents onchain state in near real-time; (3) Specification design for external contract managers enabling multi-sig or automated management (specification only, not implementation). Focus on improving contribution tracking and profit distribution UX for small teams. Compatible with Hats Protocol for permissioning.

### Funding Amount
$5,000 requested ($1,000 QA, $2,000 contribution uploads, $1,500 bug fixes/wiring, $500 contract specifications)

### General Impression
Well-scoped incremental improvements to existing PiePay system. Clear focus on UX improvements (manual uploads, real-time updates) and technical enhancements (external contract managers specification). Compatible with Hats Protocol for permissioning but doesn't explicitly commit to integration. Realistic scope with clear deliverables. Good technical foundation with verified contracts on Arbitrum Sepolia and Envio indexer. Builds on existing infrastructure. However, explicitly states "none" for collaborations, which limits ecosystem impact.

### Alignment with Round
- Interoperability: Weak - compatible with Hats Protocol but doesn't explicitly commit to multiple primitive integrations
- Collaboration: Weak - explicitly states "none" for collaborations
- UI/UX: Good - addresses contribution tracking and profit distribution UX pain points
- Product Maturity: Good - has deployed contracts, indexer, frontend; realistic incremental improvements

---

## Proposal Feedback

### What I Like About the Proposal
- Clear, focused scope on incremental improvements
- Addresses real UX pain point: manual contribution tracking
- Good technical foundation with verified contracts and working indexer
- Realistic budget and timeline
- Compatible with Hats Protocol for permissioning
- Clear deliverables with specific scope

### What Can Be Improved or Made More Clear
- Add explicit interoperability plan: commit to 2+ primitive integrations (Hats Protocol + another) with deliverables
- Specify measurement plan: KPIs for adoption, usage metrics, reporting cadence
- Add collaboration commitments: partner commitments, pilot teams
- Clarify timeline and milestone schedule for Dec 9 deadline
- Risk mitigation strategies not addressed

### Questions
- What specific Hats Protocol integration will be delivered and what are the acceptance criteria?
- What are the expected adoption metrics (number of teams using, contributions processed) and how will progress be tracked?
- Can you commit to at least one additional primitive integration beyond Hats Protocol?
- What is the reporting cadence to Karma GAP and how will metrics be aligned to CIDS framework?

---

## Rubric-Based Analysis

## 🔹 **Interoperability**

### **Interoperability Score: 11/25**

### **Rationale:**

The proposal mentions Hats Protocol as compatible for permissioning but doesn't explicitly commit to integration in deliverables. The proposal mentions "external contract managers" in D3 (specification design) which could enable multi-sig or automated management, but this is specification only, not implementation. The proposal doesn't explicitly meet the 2+ primitive requirement with detailed integration plans.

Execution credibility is moderate - the proposal has technical foundation with verified contracts on Arbitrum Sepolia and Envio indexer, clear deliverables, but integration plan needs more specificity. The proposal should commit to Hats Protocol integration with acceptance criteria and at least one additional primitive integration.

Upstream contribution evidence is not mentioned - the proposal should specify contributions to Hats Protocol or other primitives. The strength of the interoperability approach is moderate - compatible with Hats but integration plan needs more detail and additional primitives to meet round requirements.

Overall assessment is weak to moderate - needs explicit integration plan with 2+ primitives and acceptance criteria.

---

## 🔹 **UX Impact**

### **UX Impact Score: 15/20**

### **Rationale:**

The UX problem is clearly defined: small teams struggle to fairly track diverse contributions (time, capital, IP) and distribute profits transparently without manual spreadsheets or centralized intermediaries. Teams need an automated, transparent profit-sharing system that gives more control to payroll managers and recipients.

Severity and evidence are strong - the narrative clearly articulates how manual spreadsheets are inefficient and how teams need better UX for payroll managers and recipients. The proposal addresses real pain point for small teams (5-20 members) including grant-funded projects, DAO working groups, open-source collectives, and freelance Web3 teams.

The test/validation plan mentions testnet playground and whiteglove setup but doesn't specify success metrics or validation approach. The proposal should define KPIs such as number of teams onboarded, contributions processed, or time saved vs manual spreadsheets.

Impact potential is good - addresses real UX pain point for small teams, improves contribution tracking and distribution workflows, and enables transparent profit-sharing. Overall assessment is moderate to strong - clear problem with strong narrative, but validation plan needs more specificity.

---

## 🔹 **Product Maturity & Feasibility**

### **Product Maturity & Feasibility Score: 13/15**

### **Rationale:**

The current maturity stage is early production - the proposal has deployed contracts on Arbitrum Sepolia (verified on Arbiscan), Envio indexer operational, frontend deployed, and GitHub repos provided. The scope for this round is incremental improvements (manual uploads, bug fixes, specification design), which is realistic for the Dec 9th deadline.

The scope appears realistic - incremental improvements with clear deliverables are feasible within the timeline. However, timeline to Dec 9th is not explicitly specified - the proposal should confirm timeline aligns with Dec 9 deadline.

Risks are not explicitly addressed - the proposal should add risk register covering indexer reliability, CSV parsing issues, contract manager complexity, and timeline compression. Technical feasibility is high - builds on existing infrastructure, clear technical approach, realistic scope, and proven execution capability.

Overall assessment is strong - good foundation with realistic incremental improvements.

---

## 🔹 **Collaboration**

### **Collaboration Score: 3/10**

### **Rationale:**

The proposal explicitly states "none" for collaborations - no collaborations mentioned. This significantly limits ecosystem impact and doesn't align with round goals emphasizing collaboration. The proposal mentions "DAOMasons network" for pilot projects but doesn't show partner commitments or evidence.

Evidence of partnerships such as MOUs, issues, or letters is not provided - the proposal should add collaboration commitments, pilot teams, or ecosystem integration partnerships. Shared roadmap elements are not shown - the proposal doesn't show partner commitments or timeline coordination.

Cross-project potential is moderate - could be adopted by small teams but needs ecosystem integration. Without collaborations, the proposal misses opportunity to demonstrate ecosystem impact and cross-project coordination.

Overall assessment is weak - explicitly states no collaborations, which limits ecosystem impact.

---

## 🔹 **Team Track Record**

### **Team Track Record Score: 6/10**

### **Rationale:**

The team consists of UI369 (Product/Dev Lead) and Jord (UX/QA Advisor). The proposal provides limited information on team background and experience - should provide more team background, GitHub links, or detailed experience beyond roles.

Previous shipped projects include deployed PiePay contracts on Arbitrum Sepolia, Envio indexer operational, frontend deployed, and GitHub repos provided (github.com/DAOmasons/piepay-contracts, piepay-user, piepay-indexer). The proposal demonstrates some execution capability with working infrastructure.

Repository activity and quality should be verified - the proposal provides GitHub org links but doesn't show tests/CI, release notes, or recent activity signals. Credibility indicators include working infrastructure but limited team track record visibility.

Overall assessment is moderate - has working infrastructure but needs more visibility into team track record and repository quality.

---

## 🔹 **Measurement Plan**

### **Measurement Plan Score: 6/10**

### **Rationale:**

Impact metrics are not explicitly defined - the proposal mentions adoption targets and pilot projects (2-5 pilot projects with teams from DAOMasons network) but doesn't specify KPIs such as number of teams, contributions processed, profit distributions, or time saved vs manual spreadsheets.

The Karma GAP integration plan exists - profile link provided (https://gap.karmahq.xyz/project/piepay) - but the proposal doesn't specify reporting cadence or CIDS framework mapping. The proposal should define weekly updates and final impact report by Dec 9.

CIDS framework alignment likely fits UI/UX and Product Growth categories. The proposal should explicitly map metrics to CIDS categories. Reporting frequency and detail are not specified - the proposal should define weekly Karma GAP updates with specific metrics.

Overall assessment is moderate - foundation exists with Karma GAP profile but lacks specificity on metrics and reporting cadence.

---

## 🔹 **Budget & Timeline**

### **Budget & Timeline Score: 7/10**

### **Rationale:**

The budget of $5,000 seems reasonable for scope (QA, uploads, bug fixes, specifications). Good breakdown ($1,000 QA, $2,000 contribution uploads, $1,500 bug fixes/wiring, $500 contract specifications).

Milestone clarity and achievability are good - clear deliverables (D1: manual uploads, D2: QA & bug fixes, D3: specification design) with specific scope. However, D3 is specification design only (not implementation), which is appropriate for scope. Acceptance criteria are not explicitly shown - the proposal should add acceptance criteria for each deliverable.

Timeline to Dec 9th is not explicitly specified - the proposal should confirm timeline aligns with Dec 9 deadline. Risk mitigation and fallback planning are not addressed - the proposal should add risk register and mitigation strategies.

Overall assessment is moderate to strong - reasonable budget with clear deliverables but needs timeline confirmation and acceptance criteria.

---

## 🧾 Final Summary

| **Rubric Category** | **Score (X/Y)** |
| --- | --- |
| Interoperability | 11/25 |
| UX Impact | 15/20 |
| Product Maturity & Feasibility | 13/15 |
| Collaboration | 3/10 |
| Team Track Record | 6/10 |
| Measurement Plan | 6/10 |
| Budget & Timeline | 7/10 |

### **📊 Average Score: 6.9/10**

### **🔢 Total Score: 61/100**

### **📝 Summary:**

### Standout Strengths
1. Clear, focused scope on incremental improvements
2. Addresses real UX pain point for small teams
3. Good technical foundation with deployed infrastructure
4. Realistic budget and timeline

### Key Concerns / Red Flags
1. Interoperability plan needs more specificity (only Hats Protocol mentioned, needs 2+ primitives)
2. No collaborations mentioned ("none" explicitly stated) - limits ecosystem impact
3. Measurement plan and reporting cadence not specified
4. Timeline not explicitly confirmed
5. Acceptance criteria not explicitly shown for deliverables

### Critical Questions for Builder
1. What specific Hats Protocol integration will be delivered and what are the acceptance criteria?
2. Can you commit to at least one additional primitive integration beyond Hats Protocol?
3. What are the expected adoption metrics (number of teams, contributions processed) and how will progress be tracked via Karma GAP?
4. Can you add collaboration commitments (pilot teams, partnerships) to demonstrate ecosystem impact?

---

## Final Recommendation

**Conviction Level:** Low to Medium (conditional)

**Rationale:** Clear scope addressing real UX pain point but lacks interoperability focus and ecosystem integration. No collaborations mentioned limits ecosystem impact. Realistic scope with good technical foundation. Recommend funding contingent on explicit interoperability plan (2+ primitives), collaboration commitments, measurement plan, and timeline confirmation.

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

**Notes:** Primarily UI/UX improvements with Product Growth potential. Interoperability and Collaboration need strengthening to align with round goals. The proposal addresses real UX pain point but lacks ecosystem integration focus required for this round.
