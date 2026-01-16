# Coco Language

MOI's official programming language for writing and deploying on-chain Logic.

## ✨ What is Coco?

Coco is a **statically typed**, **context-oriented**, and **indentation-based** language designed specifically for MOI's participant-centric execution model.

## 🤔 When do you need Coco?

**You DON'T need Coco for:**
- Creating tokens (use Native Assets via SDK)
- Transferring assets (use SDK operations)
- Basic asset management (mint, burn, approve, revoke)

**You NEED Coco for:**
- Advanced Vaults and lending protocols
- Fee mechanisms and royalties
- Soulbound tokens (MASX custom assets)
- Any custom on-chain behavior beyond native assets

## 📚 Documentation

- **[Official Docs](https://cocolang.dev)** - Complete language reference

## 🚀 Installation

Download the latest release from [GitHub Releases](https://github.com/sarvalabs/coco/releases).

### macOS / Linux / WSL

```bash
# Remove any previous install
rm -rf ~/.coco/bin

# Unpack the archive (run in the directory where you've downloaded it)
mkdir -p ~/.coco/bin
tar -C ~/.coco/bin -xzf coco-0.7.0-macos-arm64.tar.gz  # use your downloaded file

# Add to PATH (in ~/.zshrc or ~/.bashrc)
export PATH="$PATH:$HOME/.coco/bin"

# Apply immediately
source ~/.zshrc  # or source ~/.bashrc

# Verify
coco version
```

### Windows

Use the `CocolangSetup.exe` (x86_64) from Releases, or install manually:
1. Remove any previous install
2. Unpack the archive into `%USERPROFILE%\.coco\bin`
3. Add `%USERPROFILE%\.coco\bin` to PATH

```cmd
coco version
```


## 🛠️ Editor Support

- **VS Code Extension** - [Coco Language Support](https://marketplace.visualstudio.com/items?itemName=sarvalabs.cocolang)

## 📁 Examples

- [Coco Examples Repository](https://github.com/sarvalabs/cocolang-examples)
- [tSwap Tutorial - Soulbound Tokens](../resources/tswap/TUTORIAL.md) - Build soulbound badges with Coco