## Welcome To The Growth Pool Proposal Form

This form gathers the key details of your proposal to be shared to the community and provide the evaluation council key information to evaluate your proposal.

**Who's this Pool for?**

- Experienced builders with an idea addressing a critical infrastructure need

- Builders of existing public good tooling looking to become more interoperable

**Here are the step you will take:**

1. **Fill Out From** - Provide a detailed yet concise overview of your proposal.

2. **Community Feedback** - Address feedback and questions from the community and evaluators.

3. **Gardens Submission** - Once feedback is addressed, publish proposal on Gardens platform with the funding amount, title, problem being solved and Charmverse proposal link.

Once submitted to Gardens, the Evaluation Council will review your proposal and then support proposals on Gardens. You'll be able to see evaluation feedback on Charmverse and conviction growing on Gardens.

> _As your application moves through the evaluation flow you will receive notifications sent to your email used with Charmverse._
>
> _If you have questions or need support, [reach out on Telegram](https://t.me/+U4CtT8tOneZlZGRh)._ 

### What categories of public goods does your proposal address?

Impact Measurement

### Problem Being Solved

Ethereum’s current ecosystem lacks standardized, user-friendly infrastructure for verifying real-world impact data on-chain. Developers building sustainability or ReFi applications must repeatedly design custom contracts, metadata structures, and validation pipelines – leading to redundant gas costs, poor interoperability, and inconsistent data. 

ICM introduces a unified schema and SDK for issuing verifiable impact certificates aligned with SDG targets. It reduces developer setup time and integration friction across L2s, enables post-mint attestations through EAS, and provides a consistent, low-code UX for building transparent proof-of-impact systems. 

From a UX standpoint, the SDG Engine and EAS integration simplify what used to be a multi-step, technical process. Users can now select pre-built templates, auto-populate SDG data, preview certificates, and complete validation through a single guided flow, turning complex on-chain proof systems into a simple experience accessible to all.

### Team

Atlantis’ seven-member core team combines deep climate-tech domain knowledge with full-stack Web3 engineering experience. 

Irthu (CEO) – 8 yrs in climate impact; led product design for Impact Miner & Impact Foundry. 
Nakul (COO) – Project manager with 10 yrs in ops & partnerships. 
Martin (Engineering Lead) – 10+ yrs building scalable Web3 infra; oversees ICM architecture. 
Shubham (Backend / Blockchain Lead) – Solidity & Node.js specialist. 
Devanshi (Design & UX) – Designs SDG-mapping templates & validator UIs. 
Himanshu (Frontend Engineer) + Madhav Sampat (Marketing) – UI implementation & community adoption.

### Karma GAP Profile

https://gap.karmahq.xyz/project/impact-certificate-minter

### Github Repo or Organization (If Multiple Repos)

https://github.com/AtlantisDAO1/project-impact-certificate-mint-api

### Project Tech Stack

Backend: Node.js, Express; 
Contracts: Solidity (ERC‑721); 
Storage: IPFS/Arweave; EAS (attestations); 
Cross‑chain: deployed on Base, Optimism, Arbitrum & Celo; 

### Collaborations

Partnering with regional NGOs (water, agriculture, biodiversity) for pilot certificates. In discussion with ReFi protocols for schema alignment and resuming integration with Karma GAP for shared SDG datasets during this round.

### Deliverables

D1 – SDG Engine & Mapping Templates: Release a new metadata schema supporting UN sub‑targets and intensity metrics; publish mapping templates and docs. 

Acceptance: GitHub release, sample certificates minted with new fields. 


D2 – EAS Integration & SDKs: Integrate with the Ethereum Attestation Service (EAS) by registering a custom ICM schema and enabling validator attestations for post-mint validation on at least two L2s. Release JS/Python SDKs to simplify attestation submission and verification. 

Acceptance: Schema live on EAS (Base & Arbitrum) with demo validator attestations recorded on-chain.

These deliverables directly improve the end-user experience by introducing guided SDG mapping templates, a visual certificate builder, and a validator dashboard integrated with EAS. NGOs and DAOs will move from manual, off-chain reporting to a streamlined, low-code interface for creating and validating impact certificates.

### Budget

Amount Requested: $6,000 

Engineering – $3,000 
Design & UX – $1,000 
Docs & Community – $1,000 
Operations & QA – $1,000


Risks & Mitigations: 
- EAS integration delay → fallback to manual attestation logging for interim validation.
- Cross-chain bridging issues → begin with Base and Arbitrum deployments before expanding to other L2s.

### GTM & Adoption Plan

We’ll onboard five pilot NGOs/DAOs to issue impact certificates using the new SDG Engine and attestation workflow. A Quickstart guide, SDK tutorial, and integration workshops with the Gardens and ReFi communities will drive early adoption. During the round, we’ll integrate ICM with EAS and Safe-based treasuries for automated payouts, and coordinate with Karma GAP for alignment on impact reporting. 

For the upcoming pilot phase, we’re collaborating with four local NGOs: 

- CHESS – Community Human Empowerment Service for Society (Agriculture & Sustainable Development): supporting farmers to adopt regenerative practices and mint certificates for hectares of farmland transitioned to sustainable crops. 

- Pollen Buzz (Beekeeping Education): training beekeepers and tracking pollinator-friendly flora to generate biodiversity-linked certificates. 

- VOICE (Water & Sanitation): facilitating community water access and sanitation impact reporting through verified clean-water certificates. 

- Chiranoothana (Water-body Cleanup): documenting lake and river restoration activities to issue certificates for volunteer-hours and surface area cleaned. 

These partners will use the SDG Engine to mint pilot certificates for measurable environmental outcomes (e.g., “hectares restored,” “bee-friendly flora surveyed”). We’re also planning collaborations with the GP Network, AgroforestDAO, and Rifai Sicilia to extend adoption across international ReFi and agroecology networks. 

Our goal is to establish small-scale but high-signal proof of verifiable, SDG-linked impact data on-chain, demonstrating that the ICM schema can serve as a trusted standard for NGOs, DAOs, and funders alike.

### Additional Links and Resources

https://icm-docs.atlantisp2p.com