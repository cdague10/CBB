#CBB Play-by-play
`cbb_pbp.ipynb`: Pulls CBB PBP data from ESPN API. Only pulls games from within the selected range of dates. Every shot, assist, turnover, rebound and stoppage is noted. Repeat or duplicate plays are deleted.

### Programming Languages, Software, etc
Python, Jupyter Notebook and VS Code

### Required Libraries, Packages, etc
pandas, time, os, requests

INPUTS:
SCOREBOARD_URL = "https://site.api.espn.com/apis/site/v2/sports/basketball/mens-college-basketball/scoreboard"
PBP_URL = "https://site.api.espn.com/apis/site/v2/sports/basketball/mens-college-basketball/summary"

OUTPUTS: 
cbb_pbp.csv == stores all pbp data and adds unique plays to existing ones

