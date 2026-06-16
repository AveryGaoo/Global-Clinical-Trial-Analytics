# Global Clinical Trial Analytics

## Project Overview
This project analyzes global clinical trial data conducted by major pharmaceutical companies.

The dataset contains clinical trial records from 1984 to 2020, covering multiple sponsors, disease areas, trial phases, enrollment sizes, and trial statuses.

The objective of this project is to explore trends in clinical research activity, evaluate sponsor performance, identify popular therapeutic areas, and assess clinical trial risks across different phases.

### Dataset Summary
- Total Clinical Trials: 13,485
- Total Sponsors: 10
- Total Disease Areas: 852
- Total Enrolled Participants: 5,820,807
- Time Period: 1984–2020

### Data Source
Clinical trial dataset compiled from publicly available clinical trial records.
Source file:
`AERO-BirdsEye-Data.csv`

### Analysis Scope
The analysis focuses on:
- Clinical trial trends over time
- Trial phase distribution
- Trial status distribution
- Enrollment distribution
- Sponsor activity analysis
- Treatment area popularity
- Clinical trial failure rates
- Enrollment performance by sponsor and phase

---

## Business Questions
### Q1
Which pharmaceutical companies are the most active?

### Q2
Which treatment areas are the most popular?

### Q3
Which clinical trial phase has the highest failure rate?

### Q4
Which sponsors enroll the largest number of participants?

### Q5
What is the average enrollment size by phase?

### Q6
Which phase has the largest total enrollment?

---

## Key Findings
### Q1 – Most Active Sponsors
GSK conducted the largest number of clinical trials, followed by Novartis and Pfizer.

### Q2 – Most Popular Treatment Areas
Type 2 Diabetes was the most frequently studied disease area, followed by Breast Cancer and Hypertension.

### Q3 – Failure Rate by Phase
Phase 2/Phase 3 trials showed the highest failure rate (17.27%).

### Q4 – Sponsors with Largest Enrollment
GSK enrolled more than 1.25 million participants, ranking first among all sponsors.

### Q5 – Average Enrollment by Phase
Phase 3 trials had the highest average enrollment size (~796 participants).

### Q6 – Total Enrollment by Phase
Phase 3 accounted for the largest total enrollment volume (3.89 million participants), showing its central role in clinical development.

---

## Technologies Used
- SQL
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- VS Code

---

## Project Structure
```
Global-Clinical-Trial-Analytics
│
├── data
│   ├── raw
│   └── clean
│
├── sql
│   ├── Q1.sql
│   ├── Q2.sql
│   ├── Q3.sql
│   ├── Q4.sql
│   ├── Q5.sql
│   └── Q6.sql
│
├── notebooks
│   ├── 01_data_understanding.ipynb
│   ├── 02_exploratory_analysis.ipynb
│   └── 03_dashboard.ipynb
│
├── screenshots
│   ├── sql
│   └── EDA
│
├── Dashboard
│
└── report
```

---

## Author

Rui Gao (Avery)

Master of Management Information Systems - University of Lisbon

Project Type:
SQL + Python + Data Visualization + Business Analytics