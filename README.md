# 🏏 IPL Data Analysis using Apache Spark & Databricks

This project explores Indian Premier League (IPL) data using **Apache Spark** on the **Databricks** platform. It leverages distributed computing to analyze large-scale match and player data and extract meaningful insights related to team and player performance.

---

## 📌 Project Workflow

![Workflow Diagram](IPL%20Data%20Analysis%20.png)

1. **Data Source**: IPL datasets including ball-by-ball records, match metadata, and player info.
2. **Storage**: Data ingested and stored in **Amazon S3**.
3. **Processing on Databricks**:
   - **Spark** for large-scale transformation
   - **SQL Analytics** for querying insights
   - **Visualization tools** for reporting and dashboards

---

## 🧾 Dataset Files

- `Ball_By_Ball.csv` – Every ball's event: runs, extras, wickets, bowler, batsman
- `Match.csv` – Match metadata: teams, venue, toss, result
- `Player.csv` – Player master table
- `Player_match.csv` – Player appearances per match
- `Team.csv` – Team details

---

## 🛠️ Tools & Technologies

- **Apache Spark (PySpark)**
- **Databricks**
- **Amazon S3**
- **SQL / Spark SQL**
- **Data Visualization (Charts, Plots)**

---

## 📊 Key Insights Extracted

- Top-performing batsmen and bowlers
- Toss impact on match outcomes
- Season-wise player dominance
- Match-winning trends by venue and team
- Player matchups and ball-by-ball analytics

---

## 🚀 How to Run This Project

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/ipl-data-spark-databricks.git
   cd ipl-data-spark-databricks
