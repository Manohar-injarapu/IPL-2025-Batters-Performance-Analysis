# IPL-2025-Batters-Performance-Analysis

This repository contains a comprehensive end-to-end data analysis of the IPL 2025 Batters dataset. The goal is to demonstrate the complete workflow from data loading to advanced analytics and visualization, covering all major topics in data science.

Project Overview

This project performs an end-to-end exploratory data analysis (EDA) and visualization of IPL 2025 Batters statistics using Python, Pandas, NumPy, and Matplotlib.
---

## 🔍 Analysis Workflow

### 1️⃣ Data Loading & Inspection
- Loaded dataset using Pandas.
- Verified shape, columns, and data types.
- Checked for missing values and duplicates.

### 2️⃣ Data Cleaning
- Standardized column names for consistency.
- Converted averages and scores to numeric types.
- Cleaned highest score values (removed `*`).
- Removed players with very low innings (less than 3).
- Standardized team names (uppercase).

### 3️⃣ Exploratory Data Analysis (EDA)
- Analyzed distribution of runs and strike rates.
- Identified outliers (top performers).
- Conducted player consistency analysis.
- Evaluated team-wise batting strength.

### 4️⃣ Feature Engineering
- Created new features:
  - Runs per match
  - Boundary runs contribution
  - % of runs from boundaries
  - Strike rate categories (Low / Medium / High)
  - Performance consistency flags

### 5️⃣ Advanced Analysis
- Player ranking (overall and team-wise).
- Team vs team comparison (e.g., GT vs RCB).
- Correlation analysis.
- Z-score normalization.
- Identification of underrated players.

---

## 📊 Visualizations Included

- ✔ Line plots – Runs vs Matches
- ✔ Scatter plots – Strike Rate vs Runs
- ✔ Bar charts – Top scorers & team averages
- ✔ Histograms – Runs distribution
- ✔ Box & Violin plots – Outliers & density
- ✔ Heatmaps – Correlation analysis
- ✔ Subplots – Multi-view analysis
- ✔ Groupby plots – Team-wise insights

Each plot includes clear titles, labels, and observations.

---

## 📈 Key Insights

- IPL batting data is right-skewed.
- Few players dominate total runs.
- Boundary hitting is a major run driver.
- High strike rate does not always mean high runs.
- Balanced teams outperform star-dependent teams.
