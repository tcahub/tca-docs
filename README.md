# TCA — Trading Cards Assets

> Draft parameters · subject to the formal release · not financial advice

**Make TCG more fun.**

**Positioning.** The on-chain asset-tokenization and themed-issuance platform for graded physical cards.

**What TCA is.** TCA is a launchpad that brings graded physical cards on-chain: each card theme becomes one slot, and each slot issues one token.

Pledge graded cards to earn issuance rights. The card-pledge hard cap is about **$1,000**, first come, first served. The token-sale soft cap is about **$100,000**. When the soft cap fills, the token launches and can trade. Every fee flows back through four buckets: Treasury, Platform, Staker share, and Buyback & burn.

- Site: [https://tcahub.xyz/](https://tcahub.xyz/)
- X: [@tapecards](https://x.com/tapecards)
- Partner: [Renaiss](https://www.renaiss.xyz/ref/tcahub) (the public word is “partner”)

This repository holds **public paper docs** only. Rates, the soft cap, unlock schedules, and lottery eligibility are draft and follow the formal release.

**Source of truth.** The site and these docs share the locks synced on 2026-11-06 (Asia/Shanghai). Public paper parameters live in this repository.

---

## Document index

| File | What it covers |
|------|----------------|
| [00-glossary.md](./00-glossary.md) | Terms used in these docs |
| [01-overview.md](./01-overview.md) | Slogan, positioning, and what TCA is |
| [02-mechanism.md](./02-mechanism.md) | Seven steps from pledge to the lottery |
| [03-fees-treasury.md](./03-fees-treasury.md) | Four fee buckets and the treasury |
| [04-buy-protection.md](./04-buy-protection.md) | Buy protection by fill speed |
| [05-lottery.md](./05-lottery.md) | Lottery eligibility, as a direction |
| [06-council.md](./06-council.md) | Council · decision rights |
| [07-risk.md](./07-risk.md) | Risk statement |
| [OPEN-ITEMS.md](./OPEN-ITEMS.md) | Figures and rules that are still unset |

---

## Settled summary (2026-11-06)

- Slogan: **Make TCG more fun.**
- Positioning: graded-card tokenization and themed issuance. One theme, one slot, one token. Slot names are illustrative only.
- Always “graded cards.” With Renaiss, always “partner.”
- Card-pledge hard cap about $1,000, first come, first served. The platform may join a new pool for about 10–30% and does not fill the pool alone.
- Pledgers whose pledges count toward the cap share about **5%** of that theme token’s supply equally, then unlock **daily over 30 days**. A pledger is not necessarily the controller of the theme token.
- **40% treasury**: the platform executes this by the rules (buy graded cards of the theme, and buy back platform TCA).
- Four fee buckets: **40 / 20 / 20 / 20** (Treasury / Platform / Staker share / Buyback & burn). Buyback & burn buys back and burns the token of that trade.
- Total fee: a theme token is a fixed **2.5%**. TCA is **10%** until about **$1M** cumulative volume, then **5%** until about **$10M**, then **2.5%**. After a step-down, the buckets still split **40 / 20 / 20 / 20**.
- Buy protection: soft cap about $100k. A fast fill uses the progress track (about ≤35% / 35–70% / >70% → 10% / 20% / 30%). A slow fill uses the time track (within about 1 hour / within about 2 hours / after about 3 hours → 10% / 20% / 30%). The locked remainder unlocks evenly across about 10 days, a portion each day. Example: 10% instantly sellable → the remaining 90% is about **9% of the purchase total per day** for about 10 days. When the soft cap is reached, the token launches and this rule lapses.
- Lottery: at least 10 Renaiss SBTs, plus a holding of the matching theme token (amount not set). About every 24 hours. A holder perk. The page points to [@tapecards](https://x.com/tapecards).
- Council: tentatively 12 seats, screened from the community and added only after human review. Votes cover buybacks, burns, which theme or series to support, what launches next, and how treasury funds are used. Day-to-day card buys are not voted.
- Open items (the pledge-return threshold, and similar) are listed in [OPEN-ITEMS.md](./OPEN-ITEMS.md). They are not invented here.

---

*Last synced: 2026-11-06 (Asia/Shanghai)*
