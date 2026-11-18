# acc-reality-check-project
Data: 
**How extraction works:** Section 1 saves all responses in 'raw/'
(`torvik_YYYY-MM-DD.csv`, `scoreboard_YYYYMMDD.json`, `summary_GAMEID.json`)
and skips files already saved. Scoreboards stop at yesterday (ensures only finished games are saved)
**Sources:**
- Bart Torvik ratings (CSV): https://barttorvik.com/2027_team_results.csv (snapshots from 2026-11-18)
- ESPN API (JSON), base URL https://site.api.espn.com/apis/site/v2/sports/basketball/mens-college-basketball (games 2026-11-01 to 2026-11-17)
