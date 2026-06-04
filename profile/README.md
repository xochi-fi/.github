# Xochi (/'SOH-chee'/)

**The Friendly Dark Pool for Crypto**

Xochi is a cross-chain private execution venue anchored on Ethereum. You sign an intent, solvers compete to fill it across six chains (~2s typical, <6s P95), and nothing hits the mempool. A zero-knowledge compliance oracle proves the trade is AML and sanctions-compliant without revealing it. Regulators verify a proof. They never see the trade.

Privacy is free by default. Attestation-verified members unlock stealth settlement, shielded L2 notes, and lower fees.

### How it works

```solidity
Intent signed --> Solvers compete --> ZK compliance proof --> Shielded settlement
  (private)       (~2s fill)           (no data revealed)     (L1 stealth or L2)
```

| Repo                                                                     | What it is                                                |
| ------------------------------------------------------------------------ | --------------------------------------------------------- |
| [xochi](https://github.com/xochi-fi/xochi)                               | Frontend, API, and shared protocol logic                  |
| [ERC-8262](https://github.com/xochi-fi/ERC-8262)                         | ERC reference implementation for the ZK compliance oracle |
| [nahualli](https://github.com/xochi-fi/nahualli)                         | Vanity stealth key grinder for ERC-5564                   |
| [XIPs](https://github.com/xochi-fi/XIPs)                                 | Xochi Improvement Proposals                               |
| [xochi-brand-identity](https://github.com/xochi-fi/xochi-brand-identity) | Brand assets, palette, typography, guidelines             |

### What's live

Riddler (our solver) runs on Ethereum, Optimism, Base, Arbitrum, Tron, and Polygon. Stealth smart accounts with gasless claiming. Attestation-based trust scoring across four categories: humanity, identity, reputation, compliance.

---

[xochi.fi](https://xochi.fi) · [whitepaper](https://xochi.fi/whitepaper) · hello@xochi.fi
