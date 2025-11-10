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

Governance/Coordination, Identity/Reputation

### Problem Being Solved

Ethereum's high gas costs make complex computations economically unviable, creating a fundamental barrier to mass adoption. Operations involving multiple storage reads, calculations, and state updates are prohibitively expensive on mainnet, forcing developers into extensive gas optimization rather than focusing on security and expressiveness. This computational limitation affects critical use cases including privacy protocols requiring heavy cryptographic operations like ZK proof verification, complex computational logic, and on-chain governance systems. 

This computational limitation directly impacts public goods tooling: quadratic funding mechanisms require complex vote tallying, reputation systems need iterative score calculations, impact measurement tools must process large datasets that are on-chain, and capital allocation protocols demand sophisticated multi-stakeholder computations. These operations are often prohibitively expensive or impossible within block gas limits, forcing compromise on decentralization, transparency, or feature richness. 

Layer 2 solutions have fragmented the ecosystem and pushed value away from Ethereum L1. Gas Killer addresses this by making gas-intensive operations dramatically cheaper through off-chain computation and aggregate signature verification, reducing any function with internal reads and calculations above verification cost down to just that verification plus necessary storage writes with only one line of code required for integration. This enables cheaper smart contract transactions and previously impossible applications while keeping computation and value on Ethereum mainnet.

This means at least two very big things. 

1. Smart contract developers do not need to do nearly as much gas optimizations as what is the norm today. Instead of optimizing for gas costs, developers can now optimize for other things like security or expressiveness. This also means we can do calculations on dynamic arrays! 

2. We can now run methods that go beyond the block gas limit. No matter how complex the computation, even if it’s more gas than is technically allowed in a block, Gas Killer can run it. Of course the exact extent of how far this can go needs to be tested but it should be ok if it can be run on a single computer. 

The impact of Gas Killer is easily measurable with the amount of gas that the protocol is able to abstract away thus increasing the computation per gas spent in the EVM.

### Team

- Ron Turetzky - EigenCloud Protocol Advisor - inventor of Gas Killer and experienced EigenCloud protocol developer 

- Joshua Davila - Strategy Lead -  ex-Deloitte and experienced blockchain consultant 

- Bagelface - Lead Engineer - experienced Solidity developer 

- Junkicide - Rust Developer - ex-researcher at Poetic Technologies focused on Rust

### Karma GAP Profile

https://gap.karmahq.xyz/project/gas-killer

### Github Repo or Organization (If Multiple Repos)

https://github.com/BreadchainCoop/gas-killer-router

### Project Tech Stack

- Commonware (Framework for BLS signature aggregation and p2p networking) 

- EigenCloud (Main protocol facilitating Gas Killer) 

- Dune Analytics (Measuring usage) 

- EVM (Can be deployed on any EVM chain)

### Collaborations

MOUs signed with: 
Gardens
YieldNest
Smart Transactions

Other collaborations:
Opacity Network
EigenCloud

### Deliverables

D1: Launch Gas Killer on Ethereum mainnet → Accepted when the Gas Killer AVS is operational on Ethereum mainnet with at least one production integration successfully processing transactions. Verification: deployed contract addresses on Etherscan, live transaction logs demonstrating gas savings, and public announcement of mainnet launch.

### Budget

Amount Requested: $10,000 

- Engineering (Mainnet Deployment & Integration) - $8,000 

  - Mainnet deployment and operator network setup

  - One integration in Production 

  - Full testing in mainnet environment 

- Project Management & Coordination - $2,000 

  - Partner coordination for production integrations 

  - Timeline management and milestone tracking 

  - Community communication and documentation 

- Operational Costs - $1,000 

  - Cloud infrastructure and server costs for operator network 

  - RPC node access and blockchain data services 

Risks & Mitigations: 

- Mainnet deployment delays → Pre-stage all infrastructure on testnet; maintain parallel testnet environment as fallback for demonstration 

- Integration partner availability → Identify 2-3 backup capital allocation protocols willing to test integration 

- Gas price volatility affecting benchmarks → Collect data over multiple time periods and normalize against average gas prices

### GTM & Adoption Plan

Initial Users/Integrators: We're targeting two distinct user segments based on integration readiness: 

Early Adopters: Protocols with signed MOUs demonstrating Gas Killer’s value, self-developed applications exploring new design patterns (e.g., a Safe module for real-time large-scale voting), artists, and early-stage developers integrating Gas Killer from the start. 

Future Pipeline: Established privacy protocols (Railgun) after proven success, governance platforms (Snapshot, Tally), extended use cases like gaming, infrastructure, etc., and novel EVM computation methods. 

Promotion & Onboarding: 

Developer Adoption: 

- Direct outreach to 5-10 early-stage projects in privacy and governance sectors, offering hands-on integration support 

- Build and deploy reference applications demonstrating Gas Killer's capabilities (e.g., gas-efficient quadratic voting dApp, privacy-preserving governance tool) 

- Launch "Ethereum Gas Guzzlers" webpage showcasing high-gas protocols and calculating potential savings with Gas Killer, creating viral awareness and FOMO 

- Publish integration quickstart guide with specific examples 

- Present at privacy/governance-focused events (web3privacy now, Governance Research forums) with gas savings demonstrations 

Node Operator Recruitment: 

- Onboard initial operator cohort from EigenCloud ecosystem, offering attractive early rewards structure 

- Provide operator setup documentation and infrastructure templates 

- Establish operator performance metrics and monitoring dashboards for network health 

- Build reputation system for operators to incentivize quality and uptime 

Post-Round Sustainability: 

- Transition to fee-based model where users pay fraction of gas saved distributed to operator network 

- Pursue security audits to unlock established protocol partnerships and larger market opportunity 

- Build case study portfolio with early adopters and reference applications to attract major projects 

- Scale operator network through self-sustaining economics as integration volume grows 

- Explore additional funding from Ethereum Foundation, privacy-focused organizations, and governance tooling grants

### Additional Links and Resources

Main repos with code and open source licenses: 

https://github.com/BreadchainCoop/gas-killer-node 

https://github.com/BreadchainCoop/gas-killer-router

Intro blog: 

https://paragraph.com/@gaskiller/introducing-gas-killer