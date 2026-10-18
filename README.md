# ⚽ Timestamped Football Odds incl. Pinnacle — 9 Leagues of the Americas: MLS, Liga MX, Brasileirão, Argentina + 5 More (free sample)

**Futbol, Futebol & Soccer Premium — free sample: 20 matches out of 30,999, from each of the 9 leagues.** Same files,
same columns, same formats as the full product. Only the number of matches differs.

Most football odds datasets give you one closing number per match. The full product gives you
**73,680,541 timestamped quotes** from 5 named bookmakers, pre-match and in-play, with the score
and the match clock the bookmaker sent on its in-play quotes, plus the opening and the closing of every book and
market with the
exact time each was recorded, and 1,781,722 dated snapshots from 37 more bookmakers.

⚽ **[→ Get the full dataset on Gumroad](https://sportsdataolivier.gumroad.com/l/diswpw?utm_source=github&utm_medium=repo&utm_campaign=americas_premium&utm_content=readme_top)** — 30,999 matches, 9 top flights, 96 league-seasons, 2016–2026.

---

## In this repository

| Path | What it is |
|---|---|
| `sample/` | The free 20-match sample: same files, same columns as the full product |
| `Americas_Verify_Before_You_Buy.ipynb` | *Verify before you buy*: every figure of the listing recomputed on the **full** product, outputs included |

Also on [Hugging Face](https://huggingface.co/datasets/oliviersportsdata/Americas-Football-Timestamped-Odds-Pinnacle-Match-Stats), with a table viewer, and on [Kaggle](https://www.kaggle.com/datasets/oliviersportsdata/americas-football-odds-with-pinnacle-sample).

---

## What's in this sample

| Table | Sample | Full product |
|---|---:|---:|
| Odds_Timestamped | 89,742 | 73,680,541 |
| Minute_Stats | 9,172 | 8,353,269 |
| Bookmaker_Snapshots | 1,550 | 1,781,722 |
| Lineups | 754 | 983,966 |
| Events | 998 | 954,808 |
| Team_Stats | 40 | 61,998 |
| Opening_Closing | 20 | 30,999 |
| Matches | 20 | 30,999 |

The 20 matches: a recent match of each of the 9 leagues (September 2026), the one with the most complete data
among the league's last matchdays, plus 11 matches chosen for what they show: the Liga MX final
of December 2025 (both legs), a full MLS best-of-three series (the deciding game is shown quote by quote below),
the Colombian final of June 2024 (both legs), a Superclásico, the Argentine final of December 2025, a match between
two Canadian clubs played in the USA, and a match whose kickoff time in the source is two days late. 2 went
to extra time, 5 to a penalty shoot-out.

| Country | League | Season | Stage | Date (UTC) | Match | Result | Note |
|---|---|---|---|---|---|---|---|
| Argentina | Argentine Primera Division (Copa de la Liga) | 2024 | Quarter-finals | 2024-04-21 | River Plate – Boca Juniors | 2-3 | Superclásico at a neutral ground in Argentina: Neutral_Venue 0 |
| Argentina | Argentine Primera Division (Apertura) | 2025 | Group Stage, matchday 8 | 2025-03-04 | Platense – Defensa y Justicia | 0-1 | kickoff in the source: 2025-03-04 23:00 UTC; played 2025-03-03 00:30 UTC, pre-match cut at the real start |
| Argentina | Argentine Primera Division (Clausura) | 2025 | Final | 2025-12-14 | Racing Club – Estudiantes LP | 1-1 · 1-1 aet · 4-5 pens | single-match final: extra time, penalties |
| Argentina | Argentine Primera Division (Clausura) | 2026 | Group Stage, matchday 9 | 2026-09-15 | Instituto AC Cordoba – Estudiantes Rio Cuarto | 2-1 |  |
| Bolivia | Bolivian Primera Division | 2026 | Regular Season, matchday 19 | 2026-09-12 | Real Potosi – Oriente Petrolero | 2-1 | no lineups in the source for this league |
| Brazil | Campeonato Brasileiro Serie A | 2026 | Regular Season, matchday 27 | 2026-09-14 | EC Bahia – Remo | 2-1 |  |
| Chile | Chilean Primera Division | 2026 | Regular Season, matchday 23 | 2026-09-13 | Colo Colo – Deportes Concepcion | 1-1 |  |
| Colombia | Categoria Primera A (Apertura) | 2024 | Final, leg 1 | 2024-06-09 | Atletico Bucaramanga – Independiente Santa Fe | 1-0 | Apertura 2024 final, first leg |
| Colombia | Categoria Primera A (Apertura) | 2024 | Final, leg 2 | 2024-06-16 | Independiente Santa Fe – Atletico Bucaramanga | 3-2 · 5-6 pens · agg 3-3 | final, second leg: level on aggregate, penalties |
| Colombia | Categoria Primera A (Finalizacion) | 2026 | Regular Season, matchday 12 | 2026-09-26 | Deportivo Pereira – Internacional de Bogota | 0-0 |  |
| Ecuador | LigaPro Serie A | 2026 | Regular Season, matchday 30 | 2026-09-13 | Club Atletico Libertad – Independiente del Valle | 2-3 |  |
| Mexico | Liga MX (Apertura) | 2025/26 | Final, leg 1 | 2025-12-12 | Tigres UANL – Toluca | 1-0 | Liga MX Apertura 2025 final, first leg |
| Mexico | Liga MX (Apertura) | 2025/26 | Final, leg 2 | 2025-12-15 | Toluca – Tigres UANL | 2-1 · 2-1 aet · 9-8 pens · agg 2-2 | final, second leg: extra time, then penalties 9-8 |
| Mexico | Liga MX (Apertura) | 2026/27 | Regular Season, matchday 9 | 2026-09-21 | Pachuca – Tijuana | 2-2 |  |
| USA | Major League Soccer | 2021 | Regular Season | 2021-04-17 | CF Montreal – Toronto FC | 4-2 | two Canadian clubs in Fort Lauderdale, 2021: Neutral_Venue 1 |
| USA | Major League Soccer | 2025 | Round of 16, game 1 | 2025-10-28 | Minnesota United – Seattle Sounders | 0-0 · 3-2 pens | best-of-three, game 1: a draw goes straight to penalties |
| USA | Major League Soccer | 2025 | Round of 16, game 2 | 2025-11-04 | Seattle Sounders – Minnesota United | 4-2 | best-of-three, game 2 |
| USA | Major League Soccer | 2025 | Round of 16, game 3 | 2025-11-08 | Minnesota United – Seattle Sounders | 3-3 · 7-6 pens | best-of-three, game 3: shown quote by quote below |
| USA | Major League Soccer | 2026 | Regular Season | 2026-09-27 | Vancouver Whitecaps – DC United | 3-3 |  |
| Venezuela | Liga FUTVE (Clausura) | 2026 | Regular Season, matchday 9 | 2026-09-12 | Deportivo La Guaira – UCV | 0-2 | no lineups in the source for this league |

The top division of Argentina, Bolivia, Brazil, Chile, Colombia, Ecuador, Mexico, USA and Venezuela (Major League Soccer, with its Canadian clubs):
96 league-seasons and 143 editions (Apertura, Clausura, Finalizacion, Copa de la Liga...) in the full product, with season,
tournament, stage (regular season, groups, play-in, round of 16 to final, play-offs), matchday and leg on every
match. `Americas_Coverage.csv` (in this sample too) gives the coverage of the full product, league by league and
season by season.

---

## Book coverage (full product)

Coverage is not uniform. Here is what each book actually priced.

| Book | Quotes | Matches with a FT 1X2 close | First FT 1X2 close | Closing prices on |
|---|---:|---:|---|---|
| Bet365 | 53,681,928 | 30,893 (99.7 %) | 2016-08-28 | all 8 markets |
| Pinnacle | 2,566,889 | 23,110 (74.6 %) | 2018-09-27 | 1X2, Asian handicap, total goals |
| Unibet | 5,036,170 | 28,000 (90.3 %) | 2017-04-15 | 1X2, total goals |
| Betfair (Sportsbook) | 10,750,348 | 5,857 (18.9 %) | 2023-11-03 | 1X2 |
| Betsson | 1,645,206 | 12,582 (40.6 %) | 2022-07-03 | 1X2, total goals |

Split: **58,887,358 in-play** (79.9 %) · **14,793,183 pre-match** (20.1 %).

Markets: full-time 1X2, Asian handicap, total goals and total corners, and the same four for the
first half. Bookmakers are always named, never aggregated. The 37 other bookmakers are in
`Bookmaker_Snapshots`: their first and last pre-match snapshot, each with its time.

### Coverage over time

A bookmaker, or a table, is not in the source for the whole period. Computed month by month on the full product:

| Source | From | Gaps (months when fewer than half of the matches have it) | Stops for |
|---|---|---|---|
| Bet365 | 2016-08-28 | none | - |
| Pinnacle | 2018-09-27 | 2023-09 to 2023-11, 2026-07 to 2026-08 | - |
| Unibet | 2017-04-15 | 2026-07 to 2026-08 | - |
| Betfair (Sportsbook) | 2023-11-03 | 2024-11 to 2025-08, 2026-07 to 2026-08 | - |
| Betsson | 2022-07-03 | 2025-12, 2026-07 to 2026-08 | - |
| Minute-by-minute statistics | 2017-06-10 | 2018-02 to 2019-09, 2026-07 | - |
| Events | 2016-08-28 | none | - |

Bookmakers: a FT 1X2 closing price, counted on the matches for which the bookmaker was collected. A gap is a
calendar month (with at least 100 matches) in which fewer than half of the matches have it. The same table is in
the README, and the notebook recomputes it from the files.

---

## Said plainly

Stated up front rather than discovered after paying.

- **Not collected:** Betfair and Betsson for Argentina 2016/17 to 2019/20 (1,422 matches) and for
  the 2020 MLS is Back tournament (51 matches).
- **No lineups for Bolivia and Venezuela** in the source. The odds, the match sheet, the events and the
  statistics are there.
- **Gaps in time:** Pinnacle 2023-09 to 2023-11 and 2026-07 to 2026-08; Unibet 2026-07 to 2026-08; Betfair (Sportsbook) 2024-11 to 2025-08 and 2026-07 to 2026-08; Betsson 2025-12 and 2026-07 to 2026-08; minute-by-minute statistics 2018-02 to 2019-09 and 2026-07. In July and August 2026, Bet365 is the only book with near-full coverage.
- **`Kickoff_UTC` is the scheduled kickoff.** MLS matches start a few minutes later: on 4,405 of the 4,589
  MLS matches, Bet365's live clock puts the real start 5 to 30 minutes after it. Quotes recorded in between are
  In-play (no score yet) and the closing price is the last quote before the scheduled time: never an in-play
  price. For 7 matches the source's kickoff is more than 3 hours later than the real start: pre-match is cut at the real start.
- **Score and clock on in-play quotes are the bookmaker's own:** 93.7 % of in-play quotes carry both
  (Bet365 98.8 %, Unibet 99.4 %, Betsson 98.9 %). Pinnacle almost never sends a numeric
  clock (34 of its 211,125 in-play quotes),
  Betfair a full score on 22.1 % of its in-play quotes; nothing is filled in from another book.
- **Minute-by-minute statistics have no recording time before 2021-05-11:** `Timestamp_UTC` and `Epoch` are
  empty on the 5,535 matches played before (25.2 % of the rows); `Minute` and `Value` are always there.
- **A closing quote is the last pre-match price recorded.** Median gap to kickoff on FT 1X2: Pinnacle 4 min, Betfair 5 min, Betsson 11 min, Bet365 25 min, Unibet 1.7 h.
  That is why every book has its own closing time.
- **The other bookmakers' table is a dated snapshot, not a closing price:** the source keeps three
  snapshots per book (first price, around kickoff, last price). Check `Minutes_Before_Kickoff`.
- **Some knockout matches are missing from the source** (Colombia's 2018 knockout phases, for example):
  7 ties have only their second leg and 5 only their first. Every gap is listed in `sample/README.md`.
- **Data starts on 2016-08-28:** the first season of each league is partial (its first matchdays
  are missing); Chile starts with its 2018 season. The current seasons stop at 2026-09-30.
- **50 source events were removed** (duplicate ids, results awarded or changed by the federation,
  the abandoned first attempt of replayed matches, resumption ids of interrupted matches, lower-division matches
  filed with the league...), each listed with its evidence in `sample/README.md`. 4 matches the source flags as
  decided by the federation are kept: their score is the one played on the pitch.
- **Odds are UTC and come from one provider.** No cross-provider reconciliation is claimed.

---

## What in-play looks like, in this sample

Minnesota United 3-3 Seattle Sounders, MLS Round One, game 3 of the best-of-three series (`Stage` Round of 16,
`Leg` 3), 8 November 2025. Seattle led 2-0 after 8 minutes. Minnesota pulled one back from a free kick, played
the second half with ten men (red card at 41'), went 3-2 up with two headers, conceded the 3-3 at 88' and won
the shoot-out 7-6 after 10 rounds. Bet365 full-time 1X2, in-play, around each goal. Every row is in
`sample/odds_timestamped/Americas_Odds_Timestamped_USA.csv.gz`.

| Timestamp (UTC) | Min | Score | Minnesota United | Draw | Seattle Sounders |
|---|---:|---|---:|---:|---:|
| 2025-11-08T21:03:25Z |  | – | 3.1 | 3.4 | 2.25 |
| 2025-11-08T21:16:08Z | 3 | 0-0 | 3.1 | 3.4 | 2.3 |
| 2025-11-08T21:16:51Z | 3 | 0-0 | 3.1 | 3.25 | 2.3 |
| 2025-11-08T21:18:03Z | 5 | 0-1 | suspended | | |
| 2025-11-08T21:19:17Z | 6 | 0-1 | 6 | 4.333 | 1.5 |
| 2025-11-08T21:20:43Z | 7 | 0-2 | suspended | | |
| 2025-11-08T21:20:57Z | 8 | 0-1 | 6 | 4.333 | 1.5 |
| 2025-11-08T21:21:02Z | 8 | 0-2 | suspended | | |
| 2025-11-08T21:32:03Z | 19 | 0-2 | 19 | 8 | 1.125 |
| 2025-11-08T21:32:10Z | 19 | 1-2 | 8 | 4.5 | 1.4 |
| 2025-11-08T22:37:42Z | 61 | 1-2 | suspended | | |
| 2025-11-08T22:39:09Z | 62 | 2-2 | 10 | 2.2 | 2 |
| 2025-11-08T22:47:05Z | 70 | 2-2 | suspended | | |
| 2025-11-08T22:48:49Z | 72 | 3-2 | 1.5 | 3.25 | 11 |
| 2025-11-08T23:03:24Z | 86 | 3-2 | suspended | | |
| 2025-11-08T23:05:26Z | 88 | 3-3 | 13 | 1.285 | 4.75 |

The first row is In-play although it has no score and no clock: the match was scheduled at 21:00 UTC and Bet365's
clock puts the real kickoff at about 21:13, so the quotes in between are In-play and the closing price is the last
quote before 21:00. Around the second goal, the score sent with the quotes goes back to 0-1 for a few seconds.
Quotes are delivered as the bookmaker sent them, never smoothed: a suspended market is an empty price with
`Suspended` = 1.

255 in-play Bet365 1X2 quotes on this match alone, 2,991 quotes from
the 5 books in all, and the lineups, the events (the 20 shoot-out kicks included), the team statistics and the
minute-by-minute statistics of the same match in the other tables.

```python
import pandas as pd

o = pd.read_csv("sample/odds_timestamped/Americas_Odds_Timestamped_USA.csv.gz", dtype={"Match_ID": str})
live = o[(o.Match_ID == "10862382") & (o.Book == "Bet365") &
         (o.Market == "FT_1X2") & (o.Phase == "In-play")]
print(live[["Timestamp_UTC", "Minute", "Score_Home", "Score_Away",
            "Price_Home", "Price_Draw", "Price_Away", "Suspended"]].to_string())
```

---

## Eight tables, one key

Everything joins on `Match_ID`. No fuzzy name matching.

| File | One row per | Key content |
|---|---|---|
| `Americas_Matches.csv` / `.xlsx` | match | season, tournament, stage, matchday, leg, kickoff, scores HT / 90' / AET / penalties, aggregate, table positions, formations, managers, referee, venue, neutral-venue flag |
| `Americas_Opening_Closing_Odds.csv` / `.xlsx` | match | open and close per book and market, each with its time |
| `odds_timestamped/` (9 × `.csv.gz`) | price update | book, market, phase, prices, line, score, clock, suspension, UTC, epoch |
| `bookmaker_snapshots/` (9 × `.csv.gz`) | snapshot | 37 more books: first and last pre-match snapshot, with minutes before kickoff |
| `Americas_Team_Stats.csv` / `.xlsx` | match × team | 29 metrics incl. xG |
| `lineups/` (9 × `.csv.gz`) | player × match | starters, subs, shirt, position |
| `events/` (9 × `.csv.gz`) | event | 13 event types with minute and player, shoot-out kicks included |
| `minute_stats/` (9 × `.csv.gz`) | stat × minute | running stats minute by minute |

Plus `Americas_Coverage.csv` / `.xlsx`: one row per league and season, coverage of every table and book in %.

The complete column dictionary, the seasons, tournaments and stages of every league, the coverage tables and the
integrity notes are in `sample/README.md`, the README shipped with the product.

**Nothing a spreadsheet can reinterpret.** Scores, minutes and shoot-outs are separate integer
columns. Timestamps are full ISO 8601 with the T and the Z, plus an epoch. Formations are digits
(4231 = 4-2-3-1), so 4-4-2 never becomes 4 April 2002. Seasons read 2016/17 or 2019. Every cell
was audited against Excel auto-conversion patterns at write time: zero risky cells. A closing price
is never an in-play price.

---

## Licence

Sample: free to explore and evaluate.
Full product: single commercial user. Research, modelling and internal use permitted.
Redistribution and resale of the files are not.

A question before buying: contact@oliviersportsdata.com

---

👉 ⚽ **[→ Get the full dataset on Gumroad](https://sportsdataolivier.gumroad.com/l/diswpw?utm_source=github&utm_medium=repo&utm_campaign=americas_premium&utm_content=readme_bottom)** 👈

---

*Olivier Sports Data — From Chicken Area 🐔*
Hand-built historical sports market data.
