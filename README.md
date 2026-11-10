# SupeRR Selector — Player Analysis Dashboard

Complete player analysis for SupeRR Selector Season 2, Round 1: *Identify the Most Reliable Players Under Pressure*.

Built from the supplied ball-by-ball data: **867 matches, 200,999 deliveries, 958 players** (IPL + T20I, 2022 onwards).

Open `index.html` in a browser. No server needed.

## What is inside

- **Top Batters / Top Bowlers** — sortable leaderboards with a minimum-balls filter.
- **Pressure boards** — top batters and bowlers under pressure (death overs 16-20 plus super overs).
- **Player search** — full profile for any player: matches, innings, runs, balls, average, strike rate, 4s/6s, 50s/100s, highest score, dot-ball %; phase splits (powerplay / middle / death); pressure numbers; vs pace and vs spin (batting), vs RHB and vs LHB (bowling); dismissal breakdown by type, by over, and by ball of the over; the bowlers who dismissed him most; best bowling; and a Weakness box.
- **How the numbers are made** — every definition, in the page.

## How the numbers are made

- Balls faced exclude wides. Legal balls bowled exclude wides and no-balls.
- Bowler runs conceded = batsman runs + 1 per wide + 1 per no-ball (leg-byes and byes are not charged to the bowler).
- The extras columns in the raw file are type codes, not run counts, so team totals cannot be rebuilt from them.
- The dismissed player is counted out (run outs can be the non-striker). Bowlers are credited the wicket for every dismissal except Run Out, Retire Out and Obstructing the field.
- Pressure = death overs (16-20) plus super overs (innings 3-4).
- Matches played come from the playing-XI file; innings = match-innings in which the player batted or bowled.
- 16 of 883 matches have no ball-by-ball rows.
