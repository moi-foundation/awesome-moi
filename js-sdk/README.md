# JS-MOI-SDK

A comprehensive JavaScript/TypeScript library for seamless interaction with the MOI Protocol and its ecosystem.

## ✨ What it does

- **Interaction Management** - Create, sign, and send interactions on the MOI network
- **Account Operations** - Retrieve balances, access interaction histories
- **Logic Object Handling** - Deploy, interact with, and query logic objects
- **Native Asset Support** - Work with MAS0, MAS1, MAS2 asset standards
- **Utility Functions** - Comprehensive toolset for MOI development

## 📚 Documentation

- **[Official Docs](https://js-moi-sdk.docs.moi.technology)** - Complete API reference
- **[MOI Docs - JS SDK](https://docs.moi.technology/docs/build/packages/js-moi-sdk/)** - Getting started guide

## 🚀 Installation

```bash
npm install js-moi-sdk
```

## 💡 Quick Example

```javascript
import { JsonRpcProvider } from "js-moi-sdk";

const provider = new JsonRpcProvider("https://voyage-rpc.moi.technology/babylon/v0");
const address = "0x...";
const tesseract = await provider.getTesseract(address, true);
console.log(tesseract);
```

## 📖 Guides

- [Connecting to Devnet](https://js-moi-sdk.docs.moi.technology/providers) - Provider setup and RPC connections
- [Account Management](https://js-moi-sdk.docs.moi.technology/interactions#account-management) - Managing accounts and wallets
- [Asset Management](https://js-moi-sdk.docs.moi.technology/interactions#asset-management) - AssetFactory, AssetDriver, MAS0, MAS1, MAS2
- [Logic Management](https://js-moi-sdk.docs.moi.technology/interactions#logic-management) - Deploying and interacting with logic

## 🛠️ Related Libraries

- **[js-polo](https://github.com/sarvalabs/js-polo)** - POLO encoding/decoding for MOI

## 📁 Examples

- [JavaScript Examples](https://github.com/sarvalabs/js-moi-examples) - Code samples and tutorials
- [Submit Interaction Tutorial](https://docs.moi.technology/docs/build/tutorials/submit-ixn/) - Step-by-step guide
