# Aadhaar Data Hackathon – Insights

**Unlocking Societal Trends in Aadhaar Enrolment and Updates**  
Hackathon submission analyzing UIDAI Aadhaar datasets (demographic + biometric).

**Team:** Anirban Chandra, Abhiraj Adhikary, Pralay Halder, Anik Chand  
**Submission Date:** January 20, 2026

## Overview

We analyzed Aadhaar enrolment and biometric data to uncover:

- Demographic patterns (state concentration, youth dependency, district outliers)
- Temporal & operational trends (monthly growth, day-of-week efficiency)
- Biometric age-group insights (5–17 vs 17+, time series, top districts, distributions)

## Approach Summary

### Data Cleaning

- Standardized state names (e.g. "Westbengal" → "West Bengal")
- Corrected geopolitical assignments (e.g. Hyderabad/Warangal → Telangana)
- Removed garbage district entries (e.g. "Sector 5", "Near Hospital")
- Parsed dates properly, handled missing/invalid values

### Key Analyses & Visualizations

**Demographic Report**

- Top states by age group (youth vs adult)
- State population heatbar
- Youth dependency ratio ranking
- Monthly trends (absolute + stacked)
- Day-of-week average enrollment
- State variance with error bars
- Extreme district youth ratios

**Biometric Report**

- Time series of bio-age counts
- State-level comparison & overall pie
- Top 10 districts (5–17 and 17+)
- Histogram distributions

All plots generated via Python (Pandas + Matplotlib/Seaborn) and embedded in LaTeX PDFs.
