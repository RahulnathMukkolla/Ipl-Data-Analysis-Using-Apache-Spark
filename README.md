# 🏏 IPL Data Analysis using Apache Spark & Databricks

This project explores Indian Premier League (IPL) data using **Apache Spark** on the **Databricks** platform. It leverages distributed computing to analyze large-scale match and player data and extract meaningful insights for teams, players, and match performances.

---

## 📌 Project Workflow

![Workflow Diagram]([IPL Data Analysis](https://github.com/RahulnathMukkolla/Ipl-Data-Analysis-Using-Apache-Spark/blob/main/IPL%20Data%20Analysis%20.png))

1. **Data Source**: IPL datasets such as ball-by-ball records, match details, players, and teams.
2. **Storage**: Data ingested and stored in **Amazon S3** buckets.
3. **Processing**: Data processed on **Databricks** using:
   - **Apache Spark** for transformation
   - **SQL Analytics** for queries
   - **Visualization tools** for insight generation

---

## 🧾 Dataset Files

- `Ball_By_Ball.csv` – Ball-level IPL data (runs, wickets, overs)
- `Match.csv` – Match metadata (venues, toss info, dates)
- `Player.csv` – Player master data
- `Player_match.csv` – Player participation in matches
- `Team.csv` – Team master data

---

## 🛠️ Tools & Technologies

- **Apache Spark (PySpark)**
- **Databricks**
- **Amazon S3**
- **SQL / Spark SQL**
- **Data Visualization Libraries / BI Tools**

---

## 📊 Key Insights Extracted

- Top-performing batsmen and bowlers
- Match-winning patterns by toss, venue, or team
- Team-wise total wins, losses, and performance trends
- Season-wise player participation and dominance
- Player matchups and detailed ball-by-ball outcomes
