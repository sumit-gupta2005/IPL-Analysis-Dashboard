# IPL-Analysis-Dashboard
# IPL Data Analysis Dashboard

## Project Overview

This project analyzes historical **Indian Premier League (IPL)** cricket data to extract insights about team performance, player statistics, and match trends. The analysis was performed using **Python for data processing** and **Power BI for visualization**.

The goal of this project is to transform raw sports data into **interactive insights through dashboards**, demonstrating practical skills in **data cleaning, exploratory data analysis (EDA), and business-oriented visualization**.

---

## Problem Statement

The IPL generates large volumes of match and ball-by-ball data every season. However, without structured analysis it is difficult to understand:

* Which teams dominate the tournament
* Which players consistently perform well
* How toss decisions influence match outcomes
* Which stadiums produce high-scoring matches

This project addresses these questions by building a **data analytics pipeline and an interactive Power BI dashboard**.

---

## Dataset Information

### Matches Dataset

Contains match-level information such as:

* Match ID
* Season
* City
* Teams
* Toss winner and decision
* Match winner
* Venue
* Player of the match

Total records: **1095 matches**

---

### Deliveries Dataset

Contains ball-by-ball match data including:

* Batter
* Bowler
* Runs scored
* Extra runs
* Wickets
* Over and ball number

Total records: **260,920 deliveries**

---

## Data Cleaning and Processing

Several preprocessing steps were performed using **Pandas**:

* Standardized inconsistent **season formats**
* Corrected **team name inconsistencies** (e.g., Kings XI Punjab → Punjab Kings)
* Handled missing values in city, dismissal, and method columns
* Created derived metrics such as:

  * Total match runs
  * Strike rate
  * Bowling economy rate

---

## Key Analysis Performed

### Player Performance

* Top run scorers in IPL history
* Highest strike-rate batsmen
* Best bowlers by economy rate
* Most "Player of the Match" awards

### Team Performance

* Total wins by team
* Win percentage comparison
* Total runs scored by teams

### Match Strategy

* Impact of toss decision on match outcome
* Bat-first vs field-first win percentage

### Venue Analysis

* Stadiums with highest average match runs

---

## Tools and Technologies

| Tool       | Purpose                          |
| ---------- | -------------------------------- |
| Python     | Data analysis                    |
| Pandas     | Data cleaning and transformation |
| NumPy      | Numerical operations             |
| Matplotlib | Exploratory visualization        |
| Power BI   | Dashboard creation               |

---

## Dashboard Features

The Power BI dashboard provides interactive analysis including:

* Key performance indicators (total runs, wickets, boundaries)
* Top batsmen and bowlers
* Team performance comparison
* Toss decision analysis
* Player of the match leaderboard
* Dynamic filtering by season and player

---

## Key Insights

* Some players consistently dominate the IPL run charts across seasons.
* Certain bowlers maintain **low economy rates**, making them highly effective.
* Toss decisions influence match outcomes but are not the sole deciding factor.
* A few stadiums consistently produce **high-scoring matches**, indicating batting-friendly conditions.

---

## Conclusion

This project demonstrates how **data analytics techniques can be applied to sports data** to generate meaningful insights. By combining Python-based data analysis with Power BI visualization, the project delivers an interactive dashboard that helps explore IPL match dynamics and player performance trends.

---

## Author

**Sumit Gupta**

Aspiring **Data Analyst** with interest in data visualization, sports analytics, and business intelligence dashboards.
