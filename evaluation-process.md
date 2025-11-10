# GG24 Growth Pool Evaluation Process

**Round:** Gitcoin Grants Round 24 - Public Goods Tooling Development
**Pool:** Growth Pool
**Evaluator:** Luiz Fernando

---

## Quick Reference

### Key Deadlines
- **Proposal Submission Deadline:** October 31st
- **Building & Impact Reporting Deadline:** December 9th
- **Retro Rewards Announcement:** December 12th

### Time Scope for Proposals
- Proposals should be scoped for **4-6 weeks of work** (late October to December 9th)
- "Less is more" - prioritize completable milestones over ambitious scope

---

## Round Goals & Theory of Change

### Round Goals (Priority Order)
1. **Increase Interoperability** - Support projects integrating with shared public goods primitives
2. **Create Collaborations** - Prioritize teams demonstrating clear cross-project partnerships
3. **Improve UI/UX** - Fund solutions addressing key public goods UX challenges
4. **Grow Project Maturity** - Back projects with active roadmap moving toward next growth phase

### Theory of Change
**IF** Ethereum public goods tool builders are connected to diverse forms of capital to build stronger network effects, foster deeper collaboration, and enhance interoperability across the ecosystem.

**THEN** public goods tooling will mature more rapidly and gain broader adoption across traditional markets and local communities.

**BECAUSE** building resilient and impactful tools depends on trust, and trust grows through collective effort.

---

## Eligibility Criteria

All proposals must meet these basic requirements:
- ✅ **Open source** - Code is publicly accessible
- ✅ **Permissionless** - Can be built on without permission
- ✅ **Public goods traction** - Established use in improving community/network/ecosystem infrastructure
- ❌ **Not ecosystem-wide infrastructure** - Not Ethereum clients, wallets, or general dev tooling

---

## Recognized Public Goods Primitives

### Capital Formation
- Juicebox
- Giveth
- RevNets
- Obol
- Octant Vaults

### Capital Allocation + Governance
- Aragon OSx
- Snapshot
- Giveth QF
- Safe + Zodiac
- Kleros
- Superfluid
- 0xSplits
- Nouns Builder
- Easy RetroPGF
- DAOhaus (Moloch v2/v3 "Baal")
- OpenZeppelin Governor Contracts

### Reputation & Identity
- ENS
- EAS (Ethereum Attestation Service)
- Hats Protocol
- Human Passport
- Prosperity Pass
- Zodiac Roles
- OpenGrants

### Impact Measurement
- Hypercerts
- Karma GAP
- Dune Analytics
- DefiLlama

---

## Evaluation Rubric (100 points total)

### 1. Interoperability (25 points) - HIGHEST WEIGHT
**Key Questions:**
- Does the proposal integrate with at least 2 recognized public goods primitives?
- Is there a concrete, credible execution plan for these integrations?
- Is there evidence of upstream contributions (PRs, schema proposals, standards work)?
- Does it enhance composability across the ecosystem?
- Are integration points technically sound?

**Look For:**
- Specific primitive names and integration approaches
- Technical depth in integration strategy
- Evidence of coordination with primitive maintainers
- Potential for network effects

---

### 2. UX Impact (20 points)
**Key Questions:**
- Is there a clearly defined UX problem being solved?
- What category: onboarding, account abstraction, safety, gas, dev-ex, privacy, other?
- How severe is the problem? Is there evidence?
- Is there a test/validation plan for UX improvements?
- Will this meaningfully improve the end-user experience?

**Look For:**
- Specific UX pain points articulated
- User research or evidence of the problem
- Before/after scenarios
- Measurement approach for UX improvement
- User testing plans

---

### 3. Product Maturity & Feasibility (15 points)
**Key Questions:**
- What is the current Technology Readiness Level (TRL) stage?
- Is the scope realistic for 4-6 weeks (until Dec 9th)?
- Are technical risks identified and mitigated?
- Does the team have the capacity to deliver?
- Is there a risk register or acknowledgment of challenges?

**Look For:**
- Current state of the project (prototype, beta, production)
- Realistic milestone breakdown
- Technical dependencies identified
- Contingency planning
- Time estimates that make sense

---

### 4. Collaboration (10 points)
**Key Questions:**
- Are integration partners named specifically?
- Is there evidence of existing relationships (MOUs, GitHub issues, prior work)?
- Are there shared roadmap elements or co-development plans?
- Does this create new cross-project connections?

**Look For:**
- Named partners with contact info or links
- Letters of support or commitment
- Open GitHub issues showing coordination
- Joint development plans
- Evidence of community support

---

### 5. Team Track Record (10 points)
**Key Questions:**
- What has this team shipped before?
- Are there public repositories showing their work?
- Have they completed audits or security reviews?
- Do they have proof-of-ship credibility?
- Are team members identifiable with track records?

**Look For:**
- GitHub profiles and repository links
- Previously deployed contracts or apps
- References to past projects
- Team member credentials
- Community reputation

---

### 6. Measurement Plan (10 points)
**Key Questions:**
- What specific metrics will be tracked (onchain/offchain)?
- Is there a Karma GAP integration plan?
- Will they use EAS schemas or Hypercerts?
- Does the measurement plan align with CIDS framework?
- How frequently will they report progress?

**Look For:**
- Specific KPIs or metrics defined
- Karma GAP project setup commitment
- Impact reporting framework understanding
- Milestone-linked deliverables
- Quantifiable outcomes

---

### 7. Budget & Timeline (10 points)
**Key Questions:**
- Is the funding request reasonable for the scope?
- Are milestones clearly defined with acceptance criteria?
- Does the timeline align with the Dec 9th deadline?
- Is there a fallback plan if something goes wrong?
- Are licenses and dependencies clear?

**Look For:**
- Itemized budget breakdown
- Cost justification
- Clear milestone definitions
- Realistic time allocation
- Risk mitigation strategies

---

## CIDS Framework Alignment

Each proposal should align with one or more of these activity structures:
1. **Interoperability** - Integrating multiple primitives
2. **Collaboration** - Cross-project partnerships
3. **UI/UX** - User experience improvements
4. **Product Growth** - Maturity advancement

---

## Evaluation Workflow

### Step 1: Screenshot Analysis
When you share a proposal screenshot:
1. I will extract all visible proposal details
2. Note: project name, team, funding request, description, milestones, primitives mentioned

### Step 2: Systematic Review
I will analyze the proposal against each rubric criterion:
1. Interoperability (25 pts)
2. UX Impact (20 pts)
3. Product Maturity & Feasibility (15 pts)
4. Collaboration (10 pts)
5. Team Track Record (10 pts)
6. Measurement Plan (10 pts)
7. Budget & Timeline (10 pts)

### Step 3: Generate Structured Feedback
Output will include:
- **Key Aspects** - Quick overview
- **Proposal Feedback** - Likes, improvements, questions
- **Rubric Analysis** - Qualitative assessment per criterion (no numerical scores)
- **Summary** - Strengths, concerns, critical questions
- **Final Recommendation** - Conviction level and rationale

### Step 4: Save Evaluation
File saved to: `/Users/luizfernando/Desktop/Workspaces/Zettelkasten/251001 GG24/evaluations/[proposal-name]-evaluation.md`

---

## Red Flags to Watch For

- ❌ Scope too ambitious for 4-6 weeks
- ❌ No specific primitive integrations named
- ❌ Vague milestones or acceptance criteria
- ❌ No measurement or impact reporting plan
- ❌ Team with no visible track record
- ❌ Budget not justified or unreasonable
- ❌ No clear UX problem definition
- ❌ Ignores the Dec 9th deadline
- ❌ No collaboration or partnership evidence
- ❌ Missing technical feasibility details

---

## Green Flags to Look For

- ✅ 2+ primitive integrations with clear approach
- ✅ Named partners with evidence of coordination
- ✅ Realistic, detailed milestone breakdown
- ✅ Strong team track record with links
- ✅ Specific UX problem with evidence
- ✅ Comprehensive measurement plan (Karma GAP, etc.)
- ✅ Upstream contributions planned (PRs, schemas)
- ✅ Risk awareness and mitigation strategies
- ✅ Clear CIDS framework alignment
- ✅ Budget justified with line items

---

## Using This Process

### Quick Start
1. Share a proposal screenshot with me
2. I'll analyze it against the rubric
3. Review the generated evaluation
4. Use it as basis for your formal evaluation
5. Add your own insights and adjust as needed

### Integration with Conviction Voting
- Use evaluations to inform your conviction allocation
- Higher conviction on proposals with strong alignment across multiple criteria
- Lower/no conviction on proposals with significant red flags or misalignment

### Collaboration with Council
- Share standout proposals and concerns in Telegram
- Use evaluations as discussion starting points
- Iterate on feedback based on council dialogue

---

## Notes

- Evaluations are **qualitative** - no numerical scores assigned
- Focus on **constructive feedback** to help builders improve
- Be **specific** in questions and suggestions
- Consider the **Theory of Change** when assessing alignment
- Remember: this is about **building trust through collective effort**

---

**Ready to evaluate? Share a proposal screenshot to begin!**

