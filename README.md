# Smart Cult — Infinite Interoperability (PoW)

[![License: Apache 2.0](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)
[![Smart Cult Docs](https://img.shields.io/badge/docs-online-green.svg)](https://smartcult.online/docs)
[![Status](https://img.shields.io/badge/status-beta-yellow.svg)](https://smartcult.online/status)

> **Smart Cult** is the **ultimate crypto interoperability solution**: an omni-master chain ($SMARTCULT) coordinating **Smart-Upgraded Chains (SUCs)**, each secured by **Proof-of-Work**, with immutable **1B token supply caps**.

---

## 🚀 Vision
- **Infinite Interoperability** — seamless swaps between canonical and smart-upgraded assets.
- **Proof-of-Work Security** — every chain (including $SMARTCULT) runs PoW or AuxPoW (merged mining).
- **Immutable Hard Caps** — $SMARTCULT and all SUC tokens fixed at **1,000,000,000** supply.
- **Omni-Master Governance** — bridge registry, canonical assets, route engine, and incentives.

---

## 📖 Documentation
- **Whitepaper (PoW Edition):** [Read Online](https://smartcult.online/whitepaper.html)
- **Status Page:** [Live Status](https://smartcult.online/status.html)
- **Deployment Guide (GUI-only):** [Deploy Docs](https://smartcult.online/deploy.html)

---

## 🛠️ Components
- **$SMARTCULT** — omni-master chain coordinating bridges, incentives, and governance.
- **Smart-Upgraded Chains (SUCs):**
  - Smart DOGE (`sDOGE`)
  - Smart BTC (`sBTC`)
  - Smart ETH (`sETH`)
  - Smart SOL (`sSOL`)
  - Smart AVAX (`sAVAX`)
  - Smart LTC (`sLTC`)

Each SUC has:
- **FixedSupplyToken.sol** (1B hard cap)
- **VestingVault.sol** (linear vesting with cliffs)
- **MerkleAirdrop.sol** (one-time airdrop)

---

## 📦 Repos & Packages
- `smartcult_pow_contracts/` — $SMARTCULT contracts (ERC-20, vesting, airdrop).
- `suc_tokens/` — six SUC token repos (sDOGE, sBTC, sETH, sSOL, sAVAX, sLTC).
- `allocations_pack/` — CSV/JSON templates for genesis allocations.
- `docs_site/` — Cloudflare Pages-ready docs site with whitepaper + status.

---

## 🔒 License
Copyright © 2025 **Fixing Good LLC (EIN 33-3570117)**  
Licensed under the [Apache License 2.0](LICENSE).

---

## 🤝 Contributing
Contributions are welcome! Please:
1. Fork the repo.
2. Create a feature branch (`git checkout -b feature/your-idea`).
3. Commit changes (`git commit -m 'feat: add your idea'`).
4. Open a Pull Request.

Bug reports and feature requests can be submitted via [Issues](../../issues).

---

## 🎃 Roadmap
- **Q4 2025 (Halloween Launch)**:  
  - $SMARTCULT PoW chain live  
  - Smart DOGE EVM PoW with bridges & caps  
  - Whitepaper v1.0 release  

- **2026**:  
  - Smart BTC, ETH, SOL, AVAX, LTC onboarding  
  - Multi-hop atomic swaps  
  - zk-light clients R&D

---

## 🌐 Links
- Website: [smartcult.online](https://smartcult.online)
- Docs: [smartcult.online/docs](https://smartcult.online/docs)
- Status: [smartcult.online/status](https://smartcult.online/status)
