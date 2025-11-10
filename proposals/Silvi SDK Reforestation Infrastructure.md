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

Impact Measurement, Capital Allocation, Governance/Coordination

### Problem Being Solved

**The Real Innovation Opportunity:**

Tree impact has remained generationally symbolic but siloed around the world—different organizations run isolated campaigns with custom verification standards and funding mechanisms. We need standardized tree impact primitives that any protocol can integrate, just as ERC-20 standardized fungible tokens and enabled DeFi. Our parallel $100k reforestation campaigns across Brasil, Italy, Nigeria, Uganda, Kenya and many more ethereum local nodes and ReFi/GP chapters provide the perfect testbed—real implementing partners with real data who need this toolkit immediately. By exposing Silvi's methodology configuration as an SDK and creating on-chain queryable metadata, we transform from a closed MRV frontend into open infrastructure. This enables any organization to deploy their own reforestation products that compose with the broader ReFi ecosystem—with the vision one day of AMMs pricing TreeForwards, carbon/biodiversity markets having derivative Silvi data, and impact funds programmatically scoping, discovering and funding projects. Further, the Treekipedia partnership enables ecological optimization as part of the configuration, making tree impact not just verified but scientifically optimized at the protocol level.

**The Methodology Configuration Bottleneck:**

While the Silvi MRV app is free and permissionless, reforestation project and campaign configuration has required manual backend intervention for every new implementing partner at Silvi. When organizations like Rifai Sicilia or Project Osisi want to run reforestation campaigns through Silvi, our team must manually configure their specific claim milestones, verification thresholds, payout schedules, and beneficiary splits directly in the backend. This process creates friction and prevents scale beyond a handful of carefully onboarded organizations. More critically, this closed architecture prevents the composability that ReFi needs—while our reporting frameworks are increasingly open (EAS,  txs, new Karma data flows, etc) external protocols cannot programmatically discover, verify, or integrate with tree impact data because it's locked inside Silvi admin console. This has allowed us to iterate and refine our stack, but it's time for the community to configure projects as they wish.

### Team

Djimo  - Tree man
Sev  - Product manager
Hannah - Lead designer
Dennis - Front end dev

Moses - Back end dev

Jeremic - data engineer

Marina - data scientist

### Karma GAP Profile

https://gap.karmahq.xyz/project/silvi

### Github Repo or Organization (If Multiple Repos)

https://github.com/SilviProtocol

### Project Tech Stack

**Core Infrastructure (Existing, Production-Ready):**

- Backend: Django REST Framework, PostgreSQL, PostGIS (geospatial)

- Task Queue: RabbitMQ (async evidence processing, attestations)

- Frontend: Next.js 15, React Query, Mapbox GL

- Authentication: NextAuth v5, JWT refresh, Web3 wallet auth

**Ethereum/Web3 Stack:**

- **Karma** (impact metrics and data streaming already pushing data!)

- **EAS** (Ethereum Attestation Service—immutable event logging)

- **AlloKit** (funding pools, strategy contracts, milestone-based payouts)

- **Web3.py** (contract interaction, transaction building)

- **Wagmi + RainbowKit** (wallet connection, transaction UI)

- **Celo RPC** (default chain)

- **Hypercerts v2** (impact claim primitives—in development)

**Interoperability Standards:**

- **STAC** (SpatioTemporal Asset Catalog—GIS interoperability)

- **IPFS** (distributed storage)

- **GeoJSON** (geospatial data exchange)

- **OpenAPI 3.0** (SDK documentation)

- **ATProto Lexicons** (in development)

**SDK Tech Stack (to be built):**

- **TypeScript** (primary SDK, npm package)

- **Python** (alternate SDK, PyPI package)

- **React** (landing page widget)

- **Viem + Ethers.js** (low-level contract interaction)

**Account Abstraction :**

- **Ithaca/Porto/Alchemy** (passkey-based onboarding, smart accounts)

- **ERC-4337** (account abstraction contracts)

### Collaborations

Hypercerts, Karma, ClimateCoordinationNetwork, GoodDollar, BioFi Project, Regen Network, Regen Coordination, RefiDAO, GreenPill Network, Rifai Sicily, Ma Earth and many more!

Key interoperability examples already established or ripe for SDK:
GoodDollar - working, on-chain daisy chain of conservation basic income
Karma - first metrics tested, streaming tree impact data to grant pages!
RifaiSicily - first use case of adopt-a-tree
BioregionalReforestationCampaigns-9 geographies with 25+ projects involving splits and custom logic 

### Deliverables

**Deliverable: Methodology Configuration SDK**

**Description:** A TypeScript/JavaScript SDK that enables implementing partners to programmatically configure their reforestation goal methodology without Silvi backend access. This transforms methodology configuration from a manual closed process into a permissionless and automated deployment, unlocking Silvi as infrastructure rather than a closed platform.

**Scope Includes:**

- Configuration engine enabling partners to define custom claim stages (seedbed → transplanting → outplanting → monitoring → verified etc)

- Verification rules engine (thresholds, approval workflows, evidence requirements, evaluations)

- Payout schedule configuration (milestone-based percentages, beneficiary splits, recipient addresses)

- Treekipedia integration for ecological optimization (species selection, site suitability, polyculture scoring)

- Integrate into Reforestation Guide and documentaion

**How Verified:**

- On-chain: Partner methodology deployments queryable via smart contract (block explorers show configuration transactions)

- GitHub: SDK repo with partner configuration code examples

- Integration tests: Public test suite demonstrating methodology patterns deployable

- Partner attestation: Written confirmation from partners that SDK enabled their deployment

**Timeline:** December 9, 2025 

---

**Followup roadmap (for context, not deliverable): More Robust Composability and Queury Layer**

**Description:** A combination of smart contracts, IPFS, hypercert, atproto and registries that expose Silvi-configured project metadata and verification states as queryable, composable primitives. This enables external protocols to programmatically discover projects, verify tree impact claims, and build derivative products—transforming tree impact from a closed data silo into composable ReFi infrastructure.

**Scope Includes:**

- Smart contract interfaces for on-chain project discovery (queryable by location, target size, verification status)

- On-chain attestation system exposing verification state without storing evidence (references IPFS/EAS for data)

- Standardized interfaces enabling external protocols to read Silvi verification data

- Integration with EAS for immutable claim verification

- Reforestation primitive lexicon

**Timeline:** Post-December 9, 2025 

### Budget

_Total Amount Requested: $13,000
_
| Category | Amount | Focus | 
|----------|--------|-------| 
| **SDK Development (TypeScript)** | $8,000 | Configuration MVP, verification rules, payout scheduling, Treekipedia integration, type definitions, validation layer, error handling | 
| **Composability and Queury Layer** | $2,000 | Smart contract development, Hypercert primitive, EAS integration, standardized interfaces, Appview, atproto lexicon | 
| **Developer Experience & Documentation** | $3,000 | Reference implementations (at least 1 partner config), interactive documentation, integration guides for external protocols, code examples 

### GTM & Adoption Plan

**Traction from Parallel $100K Campaign Deployment:**

Our go-to-market strategy leverages immediate SDK validation through simultaneously-deploying $100k reforestation campaigns. ACTIVE implementing partners and campaigns being deployed right now—they are not hypothetical future users but active stakeholders, projects and committed capital. The 9 bioregions leveraging our latest stack represent diverse geographies (Brazil, Sicily, Cascadia, Nigeria, Kenya, Uganda, Colombia, Appalachia eot name a few), organization types (NGO, impact startup, community networks, web3 local node,), and restoration models (Atlantic Forest with indigenous communities, Mediterranean cork forests, distributed community green spaces). Each will have entire methodologies  configured via the same system that will become exposed via the SDK during Phase 1, providing real-world validation of UX, error cases, and edge cases. And the deployment data will become the reference implementation for future adopters.

**From Self-Hosting to Protocol Composabilit (for context, not deliverable)**

The query and composability layer will enable our second growth vector: external protocols discovering and integrating with Silvi-configured projects. Rather than organizations "using Silvi," external systems will compose with Silvi primitives. We are already integrated with GoodDollar (conservation basic income) as one of the first integration partners. This will offer as a blueprint for other composable daisy-chain operations and with particular interest in nested queries. For example, integrating with a VCU standards so that carbon credit  can programmatically query "all verified tree data for a given location or biodiversity cobenefit" and automatically cross-reference their evidence. This will allow use to expand from just platform to an infrastructure standard. 

### Additional Links and Resources

[https://silvi.earth/](https://docs.silvi.earth/)
[https://app.silvi.earth/](https://docs.silvi.earth/)
[https://treekipedia.silvi.earth/
https://docs.silvi.earth/](https://docs.silvi.earth/)
<https://x.com/SilviProtocol>
<https://github.com/SilviProtocol>