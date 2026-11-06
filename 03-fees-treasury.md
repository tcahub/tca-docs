# 03 · Fees and the treasury

Trading fees split **40 / 20 / 20 / 20** (Treasury / Platform / Staker share / Buyback & burn). The four shares add up to 100%.

```mermaid
flowchart LR
  fee[Trading fee] --> treasury["40% Treasury"]
  fee --> platform["20% Platform"]
  fee --> staker["20% Staker share"]
  fee --> burn["20% Buyback and burn"]
```

| Share | Use |
|------|------|
| 40% | **Treasury.** The platform executes this by the rules: buy graded cards of that theme, and buy back the platform token, TCA. The split between those two uses is not set. |
| 20% | **Platform.** Runs the launchpad. This share stays with the platform. |
| 20% | **Staker share.** Paid to pledgers whose pledges counted toward the cap. |
| 20% | **Buyback & burn.** Buy back and burn **the token of that trade** (TCA trades burn TCA; theme-token trades burn that theme token). |

Counted separately: the pledger token reward (about 5% of the theme-token supply, split equally and unlocked daily over 30 days) does not draw on the four buckets. TCA is both the name of the launchpad and, in this draft, the platform token the treasury can buy back.

## Total fee

| Token | Total fee |
|------|-----------|
| **Theme token** | Fixed **2.5%**. |
| **TCA** | **10%** until about **$1M** cumulative volume, then **5%** until about **$10M**, then **2.5%**. |

After any step-down, the four buckets still split **40 / 20 / 20 / 20** (Treasury / Platform / Staker share / Buyback & burn).
