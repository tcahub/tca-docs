# 08 · Supply, backing, and liquidity

## What one theme token is made of

Each theme issues exactly one token with a fixed supply of **1,000,000,000**. **80%** goes to the public during filling. The remaining 20% is fully accounted for: **10%** theme treasury, **5%** pledgers, **5%** lottery. There is no team slice.

| Share | Tokens | Use |
|------|--------|-----|
| 80% | 800,000,000 | Public sale. Sold during filling. The launch price is set by the raise itself. |
| 10% | 100,000,000 | Theme treasury. Graded-card purchases, theme operations, and the token side of the opening pool. Council votes. Ledger disclosed. |
| 5% | 50,000,000 | Pledgers. Split equally by counted pledgers. The card itself is a refundable pledge. This 5% is the reward, not the compensation, and it is not the 20% Staker share fee bucket. |
| 5% | 50,000,000 | Lottery fund. Prize pool for the holder perk. Eligibility comes from holding, not from buying tickets. |

Every theme token is 100% community-held from day one. There is no team slice, no seed or advisor allocation, and no market-maker reserve. The platform earns from its 20% fee bucket and from TCA, not from a theme token it set aside for itself.

Allocation is the working proposal and follows the formal release.

## Backing, not a floor

A theme token is not a claim on a card. What is published is a ratio: how much graded-card value stands behind the theme's market cap. It is a disclosure, not a price promise.

**CBR** = card FMV in the theme treasury ÷ theme market cap.

Worked example on the V4 page, not a live treasury reading: cards $40,000, market cap $125,000, CBR 32.0%.

CBR is published on the site and refreshed with the Renaiss quote, with the last update shown. It rises when the treasury actually buys a card. It never triggers a contract. There is no redemption, no guaranteed buyback, and no floor price.

No page should state that holders can redeem cards for value or that the protocol will defend a price.

## Liquidity that cannot leave

The opening pool is built at the launch price. Its token side comes out of the treasury share, never out of anyone's purchase. The cash side is only a slice of the raise, because 80% of the supply is already in public hands. The rest of the raise buys graded cards on a purchasing schedule.

| Piece | Draft figure |
|------|----------------|
| Pool — cash side | about **12.5%** of the raise |
| Pool — token side | from the treasury **10%** |
| Graded cards | the rest of the raise |
| Pool position | locked |

### Anti-snipe · first 30 minutes

- At launch → **25%**
- Linear decay over → **30 minutes**
- From minute 30 on → **2.5%**

The position sits in a protocol contract with no withdraw path. Fee rights stay with the 40/20/20/20 splitter, so every trade in the pool keeps feeding treasury, platform, pledgers, and burn. Nobody, the team included, can pull the principal.

The extra fees collected during the opening window go to the treasury, not to the platform. The decay picks up where quota release stops covering the market.

Pool split, the anti-snipe window, and the decay rate are drafts and follow the formal release. The 2.5% at minute 30 is the post-decay trade fee in that window's schedule. The theme token's standing fee is also a flat 2.5%, as in [03-fees-treasury.md](./03-fees-treasury.md).
