#  IPL Data Analysis

A comprehensive exploratory data analysis (EDA) of Indian Premier League (IPL) match data using Python. This project uncovers patterns in team performance, player statistics, and match trends across all IPL seasons.

---

##  Objective

To analyze IPL match and player data to derive meaningful insights about team performance, batting and bowling statistics, home vs away trends, and season-wise patterns — and present them through clear visualizations.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
| Python 3.11 | Core programming language |
| Pandas | Data loading, cleaning, and analysis |
| NumPy | Numerical computations |
| Matplotlib | Data visualization |
| Seaborn | Advanced and styled visualizations |
| Jupyter Notebook | Interactive development environment |
| Excel (openpyxl) | Reading `.xlsx` player data |

---

## 📂 Dataset

The dataset consists of 6 files covering IPL matches from 2008 to 2017:

| File | Description |
| `matches.csv` | Match-level data — teams, venue, toss, winner, season |
| `deliveries.csv` | Ball-by-ball data — runs, wickets, bowler, batsman |
| `most_rus_average_strikerate.csv` | Aggregated batting stats — runs, average, strike rate |
| `players.xlsx` | Player information and details |
| `teams.csv` | Team details |
| `teamwise_home_and_away.csv` | Home and away win stats per team |

---

## 📊 Analysis Performed

### 1. Team Performance

- Top 10 teams by total match wins
- Toss decision distribution (bat vs field)
- Impact of toss outcome on match result

### 2. Home vs Away Analysis

- Home and away wins per team
- Home vs away win percentage comparison

### 3. Batting Statistics

- Top 10 run scorers across all IPL seasons
- Top 10 batsmen by strike rate (min. 500 runs)
- Top 10 batsmen by batting average (min. 500 runs)

### 4. Bowling Statistics

- Top 10 wicket takers across all seasons
- Top 10 most economical bowlers (min. 300 balls)

### 5. Season Trends

- Number of matches played per season
- Win trends across seasons for top 5 teams

---

## 📈 Key Insights

1. **Virat Kohli** is the all-time leading run scorer in IPL history with **5,426 runs**.
2. **Mumbai Indians** have the most IPL match wins across all seasons.
3. Teams prefer to **field after winning the toss** — approximately 60% of the time.
4. Winning the toss does **not significantly guarantee** winning the match.
5. **Delhi Capitals** surprisingly have a higher away win percentage (70%) than home win percentage (50%).
6. **DA Warner** has the best batting average (41.37) among top run scorers, showing elite consistency.

---

## 📁 Project Structure

```
ipl-data-analysis/
│
├── ipl_analysis.ipynb        # Main Jupyter Notebook with all analysis
│
├── data/
│   ├── matches.csv
│   ├── deliveries.csv
│   ├── most_rus_average_strikerate.csv
│   ├── players.xlsx
│   ├── teams.csv
│   └── teamwise_home_and_away.csv
│
├── charts/
│   ├── team_wins.png
│   ├── toss_decision.png
│   ├── toss_impact.png
│   ├── home_away.png
│   ├── top_batsmen.png
│   ├── top_strikerate.png
│   ├── top_average.png
│   ├── top_bowlers.png
│   ├── top_economy.png
│   ├── matches_per_season.png
│   └── season_wins_trend.png
│
└── README.md
```

---

##  How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/ipl-data-analysis.git
   cd ipl-data-analysis
   ```

2. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn openpyxl
   ```

3. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open `ipl_analysis.ipynb` and run all cells.

---

##  Author

**Md Kasid Shaikh**
B.Tech CSE (AI & ML) — 1st Year

[GitHub](https://github.com/Kasidmd34-sudo)

[LinkedIn](Linkedin: https://www.linkedin.com/in/md-kasid-shaikh-04b971315?)
