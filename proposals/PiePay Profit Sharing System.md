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

Governance/Coordination, Capital Allocation

### Problem Being Solved

Small teams struggle to fairly track diverse contributions (time, capital, IP) and distribute profits transparently without manual spreadsheets or centralized intermediaries. Teams need an automated, transparent profit-sharing system that gives more control to payroll managers and payroll recipients to find pay structures that work for their needs.

### Team

Product/Dev Lead - UI369
UX/QA Advisor - Jord

### Karma GAP Profile

https://gap.karmahq.xyz/project/piepay

### Github Repo or Organization (If Multiple Repos)

https://github.com/DAOmasons/piepay-contracts

### Project Tech Stack

PiePay Tech Stack

Smart Contracts Layer

Framework & Language:

- Solidity ^0.8.24: Core contract language

Contract Architecture:

- PiePay.sol (1,144 lines): Main contract managing contributions, units, and payouts

- PiePayFactory.sol: Factory pattern for deploying isolated project instances

Deployment:

- Network: Arbitrum Sepolia (testnet, Chain ID: 421614)

- L2 Choice: Arbitrum for \~10-100x cheaper gas vs Ethereum mainnet

- Current Factory Address: 0x84C150b835Df72aD8Fc0FB5286c25e8dC5357F19

- Verification: Contracts verified on Arbiscan

- Permissions: Compatible with Hats Protocol for composable permissioning 

---

Indexer Layer

Technology:

- Envio: Hosted blockchain indexer service

- GraphQL API: Query interface for indexed blockchain data

- PostgreSQL: Database (managed by Envio infrastructure)

- TypeScript: Event handler logic

Architecture:

- Event-Driven: Listens to smart contract events emitted on-chain

- Schema Definition: schema.graphql defines entities (Project, Contribution, PayoutConfig, etc.)

- Event Handlers: EventHandlers.ts processes events and updates database

- Config: config.yaml specifies which contracts/events to index

Endpoints:

- HTTP: https://indexer.dev.hyperindex.xyz/af0f4dd/v1/graphql

- WebSocket: wss://indexer.dev.hyperindex.xyz/af0f4dd/v1/graphql

Key Indexed Entities:

- Projects, Contributors, Contributions, Payouts, Unit Conversions, PayoutConfigs

---

Frontend Layer:

Framework & Libraries:

- React 18: UI framework

- TypeScript: Type-safe development

- Create React App: Build tooling (for piepay-user)

- Vite: Alternative build tool (for piepay-frontend)

UI Components:

- 

Web3 Integration:

- Viem: Ethereum library (underlying wagmi)

Data Layer:

- @tanstack/react-query: Async state management and caching

- GraphQL Client: Query indexed data from Envio

---

Development & Deployment

Version Control:

- Git: Source control

Environment Management:

- .env files for contract addresses, RPC URLs, API keys

- Separate configs for testnet/mainnet

Testing:

- Foundry Tests: Smart contract unit tests (PiePay.t.sol)

- Mock Contracts: MockUSDC.sol for testing payments

---

Blockchain Infrastructure:

- Arbitrum Sepolia RPC: https://sepolia-rollup.arbitrum.io/rpc

- Alternative RPCs: Alchemy, Infura for reliability

Hosted Services:

- Envio: Indexer hosting (no self-hosting required)

- Arbiscan: Block explorer and contract verification

Local Development:

- Node.js 18+

- npm package manager

- Foundry toolchain

- MetaMask or compatible wallet with testnet ETH

- Compatible with Hats Protocol for permissioning

---

Key Design Decisions

1. L2 Deployment: Arbitrum chosen for gas efficiency while maintaining EVM compatibility

2. Hosted Indexer: Envio eliminates need for self-hosted infrastructure (vs The Graph subgraphs)

3. Factory Pattern: Each project gets isolated contract instance for security/flexibility

4. GraphQL over RPC: Faster queries, better DX, reduced RPC load

5. React Hooks Abstraction: usePiePayContract hides blockchain complexity from UI developers

6. Mantine UI: Comprehensive component library reduces custom CSS needs

7. RainbowKit: Battle-tested wallet connection vs custom implementation

This stack prioritizes developer experience (TypeScript, React hooks, GraphQL) while maintaining transparency (on-chain execution, indexed events).

### Collaborations

none

### Deliverables

D1: Add ability for Payroll Manager to upload contributions manually for whitelisted users both serially and by uploading a .csv file

D2: Complete QA & Bug sweep including all transactions to the indexer for real-time GUI updates. Ensure GUI always represents onchain state in near real-time. 

D3: Begin specification design on external contract managers for Payroll Admin and Project Lead - potentially enabling multi-sig or automated management of these roles by external systems rather than only EOAs.

### Budget

Amount Requested: $5000
- QA: $1000
- Contribution Uploads: $2000
- Bug Fixes & Wiring: $1500
- Contract Specifications: $500

### GTM & Adoption Plan

Initial Users/Integrators

Primary Target: Small Web3-native teams (5-20 members) already comfortable with wallets/transactions

- Grant-funded projects: Gitcoin grantees, Optimism RetroPGF recipients, ecosystem grant teams

- DAO working groups: SubDAOs, guilds, committees needing internal payroll

- Open-source collectives: Developer teams building public goods (Protocol Guild model)

- Freelance Web3 teams: Design studios, development shops, security auditors



Phase 1: Proof of Concept (Current - 3 months)

- Deploy 2-5 pilot projects with teams from DAOMasons network

- Document case studies: "How \[Team\] distributed $50K in 3 clicks"

- Potential internal re-brand of P/D/C Unit model based on user feedback

Onboarding Tactics:

- Testnet playground: Sandbox mode with mock USDC for risk-free exploration

- Whiteglove setup, teaching and admin service

Phase 2: Community-Led Growth (Months 4-12)

- Educational content: Blog posts, Twitter threads explaining P/D/C unit models (or rebrand)

- Focus: User feedback -> Feature improvement flywheel

### Additional Links and Resources

Project Demo & usage overview: https://piepay-user.vercel.app/help

Contracts: https://github.com/DAOmasons/piepay-contracts

UI: https://github.com/DAOmasons/piepay-user

Indexer: https://github.com/DAOmasons/piepay-indexer