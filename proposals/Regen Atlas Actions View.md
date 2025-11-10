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

Impact Measurement, Capital Allocation

### Problem Being Solved

_Regen Atlas addresses a core Ethereum UX challenge around discoverability and composability of verified impact data. Today, regenerative projects issue onchain proofs of impact (e.g., Hypercerts, Impact Certificates) across multiple chains and formats, but there is no unified, user-friendly interface to see, query, or build upon these proofs spatially. This fragmentation limits participation, funding coordination, and data reuse in regenerative finance and public goods impact applications. With this grant, we will develop an Actions View: a spatial aggregator of non-transferable onchain impact artifacts, integrated into a map-based UI that lets users visualize and filter actions by location, SDG, and protocol. The result is a measurable UX improvement in discoverability, interoperability, and developer experience for Ethereum-based impact and regenerative projects._

### Team

Pawel is a CTO that ships:

- 10 years coding experience

- Typical tech stack: TypeScript, React, Wagmi/Viem, Node.js

- Worked in 2 start-ups (Ziflow, Talentry)

- Member of dOrg, the decentralized builder collective

- Successfully delivered multiple MVPs – 4 of them from 0 to launch

- https://www.linkedin.com/in/paweljanicki/?originalSubdomain=hk 

Louise is a Researcher/Generalist that knows the intersection of crypto and climate like the back of her hand:

- Published report on blockchain-based MRV: https://www.kolektivo.network/blogs/monitoring-reporting-and-verification-methodologies-in-regenerative-finance

- 3rd prize winner of the 2023 Solana ReFi Hackathon Berlin. ​​https://www.linkedin.com/pulse/refi-hackathon-berlin-sunrisestake/

- Took the Interchain Foundation’s developer academy course in 2023

- https://www.linkedin.com/in/louise-borreani-887278203/?originalSubdomain=de

Pat is a Product/Marketing guy that has been around the block:

- Started Web3 in 2017 with the DAOstack team, an open-source DAO framework

- Co-founded Curve Labs, a Web3 mechanism design and development agency (exited 2024)

- Has produced whitepapers, industry essays, and mechanism design research under ecofrontiers.xyz

- https://www.linkedin.com/in/pat-rawson-48306867/

Finally, Louise and Pat are authors of the Green Crypto Handbook (2025), an upcoming textbook that discusses the Web3 mechanism design necessary to innovate in the natural capital sector: https://cosmic-move-29b.notion.site/The-Green-Crypto-Handbook-10c874bd4c32803e8494eebd005cc303

### Karma GAP Profile

https://gap.karmahq.xyz/project/regen-atlas-/updates

### Github Repo or Organization (If Multiple Repos)

https://github.com/Regen-Atlas

### Project Tech Stack

Existing: 

- Next.js + Mapbox GL (Actions View UI)

- React (TypeScript)

- Supabase (Postgres + Row Level Security)

- Node/Next API routes (data adapters) 

- ethers.js / wagmi + WalletConnect (wallet integration) 

- ENS / DID (identity anchors) 

- Karma GAP Protocol - Orgs panel linkout

- URL Safe (treasury ops) 

Planned / hypothetical:

- EAS (Ethereum Attestation Service) — ingest/display spatial attestations

- Hypercerts (impact attestations + SDK/API)

- The Graph (AtlantisDAO / collaborator subgraphs)

- IPFS / Pinning service (evidence files, metadata CIDs)

- Open Forest Protocol API (restoration monitoring data)

### Collaborations

Regen Atlas collaborates across the regenerative finance (ReFi) and onchain impact ecosystem to create an open, spatially intelligent map of the regenerative web.

Planned collaborations:

Hypercerts – integration of impact attestations and retroactive public goods funding data.

AtlantisDAO – mapping of verified Impact Certificates minted by Impact Miners.

Open Forest Protocol (OFP) – spatial import of verified reforestation and monitoring reports.

ReFi DAO – alignment with local node actions, bounties, and Prosperity Passport credentials.


Existing partnerships:

\- ecoToken: Regen Atlas has partnered with ecoToken to enable the retirement (retiring) of ecological credits (Regen Network green assets) on Celo via the Atlas interface.

\- LandX: We partnered with LandX to list real-world farms producing tokenized assets (xTokens) on the platform.

\- OpenVino: We partnered with OpenVino (a protocol for tokenizing organic wines) to list organic wine tokens and develop a framework for certifying green assets.

\- Celo / Prezenti Grants: Regen Atlas’s prototype V3 was powered by a Prezenti grant (from the Celo ecosystem) — implying support / collaboration with Celo’s public goods / grants teams, such as the Celo Europe Regional DAO.

Together, these partnerships help or will help position Regen Atlas as the spatial aggregation layer for verified regenerative work, interoperable with leading ReFi protocols, impact data standards, and open-source ecosystems.

### Deliverables

D1: Interactive Demo Mock of the Actions View → Accepted when a clickable Mapbox prototype (using sample or cached data from Hypercerts and AtlantisDAO) is deployed on a private demo URL and shown in a short recorded walkthrough. Verification: demo link and video presentation shared with the grant program. 

D2: Post-sprint Partner Integration Plan → Accepted when a short technical brief outlines data schemas, API endpoints, and next-phase implementation steps for live integration of verified actions into Regen Atlas beyond the initial design partner. Verification: PDF submission.

### Budget

Scope to be Delivered by December 9: Development of a lightweight Actions View prototype within the Regen Atlas platform (D1 + D2). This proof-of-concept will display verified regenerative actions (e.g., Hypercerts impact attestations) as a new map layer with clickable metadata and SDG tags. It will include one ingestion script, a Supabase schema extension, a simple Mapbox visualization, and a short public demo video. 

Budget Breakdown: 

- Engineering ($3,000): Build data ingestion script for one live onchain source (Hypercerts) and connect to Regen Atlas database and UI.

- Design & Data Integration ($1,000): Create a minimal Actions Layer visualization in Mapbox with impact icons and SDG color tags.

- Project Management & Documentation ($1,000): Coordinate with data partners, write docs, and produce short demo.

- Hosting & Contingency ($1,000): Cover Supabase instance, domain, testing, and small buffer for schema adjustments.

Risks & Mitigations: If API integrations are delayed, we will use cached or mock JSON data to demonstrate the functionality. The prototype will prioritize a single live integration (e.g. Hypercerts) to ensure delivery within scope and budget.

### GTM & Adoption Plan

Our go-to-market strategy focuses on onboarding early regenerative finance and impact protocol partners (a minimum of three) that already issue verifiable proofs of impact / Actions and can immediately benefit from spatial visualization. The initial data integrators we are evaluating at present include AtlantisDAO (Impact Certificates), Hypercerts/Ecocerts, and Open Forest Protocol. During the prototype phase, we’ll co-develop ingestion adapters and host an open “Actions View Quickstart” guide. 

Each integration comes with active communities. These early adopters effectively become co-contributors, which sets the stage for organic community growth in the next phase. Adoption will be promoted through social media channels, such as LinkedIn, X, Farcaster, Telegram, Discord, and Discord boards.

Post-round, sustainability will come from API access tiers, data partnerships, and co-funded integrations with impact registries and grant protocols/platforms that need spatial verification — ensuring Regen Atlas remains the open, neutral data aggregation layer connecting verified regenerative actions across the Ethereum ecosystem.

### Additional Links and Resources

- Atlas: https://www.regenatlas.xyz/

- Github: https://github.com/Regen-Atlas

- Docs: https://regen-atlas.gitbook.io/regen-atlas-docs

Verifiable action examples:

- Atlantis: https://docs.google.com/document/d/14MDfq8dUTAiZ3FW-8ptorKadUwrjsJAJfJFBg9uVWCw/edit?tab=t.0#heading=h.gnj3wusv9zme

- Ecocerts: https://www.ecocertain.xyz/faqs

- Gainforest: https://gainforest.app/