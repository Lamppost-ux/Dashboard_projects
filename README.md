# Data Jobs Market Analysis Dashboard

![Dashboard Page 1](/images/dashboard%201.0_pg1.png)
## Introduction

This dashboard was created for **Job Seekers, Job Transitioners, and Job Swappers** to solve a common problem: information about the data jobs market is scattered and hard to grasp. Using *real-world dataset of 2024 data science job postings* (including titles, salaries, and location), this project provides a single, easy-to-use interface to explore market trends and compensation.

## Data Source
- **Dataset:** 2024 Data Science Job Postings from [Luke Barousse's Data Jobs Database](https://lukebarousse.com/data)
- **Records:** 479,000+ job postings
- **Time Period:** January - December 2024
- **Columns:** Job title, salary (yearly/hourly), location, company, skills required, work type, benefits.

## Skills Showcased

- **Power Query (ETL):** Cleaned and transformed raw data—handled missing values, standardized data types, created calculated columns
- **DAX Measures:** Created custom calculations for median salaries, job counts, and percentage metrics
- **Data Modeling:** Structured relationships between tables for efficient analysis
- **Visualization Design:** 
  - **Column/Bar Charts** for comparisons
  - **Line Charts** for time-series trends
  - **Map Charts** for geographic distribution
  - **KPI Cards** for at-a-glance metrics
  - **Tables** for detailed, sortable data
  - **Drill-through pages** for interactive exploration
- **Dashboard Design:** Created an intuitive, user-friendly interface with clear visual hierarchy

## Dashboard Overview

### Page 1: High-Level Market View

![Dashboard Page 1](/images/dashboard%201.0_pg1.png)

This is the mission control for the data job market. It showcases key KPIs like total job count, median salaries, and top job titles to give a quick understanding of what's happening in the job market at a glance.

### Page 2: Job Title Drill Through

![Dashboard Page2](/images/dashboard1.0_pg2.png)

This is the deep-dive page. From the main dashboard, you can drill through to this view to get specific details for a single job title, including salary ranges, work-from-home stats, top hiring platforms, and a global map of job locations.

## Key Insights

From analyzing 479K+ job postings, here's what the data reveals:

1. **Top Skills in Demand:** Python and SQL dominate across all data roles
2. **Salary Leaders:** Senior Data Scientists ($156K) and Machine Learning Engineers ($155K) command the highest compensation
3. **Remote Reality Check:** Only 10% of Data Analyst positions explicitly offer work-from-home
4. **Seasonal Hiring Patterns:** Job postings peaked in July (51K) and hit a low in November (14K)
5. **Geographic Concentration:** North America leads in data job opportunities

These insights help job seekers understand where to focus their skill development and which roles offer the best compensation.

## Conclusion

This dashboard showcases how raw data (in this case; Job Posting data) can be transformed for career analysis using Power BI. It allows for use of slicers and drill through to making informed decisions about specific career paths.