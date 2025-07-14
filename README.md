# 🌱 ESG Decarbonization NFT Minter

A simple HTML + JavaScript frontend for minting decarbonization projects as NFTs on-chain.  
Users can register their project name, description, location, and an image — all bundled into metadata and minted to the blockchain.

---

## 📦 Features

- 🦊 Connect MetaMask (via `ethers.js`)
- 📝 Input form: project name, description, location
- 🖼 Upload project image (used in NFT metadata)
- 🔗 Generate metadata JSON on the fly
- 🪙 Call `mintNFT(address, tokenURI)` in an ERC-721 contract
- ✅ Display transaction hash and metadata link

---

## 🚀 Getting Started

### 1. Clone and serve

```bash
git clone https://github.com/persikida/esg-nft-minter.git
cd esg-nft-minter
serve .