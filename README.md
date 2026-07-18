# 🏏 IPL Performance Analytics Dashboard (2021–2023)

## 📌 Project Overview

This project is an interactive **Power BI dashboard** developed to analyze **Indian Premier League (IPL)** performance using historical data from the **2021, 2022, and 2023 seasons**. The dashboard provides comprehensive insights into player and team performance and includes data-driven predictions for the IPL 2024 season.

The project is based on the **Sports Basics** case study, where a sports media company aims to publish an IPL 2024 special edition magazine using analytics from the previous three seasons.

---

## 🎯 Objectives

- Analyze batting, bowling, and team performance across IPL 2021–2023.
- Identify top-performing batsmen, bowlers, and teams using key performance metrics.
- Build interactive dashboards for cricket fans, analysts, and decision-makers.
- Generate data-driven predictions for IPL 2024.

---

## 📂 Dataset

The project uses four datasets:

- **dim_match_summary** – Match details and results
- **fact_batting_summary** – Batting statistics
- **fact_bowling_summary** – Bowling statistics
- **dim_players** – Player information

---

## 🛠️ Tools & Technologies

- Power BI
- DAX
- Power Query
- Data Modeling (Star Schema)
- Data Visualization
- Microsoft Excel

---

## 📊 Dashboard Features

### Batting Analysis
- Top 10 Batsmen by Total Runs
- Top 10 Batsmen by Batting Average
- Top 10 Batsmen by Strike Rate
- Top 5 Batsmen by Boundary Percentage

### Bowling Analysis
- Top 10 Bowlers by Total Wickets
- Top 10 Bowlers by Bowling Average
- Top 10 Bowlers by Economy Rate
- Top 5 Bowlers by Dot Ball Percentage

### Team Analysis
- Top 4 Teams by Winning Percentage
- Top 2 Teams with Most Successful Run Chases
- Team Performance Comparison
- Interactive Team Insights

### IPL 2024 Predictions
- Orange Cap Prediction
- Purple Cap Prediction
- Top 4 Qualifying Teams
- Winner & Runner-Up Prediction
- Best Playing XI
- Top 3 All-Rounders

---

## 📈 Key Metrics

### Batting
- Total Runs
- Batting Average
- Strike Rate
- Boundary Percentage

### Bowling
- Total Wickets
- Bowling Average
- Economy Rate
- Dot Ball Percentage

### Team
- Matches Played
- Matches Won
- Winning Percentage
- Chasing Wins

---

## 📌 Power BI Features Used

- Interactive Dashboards
- KPI Cards
- Slicers
- Drill-through
- Bookmarks
- Dynamic Titles
- Tooltips
- Conditional Formatting
- Ranking using DAX
- Image URLs for Team Logos

---

## 📊 Data Modeling

A **Star Schema** was implemented by connecting the fact tables with dimension tables to ensure efficient querying and improved dashboard performance.

---

## 📷 Dashboard Preview

### Dashboard Pages
- Overview
- Batting Analysis
- Bowling Analysis
- Team Analysis
- IPL 2024 Predictions
- Best Playing XI


---

## 🚀 Key Insights

- Identified the top-performing batsmen and bowlers based on three years of IPL statistics.
- Compared teams using winning percentage and successful chase analysis.
- Evaluated players using batting average, strike rate, economy rate, boundary percentage, and dot ball percentage.
- Selected the Best Playing XI and Top 3 All-Rounders using historical performance and player roles.
- Generated data-driven predictions for IPL 2024 outcomes.

---

## 📁 Project Structure

```
IPL-Performance-Analytics/
│── Data/
│   ├── dim_match_summary.csv
│   ├── dim_players.csv
│   ├── fact_batting_summary.csv
│   └── fact_bowling_summary.csv
│
│── Dashboard/
│   └── IPL_Analytics.pbix
│
│── 
│
└── README.md
```

---

## 📌 Future Enhancements

- Integrate live IPL data using APIs.
- Add venue-wise and opposition-wise player analysis.
- Develop machine learning models for match outcome prediction.
- Publish the dashboard to the Power BI Service with scheduled refresh.

---

## 👨‍💻 Author

**Abhinandan Pakhare**


---

## ⭐ If you found this project useful, consider giving it a star!
