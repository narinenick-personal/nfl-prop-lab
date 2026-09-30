# NFL Prop Lab

A browser-based NFL player prop research dashboard. Search current offensive rosters, choose a prop and opposing defense, and compare the player's last 10 recorded games to an entered line. The defense panel focuses on the selected player's position (QB, RB, WR, or TE), showing the last 10 completed games, position totals, matching contributors, and team totals for context. A 2026 NFL ranking compares the selected prop and position by per-game average across completed regular-season games. Rank #1 allows the fewest; equal averages share a rank.

## Props

- Passing, rushing, and receiving yards
- Receptions
- Rush + receiving yards (sum of the two for each player)
- Passing touchdowns

## Run

Open `index.html` in a browser or serve this directory with any static web server. No build step or API key is required. It can also be published with GitHub Pages using the repository root as the site source.

## Data and limitations

Data is loaded from ESPN's public NFL team roster, schedule, and game summary endpoints. Roster and game data require an internet connection. Player search uses current team rosters; games played for a previous team may not appear in the player view. The game history presently spans the 2025 and 2026 seasons. Positions are matched from current rosters with individual athlete lookups for former players. Unresolved positions are disclosed and excluded from position totals; a league ranking is withheld if required data is incomplete. This tool is for research, not a betting recommendation.
