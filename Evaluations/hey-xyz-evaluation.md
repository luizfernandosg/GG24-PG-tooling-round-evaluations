# Evaluation: Hey.xyz

---

## 📊 Evaluation Scores & Rationale

| **Rubric Category** | **Score** |
| --- | --- |
| Interoperability | 19/25 |
| UX Impact | 18/20 |
| Product Maturity & Feasibility | 11/15 |
| Collaboration | 6/10 |
| Team Track Record | 6/10 |
| Measurement Plan | 7/10 |
| Budget & Timeline | 7/10 |

### **📊 Average Score: 7.7/10**

### **🔢 Total Score: 74/100**

---

## Key Aspects

### Integration/Development in Question
Ship Hey.xyz mobile + developer tooling to reduce friction for onchain social (Lens Protocol). Deliverables include: D1: Deploy Hey Developer SDK for building Lens-integrated social tools (accepted when open-sourced on GitHub with docs and verified demo integration on testnet); D2: Launch Hey Mobile App with full Lens + Ethereum social support (accepted when released on iOS and Android, verified through public repo build, EAS attestation, and active on-chain user sessions). The proposal integrates with Lens Protocol, EAS (mentioned in deliverables), and mentions Hypercerts and Safe/Zodiac in tech stack.

### Funding Amount
$30,000 requested ($6,000 Design, $18,000 Engineering, $4,000 Infra & Deployment, $2,000 Project Management & Ops)

### General Impression
Clear UX-oriented proposal to make onchain social more accessible with high distribution potential. Hey.xyz has existing user base (~850K users, 6K DAU) and strong Lens Protocol integration. Strong alignment if integrations are concrete and upstreamed. Mobile execution and developer tooling can unlock adoption, but scope should be right-sized to Dec 9 with measurable outcomes.

### Alignment with Round
- Interoperability: Strong - targets EAS/Hypercerts + Safe/Zodiac; needs concrete artifacts and upstream PRs
- Collaboration: Moderate - leans on Lens ecosystem and creator partners; needs named partners and evidence
- UI/UX: Strong - focus on mobile onboarding and developer experience
- Product Maturity: Moderate - feasible MVP if tightly scoped (mobile app + 2 integrations + quickstart)

---

## Proposal Feedback

### What I Like About the Proposal
- Addresses real UX friction for onchain social with mobile-first approach
- Plans to publish SDK/quickstart and developer APIs to enable composition
- Integrates widely recognized primitives (Lens, EAS) to standardize identity/recognition
- Existing user base (~850K users, 6K DAU) demonstrates traction
- Clear deliverables with specific acceptance criteria

### What Can Be Improved or Made More Clear
- Confirm two+ integrations (e.g., EAS attestations + Hypercerts badges/receipts) with concrete artifacts and upstream PRs
- Provide itemized budget justification - $30,000 is higher than average
- Name creator/dev partners and share evidence (issues, letters, MOUs)
- Clarify timeline and milestone schedule for Dec 9 deadline

### Questions
- Which two+ primitives will be fully integrated by Dec 9 and what artifacts will ship for each (schemas, adapters, example app, upstream PRs)?
- What is the detailed timeline for completing D1 and D2 by Dec 9?
- Who are the launch partners (Lens creators, devs)? What commitments/evidence can you provide?
- Can you justify the $30,000 budget request with detailed breakdown?

---

## Rubric-Based Analysis

## 🔹 **Interoperability**

### **Interoperability Score: 19/25**

### **Rationale:**

The proposal demonstrates strong interoperability through integration with Lens Protocol (explicit primary integration), EAS (mentioned in D2 acceptance criteria), and mentions Hypercerts and Safe + Zodiac in the tech stack. The proposal explicitly commits to EAS attestation in D2 acceptance criteria ("verified through public repo build, EAS attestation").

Execution credibility is high - Hey.xyz has existing codebase with ~850K users and 6K DAU, demonstrating proven execution capability. The mobile + SDK approach is sound, but the proposal needs specific adapters and upstream engagement details. The proposal mentions integrating Lens Protocol extensively, which is a recognized primitive for identity/reputation.

However, upstream contribution evidence is not explicitly linked - the proposal should specify EAS schema PRs and Hypercerts example templates. The strength of the interoperability approach has high potential if concrete integrations + upstream PRs land, but needs more specificity on what will be contributed upstream.

Overall assessment is moderate to strong - meets requirement with Lens + EAS, but would be stronger with explicit Hypercerts integration commitment and upstream PRs.

---

## 🔹 **UX Impact**

### **UX Impact Score: 18/20**

### **Rationale:**

The UX problem is clearly defined: onboarding and usability in Ethereum social apps are complex. Hey.xyz simplifies this by offering gasless actions, smart wallet support, and a smooth Lens-based social experience, reducing friction and enabling anyone to interact on-chain in seconds.

Severity and evidence are strong - the proposal mentions existing user base (~850K users, 6K DAU) demonstrating demand. The problem addresses onboarding/sign-in, permissions, cross-device continuity, and developer integration friction. However, baseline metrics (activation, retention, steps) and research references could strengthen the evidence.

The test/validation plan could be more specific - the proposal mentions onboarding existing Lens creators and developer partners, running community campaigns, and closed beta for verified Lens creators, but doesn't define MVP success metrics (MAU, retention D7/D30, action completion funnels) or survey cadence.

Impact potential is high with mobile distribution and developer kits - enabling onchain social interaction "in seconds" addresses fundamental UX barrier. Overall assessment is strong, though validation plan could be more specific.

---

## 🔹 **Product Maturity & Feasibility**

### **Product Maturity & Feasibility Score: 11/15**

### **Rationale:**

The current maturity stage is existing codebase with proven user base - Hey.xyz has ~850K users and 6K DAU, demonstrating active platform. Shipping mobile + SDK within the Dec 9 window is plausible if scope is tight, but the proposal includes both D1 (SDK) and D2 (mobile app), which may be ambitious.

The scope appears realistic for Dec 9th deadline IF limited to MVP app + 2 integrations + quickstart + limited APIs. However, D2 includes "full Lens + Ethereum social support" which may be broad. The proposal should confirm if both D1 and D2 can be completed by Dec 9.

Risks identified include app store approvals and dependency churn, but mitigations are not explicitly detailed. The proposal should add mitigations and fallback channels (TestFlight/APK + web PWA). Technical feasibility is reasonable with focused deliverables and prior experience, but scope concerns remain.

Overall assessment is moderate to strong - existing platform provides foundation but scope may be ambitious for timeline.

---

## 🔹 **Collaboration**

### **Collaboration Score: 6/10**

### **Rationale:**

The proposal mentions Lens Protocol as a collaboration partner and mentions onboarding "existing Lens creators and developer partners already active on Hey.xyz" but doesn't provide explicit named partners or evidence of commitments. The proposal mentions "closed beta of the Hey mobile app for verified Lens creators" but doesn't specify who these creators are.

Evidence of partnerships such as MOUs, issues, or letters is not provided - the proposal should add links/screenshots or evidence of collaboration commitments. Shared roadmap elements are not shown - the proposal should propose public milestones and partner timelines.

Cross-project potential is high across social and identity layers - the SDK and mobile app can enable broader ecosystem adoption. However, without explicit partner commitments and evidence, the collaboration aspect is weaker.

Overall assessment is moderate - good collaboration signals with Lens ecosystem but needs explicit named partners and evidence.

---

## 🔹 **Team Track Record**

### **Team Track Record Score: 6/10**

### **Rationale:**

The team consists of Yoginth (Founder and Engineer, aka A to Z). The proposal provides GitHub repo link (github.com/heyverse/hey) but doesn't show specific team member background, previous shipped projects, or detailed experience beyond founder role.

Previous shipped projects include Hey.xyz platform with ~850K users and 6K DAU, demonstrating proven execution capability. The proposal mentions existing codebase and user base, but doesn't provide links to prior launches (mobile/web) or detailed track record.

Repository activity and quality should be verified - the proposal provides GitHub repo link but doesn't show tests/CI, semver, changelogs, or recent activity signals. Credibility indicators include existing user base and platform traction, but more detail on team background would strengthen this aspect.

Overall assessment is moderate - proven platform execution but limited visibility into team track record and repository quality.

---

## 🔹 **Measurement Plan**

### **Measurement Plan Score: 7/10**

### **Rationale:**

Impact metrics are proposed but not explicitly defined - the proposal mentions onboarding existing Lens creators and developer partners, running community campaigns, and measuring adoption, but doesn't specify KPIs such as verified creators onboarded, daily actions, EAS attestations minted, Hypercerts issued, app store installs/retention.

The Karma GAP integration plan exists - profile link provided (https://gap.karmahq.xyz/project/heyxyz-formerly-lenster) - but the proposal doesn't specify reporting cadence or CIDS framework mapping. The proposal should provide weekly cadence and map metrics to CIDS categories.

CIDS framework alignment fits UI/UX, Interoperability, and Product Growth categories, with Collaboration via partners. The proposal should explicitly map how metrics align to these categories. Reporting frequency and detail are not specified - the proposal should define weekly updates and final impact report by Dec 9.

Overall assessment is moderate to strong - foundation exists with Karma GAP profile and clear potential metrics, but needs specificity on KPIs and reporting cadence.

---

## 🔹 **Budget & Timeline**

### **Budget & Timeline Score: 7/10**

### **Rationale:**

The budget of $30,000 is higher than average for this round, with breakdown ($6,000 Design, $18,000 Engineering, $4,000 Infra & Deployment, $2,000 PM & Ops). The proposal should justify the higher budget with clear value proposition and detailed deliverables.

Milestone clarity and achievability are good - clear deliverables (D1: SDK, D2: Mobile App) with specific acceptance criteria. However, the proposal should define 3-4 milestones with acceptance criteria (e.g., MVP app live, 2 integrations shipped with PRs, quickstart published, partner pilot live).

Timeline to Dec 9th appears feasible with tight scoping, but the proposal doesn't explicitly confirm timeline alignment. The proposal should confirm if both D1 and D2 can be completed by Dec 9, or if D2 is a stretch goal.

Acceptance criteria are specified but could be more detailed per milestone. Risk mitigation and fallback planning should include alternative distribution if app store delays occur (TestFlight/APK, web PWA).

Overall assessment is moderate to strong - reasonable budget structure but needs justification for higher amount and timeline confirmation.

---

## 🧾 Final Summary

| **Rubric Category** | **Score (X/Y)** |
| --- | --- |
| Interoperability | 19/25 |
| UX Impact | 18/20 |
| Product Maturity & Feasibility | 11/15 |
| Collaboration | 6/10 |
| Team Track Record | 6/10 |
| Measurement Plan | 7/10 |
| Budget & Timeline | 7/10 |

### **📊 Average Score: 7.7/10**

### **🔢 Total Score: 74/100**

### **📝 Summary:**

### Standout Strengths
1. High-impact mobile UX improvements for onchain social
2. Developer-oriented SDK/APIs enabling composition
3. Existing user base (~850K users, 6K DAU) demonstrates traction
4. Integrations with recognized primitives (Lens, EAS) to standardize identity/recognition

### Key Concerns / Red Flags
1. Concrete integration plan and upstream contributions not linked (EAS/Hypercerts PRs)
2. Partner commitments not named/evidenced (Lens creators, devs)
3. Budget ($30,000) is higher than average - needs justification
4. Scope may be ambitious - can both D1 and D2 be completed by Dec 9?

### Critical Questions for Builder
1. Which two+ primitives will be integrated by Dec 9 (EAS, Hypercerts, Safe/Zodiac), and what artifacts will ship (schemas, adapters, PRs, demo)?
2. What is the detailed timeline for completing D1 and D2 by Dec 9? Can both be completed?
3. Who are the launch partners (creators/devs), and what evidence can you provide?
4. Can you justify the $30,000 budget request with detailed value proposition?

---

## Final Recommendation

**Conviction Level:** Medium-High (conditional)

**Rationale:** Strong UX + interop potential with realistic MVP scope and ecosystem fit. Existing user base demonstrates traction. Recommend funding contingent on concrete integrations (EAS/Hypercerts), partner evidence, clear acceptance criteria, budget justification, and timeline confirmation.

**Conditions/Suggestions:**
- Commit to EAS + Hypercerts integrations with upstream PRs; publish quickstart and developer API docs
- Launch MVP mobile app (TestFlight/APK if store approval pending); run a partner pilot
- Provide weekly GAP updates mapped to CIDS with KPIs for installs, MAU, actions, attestations
- Justify $30,000 budget with detailed breakdown and value proposition
- Confirm timeline - can both D1 and D2 be completed by Dec 9?

---

## CIDS Activity Alignment

Which CIDS activity structure(s) does this proposal align with?
- [x] UI/UX
- [x] Interoperability
- [x] Product Growth
- [x] Collaboration (with Lens creators/devs)

**Notes:** Treat as a UX-led proposal underpinned by interop deliverables; ensure at least two primitives with upstream artifacts to satisfy Growth Pool priorities. Strong fit - reduces onboarding friction (UI/UX), integrates Lens and EAS (Interoperability), expands Hey.xyz to mobile (Product Growth), involves Lens ecosystem (Collaboration).
