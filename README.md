# D12 2026 — season projections

Projections for a 12-team superflex fantasy auction where every manager spent exactly $200
on a 15-man roster. Two analyses, each a self-contained page, published from this repo.

| Page | Projection source | URL |
|---|---|---|
| **Twenty-Four Quarterbacks** | Sleeper's weekly 2026 projections, scored with the league's settings | https://jrgutier.github.io/d12-2026/sleeper/ |
| **The $2,400 Board** | the league's own 2026 ranking board | https://jrgutier.github.io/d12-2026/ |

## Method

Every one of the 180 auction picks is projected for the season, then run through 20,000
simulated seasons. Each simulated season models per-position weekly variance, injury hazards
weighted by age and workload, bye weeks, optimal weekly lineup fill from whoever is available,
and both the head-to-head result and the weekly median match the league scores.

Scoring is this league's own: 0.5 PPR, 5-point passing touchdowns, 0.05 per passing yard,
0.1 per rushing and receiving yard, and 0.2 per rush attempt — which is worth roughly 50 points
a season to a workhorse back and is the reason the running back ordering here differs from a
standard-scoring board.

## Caveat

Both pages project the preseason, not the season. They inherit every error in their underlying
projections and have watched no football — no camp news, no depth-chart changes, no in-season
trades or waiver claims. The spread between first and last is small relative to the week-to-week
variance, and the win ranges overlap heavily. Treat the orderings as priors, not results.
