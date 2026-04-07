# Xochi

**ETH's Friendly Dark Pool**

Xochi is a private execution venue for Ethereum. You sign an intent, solvers compete to fill it, and nothing hits the mempool. Settlement lands in under 3 seconds. A zero-knowledge compliance oracle proves all parties are clean without revealing the trade itself. Regulators verify a proof. They never see the data.

Privacy is free at the base tier. Verified users unlock stealth smart accounts, shielded settlement, and better rates. The protocol is cash-positive on every transaction.

### How it works

```
Intent signed --> Solvers compete --> ZK compliance proof --> Shielded settlement
  (private)       (~2s fill)           (no data revealed)     (L1 stealth or L2)
```

### Repos

| Repo                                                                     | What it is                                                          |
| ------------------------------------------------------------------------ | ------------------------------------------------------------------- |
| [xochi](https://github.com/xochi-fi/xochi)                               | Frontend, API, and shared protocol logic                            |
| [erc-xochi-zkp](https://github.com/xochi-fi/erc-xochi-zkp)               | ERC draft and reference implementation for the ZK compliance oracle |
| [nahualli](https://github.com/xochi-fi/nahualli)                         | Vanity stealth key grinder for ERC-5564                             |
| [XIPs](https://github.com/xochi-fi/XIPs)                                 | Xochi Improvement Proposals                                         |
| [xochi-brand-identity](https://github.com/xochi-fi/xochi-brand-identity) | Brand assets, palette, typography, guidelines                       |

### What's live

Riddler (our solver) runs on Ethereum, Optimism, Base, Arbitrum, and Polygon. Stealth smart accounts with gasless claiming. Attestation-based trust scoring across four categories: humanity, identity, reputation, compliance. Bare-metal infrastructure we've operated since 2021.

---

[xochi.fi](https://xochi.fi) · [whitepaper](https://xochi.fi/whitepaper) · hello@xochi.fi
