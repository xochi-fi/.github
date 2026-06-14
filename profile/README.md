# Xochi

**The Friendly Dark Pool for Crypto**

Xochi (pronounced /'SOH-chee'/) is a cross-chain private execution venue anchored on Ethereum. You sign an intent, solvers compete to fill it across six chains in about two seconds, and nothing hits the mempool.

For compliance, a zero-knowledge oracle (ERC-8262) proves the trade is AML and sanctions-clean. Regulators verify the proof. They don't see the trade.

Privacy is the default. Members who complete attestation get stealth settlement on L1, shielded notes on L2, and lower fees.

### How it works

```solidity
Intent signed --> Solvers compete --> ZK compliance proof --> Shielded settlement
  (private)       (~2s fill)           (no data revealed)     (L1 stealth or L2)
```

### Open source

| Repo                                                                     | What it is                                                       |
| ------------------------------------------------------------------------ | ---------------------------------------------------------------- |
| [ERC-8262](https://github.com/xochi-fi/ERC-8262)                         | ERC-8262 ZK Compliance Oracle reference implementation           |
| [xochi-sdk](https://github.com/xochi-fi/xochi-sdk)                       | SDK for generating and verifying ERC-8262 proofs                 |
| [pxe-bridge](https://github.com/xochi-fi/pxe-bridge)                     | JSON-RPC bridge from EVM solvers to Aztec shielded settlement    |
| [nahualli](https://github.com/xochi-fi/nahualli)                         | Vanity stealth key grinder for ERC-5564                          |
| [XIPs](https://github.com/xochi-fi/XIPs)                                 | Xochi Improvement Proposals                                      |
| [xochi-brand-identity](https://github.com/xochi-fi/xochi-brand-identity) | Brand assets, palette, typography, guidelines                    |

### What's live

Riddler, our solver, runs on Ethereum, Optimism, Base, Arbitrum, Tron, and Polygon. Stealth smart accounts ship with gasless claiming. Attestations cover four trust categories: humanity, identity, reputation, compliance.

---

[xochi.fi](https://xochi.fi) · [whitepaper](https://xochi.fi/whitepaper) · hello@xochi.fi
