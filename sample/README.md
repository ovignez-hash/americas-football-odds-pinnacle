# FREE SAMPLE - 20 matches

This sample is an exact copy of the full product: same files, same columns, same formats. Only the number of matches differs: a recent match of each of the 9 leagues (September 2026, the most complete of the league's last matchdays), plus 11 matches chosen for what they show (the Liga MX final of December 2025, a full MLS best-of-three series, the Colombian final of June 2024, a Superclasico, the Argentine final of December 2025, two Canadian clubs playing in a US stadium, a match whose kickoff time in the source is two days late). `Americas_Coverage.csv` is the full product's coverage table, league by league and season by season.

| Match_ID | Code | Season | Stage | Kickoff_UTC (date) | Match | Result |
|---|---|---|---|---|---|---|
| 8112197 | ARG | 2024 | Quarter-finals | 2024-04-21 | River Plate - Boca Juniors | 2-3 |
| 9305011 | ARG | 2025 | Group Stage | 2025-03-04 | Platense - Defensa y Justicia | 0-1 |
| 11103267 | ARG | 2025 | Final | 2025-12-14 | Racing Club - Estudiantes LP | 1-1 · 1-1 aet · 4-5 pens |
| 12322444 | ARG | 2026 | Group Stage | 2026-09-15 | Instituto AC Cordoba - Estudiantes Rio Cuarto | 2-1 |
| 12371604 | BOL | 2026 | Regular Season | 2026-09-12 | Real Potosi - Oriente Petrolero | 2-1 |
| 13053529 | BRA | 2026 | Regular Season | 2026-09-14 | EC Bahia - Remo | 2-1 |
| 11255767 | CHI | 2026 | Regular Season | 2026-09-13 | Colo Colo - Deportes Concepcion | 1-1 |
| 8296447 | COL | 2024 | Final | 2024-06-09 | Atletico Bucaramanga - Independiente Santa Fe | 1-0 |
| 8299369 | COL | 2024 | Final | 2024-06-16 | Independiente Santa Fe - Atletico Bucaramanga | 3-2 · 5-6 pens · agg 3-3 |
| 12099983 | COL | 2026 | Regular Season | 2026-09-26 | Deportivo Pereira - Internacional de Bogota | 0-0 |
| 13090163 | ECU | 2026 | Regular Season | 2026-09-13 | Club Atletico Libertad - Independiente del Valle | 2-3 |
| 11095671 | MEX | 2025/26 | Final | 2025-12-12 | Tigres UANL - Toluca | 1-0 |
| 11096108 | MEX | 2025/26 | Final | 2025-12-15 | Toluca - Tigres UANL | 2-1 · 2-1 aet · 9-8 pens · agg 2-2 |
| 12027338 | MEX | 2026/27 | Regular Season | 2026-09-21 | Pachuca - Tijuana | 2-2 |
| 3426544 | USA | 2021 | Regular Season | 2021-04-17 | CF Montreal - Toronto FC | 4-2 |
| 10862076 | USA | 2025 | Round of 16 | 2025-10-28 | Minnesota United - Seattle Sounders | 0-0 · 3-2 pens |
| 10862385 | USA | 2025 | Round of 16 | 2025-11-04 | Seattle Sounders - Minnesota United | 4-2 |
| 10862382 | USA | 2025 | Round of 16 | 2025-11-08 | Minnesota United - Seattle Sounders | 3-3 · 7-6 pens |
| 11068601 | USA | 2026 | Regular Season | 2026-09-27 | Vancouver Whitecaps - DC United | 3-3 |
| 13101886 | VEN | 2026 | Regular Season | 2026-09-12 | Deportivo La Guaira - UCV | 0-2 |

Full product (all 30,999 matches): **[→ Get the full dataset on Gumroad](https://sportsdataolivier.gumroad.com/l/diswpw?utm_source=sample_readme&utm_medium=readme&utm_campaign=americas_premium&utm_content=sample_readme)**

Questions: contact@oliviersportsdata.com

---

# Futbol, Futebol & Soccer Premium - 9 Top Flights of the Americas: Odds, In-Play Ticks & Full Match Layer (2016-2026)

30,999 finished matches from the top division of 9 countries of the Americas, 2016-08-28 to 2026-09-30:
Argentina, Bolivia, Brazil, Chile, Colombia, Ecuador, Mexico, USA (Major League Soccer, with its Canadian clubs) and Venezuela. Every recorded price update from 5 named bookmakers, pre-match
and in-play, with the score and the match clock given by the bookmaker on in-play quotes; opening and closing prices
with the exact time of each; dated snapshots from more bookmakers. Season, tournament (Apertura, Clausura, Finalizacion, Copa de la Liga...),
stage (regular season, groups, play-in, round of 16 to final, play-offs), matchday and leg on every match. Match sheet,
team statistics, lineups, events and minute-by-minute statistics. All tables join on `Match_ID`; the columns follow
the same schema as the other league packs.

## At a glance

|  |  |
|---|---|
| Matches | 30,999 (911 in knockout stages, 288 two-legged ties) |
| Leagues | 9 top divisions, 96 league-seasons, 143 editions (a season, or a tournament inside a season) |
| Period | 2016-08-28 to 2026-09-30 (data up to 2026-09-30) |
| Bookmakers (full history) | Bet365, Pinnacle, Unibet, Betfair (Sportsbook), Betsson - always named, never aggregated |
| Markets | FT 1X2, FT Asian handicap, FT total goals, FT total corners, HT 1X2, HT Asian handicap, HT total goals, HT total corners |
| Timestamped price updates | 73,680,541 |
| Other bookmakers' snapshots | 1,781,722 |
| Events | 954,808 |
| Lineup rows | 983,966 |
| Minute-by-minute statistics | 8,353,269 |

## Files

| File | Rows | One row per | Format |
|---|---|---|---|
| Americas_Matches.csv / .xlsx | 30,999 | match | CSV + XLSX |
| Americas_Opening_Closing_Odds.csv / .xlsx | 30,999 | match (opening and closing price + time, per bookmaker and market) | CSV + XLSX |
| Americas_Team_Stats.csv / .xlsx | 61,998 | match x team | CSV + XLSX |
| Americas_Coverage.csv / .xlsx | 96 | league x season (coverage in %) | CSV + XLSX |
| odds_timestamped/Americas_Odds_Timestamped_<CODE>.csv.gz | 73,680,541 | price update (bookmaker x market x time) | 9 gzip CSV |
| bookmaker_snapshots/Americas_Bookmaker_Snapshots_<CODE>.csv.gz | 1,781,722 | snapshot of another bookmaker (match x book x market x snapshot) | 9 gzip CSV |
| events/Americas_Events_<CODE>.csv.gz | 954,808 | match event | 9 gzip CSV |
| lineups/Americas_Lineups_<CODE>.csv.gz | 983,966 | player in a match squad | 9 gzip CSV |
| minute_stats/Americas_Minute_Stats_<CODE>.csv.gz | 8,353,269 | statistic x team x minute | 9 gzip CSV |

Load in pandas: `pd.read_csv("Americas_Matches.csv", dtype={"Season": str, "Match_ID": str})` and
`pd.read_csv("events/Americas_Events_ARG.csv.gz")` (gzip is read directly). Comma-separated, UTF-8 with BOM,
"." decimals. The XLSX workbooks are typed: text stays text, numbers are numbers, header frozen, filters on.

## Leagues and coverage

| Code | Country | League | Matches | Seasons | Lineups | Minute stats | Events | Bet365 close |
|---|---|---|---|---|---|---|---|---|
| ARG | Argentina | Argentine Primera Division | 4,717 | 2016/17 to 2026 (11) | 99 % | 78 % | 100 % | 100 % |
| BOL | Bolivia | Bolivian Primera Division | 2,803 | 2016/17 to 2026 (10) | 0 % | 71 % | 99 % | 100 % |
| BRA | Brazil | Campeonato Brasileiro Serie A | 3,866 | 2016 to 2026 (11) | 100 % | 78 % | 99 % | 100 % |
| CHI | Chile | Chilean Primera Division | 2,147 | 2018 to 2026 (9) | 100 % | 80 % | 100 % | 100 % |
| COL | Colombia | Categoria Primera A | 4,098 | 2016 to 2026 (11) | 87 % | 74 % | 99 % | 100 % |
| ECU | Ecuador | LigaPro Serie A | 2,645 | 2016 to 2026 (11) | 86 % | 73 % | 99 % | 99 % |
| MEX | Mexico | Liga MX | 3,347 | 2016/17 to 2026/27 (11) | 100 % | 73 % | 99 % | 100 % |
| USA | USA | Major League Soccer | 4,589 | 2016 to 2026 (11) | 100 % | 75 % | 99 % | 100 % |
| VEN | Venezuela | Liga FUTVE | 2,787 | 2016 to 2026 (11) | 0 % | 67 % | 98 % | 99 % |
| **Total** |  |  | **30,999** | 96 | 79 % | 75 % | 99 % | 100 % |

Lineups = both starting elevens present. Minute stats = at least one minute-by-minute statistic.
Events = at least one event in the source timeline. Bet365 close = a FT 1X2 closing price from Bet365.

### Coverage by bookmaker (FT 1X2 closing price present)

| Bookmaker | Matches with a FT 1X2 close | Coverage | Markets (closing prices present) |
|---|---|---|---|
| Bet365 | 30,893 | 99.7 % | FT_1X2, FT_Total_Goals, FT_Asian_Handicap, HT_Total_Goals, HT_Total_Corners, HT_1X2, FT_Total_Corners, HT_Asian_Handicap |
| Pinnacle | 23,110 | 74.6 % | FT_Total_Goals, FT_1X2, FT_Asian_Handicap |
| Unibet | 28,000 | 90.3 % | FT_Total_Goals, FT_1X2 |
| Betfair (Sportsbook) | 5,857 | 18.9 % | FT_1X2 |
| Betsson | 12,582 | 40.6 % | FT_1X2, FT_Total_Goals |

### Coverage by league (share of matches with a FT 1X2 closing price)

| League | Matches | Bet365 | Pinnacle | Unibet | Betfair | Betsson |
|---|---|---|---|---|---|---|
| ARG | 4,717 | 100 % | 75 % | 91 % | 20 %* | 46 %* |
| BOL | 2,803 | 100 % | 72 % | 87 % | 16 % | 34 % |
| BRA | 3,866 | 100 % | 73 % | 94 % | 20 % | 39 % |
| CHI | 2,147 | 100 % | 87 % | 98 % | 22 % | 43 % |
| COL | 4,098 | 100 % | 74 % | 91 % | 19 % | 42 % |
| ECU | 2,645 | 99 % | 72 % | 90 % | 18 % | 38 % |
| MEX | 3,347 | 100 % | 74 % | 92 % | 19 % | 40 % |
| USA | 4,589 | 100 % | 76 % | 94 % | 20 %* | 45 %* |
| VEN | 2,787 | 99 % | 70 % | 72 % | 15 % | 31 % |

\* not collected for part of the league's seasons (see *Said plainly*); the share is over all the league's matches.

Season by season: `Americas_Coverage.csv`.

### Coverage over time

| Source | From | Gaps (months when fewer than half of the matches have it) | Stops for |
|---|---|---|---|
| Bet365 | 2016-08-28 | none | - |
| Pinnacle | 2018-09-27 | 2023-09 to 2023-11, 2026-07 to 2026-08 | - |
| Unibet | 2017-04-15 | 2026-07 to 2026-08 | - |
| Betfair (Sportsbook) | 2023-11-03 | 2024-11 to 2025-08, 2026-07 to 2026-08 | - |
| Betsson | 2022-07-03 | 2025-12, 2026-07 to 2026-08 | - |
| Minute-by-minute statistics | 2017-06-10 | 2018-02 to 2019-09, 2026-07 | - |
| Events | 2016-08-28 | none | - |

Bookmakers: a FT 1X2 closing price, counted on the matches for which the bookmaker was collected. A gap is a calendar month (with at least 100 matches) in which fewer than half of the matches have it. *Stops for*: nothing after that date for that league, with at least 100 matches played since. Season by season and league by league: `Americas_Coverage.csv`.

## Seasons, tournaments and stages

Most leagues of the Americas play more than one tournament per season, each with its own knockout phase. `Season`
is `2016/17` for seasons played across two years and `2019` for seasons played within a calendar year; `Tournament`
names the tournament inside the season (empty for a season-long championship); `Stage` uses one generic vocabulary
for every league (column dictionary below). An edition is a season, or a tournament inside a season.

| League | Season form | Tournaments | Stages played (editions) |
|---|---|---|---|
| Argentine Primera Division (ARG) | 2016/17 to 2019/20, then calendar year | Copa Diego Maradona, Copa de la Liga, Liga Profesional, Apertura, Clausura | Regular Season (8), Group Stage (9), Championship Round (1), Qualification Round (1), Round of 16 (3), Quarter-finals (7), Semi-finals (7), Final (8), Play-Offs (2) |
| Bolivian Primera Division (BOL) | 2016/17 (transition), then calendar year | Apertura, Adecuacion, Clausura | Regular Season (13), Group Stage (3), Quarter-finals (3), Semi-finals (3), Third Place (1), Final (5), Play-Offs (8) |
| Campeonato Brasileiro Serie A (BRA) | calendar year | - | Regular Season (11) |
| Chilean Primera Division (CHI) | calendar year | - | Regular Season (9), Play-Offs (1) |
| Categoria Primera A (COL) | calendar year | Finalizacion, Apertura | Regular Season (20), Semi-final Groups (11), Quarter-finals (6), Semi-finals (5), Final (17), Play-Offs (1) |
| LigaPro Serie A (ECU) | calendar year | - | Regular Season (2), First Stage (8), Second Stage (9), Championship Round (2), Qualification Round (2), Relegation Round (2), Quarter-finals (1), Semi-finals (1), Final (7) |
| Liga MX (MEX) | across two years (2016/17) | Apertura, Clausura | Regular Season (21), Play-In (11), Quarter-finals (19), Semi-finals (19), Final (19) |
| Major League Soccer (USA) | calendar year | MLS is Back | Regular Season (11), Group Stage (1), Play-In (10), Round of 16 (5), Quarter-finals (11), Semi-finals (11), Final (11) |
| Liga FUTVE (VEN) | calendar year | Clausura, Apertura | Regular Season (15), First Stage (1), Group Stage (2), Championship Round (3), Qualification Round (2), Semi-final Groups (5), Quarter-finals (7), Semi-finals (7), Third Place (1), Final (19) |

### Season notes

Formats, interruptions and gaps of the source, edition by edition:

| League | Season | Tournament | Note |
|---|---|---|---|
| ARG | 2016/17 | - | 30 teams, one league phase (30 rounds); data from 2016-08-28 (the start of the tournament is missing from the source) |
| ARG | 2020 | Copa Diego Maradona | 6 groups of 4 (home and away), then 2 zones of 6 for the title (Championship Round) and 2 zones of 6 of the Complementacion (Qualification Round); final Boca Juniors - Banfield |
| ARG | 2020 | Copa Diego Maradona | Rosario Central - Velez Sarsfield (2021-01-17, winners of the Complementacion zones): Play-Offs |
| ARG | 2021 | Copa de la Liga | 2 zones of 13 plus an inter-zone round (Group Stage), then quarter-finals, semi-finals and final as single matches |
| ARG | 2022 | Copa de la Liga | 2 zones of 14 plus an inter-zone round (Group Stage), then quarter-finals, semi-finals and final as single matches |
| ARG | 2023 | Copa de la Liga | 2 zones of 14 plus an inter-zone round (Group Stage), then quarter-finals, semi-finals and final as single matches |
| ARG | 2023 | - | Colon - Gimnasia LP (2023-12-01): relegation decider (table of points averages) |
| ARG | 2024 | Copa de la Liga | 2 zones of 14 plus an inter-zone round (Group Stage), then quarter-finals, semi-finals and final as single matches |
| ARG | 2025 | Apertura | 2 zones of 15 plus inter-zone matches (Group Stage), then round of 16, quarter-finals, semi-finals and final as single matches |
| ARG | 2025 | Clausura | 2 zones of 15 plus inter-zone matches (Group Stage), then round of 16, quarter-finals, semi-finals and final as single matches |
| ARG | 2026 | Apertura | 2 zones of 15 plus inter-zone matches (Group Stage), then round of 16, quarter-finals, semi-finals and final as single matches |
| ARG | 2026 | Clausura | in progress on 2026-09-30 |
| BOL | 2016/17 | Apertura | 12 teams, 22 rounds; title decider The Strongest - Bolivar (2016-12-24); data from 2016-08-28 (the start of the tournament is missing from the source) |
| BOL | 2016/17 | Adecuacion | transition tournament to calendar-year seasons (January to June 2017), 22 rounds |
| BOL | 2016/17 | - | relegation play-offs of December 2017 (aggregate table of the three tournaments) |
| BOL | 2018 | Apertura | 2 groups of 7 (Group Stage); title bracket: quarter-finals, semi-finals, third place, final and a deciding match; bracket for Copa Sudamericana places (5th to 7th of each group): Play-Offs |
| BOL | 2018 | - | relegation play-off Destroyers - Aviles Industrial (December 2018) |
| BOL | 2020 | - | single tournament (14 teams, 26 rounds), stopped from March to November (Covid-19), ended on 2020-12-31 |
| BOL | 2021 | - | single tournament (16 teams, 30 rounds); promotion-relegation play-off Real Potosi - Universitario: Play-Offs |
| BOL | 2022 | Apertura | 2 groups of 8 (including 2 inter-group rounds) (Group Stage), then quarter-finals, semi-finals, final |
| BOL | 2022 | Clausura | abandoned after 24 rounds (unrest), no title awarded |
| BOL | 2022 | - | promotion-relegation play-off Libertad Gran Mamore - Universitario (November 2022) |
| BOL | 2023 | - | single tournament (17 teams, 34 rounds); play-off San Antonio Bulo Bulo - Libertad Gran Mamore: Play-Offs |
| BOL | 2024 | Apertura | 4 groups of 4 (8 matches per team) (Group Stage), then quarter-finals, semi-finals, final |
| BOL | 2024 | Clausura | 16 teams, 30 rounds |
| BOL | 2024 | - | play-off Royal Pari - Real Oruro: first leg only (2024-12-21); the second leg is missing from the source |
| BOL | 2024 | - | season final San Antonio Bulo Bulo - Bolivar (2024-12-22, winners of the Apertura and the Clausura) |
| BOL | 2025 | - | single tournament (16 teams, 30 rounds); play-off Integracion del Norte - ABB: Play-Offs |
| BOL | 2026 | - | in progress on 2026-09-30 |
| BRA | 2016 | - | data from 2016-08-28 (the start of the tournament is missing from the source) (rounds 18 to 38) |
| BRA | 2020 | - | Covid-19 season: August 2020 to February 2021 |
| BRA | 2026 | - | in progress on 2026-09-30 |
| CHI | 2019 | - | season stopped after round 24 (social unrest); 2 matches of round 26 played on 2019-11-22 |
| CHI | 2020 | - | season until 2021-02-17; Colo-Colo - Universidad de Concepcion (2021-02-17): relegation decider (Play-Offs) |
| CHI | 2026 | - | in progress on 2026-09-30 |
| COL | 2016 | Finalizacion | data from 2016-08-28 (the start of the tournament is missing from the source) |
| COL | 2017 | Apertura | knockout phase incomplete in the source (3 quarter-final first legs and the final's second leg) |
| COL | 2017 | Finalizacion | second legs only for the quarter-finals; their first legs are missing from the source |
| COL | 2018 | Apertura | knockout phase (quarter-finals, semi-finals, final) missing from the source |
| COL | 2018 | Finalizacion | knockout phase (quarter-finals, semi-finals, final) missing from the source |
| COL | 2019 | Apertura | two groups of four (Semi-final Groups), the group winners play the final |
| COL | 2019 | Finalizacion | two groups of four (Semi-final Groups), the group winners play the final |
| COL | 2020 | - | single tournament (stopped in March, resumed in September): 20 rounds, quarter-finals, semi-finals, final; tournament of the 12 teams not qualified, for a Copa Sudamericana place (groups, semi-finals, final, deciding match): Play-Offs |
| COL | 2021 | Apertura | quarter-final Deportes Tolima - Deportivo Cali: second leg played on 2021-06-04, 40 days after the first (postponed during the national strike) |
| COL | 2021 | Finalizacion | two groups of four (Semi-final Groups), the group winners play the final |
| COL | 2022 | Apertura | two groups of four (Semi-final Groups), the group winners play the final |
| COL | 2022 | Finalizacion | two groups of four (Semi-final Groups), the group winners play the final |
| COL | 2023 | Apertura | two groups of four (Semi-final Groups), the group winners play the final |
| COL | 2023 | Finalizacion | two groups of four (Semi-final Groups), the group winners play the final |
| COL | 2024 | Apertura | two groups of four (Semi-final Groups), the group winners play the final |
| COL | 2024 | Finalizacion | two groups of four (Semi-final Groups), the group winners play the final |
| COL | 2025 | Apertura | two groups of four (Semi-final Groups), the group winners play the final |
| COL | 2025 | Finalizacion | two groups of four (Semi-final Groups), the group winners play the final |
| COL | 2026 | Finalizacion | in progress on 2026-09-30 |
| ECU | 2016 | - | second stage only (data from 2016-08-28 (the start of the tournament is missing from the source)) |
| ECU | 2018 | - | final between the stage winners missing from the source |
| ECU | 2019 | - | two stages of 15 rounds, then quarter-finals, semi-finals, final |
| ECU | 2025 | - | 30 rounds, then a group of six for the title (Championship Round), a group of six for places 7 to 12 (Qualification Round) and a group of four for relegation (Relegation Round) |
| ECU | 2026 | - | same format as 2025; second phase in progress on 2026-09-30 |
| MEX | 2016/17 | Apertura | data from 2016-08-28 (the start of the tournament is missing from the source) (rounds 7 to 17) |
| MEX | 2018/19 | Apertura | second legs only for the semi-finals; their first legs (2018-12-06) are missing from the source |
| MEX | 2019/20 | Clausura | stopped after round 10 (Covid-19), no knockout phase |
| MEX | 2026/27 | Apertura | in progress on 2026-09-30 |
| USA | 2016 | - | data from 2016-08-28 (the start of the tournament is missing from the source) |
| USA | 2020 | - | Covid-19 season: 2 rounds in February-March, resumed in August; unequal number of matches between teams |
| USA | 2020 | MLS is Back | July-August 2020 tournament: 6 groups (Group Stage), round of 16, quarter-finals, semi-finals, final |
| USA | 2026 | - | regular season in progress on 2026-09-30 |
| VEN | 2016 | Clausura | data from 2016-08-28 (the start of the tournament is missing from the source) |
| VEN | 2016 | - | season final Zamora - Zulia (winners of the Apertura and the Clausura): first leg only (2016-12-04); the second leg in Maracaibo is missing from the source |
| VEN | 2017 | Clausura | 8 regular-season matches missing from the source |
| VEN | 2018 | - | season final (winners of the Apertura and the Clausura) |
| VEN | 2019 | - | season final (winners of the Apertura and the Clausura) |
| VEN | 2020 | - | first phase (January-March) annulled by the federation (Covid-19): First Stage; resumed in October: 2 groups (Group Stage), final and third-place match on 2020-12-15 |
| VEN | 2021 | - | 3 groups of 7 (4 matches per pair) (Group Stage), group of six for the title (Championship Round), group of the 3rd and 4th placed teams (Qualification Round) |
| VEN | 2021 | - | final of 2021-12-11 missing from the source |
| VEN | 2022 | - | 30 rounds; places 1 to 4 (Championship Round), places 5 to 12 in 2 groups of 4 (Qualification Round); final |
| VEN | 2023 | - | 28 rounds; places 1 to 4 (Championship Round); final |
| VEN | 2024 | Apertura | 14 teams, one round-robin, then 2 groups of 4 (Semi-final Groups), final |
| VEN | 2024 | Clausura | 14 teams, one round-robin, then 2 groups of 4 (Semi-final Groups), final |
| VEN | 2024 | - | season final Deportivo Tachira - Carabobo (winners of the Clausura and the Apertura), two legs |
| VEN | 2025 | Apertura | 14 teams, one round-robin, then 2 groups of 4 (Semi-final Groups), final |
| VEN | 2025 | Clausura | 14 teams, one round-robin, then 2 groups of 4 (Semi-final Groups), final |
| VEN | 2026 | Apertura | 14 teams, one round-robin, then 2 groups of 4 (Semi-final Groups), final |
| VEN | 2026 | Clausura | 14 teams, one round-robin, then 2 groups of 4 (Semi-final Groups), final |
| VEN | 2026 | Clausura | in progress on 2026-09-30 |

## Other bookmakers: snapshots, not closing prices

`Americas_Bookmaker_Snapshots_<CODE>` adds 37 more bookmakers (1,781,722 rows,
29,947 matches, 14.3 bookmakers per match on average). The source keeps only three snapshots per bookmaker and market
(the first price, one around kickoff, the last one): this table delivers the first price when it is pre-match (`Open`)
and the latest snapshot that is still pre-match (`Last_Pre_Match`: no score, no match clock, taken before the
scheduled kickoff). **It is a dated snapshot, not a closing price**: check `Minutes_Before_Kickoff` before comparing.

| Market | Last_Pre_Match rows | Median minutes before kickoff | Within 60 minutes | More than 24 hours before |
|---|---|---|---|---|
| FT_1X2 | 418,120 | 141 | 44 % | 26 % |
| FT_Asian_Handicap | 185,593 | 308 | 42 % | 31 % |
| FT_Total_Goals | 287,260 | 216 | 41 % | 31 % |

The 5 bookmakers of the main tables are not repeated here (their full histories are in `Odds_Timestamped`).
Prediction markets that the source lists with probabilities instead of odds (Polymarket, Kalshi) are left out.

## Column dictionary

### Americas_Matches

| Column | Meaning |
|---|---|
| `Match_ID` | Source event id (text). The key shared by every table. |
| `Competition_Code` | Country code of the league: ARG, BOL, BRA, CHI, COL, ECU, MEX, USA, VEN. |
| `Confederation / Country / Competition` | CONMEBOL (South America) or CONCACAF (Mexico, USA); the league's country (USA for Major League Soccer, whose clubs come from the USA and Canada); the league's name (top division). |
| `Team_Type / Division` | Club; division level (1 = top flight). |
| `Season` | 2016/17 form for seasons played across two years (Mexico; Argentina up to 2019/20; Bolivia's 2016/17 transition season), stays text in Excel; a single year for seasons played within a calendar year (2019). A season that ran over into the next year keeps its year (Brazil and Chile 2020). |
| `Tournament` | Name of the tournament inside a season when a league plays more than one: Apertura and Clausura (Mexico, Venezuela, Bolivia, Argentina from 2025), Apertura and Finalizacion (Colombia), Copa de la Liga and Liga Profesional (Argentina 2021 to 2024), Copa Diego Maradona (Argentina 2020), Adecuacion (Bolivia, January to June 2017), MLS is Back (USA, July-August 2020). Empty for a season-long championship, and for matches played between the tournaments of a season (season finals between tournament winners, relegation play-offs). |
| `Stage` | Regular Season: the league phase. First Stage / Second Stage: a season played as two league stages (Ecuador up to 2024; Venezuela's annulled first phase of 2020). Group Stage: a first phase in groups or zones. Championship Round / Qualification Round / Relegation Round: a second phase in groups, for the title / for continental places or lower places / against relegation. Semi-final Groups: two groups of four whose winners play the final (Colombia, Venezuela). Play-In: knockout matches that reduce the field to the main bracket (Liga MX play-in; MLS Knockout Round of 2016 to 2018, single-match Round One of 2019 to 2022, play-in and wild-card matches of 2020 and from 2023). Round of 16, Quarter-finals, Semi-finals, Third Place, Final: the title bracket, with generic names (MLS Round One from 2023 = Round of 16, Conference Semifinals = Quarter-finals, Conference Finals = Semi-finals, MLS Cup = Final; a final between the winners of two tournaments is a Final). Play-Offs: every other knockout match (relegation and promotion play-offs, deciders, ties for continental places). |
| `Round` | Matchday number given by the source, when the source's numbering is reliable for that season and stage; empty otherwise and always empty in knockout stages. |
| `Leg` | Knockout stages only. 1 and 2 in a two-legged tie (home and away reversed; the second leg decides); 3 for a deciding third match after the two legs; in an MLS best-of-three series (Round of 16 from 2023) the game number 1, 2 or 3, each game being decided on the day. Empty for a single match and outside knockout stages. A tie with one leg missing from the source shows the other leg alone (`Leg` 1 or 2; see Data integrity). |
| `Kickoff_UTC / Kickoff_Epoch` | Scheduled kickoff, ISO 8601 UTC and Unix seconds. |
| `Home_Team_ID / Home_Team / Home_Team_Country (Away_...)` | Source team id (text), team name, team country as the source's 2-letter code (ca for the Canadian MLS clubs). |
| `Home_Goals_HT / Away_Goals_HT` | Half-time score. |
| `Home_Goals_90 / Away_Goals_90` | Score after 90 minutes plus added time: the score 1X2, handicap and total markets settle on. |
| `Result_90` | H, D or A after 90 minutes. |
| `Extra_Time / Home_Goals_AET / Away_Goals_AET` | 1 when extra time was played; then the score after extra time (cumulative). |
| `Penalty_Shootout / Home_Penalties / Away_Penalties` | 1 when the match ended with a penalty shoot-out; then the shoot-out score. |
| `Home_Aggregate / Away_Aggregate` | Aggregate score of a two-legged tie, when the source gives it. |
| `Home_Table_Position / Away_Table_Position` | League positions given by the source for the match. |
| `Home_Formation / Away_Formation` | Formation as digits: 4231 = 4-2-3-1, 442 = 4-4-2. |
| `Home_Manager / Away_Manager / Referee / Referee_Country` | Names as given; country as a 2-letter code. |
| `Stadium / Stadium_City / Stadium_Country / Stadium_Capacity` | Venue as given by the source (a few restored, see Data integrity). |
| `Stadium_Latitude / Stadium_Longitude` | Venue coordinates (decimal degrees). |
| `Neutral_Venue` | 1 when the stadium's country is not the home team's country, 0 when it is, empty when one of the two is unknown (rule below). |
| `Has_Lineups / Has_Minute_Stats / Has_Match_Stats` | 1 when the tables hold both starting elevens / minute-by-minute statistics / team statistics. |

### Americas_Opening_Closing_Odds

| Column | Meaning |
|---|---|
| `Match_ID ... Neutral_Venue` | Identity and result of the match, copied from Americas_Matches so the file stands alone. |
| `{Book}_{Market}_Open_*` | Opening: first valid pre-match quote of that bookmaker and market (no suspended, empty, out-of-range or unreadable price; valid line for handicaps and totals). |
| `{Book}_{Market}_Close_*` | Closing: last valid pre-match quote. Never an in-play quote. |
| `*_Home / *_Draw / *_Away` | 1X2: home win, draw, away win. Asian handicap: home side and away side. |
| `*_Line` | Handicap line of the HOME team, or total line, as a decimal; split lines averaged (0.0,-0.5 -> -0.25). |
| `*_Over / *_Under` | Over and Under the line. |
| `*_Open_Time / *_Close_Time` | Time of the opening / closing quote, ISO 8601 UTC. |
| `Empty cells` | No valid pre-match quote for that bookmaker and market on that match. |

### Americas_Coverage

| Column | Meaning |
|---|---|
| `Competition_Code / Country / Competition / Season` | One row per league and season. |
| `Matches` | Matches delivered for that season. |
| `Lineups_Pct / Minute_Stats_Pct / Match_Stats_Pct / Events_Pct` | Share of those matches (%) with both starting elevens / minute-by-minute statistics / team statistics / at least one event. |
| `Bet365_Pct ... Betsson_Pct` | Share of matches (%) with a FT 1X2 closing price from that bookmaker; empty when the bookmaker was not collected for that season (see the limitations). |
| `Snapshots_Pct` | Share of matches (%) with at least one snapshot of another bookmaker. |

### Americas_Team_Stats

| Column | Meaning |
|---|---|
| `Match_ID / Side / Team_ID / Team` | Two rows per match: Home and Away. |
| `Goals ... Action_Areas` | Full-match totals as given by the source (29 statistics, including Possession_Pct, Shots_On_Target, Dangerous_Attacks, Corners, Corners_HT, Yellow_Cards, Red_Cards, xG). Empty when the source does not give that statistic for the match. After extra time the totals include it (Goals = score after extra time; shoot-outs excluded). |

### Americas_Odds_Timestamped_<CODE>

| Column | Meaning |
|---|---|
| `Match_ID` | Source event id (text). |
| `Book` | Bet365, Pinnacle, Unibet, Betfair, Betsson (Betfair = the Betfair Sportsbook, not the exchange). |
| `Market` | FT_1X2, FT_Asian_Handicap, FT_Total_Goals, FT_Total_Corners, HT_1X2, HT_Asian_Handicap, HT_Total_Goals, HT_Total_Corners (HT = first half). |
| `Phase` | Pre-match or In-play (rule below). |
| `Timestamp_UTC / Epoch` | Time the price was recorded, ISO 8601 UTC and Unix seconds. |
| `Minute / Second` | Match clock given by the bookmaker at that quote (integers). Unibet and Betsson give mm:ss. Empty when the bookmaker gives no numeric clock (Pinnacle almost never does) and on pre-match quotes, where Bet365 sometimes sends minute 0 just before kickoff. |
| `Score_Home / Score_Away` | Score at that quote (integers); empty pre-match and when the bookmaker sends a partial score (Betfair often does). |
| `Corners_Home / Corners_Away` | Corner count at that quote, corner markets only. |
| `Line` | Handicap line of the HOME team, or total line (decimal). Empty for 1X2. |
| `Price_Home / Price_Draw / Price_Away / Price_Over / Price_Under` | Decimal prices. Empty when suspended, absent, out of range or unreadable. |
| `Suspended` | 1 when the bookmaker showed the market suspended at that quote, else 0. |

### Americas_Bookmaker_Snapshots_<CODE>

| Column | Meaning |
|---|---|
| `Match_ID` | Source event id (text). The key shared by every table. |
| `Book` | Bookmaker name exactly as the source spells it. The product's 5 books (Bet365, Pinnacle, Unibet, Betfair, Betsson) are not repeated here: their full price histories are in Odds_Timestamped. |
| `Market` | FT_1X2, FT_Asian_Handicap, FT_Total_Goals (full time). |
| `Snapshot` | Open = the first price the source kept for that book, when it is pre-match. Last_Pre_Match = the latest of the source's three snapshots (first price, around kickoff, last price) that is still pre-match; it can be the same tick as Open. NOT a guaranteed closing price: see Minutes_Before_Kickoff. |
| `Timestamp_UTC` | Time of the snapshot, ISO 8601 UTC. |
| `Epoch` | Same instant, Unix seconds. |
| `Minutes_Before_Kickoff` | Whole minutes between the snapshot and the scheduled kickoff (always >= 0). |
| `Line` | Handicap (home team's line) or total line, decimal; split lines averaged. Empty for 1X2. |
| `Price_Home` | Decimal price, home win (1X2) or home handicap side (AH). |
| `Price_Draw` | Decimal price of the draw (1X2 only). |
| `Price_Away` | Decimal price, away win (1X2) or away handicap side (AH). |
| `Price_Over` | Decimal price of Over the line (FT_Total_Goals). |
| `Price_Under` | Decimal price of Under the line (FT_Total_Goals). |

### Americas_Events_<CODE>

| Column | Meaning |
|---|---|
| `Match_ID / Event_Order` | Source event id; position of the event in the source timeline (gaps = summary lines not delivered). |
| `Minute / Added_Time` | Match minute and added time (90+3 -> 90 and 3), integers. |
| `Event_Type` | Goal, Assist, Yellow Card, Red Card, Substitution, Corner, Shot On Target, Shot Off Target, Offside, Race To Corners, Missed Penalty, Penalty Shootout Scored, Penalty Shootout Missed. |
| `Type_Ordinal` | The source's match-wide count for that event type (1st, 2nd...); a team's kick number in a shoot-out. |
| `Team_Side / Team` | Home or Away, and the team name as written in the event. |
| `Player / Player_2` | Substitution: player on / player off. Goal: scorer / assist provider. |
| `Race_Target` | N in 'Race to N corners'. |
| `Detail` | Goal type: Shot, Header, Penalty, Own Goal, Free Kick. |
| `Extra_Time` | 1 when the source tags the event 'ET'. The tag marks extra time, but the source also puts it on some events of second-half added time: use Minute / Added_Time to tell them apart. |

### Americas_Lineups_<CODE>

| Column | Meaning |
|---|---|
| `Match_ID / Side / Team_ID / Team` | Match and team. |
| `Starter` | 1 = starting eleven, 0 = substitute. |
| `Lineup_Order` | Order in the source's team sheet. |
| `Player_ID / Player / Player_Country` | Source player id (text), name, 2-letter country code. |
| `Shirt_Number` | Shirt number. |
| `Position / Position_Group` | Position as given (Goalkeeper, Defender, Midfielder, Forward and detailed roles) and its group. |

### Americas_Minute_Stats_<CODE>

| Column | Meaning |
|---|---|
| `Match_ID / Side / Stat` | Match, team side and statistic (Attacks, Dangerous_Attacks, Possession_Pct, Shots_On_Target, Corners, Goals...). |
| `Minute / Value` | Match minute and the running value at that minute: cumulative count, or running percentage for Possession_Pct, Passing_Accuracy and Crossing_Accuracy. |
| `Timestamp_UTC / Epoch` | Time the value was recorded. Empty on the matches played before 2021-05-11: the source gives no time for them. |

## Rules applied to every cell

- **Times** are ISO 8601 UTC with the T and the Z (`2026-09-20T15:30:00Z`), plus a Unix epoch column.
  Excel and LibreOffice keep this form as text: it is never converted into a local date.
- **No cell that a spreadsheet can rewrite.** Scores, minutes and shoot-outs are separate integer columns
  (never "1-0", "90+2" or "73:02"). Formations are digits: `4231` means 4-2-3-1, `442` means 4-4-2
  ("4-4-2" in a cell becomes 04/04/2002 in French Excel). Handicap lines are decimals (`-0.25`, never "0.0,-0.5").
  Seasons are `2016/17` or `2019`. Leading "-", "+", "=" or "@" are removed from names.
- Every cell of every file was audited against these Excel conversion patterns at write time: **0 risky cells**.
- **Empty cell = absent from the source.** Nothing is imputed, interpolated or averaged across bookmakers.
- A suspended price ("-") is an empty cell with `Suspended = 1`: kept, not deleted.

## Knockout stages, extra time, penalties and neutral venues

- **Knockout stages** (911 matches): Play-In, Round of 16, Quarter-finals, Semi-finals, Third Place, Final
  and Play-Offs. Single matches (262) have an empty `Leg`.
- **Two-legged ties** (288): `Leg` 1 and 2 when two teams meet twice in a knockout stage with home and
  away reversed, at most 21 days apart, without another knockout match between them (or as written in the lexicon:
  see *Legs* in Data integrity); the second leg decides. 1 tie was decided by a third match (`Leg` 3). 7 ties have only their second leg (`Leg` 2) and 5 only their first leg (`Leg` 1): the other leg is missing from the source; `Home_Aggregate` / `Away_Aggregate` are filled only when the source gives them.
- **MLS best-of-three series** (24 series, Round of 16 from 2023): `Leg` is the game number; every game is decided on the day (a draw after 90 minutes goes to penalties, without extra time).
- **Extra time** (43 matches) and **penalty shoot-outs** (116) are recorded only in a deciding
  knockout match (single match, second leg, third match, game of a best-of-three series). Extra_Time = 1 needs proof
  in the source: a goal scored in extra time, an event dated from the 106th minute, or the source's extra-time score
  line. A shoot-out without that proof keeps Extra_Time = 0 (90 of the 116 shoot-outs): several
  of these leagues go straight to penalties after 90 minutes, and extra time may also have been played without a goal
  or an event the source dates beyond the 105th minute.
- **Neutral_Venue** compares the stadium's country with the home team's country code from the source: 1 = neutral
  (38 matches), 0 = home ground country (29,619), empty = unknown (1,342).
  CF Montreal, Toronto FC and Vancouver Whitecaps (Canadian clubs) were the home team in a US stadium on 38 matches: `Neutral_Venue` = 1 (7 in the MLS is Back tournament, 31 in 2020 and 2021 while the border was closed during Covid-19). The MLS is Back tournament (51 matches, July-August 2020) was played in Orlando: a US club's 'home' match there counts as 0, because the rule compares countries, not grounds. A neutral ground inside the home team's own country (finals played at a neutral ground) counts as 0.

## Pre-match, in-play and closing

- A quote is **Pre-match** when it carries no score AND was recorded before the kickoff anchor K. Everything
  else is **In-play**.
- **K** is the scheduled kickoff. When Bet365's live clock (tick time minus its minute, minutes 1 to 15) shows
  that the match started before the scheduled time, K is that start minus 2 minutes. Without a Bet365 live clock,
  K is also bounded by the first quote that carries a score, minus 2 minutes. K is never later than the scheduled
  kickoff, so a delayed kickoff closes the market at the scheduled time.
- **Opening** = first valid pre-match quote, **Closing** = last valid pre-match quote, per bookmaker and market,
  each with its own time. A closing price is never an in-play price.
- The source records a quote when the price changes. A `_Close_Time` hours before kickoff therefore means the
  price did not move after that time, or that the bookmaker stopped quoting the market: the data cannot tell the
  two apart. Compare the `_Close_Time` columns before comparing closing prices across books.

## Data integrity: what was corrected, and why

Each decision below is written in the build code with its evidence; the build stops if a new unresolved case appears.

**50 source events removed** (10 duplicate id without data; 9 abandoned or not completed, result awarded; 7 played, result changed afterwards; 6 lower-division match filed with the league; 6 resumption id of an interrupted match; 6 not played, result awarded; 3 abandoned match, replayed; 3 postponed fixture listed twice):

| Source event | League | Reason | Evidence |
|---|---|---|---|
| 3210646 | ARG | lower-division match filed with the league | CA San Telmo - Deportivo Madryn, 2021-02-05: match between two lower-division clubs (no club of the season), filed by the source with this league |
| 7579359 | ARG | lower-division match filed with the league | CA Douglas Haig - CA San Miguel, 2023-12-12: match between two lower-division clubs (no club of the season), filed by the source with this league |
| 9259466 | ARG | lower-division match filed with the league | CA Sarmiento de la Banda - Los Andes, 2024-12-21: match between two lower-division clubs (no club of the season), filed by the source with this league |
| 298454 | ARG | resumption id of an interrupted match | Arsenal de Sarandi - Olimpo B Blanca, 2017-06-01: separate id created for the resumption of an interrupted match; kept as 275243 (the original id) |
| 751412 | ARG | resumption id of an interrupted match | Colon - Velez Sarsfield, 2018-05-10: separate id created for the resumption of an interrupted match; kept as 403631 (the original id) |
| 1661430 | BOL | lower-division match filed with the league | Universidad Crucena - CD Torre Fuerte, 2019-06-22: match between two lower-division clubs (no club of the season), filed by the source with this league |
| 5353771 | BOL | lower-division match filed with the league | Destroyers - Club 24 de Septiembre, 2022-07-23: match between two lower-division clubs (no club of the season), filed by the source with this league |
| 773465 | BOL | abandoned or not completed, result awarded | Real Potosi - Guabira, 2018-06-03: abandoned or not played to the end (last event minute 81, last in-play quote minute 82); result 0-2 awarded (source note: "Match was abandoned after 81 minutes (0:2) due to security reasons. The result at the moment of the abandonement will stand as decided by FA 0:2.") |
| 9243875 | BOL | abandoned or not completed, result awarded | Oriente Petrolero - Bolivar, 2024-12-19: abandoned or not played to the end (last event minute 74, last in-play quote minute 74); result 1-4 awarded (source note: "Match was abandoned after 81 minutes (1:4). As per regulation by FA this result is declared as the final result of the match.") |
| 513820 | BOL | played, result changed afterwards | Jorge Wilstermann - Bolivar, 2017-11-05: played (2-2 in the match events), result changed to 0-1 by the federation (source note: "Decided by association") |
| 6278725 | BRA | abandoned or not completed, result awarded | Santos - Corinthians, 2023-06-21: abandoned or not played to the end (last event minute 86, last in-play quote minute 86); result 0-2 awarded (source note: "Match was abandoned after 86 minutes (0:2). As per regulation by FA this result is declared as the final result of the match") |
| 2128927 | CHI | abandoned match, replayed | Coquimbo Unido - Audax Italiano, 2020-01-31: match abandoned, then replayed; kept as 2687189 (the replay) |
| 2067675 | CHI | abandoned or not completed, result awarded | Union La Calera - Deportes Iquique, 2019-11-22: abandoned or not played to the end (last event minute 52, last in-play quote minute 67); result 0-0 awarded (source note: "Decided by association") |
| 2128783 | CHI | abandoned or not completed, result awarded | Colo Colo - Universidad Catolica, 2020-02-16: abandoned or not played to the end (last event minute 69, last in-play quote minute 72); result 0-2 awarded (source note: "Match was abandoned after 72 minutes (0:2) due to riots. Match will not continue by unanimous decision by the association. The result stands as final.") |
| 4533471 | COL | abandoned or not completed, result awarded | Union Magdalena - Junior, 2022-04-24: abandoned or not played to the end (last event minute 81, last in-play quote minute 75); result 0-3 awarded (source note: "Decided by association") |
| 1668422 | COL | played, result changed afterwards | Aguilas Doradas - Deportes Tolima, 2019-07-27: played (0-2 in the match events), result changed to 3-0 by the federation (source note: "Decided by Federation") |
| 2730765 | COL | not played, result awarded | Atletico Nacional Medellin - Cucuta Deportivo, 2020-11-15: not played; result 3-0 awarded by the federation (source note: "Decided by association") |
| 9279550 | COL | resumption id of an interrupted match | Deportes Tolima - Junior, 2020-02-23: separate id created for the resumption of an interrupted match; kept as 2133005 (the original id) |
| 193600 | ECU | duplicate id without data | El Nacional - Fuerza Amarilla SC, 2016-09-18: duplicate id without any odds; kept as 21386 |
| 208313 | ECU | duplicate id without data | Mushuc Runa - Emelec, 2016-09-18: duplicate id without any odds; kept as 21444 |
| 1088543 | ECU | lower-division match filed with the league | Deportivo Quevedo - Atletico Portoviejo, 2018-11-24: match between two lower-division clubs (no club of the season), filed by the source with this league |
| 1462258 | ECU | played, result changed afterwards | Emelec - America de Quito, 2019-04-28: played (0-0 in the match events), result changed to 3-0 by the federation (source note: "Decided by association") |
| 340546 | ECU | not played, result awarded | Fuerza Amarilla SC - Guayaquil City, 2017-10-14: not played; result 0-3 awarded by the federation (source note: "Decided by the association") |
| 1462120 | ECU | not played, result awarded | America de Quito - Fuerza Amarilla SC, 2019-10-20: not played; result 3-0 awarded by the federation (source note: "Decided by association") |
| 1462195 | ECU | not played, result awarded | America de Quito - Deportivo Cuenca, 2019-07-30: not played; result 3-0 awarded by the federation (source note: "Decided by Association") |
| 454509 | MEX | abandoned match, replayed | Monterrey - Santos Laguna, 2017-09-28: match abandoned, then replayed; kept as 522222 (the replay) |
| 1664448 | MEX | abandoned or not completed, result awarded | Atletico San Luis - Queretaro, 2019-10-20: abandoned or not played to the end (last event minute 81, last in-play quote minute 84); result 0-2 awarded (source note: "Date: 20-10-2019Current score: 0:2Time: 85Goalscorers & minutes: 0:1 (25.) J.Pereira, 0:2 (43.) L.RomoCustom comment: due to fan riots. Decided by the associati") |
| 198195 | MEX | postponed fixture listed twice | Veracruz - Puebla, 2017-03-11: postponed fixture listed twice; kept as 240887 (the match played) |
| 334404 | MEX | postponed fixture listed twice | Atlas - Tigres UANL, 2017-09-09: postponed fixture listed twice; kept as 509358 (the match played) |
| 98526 | USA | duplicate id without data | Toronto FC - CF Montreal, 2016-12-01: duplicate id without any odds; kept as 74628 |
| 388534 | USA | resumption id of an interrupted match | DC United - Real Salt Lake, 2017-08-13: separate id created for the resumption of an interrupted match; kept as 208494 (the original id) |
| 5668531 | USA | resumption id of an interrupted match | Charlotte FC - Columbus Crew, 2022-10-05: separate id created for the resumption of an interrupted match; kept as 4468065 (the original id) |
| 193426 | VEN | duplicate id without data | Urena SC - Atlético Venezuela, 2016-09-18: duplicate id without any odds; kept as 21508 |
| 208203 | VEN | duplicate id without data | Estudiantes de Caracas - Mineros, 2016-09-18: duplicate id without any odds; kept as 21507 |
| 208204 | VEN | duplicate id without data | CD Lara - Llaneros De Guanare, 2016-09-18: duplicate id without any odds; kept as 21538 |
| 211868 | VEN | duplicate id without data | Deportivo Zulia - Aragua, 2016-09-18: duplicate id without any odds; kept as 21492 |
| 212574 | VEN | duplicate id without data | Monagas - Trujillanos, 2016-09-18: duplicate id without any odds; kept as 21536 |
| 440789 | VEN | duplicate id without data | Deportivo Miranda FC - Zamora, 2016-09-18: duplicate id without any odds; kept as 21489 |
| 833977 | VEN | duplicate id without data | Deportivo La Guaira - Zulia, 2018-07-29: duplicate id without any odds; kept as 851703 |
| 1415187 | VEN | abandoned match, replayed | Zamora - LALA FC, 2019-03-29: match abandoned, then replayed; kept as 1536855 (the replay) |
| 1723985 | VEN | abandoned or not completed, result awarded | Aragua - Estudiantes de Caracas, 2019-09-15: abandoned or not played to the end (last event minute 78, last in-play quote minute 74); result 3-0 awarded (source note: "Decided by the Federation") |
| 1724140 | VEN | abandoned or not completed, result awarded | Trujillanos - Portuguesa, 2019-10-06: abandoned or not played to the end (last event minute 83, last in-play quote minute 84); result 1-1 awarded (source note: "Date: 06-10-2019 Current score: 1:1 Time: 83 Goalscorers & minutes: 1:0 (43.) J.Ortiz, 1:1 (80.) F.Puerta Custom comment: due to bad weather conditions. Result ") |
| 295183 | VEN | postponed fixture listed twice | Aragua - Carabobo, 2017-05-28: postponed fixture listed twice; kept as 300114 (the match played) |
| 262576 | VEN | played, result changed afterwards | Atlético Venezuela - Mineros, 2017-04-23: played (2-0 in the match events), result changed to 3-0 by the federation (source note: "Decided by association") |
| 267278 | VEN | played, result changed afterwards | Mineros - Portuguesa, 2017-04-26: played (0-0 in the match events), result changed to 0-3 by the federation (source note: "Decided by association") |
| 287376 | VEN | played, result changed afterwards | Zulia - Deportivo Tachira, 2017-05-19: played (2-0 in the match events), result changed to 0-3 by the federation (source note: "Decided by association") |
| 1724134 | VEN | played, result changed afterwards | Portuguesa - Academia Puerto Cabello, 2019-09-28: played (0-0 in the match events), result changed to 0-3 by the federation (source note: "Decided by association.") |
| 1413952 | VEN | not played, result awarded | Trujillanos - Mineros, 2019-03-20: not played; result 0-0 awarded by the federation (source note: "Decided by Federation") |
| 1721415 | VEN | not played, result awarded | Caracas - CD Lara, 2019-07-28: not played; result 0-3 awarded by the federation (source note: "Decided by the Federation") |
| 978156 | VEN | resumption id of an interrupted match | Atlético Venezuela - Trujillanos, 2018-10-18: separate id created for the resumption of an interrupted match; kept as 974580 (the original id) |

**Interrupted matches.** For the 6 matches stopped and resumed on a later date under a separate id, the original id is kept: it carries the final score and the pre-match prices of the original kickoff; its events, statistics and in-play prices cover the part played before the interruption.

**4 matches flagged by the source as decided by the federation are kept**, because the source's score equals the goals in the match events: the federation's decision did not change the score on the pitch (it may have changed the points). Each line says how far the match was played:

- 6078863: Coquimbo Unido - Cobresal, 2023-03-13: flagged by the source as decided by the federation (note: "Decided by association"); played to the 99th minute and the source's score equals the goals in the match events (2-1): kept as played
- 803377: Atletico Morelia - Unam Pumas, 2018-09-22: flagged by the source as decided by the federation (note: "Match has been finished and will not continue. The result stands as final."); played to the 85th minute and the source's score equals the goals in the match events (0-0): kept as played
- 5047305: Tigres UANL - Atlas, 2022-05-22: flagged by the source as decided by the federation (note: "Decided by association"); played to the 90th minute and the source's score equals the goals in the match events (4-2): kept as played
- 6754033: Puebla - Tijuana, 2023-09-02: flagged by the source as decided by the federation (note: "Decided by association"); played to the 90th minute and the source's score equals the goals in the match events (3-0): kept as played

**Scores.** 1 match has an incomplete 90-minute score in the source (one side empty), restored from fields of the same record that agree:

- 203266: CA Aldosivi - Atletico Rafaela, 2017-03-13 (round 15): the away side of the 90-minute score is empty in the source; its final score (1-0), its full-time score key (1-0) and the in-play score at minutes 90 to 92 (1-0) agree: 90-minute score set to 1-0

**Legs.** The automatic rule (home and away reversed, at most 21 days apart, nothing in between, or an aggregate score in the source) cannot see 14 knockout matches: their leg comes from a written list:

- 9269637: Royal Pari - Real Oruro, 2024-12-21: play-off first leg (4-0); the second leg is missing from the source (`Leg` 1)
- 296358: Jaguares de Cordoba - Atletico Nacional, 2017-05-31: quarter-final first leg; the second leg is missing from the source (`Leg` 1)
- 296359: America de Cali - Deportivo Pasto, 2017-05-31: quarter-final first leg; the second leg is missing from the source (`Leg` 1)
- 296360: Atletico Bucaramanga - Millonarios, 2017-06-01: quarter-final first leg; the second leg is missing from the source (`Leg` 1)
- 306459: Atletico Nacional - Deportivo Cali, 2017-06-19: second leg of the final; the first leg is missing from the source (`Leg` 2)
- 541992: Millonarios - La Equidad, 2017-11-30: quarter-final second leg; the first leg is missing from the source (`Leg` 2)
- 541974: Independiente Santa Fe - Jaguares de Cordoba, 2017-11-30: quarter-final second leg; the first leg is missing from the source (`Leg` 2)
- 541991: Atletico Nacional - Deportes Tolima, 2017-12-03: quarter-final second leg (2-1 after a 0-1 first leg missing from the source: 2-2 on aggregate, penalties 1-3 in the source) (`Leg` 2)
- 541973: Junior - America de Cali, 2017-12-03: quarter-final second leg (penalties 2-4); the first leg is missing from the source (`Leg` 2)
- 3447102: Deportes Tolima - Deportivo Cali, 2021-04-25: quarter-final first leg; second leg 40 days later (3589800), postponed during the national strike (`Leg` 1)
- 3589800: Deportivo Cali - Deportes Tolima, 2021-06-04: quarter-final second leg (aggregate 2-3 in the source = 0-3 + 2-0) (`Leg` 2)
- 1101429: Cruz Azul - Monterrey, 2018-12-09: semi-final second leg; the first leg (2018-12-06) is missing from the source (`Leg` 2)
- 1101430: Club America - Unam Pumas, 2018-12-10: semi-final second leg (6-1); the first leg (2018-12-06) is missing from the source (`Leg` 2)
- 101089: Zamora - Zulia, 2016-12-04: first leg of the 2016 season final; the second leg in Maracaibo is missing from the source (`Leg` 1)

**Team ids.** On 3 matches a club carries another source id than in the rest of its season: set to its usual id and name, so each club keeps one id:

- 851703: Deportivo La Guaira - Deportivo Zulia, 2018-07-29: the away team carries the source id 44182 instead of 7383 (Zulia), the id of all its other matches of the season: set to 7383
- 2150848: Municipal De Vinto - Royal Pari FC, 2020-01-25: the home team carries the source id 294330 instead of 287610 (Atletico Palmaflor Vinto), the id of all its other matches of the season: set to 287610
- 2156747: Nacional Potosi - Municipal De Vinto, 2020-01-29: the away team carries the source id 294330 instead of 287610 (Atletico Palmaflor Vinto), the id of all its other matches of the season: set to 287610

**Seasons, tournaments and stages** come from a written table (season and tournament windows, the stages each edition played, the expected number of matches per stage) checked match by match: every match is placed exactly once, every stage has exactly its number of matches, and the build stops otherwise. Editions cut short or reshaped (Covid-19 in 2020, Chile 2019 stopped by social unrest, Bolivia's 2022 Clausura abandoned, first seasons that start mid-season) are delivered as played; 81 editions carry a written note (table *Season notes*).

**Venues.** 40 matches had the stadium name written in the country field (shifted by one character, Cyrillic or bare text): stadium, city and country are restored from a written list (5 venues). Capacity and coordinates of those records are unreadable and stay empty.

**Team country.** Club San Jose (Oruro, Bolivia) carries the code us in the source: corrected on its 214 matches, so `Home_Team_Country` / `Away_Team_Country` are right and `Neutral_Venue` stays 0 at its home ground.

**Half-time scores.** 1 half-time score was higher than the final score (the source counted a goal it later cancelled): left empty rather than wrong.

## Said plainly - known limitations

- **Betfair and Betsson** were not collected for Argentina 2016/17 to 2019/20 (1,422 matches) and USA 2020 MLS is Back (51 matches): `Betfair_Pct` and `Betsson_Pct` are empty in the Coverage file for a season with none of its matches collected.
- **Lineups** are absent or almost absent from the source for 2 leagues: Bolivia, Venezuela. The odds, the match sheet, the events and the statistics are there; see `Lineups_Pct` in the Coverage file, season by season.
- **Matches missing from the source** (stages or matches never collected): Bolivia 2024: play-off Royal Pari - Real Oruro: first leg only (2024-12-21); the second leg is missing from the source; Colombia 2017 Apertura: knockout phase incomplete in the source (3 quarter-final first legs and the final's second leg); Colombia 2017 Finalizacion: second legs only for the quarter-finals; their first legs are missing from the source; Colombia 2018 Apertura: knockout phase (quarter-finals, semi-finals, final) missing from the source; Colombia 2018 Finalizacion: knockout phase (quarter-finals, semi-finals, final) missing from the source; Ecuador 2018: final between the stage winners missing from the source; Mexico 2018/19 Apertura: second legs only for the semi-finals; their first legs (2018-12-06) are missing from the source; Venezuela 2016: season final Zamora - Zulia (winners of the Apertura and the Clausura): first leg only (2016-12-04); the second leg in Maracaibo is missing from the source; Venezuela 2017 Clausura: 8 regular-season matches missing from the source; Venezuela 2021: final of 2021-12-11 missing from the source.
- **Venue unknown** for 1,342 matches (4.3 %); `Neutral_Venue` is empty on 1,342 matches.
- **Round** is filled on 25,394 matches (81.9 %): it stays empty where the source's matchday numbers are not reliable for that season and stage, and in knockout stages.
- **Kickoff times**: for 7 matches the source's scheduled kickoff is more than 3 hours later than the real start read from Bet365's live clock, for example: CA Tigre - CA Aldosivi, played 2025-09-20 (source kickoff 2025-09-21 15:00 UTC); Platense - Defensa y Justicia, played 2025-03-03 (source kickoff 2025-03-04 23:00 UTC); Banfield - CA Independiente, played 2025-03-03 (source kickoff 2025-03-04 22:30 UTC). `Kickoff_UTC` keeps the source's value; the pre-match markets are cut at the real start.
- **Score and clock on in-play quotes** are the bookmaker's own: Pinnacle almost never sends a numeric clock (`Minute` empty) and Betfair often sends a partial score (`Score_Home` / `Score_Away` empty). Nothing is filled in from another bookmaker.
- **Minute-by-minute statistics carry no recording time before 2021-05-11**: `Timestamp_UTC` and `Epoch` are empty on the 5,535 matches played before (2,102,874 rows, 25.2 %); `Minute` and `Value` are always there.
- **Score field of the source**: on 59 of the 116 penalty shoot-outs the source's own final score adds the shoot-out to the goals. This product never uses it: goals after 90 minutes, after extra time and in the shoot-out are separate columns.
- **Coverage changes over time** (table *Coverage over time*). First match covered: Unibet 2017-04-15, minute-by-minute statistics 2017-06-10, Pinnacle 2018-09-27, Betsson 2022-07-03, Betfair (Sportsbook) 2023-11-03. Months with a gap: Pinnacle 2023-09 to 2023-11 and 2026-07 to 2026-08; Unibet 2026-07 to 2026-08; Betfair (Sportsbook) 2024-11 to 2025-08 and 2026-07 to 2026-08; Betsson 2025-12 and 2026-07 to 2026-08; minute-by-minute statistics 2018-02 to 2019-09 and 2026-07.
- **Data starts on 2016-08-28**: the first season of each league is partial (its first matchdays are missing); Chile starts with its 2018 season (2018-02-03). Data stops at 2026-09-30: Argentina 2026 Clausura, Bolivia 2026, Brazil 2026, Chile 2026, Colombia 2026 Finalizacion, Ecuador 2026, Mexico 2026/27 Apertura, USA 2026 and Venezuela 2026 Clausura are in progress.
- **Events** are the source's text timeline: it keeps some events it later cancelled (goals disallowed by VAR,
  rescinded cards; a repeated ordinal marks them). Goals in events match the 90-minute score on
  98.4 % of matches; the match tables carry the match sheet's score.
- **Team statistics**: goals equal the 90-minute score on 99.98 % of rows
  of matches without extra time.
- Odds are UTC and come from one data provider. No cross-provider reconciliation is claimed.

## Format, licence, delivery

- CSV: comma-separated, UTF-8 with BOM, "." decimals. Large tables are gzip CSV, one file per league.
- Single-user commercial licence: use the data, analyse it, build and sell models on it.
  Do not resell or redistribute the files themselves.
- A question, an invoice or a custom extract: contact@oliviersportsdata.com

Olivier Vignez - Sports Betting Data Engineer - Olivier Sports Data
