# The $2,400 Board

Season projection for the D12 2026 fantasy football league — a 12-team superflex
auction where every manager spent exactly $200.

**Read it: https://jrgutier.github.io/d12-2026/**

## Two projections

The same draft is projected twice, from two different sources, using an identical simulator:

| | Source | Read |
|---|---|---|
| **The $2,400 Board** | the league's own 2026 ranking board | https://jrgutier.github.io/d12-2026/ |
| **Two Boards, One Draft** | Sleeper's weekly projections (Rotowire), scored with this league's settings | https://jrgutier.github.io/d12-2026/sleeper/ |

They disagree almost completely. Eleven of twelve teams move, and the team most likely to win
the title under the board finishes last under Sleeper's numbers. The two sources agree closely
on running backs, receivers and tight ends; they disagree only about quarterbacks, where the
board sees a 17.5 point-per-game gap from the best to the 24th-best and Sleeper sees 4.8. In a
league that starts 24 quarterbacks a week, that single number decides the season.

## What it is

Every one of the 180 auction picks is matched to a positional rank on the league's
2026 board, converted to season points on curves calibrated to this league's exact
scoring (0.5 PPR, 5-point passing touchdowns, and 0.2 points per rush attempt), then
run through 20,000 simulated seasons.

Each simulated season models per-position weekly variance, injury hazards weighted by
age and workload, randomly assigned NFL bye weeks (so rosters stacked on one NFL team
take correlated hits), optimal weekly lineup fill from whoever is available, and both
the head-to-head result and the weekly median match the league scores.

The headline finding is a pricing one: against a superflex replacement baseline,
quarterbacks went for 0.66x their value and running backs for 1.42x.

## Caveat

This projects the preseason board, not the future. It inherits every error in the
underlying rankings and knows nothing about camp, depth charts, or schedule. Only
11.6 points per game separate first place from last, and the win ranges overlap
heavily. Treat the ordering as a prior, not a result.
