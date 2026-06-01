# Rebuilding Football Challenge

A football transfer-window rebuild game where you take control of an elite club, decide which players to sell or keep in whatever order you choose, sign replacements under budget pressure, complete manager objectives, and finish with a full season report — with real player photos, ages, and club crests.

## Short Description

A single-page football rebuild game where you pick one of seven elite clubs, manage a €100M budget, work through your starting XI one player at a time, negotiate sales, sign replacements (or promote from your bench for free), complete manager challenges, and see your final squad report.

## Overview

**Rebuilding Football Challenge** is a browser-based football management game built in a single HTML file using vanilla HTML, CSS, and JavaScript. You get a real starting XI, decide the fate of each player in the order you want, weigh transfer offers, sign replacements, manage manager objectives and financial events, and review your rebuild at the end.

The goal is simple: rebuild the squad without wrecking the budget.

## Features

- Choose between **Real Madrid**, **FC Barcelona**, **Bayern München**, **Arsenal**, **Liverpool**, **Manchester City**, and **Paris Saint-Germain**
- Three difficulty levels:
  - **Low** — 1 manager challenge, buy and sell at exact market value (no haggling)
  - **Medium** — 3 manager challenges, the dealer haggles
  - **Hard** — 5 manager challenges, the dealer haggles
- Free-pick format: tap any player in your starting XI, in any order, and decide their fate — all 11 must be decided to finish
- Interactive football pitch with a real, value-and-pedigree-weighted starting XI
- Sell, keep, or replace players through transfer offers
- Three replacement tiers (cheap, balanced, superstar) **plus a free "promote from your bench" option** drawn from the club's real squad depth
- Real player **photos**, **ages**, and **market values** sourced from Transfermarkt data
- Real **club crests** on the team-select cards and in-game header
- Polaroid/sticker-style player cards (no FIFA-style tier frames)
- Dynamic budget tracking for money earned and spent
- Manager objective cards that create extra challenges
- Financial event cards that can help or hurt your rebuild
- Final season report with squad value, spending, earnings, an age profile, and completed objectives
- Fully responsive, dark stadium-inspired UI

## How to Play

1. Open the game in your browser.
2. Pick a difficulty (Low, Medium, or Hard).
3. Select one of the seven clubs.
4. Tap any player in your starting XI — in whatever order you like.
5. Review the dealer's offer and choose to **keep** or **sell**.
6. If you sell, pick a replacement: cheap, balanced, superstar, or promote a benched player for free.
7. Manage your €100M budget as you go.
8. Decide on all 11 players to complete the rebuild.
9. View your final season report, including your manager-objective results.

## Data & Attribution

Player names, photos, ages, and market values, plus club crests, are sourced from **Transfermarkt** and used for identification purposes only. This is a non-commercial fan project. All names, images, logos, and brands are the property of their respective owners.

## Tech Stack

- HTML
- CSS
- JavaScript (vanilla)
- Google Fonts

No frameworks, build tools, or backend required. All layout, styling, player data, ages/photos, club logos, game state, and logic live inside one HTML file.

## Running Locally

Download the file and open it directly in your browser:

```bash
open "Rebuilding-Football-Challenge.html"
```

Or just double-click the file.

> Note: player photos and club crests load from Transfermarkt's image servers, so an internet connection is needed for images to appear. Without it, the game still plays and shows clean silhouette fallbacks.

## Project Structure

```text
Rebuilding-Football-Challenge.html
README.md
```

Everything is contained in a single HTML file, including the layout, styling, player data, ages/photos, club logos, game state, and logic.

## Credits

Created by Ilkin Mirzayev.
Player data, photos, values, and crests powered by Transfermarkt.

## License

This project is for personal and educational use. Add a license file if you plan to make it public or allow others to reuse the code.
