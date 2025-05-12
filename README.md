# Module 5 Challenge: Pymaceuticals - Tumor Response Analysis

## Overview

This project analyzes data from a study conducted by **Pymaceuticals, Inc.** to test various drug regimens for treating squamous cell carcinoma (SCC) in mice. Over 45 days, 249 mice received different treatments, and their tumor volumes were tracked.

The analysis includes:

- Data cleaning to remove duplicate mouse/timepoint records
- Summary statistics for each drug regimen
- Visualizations:
  - Bar and pie charts using both Pandas and Matplotlib
  - Line plot tracking tumor volume over time for a mouse on Capomulin
  - Scatter plot comparing mouse weight vs. average tumor volume
  - Boxplots showing tumor volume distributions
- Correlation and linear regression analysis of weight vs. tumor size

## Technologies Used

- Python
- Pandas
- Matplotlib
- SciPy

## Key Findings

- Capomulin and Ramicane showed the most consistent tumor volume reduction.
- A strong positive correlation was found between **mouse weight** and **average tumor volume** under Capomulin treatment.
- Linear regression confirmed this relationship and provided a visual model.

## Files

- `Mouse_metadata.csv` — Metadata on each mouse
- `Study_results.csv` — Tumor volumes over time
- `pymaceuticals_starter.ipynb` — Python notebook containing the full analysis

