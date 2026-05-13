# 🏏 T20 Cricket Team Performance Analyzer

A complete cricket analytics dashboard built using **Python**, **Pandas**, **Matplotlib**, **Seaborn**, and **Streamlit** to analyze T20 cricket team performance through batting, bowling, and team-level insights.

This project transforms raw cricket score data into meaningful visual analytics and automated performance summaries.

---

## 📌 Project Overview

The **T20 Cricket Team Performance Analyzer** is a data analytics application designed to evaluate player and team performances across one or multiple T20 matches.

The project began as an exploratory data analysis notebook using IPL 2024 match data and was later converted into a fully interactive Streamlit web application with:

- Multi-file upload support
- Data validation
- Feature engineering
- Batting analytics
- Bowling analytics
- Team performance summaries
- Interactive visualizations

---

## 🚀 Try Live Project

🔗 **Live Demo:**  
[Project Live Link](https://t20-team-performance-analyzer.streamlit.app/)

> Replace the above link with your actual deployed Streamlit project URL.

---

## 📸 Project Preview

<!-- Add screenshots here -->

| Dashboard | Batting Analytics |
|---|---|
| Add Screenshot | Add Screenshot |

---

## ✨ Features

### 🏏 Batting Analytics
- Individual runs scored analysis
- Strike rate comparison
- Runs contribution charts
- Batting consistency analysis
- Batting order performance
- Phase-wise wickets lost analysis

### 🎯 Bowling Analytics
- Wickets taken analysis
- Economy rate comparison
- Wickets contribution charts
- Bowling consistency analysis
- Match-wise bowling trends

### 📊 Team Summary
- Team runs and wickets per match
- KPI cards for top performers
- Automated narrative insights
- Team contribution breakdowns

### ⚙️ System Features
- CSV and Excel upload support
- Multi-file dataset merging
- Automated data cleaning
- Validation with descriptive error handling
- Cached processing for performance optimization

---

## 🧠 Problem Statement

At the grassroots level, cricket performance is usually judged manually and subjectively. This often leads to:

- Biased player evaluation
- Inaccurate award decisions
- Lack of statistical tracking
- Poor team strategy planning

This project solves these issues by introducing a structured, data-driven analytics system accessible even to non-technical users.

---

## 🎯 Objectives

- Build an unbiased cricket analytics system
- Analyze batting and bowling performance statistically
- Measure player consistency across matches
- Identify team strengths and weaknesses
- Generate automated performance summaries
- Provide a simple upload-based interface for users

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data cleaning and analysis |
| NumPy | Numerical operations |
| Matplotlib | Visualization |
| Seaborn | Statistical plotting |
| Streamlit | Interactive web application |

---

## 📂 Dataset Structure

Each row in the dataset represents a player's performance in one match.

### Required Columns

- `Match_No`
- `Player_Name`
- `Role`
- `Batting_Position`
- `Batting_Start_Over`
- `Out_Over`
- `Balls_Played`
- `Runs_Scored`
- `Overs_Bowled`
- `Runs_Given`
- `Wickets_Taken`

### Supported Formats
- `.csv`
- `.xlsx`

---

## 🔄 Data Pipeline

### 1️⃣ Data Loading
- Upload one or more CSV/Excel files
- Files are merged automatically

### 2️⃣ Data Validation
Validation checks include:
- T20 over constraints
- Missing values
- Invalid batting/bowling stats
- Player count validation

### 3️⃣ Data Cleaning
- Missing value handling
- Role normalization
- Type conversion
- Data consistency fixes

### 4️⃣ Feature Engineering
Generated metrics:
- Strike Rate
- Economy Rate
- Batting Status
- Dismissal Status
- Consistency Scores

---

## 📊 Analytical Modules

### 🏏 Batting Module
- Total runs scored
- Runs contribution
- Match-wise run trends
- Strike rate comparison
- Batting consistency
- Batting order analysis
- Phase-wise wickets lost

### 🎯 Bowling Module
- Total wickets taken
- Wicket contribution
- Match-wise wicket trends
- Economy comparison
- Bowling consistency

### 📈 Summary Module
- Match summaries
- KPI cards
- Team insights
- Automated performance narratives

---

## 📌 Version History

### Version 1.0
- Notebook-based analysis
- Static visualizations
- IPL 2024 dataset analysis

### Version 2.0
- Streamlit web application
- Interactive dashboard
- Multi-file upload support
- Enhanced validation system

### Version 2.01
- Improved UI/UX
- KPI cards
- Better validation logic
- Additional dashboard sections

---

## ⚠️ Known Limitations

- Supports only T20 format currently
- Maximum 22 unique players per upload
- No fielding statistics support
- No extras tracking

---

## 🔮 Future Scope

- ODI and Test match support
- Opposition team analysis
- Career player profiles
- PDF report export
- Match result correlation analysis

---

## 📁 Project Structure

```bash
T20-Cricket-Team-Performance-Analyzer/
│
├── app.py
├── requirements.txt
├── README.md
├── datasets/
├── notebooks/
├── assets/
└── screenshots/
