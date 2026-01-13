# Awesome MOI

> **The curated resource hub for building the next generation of decentralized applications on the MOI L1 blockchain.**

This repository is your essential narrative tool and instructional guide for transitioning from the limitations of legacy, app-centric networks to MOI's powerful **Participant-Centric** model.

## 🌟 Introduction

Traditional blockchain development forces applications into a single global state, sacrificing scale and security. MOI fundamentally shifts this paradigm by giving every participant their own independent chain and enabling parallel, context-aware interactions.

## 📚 Table of Contents

### [0. Essentials](./essentials/)
Source of Truth Resources: Krama paper, Whitepaper, Yellow Paper, Mainnet and Testnet links and Statuses. Community: Discord, Forum, X, Telegram links.

### [1. COCO Language](./coco-language/)
- Compilers & Toolchains: Links to the COCO compiler and version manager
- Editor Support: VS Code extensions, syntax highlighters, snippets
- Language Tutorials: From "Hello World" to advanced syntax guides
- Standard Library: Standard lib for math, strings, etc.

### [2. Client Libraries](./client-libraries/)
- **JavaScript**: "js-moi-sdk" specific examples (e.g., "Signing a Transaction", "Listening to the Provider")
- **Go/Python/Rust**: Placeholders for future SDKs
- **Utilities**: Standalone libraries for MOI-specific encoding/hashing (if separate from the main SDK) such as js-polo

### [3. Developer Tools](./developer-tools/)
- Voyage RPC: Configuration guides, Postman collections for RPC testing
- CLI Tools: Tools for account generation, manifest creation, and deploy logic
- Localnet/Devnet: Docker images or scripts to spin up a local MOI node for testing
- Explorers: Links to the official explorer and community-built viewers

### [4. Logic (Pisa)](./logic/)
- **Basics**: Simple logic (Counters, Hello World)
- **Asset Management (MAS)**:
  - Fungible Tokens: Implementing standard token logic in COCO
  - Non-Fungible Assets: Unique asset logic
  - RWA and Other assets
- **Context & Governance (The "MOI Special")**:
  - Context-Aware Logic: Examples showing logic that behaves differently based on who is calling it or the context of the interaction
  - Policy Enforcement: Logic that enforces compliance (e.g., "Department-specific rules")
  - Example: "Voting App: Solidity Style (Global Count) vs. MOI Style (Participant Local Votes aggregated)"
- **Participant Storage**: Examples showing how to read/write data to a participant's local chain state (vs. global state)

### [5. Solved Patterns](./solved-patterns/)
Code examples demonstrating architectural fixes to historic blockchain problems:
- The Re-Entrancy Fix (The DAO Hack)
- The Scalability Fix (The CryptoKitties Incident)
- The Compliance Fix (The Tornado Cash Dilemma)

### [6. Current Web3 Reimagined](./web3-reimagined/)
Serves as the public demo, showing successful implementations of popular Web3 use cases rebuilt on MOI:
- Decentralized Exchange (DEX): Uniswap, Curve
- NFT Marketplace: Opensea
- Decentralized Identity (DID): ENS, Galxe
- Stablecoins: USDT(Tether), DAI

### [7. DApp Patterns](./dapp-patterns/)
Full-stack examples (COCO Logic + JS Frontend):
- Identity & Auth: Using MOI for decentralized identity
- DeFi / Finance: Simple swap or custodial logic
- Social / Chat: DApps that leverage "Hyper-Local Finality" for fast interaction
- Governance, Agentic AI and more

### [8. Nodes & Infrastructure](./nodes-infrastructure/)
- Node Setup: Guides for running a Guardian or Validator node
- Monitoring: Grafana dashboards, Prometheus exporters for node health

## 🚀 Quick Start

1. **New to MOI?** Start with [Essentials](./essentials/) for foundational resources
2. **Want to code?** Check out [COCO Language](./coco-language/) tutorials
3. **Building a dApp?** Explore [DApp Patterns](./dapp-patterns/) for full-stack examples
4. **Understanding MOI's advantages?** See [Solved Patterns](./solved-patterns/) for architectural solutions

## 📖 Resources

### Learning Paths
- **[MOI Sprint](./resources/moi-sprint/)** - Starting point for developers to learn how to build on MOI's contextual compute network
- **[tSwap Tutorial](./resources/tswap/TUTORIAL.md)** - Your first DiApp on MOI

### Documentation
- [MOI Documentation](https://docs.moi.technology)
- [JS-MOI-SDK Docs](https://js-moi-sdk.docs.moi.technology)
- [Coco Language Docs](https://cocolang.dev)

### Tools
- [Voyage Explorer](https://voyage.moi.technology) - Block explorer and wallet

## 🤝 Contributing

We welcome contributions! This is a curated resource hub, and your additions help the entire MOI developer community.

1. Fork the repository
2. Create a feature branch
3. Add your resource/tutorial/example
4. Submit a pull request

Please ensure your contributions:
- Follow the existing structure
- Include clear documentation
- Provide working examples where applicable
- Link to official resources when possible

## 💬 Community

- [Discord](https://discord.gg/GkP7mDw5)
- [GitHub Discussions](https://github.com/moi-foundation/awesome-moi/discussions)
- [Forum](https://forum.moi.technology) - [Link TBD]
- [X (Twitter)](https://x.com/moi_technology) - [Link TBD]
- [Telegram](https://t.me/moi_technology) - [Link TBD]

## 📄 License

MIT License - see [LICENSE](./LICENSE) file for details.

---

**Built with ❤️ by the MOI Foundation**
