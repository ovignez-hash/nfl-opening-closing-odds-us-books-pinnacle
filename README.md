# 🏈 NFL Opening & Closing Odds — 9 US Books, Pinnacle, Kalshi & Polymarket (2018–2026)

**26 games — every season from 2018 to 2026, all 8 Super Bowls, 2 ties, the first closing moneyline of 12 of the 14 sources**

Most NFL odds archives give you one closing number per game, from one book.

The full dataset puts **up to 14 sources side by side on each game, in American odds**: FanDuel, DraftKings, BetMGM,
Caesars, BetRivers, BetOnline, theScore, Fanatics and Hard Rock, with Pinnacle, Bet365, Betcris, Kalshi and Polymarket.
Moneyline, spread and total, plus Pinnacle's team totals: **the opening and the closing price, each with the time it was
recorded**.

→ **[Get the full archive](https://sportsdataolivier.gumroad.com/l/yjnxja?utm_source=github&utm_medium=readme&utm_campaign=nfl_us&utm_content=hero)** — 2,377 games, September 2018 to 16 November 2026 · also on [Whop](https://whop.com/oliviersportsdata/nfl-opening-closing-odds-9-us-books-pinnacle-2018-2026/?utm_source=github&utm_medium=readme&utm_campaign=nfl_us&utm_content=whop_hero)

This sample is cut from the full file: the same 309 columns, the rows copied byte for byte, at about 1% scale.

---

## One game, every source

Steelers at Saints, Stade de France, Paris, 25 October 2026, moneyline. All 14 sources closed it, 11 of them with an
opening price in the file. Pittsburgh won 16-10.

| Source | Open, Saints / Steelers | Close, Saints / Steelers |
|---|---|---|
| Pinnacle | +122 / -138 | +135 / -150 |
| Bet365 | +115 / -135 | +135 / -160 |
| FanDuel | – | +140 / -166 |
| DraftKings | – | +140 / -167 |
| BetMGM | +115 / -140 | +135 / -165 |
| Caesars | +120 / -141 | +133 / -159 |
| BetRivers | +112 / -136 | +140 / -175 |
| BetOnline | +120 / -140 | +136 / -156 |
| theScore | – | +145 / -170 |
| Fanatics | +140 / -170 | +135 / -165 |
| Hard Rock | +115 / -130 | +140 / -160 |
| Betcris | +129 / -153 | +143 / -163 |
| Kalshi | +163 / -170 | +144 / -150 |
| Polymarket | +163 / -170 | +144 / -150 |

---

## What's in this sample

| | |
|---|---|
| Games | 26 — every season from 2018 to 2026 |
| Stages | 16 regular season · 10 playoffs: all 8 Super Bowls and 2 Wild Card games |
| Endings | 22 in regulation, 4 in overtime, 2 of them ties |
| Prices | 2,028 |
| Sources | 14 — Pinnacle, Bet365, FanDuel, DraftKings, BetMGM, Caesars, BetRivers, BetOnline, theScore, Fanatics, Hard Rock, Betcris, Kalshi, Polymarket |
| Columns | 309 |
| File | `NFL_Opening_Closing_Odds_2018-2026_SAMPLE.csv`, plus the README of the full product |

| Date (ET) | Game | Week | Final, away–home | Sources, closing / opening ML |
|---|---|---|---|---:|
| 6 Sep 2018 | Falcons @ Eagles | Week 1 | 12–18 | 3 / 1 |
| 9 Sep 2018 | Steelers @ Browns | Week 1 | 21–21 OT | 3 / 1 |
| 4 Oct 2018 | Colts @ Patriots | Week 5 | 24–38 | 4 / 3 |
| 14 Oct 2018 | Seahawks @ Raiders | Week 6 | 27–3 | 4 / 3 |
| 3 Feb 2019 | Patriots @ Rams | Super Bowl | 13–3 | 4 / 2 |
| 5 Sep 2019 | Packers @ Bears | Week 1 | 10–3 | 6 / 1 |
| 2 Feb 2020 | 49ers @ Chiefs | Super Bowl | 20–31 | 6 / 3 |
| 10 Sep 2020 | Texans @ Chiefs | Week 1 | 20–34 | 8 / 2 |
| 7 Dec 2020 | Bills @ 49ers | Week 13 | 34–24 | 9 / 8 |
| 3 Jan 2021 | Dolphins @ Bills | Week 17 | 26–56 | 9 / 3 |
| 7 Feb 2021 | Chiefs @ Buccaneers | Super Bowl | 9–31 | 9 / 4 |
| 8 Jan 2022 | Chiefs @ Broncos | Week 18 | 28–24 | 8 / 7 |
| 13 Feb 2022 | Rams @ Bengals | Super Bowl | 23–20 | 8 / 4 |
| 20 Nov 2022 | Browns @ Bills | Week 11 | 23–31 | 9 / 8 |
| 12 Feb 2023 | Chiefs @ Eagles | Super Bowl | 38–35 | 8 / 3 |
| 16 Nov 2023 | Bengals @ Ravens | Week 11 | 20–34 | 10 / 7 |
| 11 Feb 2024 | 49ers @ Chiefs | Super Bowl | 22–25 OT | 10 / 6 |
| 6 Sep 2024 | Packers @ Eagles | Week 1 | 29–34 | 9 / 6 |
| 13 Jan 2025 | Vikings @ Rams | Wild Card | 9–27 | 9 / 8 |
| 9 Feb 2025 | Chiefs @ Eagles | Super Bowl | 22–40 | 9 / 4 |
| 28 Sep 2025 | Packers @ Cowboys | Week 4 | 40–40 OT | 9 / 6 |
| 16 Nov 2025 | Commanders @ Dolphins | Week 11 | 13–16 OT | 10 / 7 |
| 10 Jan 2026 | Rams @ Panthers | Wild Card | 34–31 | 10 / 5 |
| 8 Feb 2026 | Seahawks @ Patriots | Super Bowl | 29–13 | 10 / 3 |
| 25 Oct 2026 | Steelers @ Saints | Week 7 | 16–10 | 14 / 11 |
| 16 Nov 2026 | Chargers @ Ravens | Week 10 | 23–20 | 13 / 13 |

*Sources* counts, out of 14, the sources with a closing / opening moneyline for that game. Why each game is
here, game by game: `sample/README.md`.

---

## In this repository

| File | Content |
|---|---|
| `sample/NFL_Opening_Closing_Odds_2018-2026_SAMPLE.csv` | the 26 games, 309 columns |
| `sample/README.md` | why each game is here, then the README of the full product |
| `NFL_US_Verify_Before_You_Buy.ipynb` | the figures of the listing and of its README recomputed from the full file (all the file can show), results shown |

---

## Columns

| Block | Columns | Content |
|---|---:|---|
| Game | 17 | `League`, `Game_ID` (`YYYYMMDD_AWAY_HOME`, US Eastern date), `NFL_Game_ID`, `Season`, `Week`, `Stage`, `Kickoff_UTC`, `Epoch`, teams, `Neutral_Site`, final score, `Winner`, `Total_Score`, `Margin`, `Match_Ending` |
| Pinnacle | 38 | moneyline, spread and total, opening then closing, with the time of each, plus the team totals of both teams |
| Bet365, the 9 US books and Betcris | 22 each | moneyline, spread and total, opening then closing, with the time of each |
| Kalshi, Polymarket | 6 each | moneyline only |

`{Book}_ML_Home_Open` · `{Book}_ML_Home_Close` · `{Book}_ML_Close_Time` · `{Book}_Spread_Home_Line_Close` · `{Book}_Total_Line_Close` · `Pinnacle_Team_Total_Home_Line_Close` — the prefixes are `Pinnacle_`, `Bet365_`, `FanDuel_`, `DraftKings_`, `BetMGM_`, `Caesars_`, `BetRivers_`, `BetOnline_`, `theScore_`, `Fanatics_`, `HardRock_`, `Betcris_`, `Kalshi_`, `Polymarket_`.

### How to read it

**Prices are American odds**, as integers: `-150`, and `130` for +130. **The spread is the home team's line:** `-3.5` means the home team gives 3.5 points. **Overtime counts in every market**, as US books settle them; a tied game has `Winner` = `Tie`. **Times are UTC**, ISO 8601 with the T and the Z. **The opening price is the first price recorded for the game, posted at most 15 days before kickoff; the closing price is the last pre-game one.** Each one carries its own time, so you can see how close to kickoff it was taken.

```python
import pandas as pd

df = pd.read_csv("NFL_Opening_Closing_Odds_2018-2026_SAMPLE.csv")

def prob(us):  # American odds -> implied probability
    return (-us / (-us + 100)).where(us < 0, 100 / (us + 100))

# Pinnacle's no-vig probability of the home team at the close
h, a = prob(df["Pinnacle_ML_Home_Close"]), prob(df["Pinnacle_ML_Away_Close"])
pinnacle_home = h / (h + a)

# how far four US books moved the spread, open to close
books = ["FanDuel", "DraftKings", "BetMGM", "Caesars"]
spread_move = pd.DataFrame({b: df[b + "_Spread_Home_Line_Close"] - df[b + "_Spread_Home_Line_Open"] for b in books})

# how close to kickoff Bet365's closing moneyline was recorded, in minutes
start = pd.to_datetime(df["Kickoff_UTC"])
bet365_close_min = (pd.to_datetime(df["Bet365_ML_Close_Time"]) - start).dt.total_seconds() / 60
```

---

## Said plainly

- **The file starts with the 2018 season; Pinnacle starts with the 2020 season.**
- **Overtime counts in every market**, as US books settle them. 9 games ended in a tie: `Winner` says `Tie`.
- **An opening price is the book's first price posted at most 15 days before kickoff.** DraftKings and Caesars post most lines months ahead, so their openings are often empty: 15% of the 2023 to 2025 games have a DraftKings opening moneyline, 23% a Caesars opening spread.
- **Bet365 has no price on the 28 games of January 2026** (week 18 of the 2025 season and the playoffs up to the conference championships). Its totals start on 13 October 2019.
- **BetRivers' prices before 2026 come from market snapshots.** BetRivers, Fanatics and Hard Rock have almost no price in the 2025 season (1, 6 and 3 closing prices): their record that season is market snapshots, almost all stamped after kickoff, in-game prices that were not used.
- **Betcris covers every season except 2021**, the 2026 season through 2 November 2026. **BetOnline has the spread in 2018 and from 2020, the total from 2020.**
- **Kalshi and Polymarket: moneyline only**, closing prices from 16 November 2025 and 10 January 2026, opening prices from 22 October 2026. In 2026, their closing prices are identical in 97 of the 129 games where both have one.
- **Team totals come from Pinnacle only**, 3 January 2021 to 8 February 2026; none in the 2026 season so far.
- **No preseason, no Pro Bowl, no player props, no quarters or halves, no live odds, no futures.** One opening and one closing price per book and market, not every move in between. Every recorded move (timestamped odds), other books or another scope: built to order on request.

---

## Verify before you buy

The figures of the listing and of its README — games, prices, the sources and their first price, coverage, opening
and closing times, the gaps stated above, the games on the listing's images — recomputed from the full file and
printed PASS or FAIL, all but what the file cannot show (the counts of prices left out while it was built):
[on Kaggle](https://www.kaggle.com/code/oliviersportsdata/nfl-us-books-odds-verify-before-you-buy) · [on GitHub](https://github.com/ovignez-hash/nfl-opening-closing-odds-us-books-pinnacle/blob/main/NFL_US_Verify_Before_You_Buy.ipynb) (results shown).

---

## The full dataset

| | Sample | Full |
|---|---|---|
| Games | 26 | 2,377 |
| Seasons | 2018 to 2026 | 2018 to 2026, through week 10 of 2026 (16 Nov 2026) |
| Prices | 2,028 | 212,370 |
| Columns | 309 | 309 |
| Files | 1 CSV + README | 1 CSV + README |

Once a year, after the Super Bowl, the file adds the completed season. The games after 16 November 2026 come with the
[NFL US books monthly updates](https://sportsdataolivier.gumroad.com/l/uqmog?utm_source=github&utm_medium=readme&utm_campaign=nfl_us&utm_content=monthly): each month's games, same 309 columns, ready to append.

→ **[Get the full archive](https://sportsdataolivier.gumroad.com/l/yjnxja?utm_source=github&utm_medium=readme&utm_campaign=nfl_us&utm_content=footer)** · also on [Whop](https://whop.com/oliviersportsdata/nfl-opening-closing-odds-9-us-books-pinnacle-2018-2026/?utm_source=github&utm_medium=readme&utm_campaign=nfl_us&utm_content=whop_footer)

---

## Licence

Sample: free to explore and evaluate.
Full product: single commercial user. Use the data as you wish, including the models, predictions and products you sell.
Redistribution and resale of the files, or of the raw data in another format, are not permitted.

A question, an invoice or a custom extract: contact@oliviersportsdata.com

---

*Olivier Sports Data — From Chicken Area 🐔*
