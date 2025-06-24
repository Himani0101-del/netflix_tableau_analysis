# netflix_tableau_analysis
# 📺 Netflix Data Analysis: EDA + Tableau Dashboard

Welcome! This project is part of my data analytics portfolio, where I explore global Netflix content using Python and Tableau. As a recent graduate in Data Analytics from Seneca College—and a mom of two—I'm excited to apply what I've learned in a real-world dataset scenario.

---

## 📌 Project Overview

The goal of this project is to:
- Clean and explore the Netflix dataset
- Handle missing values with meaningful logic (not just imputation)
- Analyze content by country, type, rating, and duration
- Build an interactive Tableau dashboard for easy visualization

---

## 🧹 Data Cleaning (Python)

Tools used: `Pandas`, `NumPy`

Key cleaning steps:
- Converted date columns to datetime
- Extracted duration (in minutes or seasons) and categorized into Short, Medium, Long
- Split multi-country fields and used `.explode()` for better country-level analysis
- Handled missing values thoughtfully:
  - Used `'Unknown'` where appropriate instead of blind imputation
  - Dropped rows only when necessary (e.g., invalid or insufficient data)

Explore the notebook 👉 netflix_L1

---

## 📊 Visualization (Tableau)

I designed an interactive dashboard to answer key business-style questions like:
- Which countries have the most content?
- What's the breakdown between TV Shows and Movies globally?
- How do rating groups (Mature, Family-Friendly) vary by country?
- What are the typical durations across regions?

🔗 View the dashboard on Tableau Public 👉(https://public.tableau.com/views/netflix_17506419663730/Dashboard1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## 📁 Files

- netflix_L1 – Jupyter Notebook with all cleaning + EDA
- netflix_cleaned_exploded.csv – Cleaned dataset ready for Tableau
- `README.md` – This file

---

## 💡 Future Ideas

- Add time series analysis on release trends
- Build predictive models on viewer ratings (if available)
- Integrate IMDb or Rotten Tomatoes data for enrichment

---

## 🙋‍♀️ About Me

I'm transitioning into data analytics after completing my graduate certificate in Data Analytics from Seneca College. This is one of my first portfolio projects, and I'm always open to feedback, suggestions, or mentorship!

Let’s connect on www.linkedin.com/in/himani-kathuria-578020aa👋

