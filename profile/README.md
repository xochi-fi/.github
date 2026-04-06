# Xochi

**Private execution for Ethereum.**

Xochi is a dark pool where trades settle without broadcasting your business to every MEV bot on the network. You sign an intent, solvers compete to fill it, and settlement lands in under 3 seconds. A zero-knowledge proof confirms compliance. The regulator verifies the proof -- they never see the trade.

Privacy is free at the base tier. Verified users unlock stealth smart accounts, shielded settlement, and better rates. The protocol is cash-positive on every transaction.

### How it works

```
Intent signed --> Solvers compete --> ZK compliance proof --> Shielded settlement
  (private)       (~2s fill)           (no data revealed)     (L1 stealth or L2)
```

### Repos

| Repo | What it is |
|------|------------|
| [xochi](https://github.com/xochi-fi/xochi) | Frontend, API, and shared protocol logic |
| [erc-xochi-zkp](https://github.com/xochi-fi/erc-xochi-zkp) | ERC draft + reference implementation for the ZK compliance oracle |
| [XIPs](https://github.com/xochi-fi/XIPs) | Xochi Improvement Proposals |
| [xochi-brand-identity](https://github.com/xochi-fi/xochi-brand-identity) | Brand assets, palette, typography, guidelines |

### What's live

Riddler (our solver) runs on Ethereum, Optimism, Base, Arbitrum, and Polygon. Stealth smart accounts with gasless claiming. Trust scoring across 20+ attestation providers. Bare-metal infrastructure we've operated since 2021.

### Team

Built by alumni of Blockdaemon, Lido, Deloitte, General Dynamics, the U.S. DOJ, and the FBI. DeFi engineering meets federal compliance -- because compliant privacy requires people who build cryptography and people who understand how governments break it.

---

[xochi.fi](https://xochi.fi) · [whitepaper](https://xochi.fi/whitepaper) · hello@xochi.fi
