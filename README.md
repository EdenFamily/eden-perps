# Eden Perps

**From launch to leverage.** Perpetual markets for the memes that earn them on [Eden](https://edenfamily.xyz).

Most launchpads stop at graduation. A token fills its curve, gets a pool, and then has to find its own way. Eden takes it one step further: tokens that keep trading after graduation build toward their own perpetual market, funded by their own volume.

```
launch ──▶ bonding curve ──▶ graduation ──▶ locked Uniswap v4 pool ──▶ perps fund fills ──▶ perpetual market
         (fair price discovery)            (liquidity locked forever)   (from every trade)    (long and short, with leverage)
```

## How it works

**1. Every trade funds its own listing.**
Eden's share of each token's fees goes toward its perps listing. When the creator claims their fees, Eden's share drops by the same portion. Any token can still list.

**2. Listings are earned.**
Graduated tokens with real, sustained volume are the ones we take to our perps partner. No insiders picking winners.

**3. Everything is verifiable.**
Each fund is calculated from on-chain fee events on Elysium. Anyone can recompute a token's fund from the chain and check it against what Eden shows.

**4. Built for the Hyperliquid ecosystem.**
Eden runs on Elysium, the Arbitrum Orbit chain over HyperEVM, with HYPE as the native currency. Perpetual markets are where Hyperliquid's traders already live; Eden Perps connects memes born on Elysium to them.

## Why it matters

- **For traders:** the memes with real communities get the instrument serious traders want: long and short, with leverage.
- **For creators:** a reason to build past graduation. A token that keeps its market alive earns a perps listing.
- **For holders:** deeper markets and a clear, public milestone everyone can watch fill up.

## Status

Eden Perps is **in development**. Nothing in this repository is deployed yet, and no perps market is live. The Perps section on [edenfamily.xyz](https://edenfamily.xyz/docs#perps) is marked "Soon".

What is live today is the launchpad underneath it: launches, the bonding curve, graduation into locked Uniswap v4 pools, creator fees and referrals on Elysium mainnet.

## Roadmap

- [x] Eden launchpad live on Elysium mainnet: curve, graduation, locked liquidity, creator fees
- [x] Public API, docs and ABIs for builders
- [ ] Per-token perps fund shown on every token page, computed from on-chain fee events
- [ ] Published listing rules: eligibility, volume thresholds, fund targets
- [ ] Market parameters: leverage limits, oracle design, risk limits
- [ ] First listings with our perps partner

Rules and parameters will be published here before anything goes live, so traders can read them first.

## Build with Eden

- [eden-contracts](https://github.com/EdenFamily/eden-contracts): the launchpad contracts on Elysium mainnet
- [eden-docs](https://github.com/EdenFamily/eden-docs): how Eden works, the API, ABIs and events
- [eden-sdk](https://github.com/EdenFamily/eden-sdk) and [eden-sdk-python](https://github.com/EdenFamily/eden-sdk-python): trade and launch from code
- [eden-skills](https://github.com/EdenFamily/eden-skills): skills that let AI agents trade and launch on Eden

## Follow along

- App and docs: [edenfamily.xyz](https://edenfamily.xyz)
- X: [@EdenOnElysium](https://x.com/EdenOnElysium)
- Partnerships: support@edenfamily.xyz

## Security

Report vulnerabilities privately to support@edenfamily.xyz. Please do not open a public issue for a security report.

## License

MIT
