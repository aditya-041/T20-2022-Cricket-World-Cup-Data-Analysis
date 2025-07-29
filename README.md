# 🏏 T20 World Cup 2022 Data Analysis Dashboard

This project presents a complete analysis of the **T20 World Cup 2022** using both **Python (Jupyter Notebook)** for data preparation and **Power BI** for interactive visualizations. The dashboard highlights key player performances, team statistics, and match-level insights to uncover patterns and trends throughout the tournament.

---

## 📂 Project Overview

- **Objective**: Analyze and visualize T20 World Cup 2022 data to derive performance insights.
- **Tools Used**: Python (Pandas), Power BI, Excel
- **Key Focus Areas**:
  - Top run scorers and wicket-takers
  - Bowling economy and strike rates
  - Match-wise and team-wise summaries
  - Player performance comparisons

---

## 📁 Dataset

🔧 *The dataset includes ball-by-ball and match-level data for the T20 World Cup 2022, sourced from CricInfo*  
*(Replace with your source if different)*

Main fields include:
- `match_id`, `venue`, `teams`, `innings`, `player_name`
- `runs_scored`, `balls_faced`, `fours`, `sixes`
- `overs_bowled`, `runs_conceded`, `wickets_taken`
- `match_result`, `man_of_the_match`, etc.

---

## 📊 Dashboard Highlights (Power BI)

Key Visualizations:
- 🏅 **Top Run Scorers**: Total and average runs per match
- 🎯 **Leading Wicket Takers**: Sorted by wickets and economy rate
- 📈 **Batting Strike Rate vs Average**: Player comparison
- 🔁 **Bowling Economy vs Wickets**: Identifying all-round performers
- 🏟️ **Venue-wise Stats**: High scoring and low scoring grounds
- 🏏 **Match Results Summary**: Win/loss patterns and chasing stats

📌 *The dashboard allows filtering by teams, players, match dates, and venues.*

---

## 🧪 Python/Jupyter Notebook

The notebook was used to:
- ✅ Load and clean raw CSV datasets
- ✅ Merge match, player, and ball-by-ball data
- ✅ Engineer new stats like strike rate, economy, averages
- ✅ Export final dataset to Excel for Power BI

Main libraries used:
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
