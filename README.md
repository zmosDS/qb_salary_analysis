# Quarterback Salary Analysis

Exploratory analysis examining how NFL quarterback salaries relate to team success.  
The dataset, collected and cleaned manually from multiple public sources, explores patterns between annual salary, salary as a percentage of the team cap, and win percentage.

![QB Salary Clusters](qb_salary_clusters.png)

## Goal
To investigate whether higher quarterback pay correlates with better team performance and to identify possible tiers or clusters in salary-to-performance relationships.

## Built With
- Python  
- pandas, matplotlib, seaborn  
- scikit-learn (K-Means clustering)

## Features
- Salary vs. win percentage scatter plots (absolute and cap-adjusted)  
- K-Means clustering to identify QB salary tiers  
- Analysis of win-percentage variability across salary groups  

## Files
```
qb_salary_analysis/
├── qb_salaries.ipynb # Main analysis notebook
├── data/ # Cleaned salary and performance data
├── figures/ # Plots used in README
└── README.md # Project overview
```

## Data Source
Self-compiled dataset using publicly available NFL salary and team performance data (2020–2023 seasons).

