# Sigorum: public record of sharp money sports picks

Every pick [Sigorum](https://sigorum.com/?ref=github) has published and settled, with its result. Paper results: a simulated $100 on every pick, at the odds when the pick was posted. Nothing is removed, losses included.

**Record 2026-10-31 to 2026-11-21:** paper profit **+$6,428**, ROI **+9.1%** at $100 a pick.

## How a pick is made

Bets on prediction markets are public. Sigorum follows accounts with a long record of profit (proven bettors) and posts a pick when their sharp money lands on one side of a game before it starts, and not when money of the same quality sits on the other side. Each pick is posted before the start and settled after the final result.

## The file

`sigorum-picks.csv`, one row per settled pick:

| column | meaning |
|---|---|
| posted_utc | when the pick was posted (UTC) |
| start_utc | scheduled start of the game (UTC) |
| settled_utc | when the result came in (UTC) |
| sport, league, event | the game |
| market | the market the pick is on (winner, spread, total) |
| pick | the side, with the line for spreads and totals |
| odds_decimal | decimal odds when the pick was posted |
| result | won, lost, or closed early |
| paper_pnl_usd_at_100 | paper profit or loss on a $100 stake |

The live record, today's picks and the research behind the method: [sigorum.com/results](https://sigorum.com/results/?ref=github) · [sigorum.com/research](https://sigorum.com/research/?ref=github). Updates: X [@getSigorum](https://x.com/getSigorum).

Paper results only, simulated stakes, no real money. Not financial advice. 18+. Bet responsibly.

License: CC BY 4.0 (use it freely, link back to sigorum.com).
