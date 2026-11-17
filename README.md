# SupeRR Dressing Room

Entry for Rajasthan Royals' SupeRR Selector Season 2, Round 1: the most reliable batters and bowlers under pressure.

- `index.html` is the full dashboard. It is one self-contained file: the data, styles and scripts are inside it, and it needs no build step. The only outside request is Google Fonts.
- `backup/index.html` is the earlier single-page version of the same analysis.


## What is inside

- Ratings from IPL 2022 to 2026 and T20 internationals from January 2022 to 1 November 2026: 812 matches and 191,718 rated deliveries.
- Pressure is defined with a win-probability model: a ball is high pressure when its Leverage Index is 1.5 or more.
- Players are ranked on the floor (10th percentile) of the runs they add or save per 100 pressure balls.
- The raw ball-by-ball data supplied for the competition is not in this repository.
