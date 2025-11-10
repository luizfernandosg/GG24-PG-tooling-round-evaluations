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

Identity/Reputation, Governance/Coordination, Capital Allocation, Capital Formation

### Problem Being Solved

The primary challenge facing decentralized public goods is the loss of digital sovereignty due to reliance on centralized infrastructure. PGF coordination and history are tethered to centralized services (AWS, Discord), creating a single point of failure for censorship and data loss, which undermines the community's trust and resilience. Furthermore, the ecosystem lacks a unified, resilient, and user-controlled on-chain identity and reputation layer that is portable and immutable. 

Hup solves this by building a sovereign social data layer while resolving a critical governance UX pain point: the threat of voter coercion. 

We eliminate this by integrating Zero-Knowledge Proof (ZKP) tooling into community polls, ensuring all sensitive signaling is conducted with cryptographic privacy, thereby fostering honest, autonomous coordination.

### Team

 **_Amir Rahimi,_ Full-stack web3 developer**

🟡**Expertise:** 14+ years of professional software engineering experience (MS in Computer Science), with deep domain knowledge in large-scale data systems (Big Data, NLP, POS) that informs the robust architecture of Hup.

🟢 **Experience:** Highly active builder in the Ethereum ecosystem for 3 years, demonstrating rapid building capacity by participating in nearly 30 hackathons. Directly responsible for designing and deploying the core Hup Protocol (immutable social data layer) and the complex Zero-Knowledge Proof (ZKP) tooling for anonymous on-chain voting. Your commitment to hands-on building ensures the Public Goods tooling is delivered efficiently.

**Kevin Germin, Community Strategy & Project Manager (PM)**

🟡**Expertise**: Web3 Strategist and Builder (since 2020) with a strong foundation as a former Automotive Cyber Security Consultant and Project Manager at Accenture. Combines corporate project management rigor and regulatory knowledge with a specialization in efficiency optimization and community strategy.

🟢 **Experience**: Ensures the Hup roadmap is executed efficiently, directly applying methodologies proven to streamline operational processes. His role is critical for the success of the Community Layer (Month 2/3 deliverables), guaranteeing that the new tooling is interoperable and strategically positioned for adoption by diverse public goods communities and decentralized organizations.

### Karma GAP Profile

https://gap.karmahq.xyz/project/hup

### Github Repo or Organization (If Multiple Repos)

https://github.com/web3senior/hupsocial

### Project Tech Stack

Solidity

Next.js(React)

WalletConnect

IPFS

Zero-Knowledge Proofs (ZKP)

HNS (Hup Naming Service "username.hup")

Hats Protocol

Human Passport

### Collaborations

LUKSO, CELO

### Deliverables

**Milestones: Core Immutable Social Layer & Identity Breakdown** 

## 1.1: Core Smart Contract Backbone 

The first step focuses on establishing the essential, immutable ledger for all user activity. We will finalize, deploy, and verify the core smart contracts responsible for Posting, Commenting, and Liking content on the Testnet. This is the foundation that ensures all social data is permanently stored and verified on-chain. Verification for this sub-milestone will be achieved by providing the Verified Contract Addresses on the Testnet block explorer, along with the corresponding GitHub Repository link showing the completed and verified contract code.

## 1.2: Immutable Content Editor & IPFS Integration 

Following the contract deployment, we will integrate the front-end tooling. This involves making the editor fully functional and ensuring the system can reliably handle and process media, specifically images. Crucially, all content and metadata must be securely pushed to IPFS before the immutable hash is written to the blockchain. Verification will be a live Testnet URL demonstrating a successful post containing an image, with a clear log output showing the verifiable IPFS CID (Content Identifier) used to secure the data.

## 

## 1.3: Following system & On-chain Profile Implementation 

This sub-milestone delivers the core identity and social graph tooling. The Following System must be fully operational, allowing users to build a verifiable social graph. Concurrently, the Profile Bridge (Gravatar-like) will be integrated to successfully fetch and render essential user profile metadata. Acceptance requires demonstrating a user successfully following another user and seeing the profile images rendered correctly in the UI via the bridge on the Live Testnet URL.

## 1.4: Creator Tipping Finalization & Release 

The final step of Milestone 1 focuses on completing the initial capital allocation features. The Content Creator Tipping functionality must be fully deployed and successfully executed on the Testnet, demonstrating a seamless flow of value to creators. Upon successful completion of the tipping logic, the entire Milestone 1 code base will be tagged, released, and published on GitHub. Verification is achieved by presenting a Live Testnet URL showing an executed tip transaction on a post, and providing the GitHub Release Tag for "Milestone 1: Core Social Layer" with final documentation.

### Budget

_Amount Requested: $8,000_

  - _Design(UI/UX) $2,000_

  - _Engineering $3,000_

  - _Smart contract development & audit $2,000_

  - _Project Management & Docs $1,000_

### GTM & Adoption Plan

The success of our adoption plan hinges entirely on the successful completion of Milestone 1: Core Immutable Social Layer & Identity. This initial phase delivers the core social functionality (posting, commenting, liking) necessary to attract early users and provide immediate value. Crucially, Milestone 1 integrates the foundation for sovereign identity via the on-chain Following system, ensuring users can establish a portable, recognizable presence—a non-negotiable requirement for social adoption. Furthermore, the Content Creator Tipping feature provides the first financial incentive on Hup, immediately rewarding early content creation and validating the platform's economic model for creators and public goods advocates, making it a compelling alternative to centralized, ad-supported platforms. 

After completing Milestone 1, our go-to-market strategy is focused on providing highly resilient coordination infrastructure to specialized decentralized groups that suffer most from centralized platform risk and governance coercion.

Our initial users and integrators will be the targeted Public Goods communities identified in our roadmap. We will specifically onboard Decentralized Space Startups, Genome Researcher communities, and Self-Sovereign Agricultural Cooperatives. These groups require both immutable data history for their collaboration (Hup's core feature) and uncoerced private voting (ZKP). Our Modular Community Coordination Engine is designed as a drop-in tool for them to organize and govern. To promote and onboard adoption, we will implement a two-pronged strategy. First, we will engage in direct outreach to these specialized groups, offering hands-on technical support to migrate their historical coordination data onto Hup's immutable ledger. Second, we will publish a comprehensive Community Tooling SDK and Quickstart Documentation, making it trivial for any DAO or PGF organization to integrate Hup's private polling and treasury features into their existing web presence. We will leverage our success in the Gitcoin Privacy Round to promote the ZKP voting tooling as a gold standard for governance.

### Additional Links and Resources

- _GitHub Repo:_ <https://github.com/web3senior/hupsocial>

- _Nightly Repo: <https://github.com/web3senior/nightly>_

- _HNS Hup Naming Service Repo: <https://github.com/web3senior/dropid-contract>_

- _Demo:_ [https://www.hup.social](https://www.hup.social/)