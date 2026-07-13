

# IPL Data Engineering, SQL Querying and Exploratory Data Analysis Project

Project Overview

This project presents an end-to-end analysis of Indian Premier League (IPL) match data using Data Engineering techniques, SQL querying, and Exploratory Data Analysis (EDA).

The objective of this project was to transform raw cricket data into meaningful insights by performing data cleaning, handling missing values, detecting outliers, executing SQL queries, and creating visualizations to understand team performance and scoring patterns across IPL seasons.

The project demonstrates practical skills in data preprocessing, data analysis, business storytelling, and visualization using Python and SQL.


---

# Project Objectives

Perform data cleaning and preprocessing on raw IPL datasets.

Handle missing values using appropriate techniques.

Identify and remove duplicate records.

Detect outliers using the IQR method.

Perform SQL querying to extract business insights.

Create meaningful visualizations to understand trends and patterns.

Generate actionable insights from IPL match data.



---

# Dataset Information

The project uses two datasets:

1. matches.csv

Contains match-level information such as:

Match ID

Season

City

Teams

Toss Winner

Match Winner

Venue

Match Result


2. deliveries.csv

Contains ball-by-ball information such as:

Match ID

Innings

Over Number

Batting Team

Bowling Team

Batter

Bowler

Runs Scored

Extras

Wickets



---

# Technologies Used

Python

Pandas

NumPy

SQL

Matplotlib

Google Colab

GitHub



---

# Data Engineering Process

Data Collection

Imported IPL datasets into Google Colab environment.


Data Cleaning

Checked dataset structure and data types.

Identified missing values across both datasets.

Applied suitable missing value treatment techniques.

Removed columns with excessive missing values.

Validated the cleaned dataset.


Duplicate Handling

Checked for duplicate records.

Removed duplicate entries to maintain data quality.


Outlier Detection

Detected outliers in numerical columns using the Interquartile Range (IQR) method.

Outliers were retained because they represent genuine cricket events such as boundaries and extra runs.



---

# SQL Analysis

SQL queries were used to answer analytical questions and extract business insights.

The project includes:

Filtering using WHERE

Aggregation using GROUP BY

Conditional filtering using HAVING

Sorting using ORDER BY

Limiting results using LIMIT

Combining datasets using JOIN



---

# Exploratory Data Analysis

Several visualizations were created to understand scoring trends and team performance:

Box Plot for Total Runs Distribution

Histogram for Run Distribution

Bar Chart for Team Wins

Scatter Plot for Run Patterns

Grouped Analysis for Team Performance



---

# Key Findings and Insights

Most deliveries in IPL result in either a dot ball or a single run.

Boundaries such as fours and sixes contribute significantly to total team scores.

Certain franchises consistently perform better across multiple IPL seasons.

Teams with stronger batting performances generally have higher winning probabilities.

High values identified during outlier detection represent genuine cricket events rather than data quality issues.

Match outcomes are influenced by multiple factors including batting strength, team consistency, and match conditions.



---

# Project Structure

IPL-Data-Engineering-SQL-and-EDA-Analysis/
│
├── IPL_Analysis.ipynb
├── matches.csv
├── deliveries.zip
├── eda_visualizations/
│   ├── boxplot_total_runs.png
│   ├── histogram_total_runs.png
│   ├── top_winning_teams_barchart.png
│   ├── scatterplot_runs.png
│   └── groupby_analysis.png
│
├── requirements.txt
└── README.md


---

# Skills Demonstrated

Data Cleaning

Data Validation

Missing Value Treatment

Outlier Detection

SQL Query Writing

Data Visualization

Exploratory Data Analysis

Business Insight Generation

Data Storytelling

GitHub Project Management



---

#Future Improvements

Build an interactive Power BI dashboard.

Perform player-level performance analysis.

Create predictive models for match outcomes.

Develop automated reporting pipelines.


