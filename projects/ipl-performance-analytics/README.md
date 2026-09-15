# IPL Performance & Match Intelligence Dashboard

A professional IPL analytics dashboard designed from the requested Power BI-style reference.

## Data basis
The supplied IPL Crunch '26 analysis package states that it parsed 1,226 Cricsheet IPL JSON match files covering 2007/08 through 2026 and 291,574 real deliveries.

## Included
- `index.html` — Vercel-ready interactive dashboard
- `data/top_batters_2008_2026.csv`
- `data/top_bowlers_2008_2026.csv`
- `data/top_six_hitters_2008_2026.csv`
- `data/season_scoring_trend_2008_2026.csv`
- `data/team_runs_2023_reference.csv`
- `data/team_wickets_2023_reference.csv`

## Important
The dashboard uses real 2008–2026 all-time player and season metrics from the supplied Cricsheet-based analysis. The team-runs and points-table panels are intentionally labeled **2023 reference view** because those values came from the requested reference dashboard and the raw ball-by-ball files were not attached in this chat. Do not present those two panels as 2026 calculations until the raw Cricsheet JSON/CSV is loaded.

## Vercel
This is a static site. Put `index.html` at the repository root of a Vercel project, or set the project root to this folder, and deploy it.
