# Kestrel Edge — The aggressive wing

**Core Kestrel holds the line. Edge hunts.** A five-name Solana memecoin basket run by the same engine, tuned hot: equal-weight entries, drift-band rebalances around the clock, hard risk rails — equal weights, a per-name cap, no leverage, and a basket-level drawdown trigger. Only for capital that can go to zero.

Live paper tracker: https://kestrelinvest.xyz/edge.html

## Target allocation

| Slot | Weight |
|---|---|
| Five rotating Solana memecoins | 20 % each |

Fully invested. Names rotate on liquidity and momentum; new entries land six hours after their pool opens, never in the launch hour. The current basket is shown live on the Edge page.

## How it is run

Every Kestrel portfolio is held in a VANE vault the owner alone can open and is kept on target by the same agentic engine: live two-source marks, a published drift band, and a full re-true-up whenever the market pushes the mix out of band — sells before buys, every leg an atomic on-chain swap with a slippage floor the program enforces. Nothing is calendar-based and nothing is discretionary.

The complete methodology — band mathematics and parameters, cooldown, trade construction, screening thresholds and substitution rules, the entry and rotation scoring, and the drawdown trigger — is maintained in a private repository (`KestrelInvest/kestrel-strategy`).

See it live: https://kestrelinvest.xyz/portfolios.html · Custody: `KestrelInvest/vane`

---
*Not investment advice. Kestrel is in development; nothing here is live for public deposits. Portfolio definitions are versioned; a change is a new version that a vault adopts only when its owner signs.*
