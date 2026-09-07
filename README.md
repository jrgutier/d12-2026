# The $2,400 Board

Season projection for the D12 2026 fantasy football league — a 12-team superflex
auction where every manager spent exactly $200.

**Read it: https://jrgutier.github.io/d12-2026/**

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
