# TCA — Trading Cards Assets

> Paper draft · subject to the official release · not financial advice

**TCA (Trading Cards Assets)** is a prototype launchpad for trading-card themes: one theme, one slot, one token. Graded cards of that theme are staked until a first-come, first-served hard cap of about **$1,000** is filled (more than one person may join; any excess is returned). That theme can then launch its theme token.

- Site: [https://tcahub.xyz/](https://tcahub.xyz/)
- X: [@tapecards](https://x.com/tapecards)
- Partner: [Renaiss](https://www.renaiss.xyz/ref/tcahub) (write “partner”; do not write “bound”)

This repository holds **public paper docs** only. Rates, the soft cap, unlock schedules, and lottery eligibility are all draft.

**Source of truth.** Public paper parameters live in this repository. The site is a marketing summary. These docs are the paper record until the official release.

---

## Document index

| File | What it covers |
|------|----------------|
| [00-glossary.md](./00-glossary.md) | Terms used in these docs |
| [01-overview.md](./01-overview.md) | Position and the one-liner |
| [02-mechanism.md](./02-mechanism.md) | Seven steps from staking to the lottery |
| [03-fees-treasury.md](./03-fees-treasury.md) | Four fee buckets and the treasury |
| [04-buy-protection.md](./04-buy-protection.md) | Buy protection by fill speed |
| [05-lottery.md](./05-lottery.md) | Lottery eligibility, as a direction |
| [06-dao.md](./06-dao.md) | DAO · decision rights |
| [07-risk.md](./07-risk.md) | Risk statement |
| [OPEN-ITEMS.md](./OPEN-ITEMS.md) | Figures and rules that are still unset |

---

## Settled summary (2026-11-06)

- Position: make TCG more fun to play · Trading Cards Assets
- Always “graded cards.” With Renaiss, always “partner.”
- Stake-pool hard cap about $1,000, first come, first served. The platform may take about 10–30% of a new pool and does not fill a pool by itself.
- Participants whose stake counts toward the cap share about **5%** of that theme token’s supply, then unlock **daily over 30 days**. A staker is not necessarily the controller of the theme token.
- **40% treasury**: the platform carries this out under the rules (buy graded cards of the theme, and buy back platform TCA).
- Four fee buckets: **40 / 20 / 20 / 20** (Treasury / Platform / Staker share / Buyback & burn). Buyback & burn buys back and burns the token of that trade.
- Total fee: a theme token is a fixed **2.5%**. TCA is **10%**, then **5%** after about **$1M** cumulative volume, then **2.5%** after about **$10M**. After a step-down, the buckets still split **40 / 20 / 20 / 20**.
- Buy protection: soft cap about $100k. The instantly sellable share follows how fast the pool fills. A fast fill uses the progress track (about ≤35% / 35–70% / >70% → 10% / 20% / 30%). A slow fill uses the time track (about 1 hour / 2 hours / 3 hours or later → 10% / 20% / 30%). The rest unlocks over about 10 days.
- Lottery: at least 10 Renaiss SBTs, plus a holding of the matching theme token (amount not set). About every 24 hours.
- DAO: tentatively 12 seats, community-sourced, placed on the list only after human review. Votes cover buybacks, burns, and which theme to support. Routine card buys are not voted.
- Open items (the threshold figures, and similar) are listed in [OPEN-ITEMS.md](./OPEN-ITEMS.md). They are not invented here.

---

*Last synced: 2026-11-06 (Asia/Shanghai)*
