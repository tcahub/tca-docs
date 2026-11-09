# TCA — Trading Cards Assets

> Paper draft — rates, the soft cap, and unlock timing follow the formal release · not financial advice

**Make TCG more fun.**

**What TCA is.** TCA is a launchpad that brings graded physical cards on-chain: each card theme becomes one slot, and each slot issues one token — asset tokenization, issued by theme.

The token is the tool, not the point. It exists so card lovers can sweep up the cards they love and build the community around them. TCA serves the cards, and the people who collect them.

Tokens can burn. **Cards stay forever.**

- Site: [https://tcahub.xyz/](https://tcahub.xyz/)
- X: [@tapecards](https://x.com/tapecards)
- Partner: [Renaiss](https://www.renaiss.xyz/ref/tcahub) (the public word is "partner")

This repository holds **public paper docs** only. This page does not connect a wallet, trade, or run a lottery.

**Source of truth.** Mechanism and narrative in these docs follow the V4 paper. Public paper parameters live in this repository.

---

## Document index

| File | What it covers |
|------|----------------|
| [00-glossary.md](./00-glossary.md) | Terms used in these docs |
| [01-overview.md](./01-overview.md) | Slogan, why now, slots, and Renaiss |
| [02-mechanism.md](./02-mechanism.md) | Seven steps from pledge to the lottery |
| [03-fees-treasury.md](./03-fees-treasury.md) | Four fee buckets and the theme-token rate |
| [04-buy-protection.md](./04-buy-protection.md) | Soft cap and quota release |
| [05-lottery.md](./05-lottery.md) | Lottery eligibility, as a direction |
| [06-council.md](./06-council.md) | Council · decision rights |
| [07-risk.md](./07-risk.md) | Risk statement |
| [08-supply-backing-liquidity.md](./08-supply-backing-liquidity.md) | Supply, card backing ratio, and locked liquidity |
| [OPEN-ITEMS.md](./OPEN-ITEMS.md) | Figures and rules that are still unset |

---

## Settled summary (2026-11-09)

- Slogan: **Make TCG more fun.**
- One theme, one slot, one token. Slot names are illustrative only. More themes are decided by the Council.
- Always "graded cards." With Renaiss, always "partner."
- Pledge: hard cap about **$1,000**, **$200** per wallet. A theme opens only with at least **5** counted pledgers. A card worth more than $200 still counts as $200. Pledging is an X whitelist: only reviewed addresses may enter. At least half of the counted value must be pledged cards; the remainder may be pledged in TCA. If community pledging falls short, the treasury may step in for up to **20%** of a pool, at the Council's discretion.
- Counted pledgers split about **5%** of that theme token's supply equally, unlocked daily over **30 days**. That supply reward is separate from the 20% fee bucket. Pledgers are the founding community, not necessarily the controllers of the theme token.
- Before launch, a pledge can be withdrawn and the card returned. After a successful launch the pledge locks for **30 days**, then unlocks automatically.
- Four fee buckets: **40 / 20 / 20 / 20**. The fees section names them Treasury / Platform / **Staker share** / Buyback & burn. The seven-step shorthand is treasury / platform / **pledgers** / buyback-burn. Staker share goes to pledgers whose pledges counted toward the cap.
- Theme tokens charge a flat **2.5%**. Every fee still splits 40/20/20/20.
- Quota release, during filling only: two tracks run in parallel. **Whichever track triggers first applies — once set, it does not switch.** Bands are 10% / 20% / 30%. The rest stays locked and releases daily over **21 days**. When the soft cap is reached, the token launches and this rule lapses.
- Supply, working proposal: fixed **1,000,000,000**. **80%** public, **10%** theme treasury, **5%** pledgers, **5%** lottery. No team slice.
- Card Backing Ratio is a disclosure: card FMV in the theme treasury ÷ theme market cap. It is not a price floor and not a redemption right.
- Opening pool: cash side about **12.5%** of the raise; token side from the treasury 10%; the rest of the raise buys graded cards. The pool position is locked. First 30 minutes: fee decays from **25%** to **2.5%**.
- Lottery: at least 10 Renaiss SBTs, plus a holding of the matching theme token (amount not set). About every 24 hours. A holder perk. The page points to [@tapecards](https://x.com/tapecards).
- Council: tentatively 12 seats, screened from the community and added only after human review. TCA pledgers can also join theme pledging — capped at **50%**. That cap is not a fee bucket.
- Open items are listed in [OPEN-ITEMS.md](./OPEN-ITEMS.md). They are not invented here.

---

*Last synced: 2026-11-09 (Asia/Shanghai)*
