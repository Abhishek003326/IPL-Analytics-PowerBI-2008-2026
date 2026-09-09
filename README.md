# 🏏 IPL Analytics Dashboard — 2008 to 2026

![Power BI](https://img.shields.io/badge/Power%20BI-Analytics-yellow)
![DAX](https://img.shields.io/badge/DAX-Measures-blue)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-green)
![IPL](https://img.shields.io/badge/IPL-2008--2026-red)

An interactive **IPL Analytics Dashboard** built using **Microsoft Power BI**, covering IPL seasons from **2008 to 2026**.

The project analyzes team performance, player statistics, batting, bowling, match outcomes, toss impact, venue performance, and season-wise trends through a six-page interactive dashboard.

---

## 📌 Project Overview

The objective of this project is to transform IPL match-level and ball-by-ball data into an interactive analytical dashboard that provides insights into:

- Team performance
- Player performance
- Batting statistics
- Bowling statistics
- Match outcomes
- Toss impact
- Venue performance
- Season-wise trends

The dashboard allows users to interact with the data using filters and slicers and explore IPL performance across different seasons, teams, players, opponents, and venues.

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Data Modeling**
- **Data Visualization**

---

## 📊 Dataset

The project uses IPL data covering **2008–2026**, including:

- Match-level data
- Ball-by-ball data
- Player information
- Team information
- Team aliases

The raw datasets are available in the [`Dataset`](./Dataset) folder.

---

## 🔄 Data Preparation

The data was prepared using **Power Query** before being used for analysis.

The preparation process included:

1. Importing the raw IPL datasets
2. Cleaning and transforming the data
3. Correcting data types
4. Handling team names and aliases
5. Creating relationships between tables
6. Building the Power BI data model
7. Creating DAX measures
8. Designing interactive dashboard pages

---

## 🧩 Data Model

The Power BI model consists of the following tables:

- **Ball by Ball**
- **Matches**
- **Players**
- **Team Aliases**
- **Teams**

The model was designed to support match-level, team-level and player-level analysis.

### Data Model

![Data Model](./Documentation/Data_Model.png)

---

# 📈 Dashboard

The project contains **6 interactive Power BI dashboard pages**.

---

## 1️⃣ IPL Overview Dashboard

Provides a high-level overview of IPL history from 2008–2026.

### Key areas

- Total matches
- Total runs
- Total wickets
- Fours and sixes
- Players and teams
- Season-wise match trends
- Top batters
- Top wicket takers
- IPL title winners
- Venue analysis

![IPL Overview](./Dashboard/01_IPL_Overview.png)

---

## 2️⃣ Team Analysis Dashboard

Provides detailed analysis of individual team performance.

### Key areas

- Matches played
- Matches won
- Win percentage
- Team runs
- Season-wise performance
- Top batters
- Wins vs losses
- Wins against opponents

![Team Analysis](./Dashboard/02_Team_Analysis.png)

---

## 3️⃣ Batting Analysis Dashboard

Analyzes IPL batting performance across seasons and players.

### Key areas

- Total batters
- Total runs
- Fours
- Sixes
- Highest individual score
- Strike rate
- Fifties
- Centuries
- Orange Cap analysis
- Top run scorers

![Batting Analysis](./Dashboard/03_Batting_Analysis.png)

---

## 4️⃣ Bowling Analysis Dashboard

Analyzes bowling performance across IPL history.

### Key areas

- Total bowlers
- Total wickets
- Balls bowled
- Dot balls
- Runs conceded
- Economy rate
- Top wicket takers
- Dot-ball leaders
- Purple Cap analysis

![Bowling Analysis](./Dashboard/04_Bowling_Analysis.png)

---

## 5️⃣ Match & Toss Analysis Dashboard

Explores the relationship between toss decisions and match outcomes.

### Key areas

- Toss decisions
- Toss winner vs match winner
- Batting first vs chasing
- Toss impact
- Team-level toss performance
- Season-wise toss impact
- Match outcome analysis

![Match & Toss Analysis](./Dashboard/05_Match_Toss_Analysis.png)

---

## 6️⃣ Venue & Season Analysis Dashboard

Analyzes IPL performance across venues and seasons.

### Key areas

- Total venues
- Total cities
- Most-used venues
- Highest-scoring venues
- Average runs by venue
- Batting-first win percentage
- Chasing win percentage
- Venue-wise performance
- Season-wise analysis

![Venue & Season Analysis](./Dashboard/06_Venue_Season_Analysis.png)

---

# 🔍 Key Insights

The dashboard enables analysis of several important IPL trends, including:

- Identification of the most successful IPL teams based on championship titles.
- Comparison of team performance across different seasons.
- Identification of leading run scorers and wicket takers.
- Analysis of batting and bowling performance at player level.
- Comparison of team performance against different opponents.
- Analysis of toss decisions and their relationship with match outcomes.
- Comparison of batting-first and chasing success.
- Identification of frequently used and high-scoring venues.
- Analysis of IPL trends across seasons from 2008 to 2026.

---

# 📐 Power BI & DAX

The project uses DAX measures to calculate and analyze metrics such as:

- Total Matches
- Matches Won
- Win %
- Total Runs
- Total Wickets
- Fours
- Sixes
- Strike Rate
- Economy Rate
- Dot Balls
- Highest Score
- Team Performance
- Toss Impact
- Venue Performance

---

# 📁 Repository Structure

```text
IPL-Analytics-PowerBI-2008-2026/
│
├── Dashboard/
│   ├── 01_IPL_Overview.png
│   ├── 02_Team_Analysis.png
│   ├── 03_Batting_Analysis.png
│   ├── 04_Bowling_Analysis.png
│   ├── 05_Match_Toss_Analysis.png
│   └── 06_Venue_Season_Analysis.png
│
├── PowerBI/
│   └── IPL_Analytics_2008_2026.pbix
│
├── Documentation/
│   └── Data_Model.png
│
└── Dataset/
    └── Raw IPL dataset files
   
