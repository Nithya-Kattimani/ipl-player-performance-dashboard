[README (1).md](https://github.com/user-attachments/files/27001705/README.1.md)
# 🏏 IPL Player Performance Dashboard (2008–2025)

An interactive Power BI dashboard analyzing IPL cricket data across 18 seasons, covering batting, bowling, team performance, and season trends.

---

## 📊 Dashboard Pages

| Page | Description |
|------|-------------|
| **Overview** | KPI cards (Total Runs, Wickets, Matches, Fours, Sixes), Top 10 Run Scorers & Wicket Takers |
| **Batting Analysis** | Career run scorers, 50s & 100s breakdown, runs by season trend, Strike Rate vs Runs scatter |
| **Bowling Analysis** | Top wicket takers, best economy rates, wickets by season trend, Bowling SR vs Wickets scatter |
| **Team & Season Trends** | Team win %, all-time wins by team, avg runs per match trend, Fours vs Sixes by season |

---

## 🗂️ Project Structure

```
IPL_Project/
│
├── IPL.csv                  # Raw dataset (2008–2025, 278K rows)
│
├── ipl_preprocess.py        # Python preprocessing script
│
├── batting_stats.csv        # Cleaned batting data per player per season
├── bowling_stats.csv        # Cleaned bowling data per player per season
├── best_economy.csv         # Top bowlers by economy rate (career)
├── team_stats.csv           # Team wins, losses, win % per season
├── season_summary.csv       # Season-level aggregated stats
│
└── IPL_Dashboard.pbix       # Power BI Dashboard file
```

---

## 🛠️ Tools & Technologies

- **Python** (Pandas) — Data cleaning & preprocessing
- **Power BI Desktop** — Dashboard building & visualization
- **VS Code** — Python script development

---

## 📁 Dataset

- **Source:** Kaggle — IPL Dataset 2008–2025
- **Size:** 278,205 rows × 64 columns
- **Coverage:** 1,169 matches | 18 seasons | 703 batters | 550 bowlers

---

## ⚙️ How to Run

### 1. Clone this repository
```bash
git clone https://github.com/YOUR_USERNAME/ipl-dashboard.git
cd ipl-dashboard
```

### 2. Install dependencies
```bash
pip install pandas
```

### 3. Run preprocessing script
```bash
python ipl_preprocess.py
```
This generates all 5 clean CSV files needed for Power BI.

### 4. Open Power BI
- Open `IPL_Dashboard.pbix` in Power BI Desktop
- Click **Refresh** to reload data

---

## 📸 Dashboard Preview

### Overview Page
![Overview](screenshots/overview.png)

### Batting Analysis
![Batting](screenshots/batting.png)

### Bowling Analysis
![Bowling](screenshots/bowling.png)

### Team & Season Trends
![Teams](screenshots/teams.png)

---

## 🔍 Key Insights

- **Virat Kohli** is the all-time leading run scorer in IPL history
- **YS Chahal** leads in total wickets across all seasons
- **Mumbai Indians** have the most wins of any IPL franchise
- Average runs per match has increased significantly from 2008 to 2025, reflecting the evolution of T20 batting
- Sixes have grown consistently each season, showing the shift towards aggressive batting

---

## 👤 Author

**Your Name**
- GitHub: [https://github.com/Nithya-Kattimani]
- LinkedIn: [https://www.linkedin.com/in/nithya-kattimani-149169218/]

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
