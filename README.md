# PUBG_DATA_ANALYSIS
This dashboard analyzes gameplay data from the popular online game PUBG (PlayerUnknown’s Battlegrounds). It focuses on core performance metrics such as kills, damage dealt, match duration, placement rank, and survival time. The visuals help track patterns in gameplay and identify strategies that lead to higher success rates.
# PUBG Gameplay Data Dashboard – Excel Report

##  Project Title:
PUBG Player Performance Analysis

##  Objective:
To visualize and analyze player performance using match data from PUBG, highlighting metrics that influence success such as kills, rank, survival time, and more.

---

## 📊 Dataset Overview:
- Dataset Source: PUBG Game API / Kaggle Dataset
- Key Columns Used:
  - Player Name
  - Match ID
  - Game Mode (Solo, Duo, Squad)
  - Kills
  - Damage Dealt
  - Longest Kill
  - Kill Place
  - Match Duration
  - Walk Distance
  - Ride Distance
  - Win Place

---

##  Dashboard Highlights:

### 1. KPI Summary
- **Total Matches**
- **Average Kills**
- **Win Percentage**
- **Total Damage Dealt**

### 2. Kill Distribution
- Histogram of kills per match to show player aggression and kill consistency.

### 3. Survival vs. Rank
- Line/Scatter plot showing correlation between survival time and final match placement.

### 4. Damage Analysis
- Bar chart or scatter plot of total damage vs. win place (final ranking) to evaluate performance.

### 5. Mode & Map Filters
- Slicers for:
  - Game Mode (Solo, Duo, Squad)
  - Map (Erangel, Miramar, etc.)

---

## 🧮 Calculated Metrics:
- **K/D Ratio** = Total Kills / Total Deaths
- **Win Ratio** = Number of Wins / Total Matches
- **Average Survival Time** = Sum(Survival Time) / Matches
- **Aggressiveness Score** = Weighted average of Kills and Damage

---

##  Tools & Skills Demonstrated:
- Data Cleaning and Normalization
- Excel Pivot Tables and Slicers
- Visual Design (using Charts & Conditional Formatting)
- Player Behavior Analysis
- Dashboard Storytelling

---

## 📈 Key Insights Example:
- Higher damage does not always guarantee a higher rank — strategic play matters.
- Solo mode shows more aggressive kill patterns, while Squad mode relies more on team strategy.
- Players who survive past the 25-minute mark have a significantly higher chance of placing in the top 10.

---

## 🔧 Optional Enhancements:
- Add map heatmaps (if coordinate data is available)
- Analyze weapon-specific kill rates
- Compare players or teams over time
