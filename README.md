# 🏏 IPL Data Analysis (2008–2025)

## 📌 Introduction
This project performs an **in-depth Exploratory Data Analysis (EDA)** on the Indian Premier League (IPL) dataset from 2008 to 2025.  
The goal is to uncover meaningful insights, patterns, and trends related to **teams, players, venues, and match outcomes** to understand the evolution of IPL.

---

## 📊 Dataset Description
The project uses multiple datasets:

- **Matches Dataset** → Season, date, teams, toss result, match result, winner, margin, player of the match.  
- **Ball-by-Ball Dataset** → Over-by-over delivery details: batsman, bowler, runs, extras, wickets, dismissal type.  
- **Teams Dataset** → Team ID, team name, abbreviation.  
- **Players Dataset** → Player ID, name, role, batting/bowling style, country.

**Data Source:** Updated IPL data (2008–2025) from ESPN Cricinfo / Kaggle / official IPL site.

---

## 🛠️ Data Cleaning & Preprocessing
- Handled missing values (e.g., abandoned matches).  
- Standardized team and player names.  
- Converted date fields to proper datetime formats.  
- Engineered new features (e.g., strike rate, economy, margin type).  
- Merged datasets (matches + ball-by-ball + players + teams).  

---

## ❓ Key Questions Explored
- Which teams have been the most successful across seasons?  
- How does toss decision impact match outcomes?  
- Which venues favor batting vs. bowling sides?  
- Who are the top run scorers and wicket-takers?  
- How have scoring patterns evolved across seasons?  
- What role does home advantage play?  
- Which players have been the most consistent throughout IPL history?  
- What new trends can be observed in IPL 2023–2025?  

---

## 🔑 Key Insights

### 🏆 Team Analysis
- Identified the most successful teams across seasons.  
- Toss decisions have a measurable impact on match outcomes.  
- Certain venues consistently favor batting sides, while others benefit bowlers.  

### 👨‍💻 Player Performance
- Top run scorers and wicket-takers highlighted across IPL history.  
- Specific batsmen excel in powerplay, middle overs, and death overs.  
- Bowlers dominating under pressure situations identified.  

### 📈 Match Trends
- Average first-innings scores have evolved significantly across seasons.  
- Rule changes (timeouts, impact player) introduced distinct scoring patterns.  
- Home advantage plays a strong role in determining match outcomes.  

### 🔄 Seasonal & Evolution Insights
- Team strategies have evolved season by season.  
- Consistent performers across multiple years identified.  
- New trends (especially from 2023–2025) highlight changing IPL dynamics.  

---

## 📊 Visualizations
The EDA includes interactive and static visualizations:
- Matches played per season.  
- Total runs and runs-per-match trends across seasons.  
- Venue-wise batting vs. bowling performance.  
- Top batsmen and bowlers across eras.  
- Evolution of first-innings scores and boundary contributions.  

---

## 🚀 Tools & Libraries
- **Python**  
- **Pandas, NumPy** → Data cleaning & transformation  
- **Matplotlib, Seaborn** → Data visualization  

---

## 📂 Project Structure
IPL.ipynb # Main analysis notebook
ball_by_ball_data.csv # Ball-by-ball dataset
ipl_matches_data.csv # Match-level dataset
players-data.csv # Players dataset
teams_data.csv # Teams dataset
README.md # Project documentation


---

## 📌 Conclusion
This analysis highlights how the IPL has transformed into a **data-driven, strategy-oriented league** with evolving trends in scoring, toss decisions, and player performance across years.

---

