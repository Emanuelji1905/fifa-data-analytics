# FIFA Player Analytics & Predictive Modeling ⚽📊

## Overview
An end-to-end Python data analysis and machine learning project that extracts, processes, and models data from over 17,000 FIFA players. This project covers the entire data lifecycle: from raw data extraction via web scraping to predictive modeling and mathematical optimization for budget-constrained squad building.

## Key Features
* **Web Scraping:** Automated extraction of player statistics and attributes from the web (HTML parsing).
* **Data Preprocessing:** Cleaning and structuring a dataset of 17,406 records (handling missing values, data type normalization, and duplicate removal).
* **Exploratory Data Analysis (EDA):** Visualizing distributions, correlations, and trends (e.g., age distribution, club player counts) to extract actionable insights.
* **Predictive Modeling (Machine Learning):** 
  * Market value prediction using Linear Regression (RMSE evaluation).
  * High-potential player classification using Logistic Regression.
  * Player profiling and clustering using K-Means.
* **Prescriptive Analytics & Optimization:** Algorithmic squad optimization (using Greedy algorithms and Linear Programming / `linprog`) subject to a €150M budget constraint.

## Tech Stack
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Machine Learning:** Scikit-learn
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebooks

## Repository Structure
```text
├── data/                   # Raw and processed datasets (Note: large csv files are in .gitignore)
├── notebooks/              # Jupyter notebooks containing EDA, ML models, and optimization
├── scripts/                # Python scripts for web scraping and data pipeline
├── README.md
└── requirements.txt        # Project dependencies
