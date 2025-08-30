# Cryptohost Bridged USD (CUSD) — Public Source of Truth

**Website:** https://www.cryptohostbridgedusd.io  
**Whitepaper (PDF):** https://www.cryptohostbridgedusd.io/assets/CUSD_Whitepaper.pdf  
**Logo PNG (transparent):** https://www.cryptohostbridgedusd.io/assets/CUSD.png  
**Logo SVG:** https://www.cryptohostbridgedusd.io/assets/CUSD.svg

This repository centralizes **contracts, assets, docs, and verification links** for exchanges, explorers, wallets, and data aggregators.

---

## Contracts (18 decimals)

| Chain      | Address                                                                 | Explorer                                                                 |
|----------- |-------------------------------------------------------------------------|---------------------------------------------------------------------------|
| Ethereum   | `0x54fdc17E702DC85E33C5aeCFaE57c76cECf23C4c`                           | https://etherscan.io/token/0x54fdc17E702DC85E33C5aeCFaE57c76cECf23C4c    |
| BSC (curr) | `0x7f32650c35Cf5a90447B922932b09262626a1346`                           | https://bscscan.com/token/0x7f32650c35cf5a90447b922932b09262626a1346     |
| BSC (v1)   | `0x6665B556A5e46A314d45334368fD56A65A5979FA`                           | https://bscscan.com/address/0x6665B556A5e46A314d45334368fD56A65A5979FA   |
| Arbitrum   | `0x82656b01211ed760f3ca7f597b05928cd72c1971`                           | https://arbiscan.io/address/0x82656b01211ed760f3ca7f597b05928cd72c1971   |
| Optimism   | `0x82656b01211ed760f3ca7f597b05928cd72c1971`                           | https://optimistic.etherscan.io/ (search by address)                      |

> Explorer references: ETH token page, BSC token page, BSC v1 address page are live. :contentReference[oaicite:0]{index=0}

---

## Machine-readable metadata

- Token List (Uniswap spec): [`/data/tokenlist.json`](./data/tokenlist.json)  
- Price feed (informational): [`/data/price-feed.json`](./data/price-feed.json)  
- Contracts JSON: [`/data/contracts.json`](./data/contracts.json)

> **Note:** Aggregators (CMC/CG) **do not** use project-hosted price feeds for pricing. They derive price from **tracked exchange pairs** with real liquidity/volume.

---

## Official links
- Website: https://www.cryptohostbridgedusd.io
- Whitepaper: https://www.cryptohostbridgedusd.io/assets/CUSD_Whitepaper.pdf
- Twitter (X): https://twitter.com/NenzyBrown
- Telegram: https://t.me/NenzyBrown
- GitHub (website repo): https://github.com/Nenzy10/cryptohostbridgedusd.io

---

## For reviewers
- See **`docs/press-kit.md`** for a one-pager (logos, contracts, explorers).  
- See **`docs/listings.md`** for CMC/CG submission details and pair URLs once live.  
- See **`docs/verification-post-template.md`** for the public verification tweet.

## Security & risks
See [`SECURITY.md`](./SECURITY.md) and [`DISCLAIMER.md`](./DISCLAIMER.md).
