# ⚽ FootballIQ – International Football Analytics Dashboard

![Dashboard Preview](dashboard/Football_Dashboard.png)

## 📌 Project Overview

**FootballIQ** is an end-to-end Business Intelligence project that analyzes over **49,000 international football matches** from around the world.

The project demonstrates the complete analytics lifecycle—from raw CSV datasets to an executive dashboard—using data cleaning, dimensional modeling, KPI development, and interactive visualizations.

This project was created to simulate how a **Business Intelligence Analyst** would build a reporting solution for organizations such as **FIFA, UEFA, sports broadcasters, football associations, and analytics teams**.

---

# 🎯 Business Problem

International football has generated decades of match data across hundreds of tournaments and countries.

While this data is publicly available, extracting meaningful insights is challenging due to:

- Large historical datasets
- Multiple tournaments
- Team name inconsistencies
- Historical country names
- Match-level and player-level data spread across multiple files

The objective of this project is to transform raw football data into an interactive dashboard that enables stakeholders to analyze:

- Team performance
- Goal scoring trends
- Tournament statistics
- Historical performance
- Geographic distribution
- Penalty shootout outcomes

---

# 📂 Dataset

The project uses four CSV datasets.

| File | Description |
|------|-------------|
| results.csv | Historical international football match results |
| goalscorers.csv | Goal scorer information including penalties and own goals |
| shootouts.csv | Penalty shootout results |
| former_names.csv | Historical country name mappings |

Dataset Size

- ⚽ 49,509 Match Records
- 🥅 47,898 Goal Records
- 🏆 682 Penalty Shootouts
- 🌍 300+ National Teams
- 📅 Matches spanning more than 150 years

---

# 🧹 Data Cleaning

The following preprocessing steps were performed:

- Removed duplicate records
- Handled missing values
- Converted date fields into Date format
- Standardized country names
- Mapped historical country names
- Verified score consistency
- Created analytical dimensions
- Validated relationships between datasets

---

# 🏗 Data Model

The project follows a **Star Schema** for analytical reporting.

### Fact Tables

- Fact Matches
- Fact Goals
- Fact Shootouts

### Dimension Tables

- Dim Team
- Dim Tournament
- Dim Date
- Dim Location
- Dim Former Country Names

This structure improves performance and enables scalable reporting.

---

# 📊 Dashboard Overview

The dashboard provides executive-level insights through multiple analytical sections.

### Executive Overview

- Total Matches
- Total Goals
- Average Goals per Match
- Total Teams
- Total Competitions
- Total Shootouts

---

### Team Performance

- Win Percentage
- Goals Scored
- Goals Conceded
- Goal Difference
- Home vs Away Performance
- Team Rankings

---

### Goal Analysis

- Top Goal Scorers
- Goal Distribution
- Penalty Goals
- Own Goals
- Goals by Match Minute

---

### Tournament Analysis

- Tournament Distribution
- Competition Statistics
- Goals by Tournament
- Tournament Popularity

---

### Historical Trends

- Goals by Year
- Goals by Decade
- Match Growth
- Football Evolution

---

### Geographic Analysis

- Matches by Country
- Global Football Distribution
- Host Nations
- Home Advantage

---

### Head-to-Head Analysis

Compare any two teams using:

- Wins
- Draws
- Losses
- Goals
- Historical Performance

---

### Shootout Analysis

- Shootout Wins
- Penalty Success
- Historical Shootouts

---

# 📈 Key Performance Indicators (KPIs)

- Total Matches
- Total Goals
- Average Goals per Match
- Total Teams
- Total Competitions
- Home Wins
- Away Wins
- Draw Percentage
- Penalty Shootouts
- Top Performing Team

---

# 🛠 Technologies Used

- Microsoft Excel
- CSV Files
- Data Cleaning
- Data Modeling
- Business Intelligence
- Dashboard Design
- Power BI Concepts
- KPI Design
- Data Visualization

---

# 📸 Dashboard Preview

## Executive Dashboard

> *(Insert dashboard screenshot here)*

---

# 💡 Key Insights

The dashboard helps answer questions such as:

- Which national teams have the highest historical win percentage?
- How has international football evolved over time?
- Which tournaments produce the most goals?
- Which countries host the most international matches?
- What is the impact of home advantage?
- Which teams perform best in penalty shootouts?
- Which players have scored the most international goals?

---

# 📁 Repository Structure

```
FootballIQ
│
├── data
│   ├── results.csv
│   ├── goalscorers.csv
│   ├── shootouts.csv
│   └── former_names.csv
│
├── excel
│   └── Football_BI_Project_Workbook.xlsx
│
├── dashboard
│   └── Football_Dashboard.png
│
├── screenshots
│
└── README.md
```

---

# 🚀 Future Improvements

- Interactive Power BI Dashboard
- Real-Time Football API Integration
- Machine Learning Match Prediction
- Player Performance Analytics
- Team Ranking Models
- Mobile Responsive Dashboard
- Advanced DAX Measures
- Predictive Analytics

---

# 🎓 Learning Outcomes

Through this project, I strengthened my skills in:

- Data Cleaning
- Data Transformation
- Data Modeling
- KPI Development
- Dashboard Design
- Business Intelligence
- Data Storytelling
- Sports Analytics
- Analytical Thinking

---

# 📬 Contact

**Harsh Shah**

📧 Email: *Add your email here*

💼 LinkedIn: *Add your LinkedIn profile*

🐙 GitHub: *Add your GitHub profile*

---

## ⭐ If you found this project interesting, consider giving it a star!
