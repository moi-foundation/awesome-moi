# Logic (Pisa)

Examples and tutorials for writing smart contract logic in COCO on MOI.

## 🎯 Basics

Simple logic examples to get started:

- **Counters** - [Link TBD]
- **Hello World** - [Link TBD]
- **Basic State Management** - [Link TBD]

## 💰 Asset Management (MAS)

### Fungible Tokens
- Implementing standard token logic in COCO
- Token transfers and balances
- Token minting and burning
- [Examples](./asset-management/fungible-tokens/)

### Non-Fungible Assets
- Unique asset logic
- NFT creation and ownership
- Metadata management
- [Examples](./asset-management/nft-assets/)

### RWA and Other Assets
- Real-World Asset tokenization
- Custom asset types
- [Examples](./asset-management/rwa-assets/)

## 🌐 Context & Governance (The "MOI Special")

### Context-Aware Logic
Examples showing logic that behaves differently based on:
- Who is calling it
- The context of the interaction
- Participant-specific rules
- [Examples](./context-governance/context-aware-logic/)

### Policy Enforcement
Logic that enforces compliance:
- Department-specific rules
- Role-based access control
- Governance policies
- [Examples](./context-governance/policy-enforcement/)

### Example: Voting App
- **Solidity Style (Global Count)** - Traditional blockchain voting
- **MOI Style (Participant Local Votes aggregated)** - MOI's participant-centric approach

## 💾 Participant Storage

Examples showing how to read/write data to a participant's local chain state:

- Reading participant state
- Writing to participant storage
- State queries and updates
- [Examples](./participant-storage/)

## 📁 Subdirectories

- [Basics](./basics/)
- [Asset Management](./asset-management/)
- [Context & Governance](./context-governance/)
- [Participant Storage](./participant-storage/)
