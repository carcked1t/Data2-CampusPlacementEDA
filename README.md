# Campus Placement Analysis – High-Impact Exploratory Data Analysis

## Overview
This project performs an end-to-end exploratory data analysis (EDA) on campus placement data to identify the **key academic, experiential, and skill-based factors** that influence student placement outcomes.

The goal is not prediction, but **understanding employability drivers** using real-world student data.

---

## Problem Statement
Placement outcomes are often attributed to academic performance alone.  
This project investigates whether factors such as internships, training, communication skills, and project work play a more significant role in employability.

---

## Dataset
The dataset contains anonymized student records including:
- Academic performance (10th, 12th, CGPA)
- Practical exposure (internships, training, projects)
- Skills (communication level)
- Academic risk factors (backlogs)
- Final placement outcome

Personally identifiable information was removed during analysis.

---

## Project Structure

project/

├── data/ # Raw dataset

├── notebooks/ # Step-by-step analysis notebooks

├── visuals/ # Final presentation-ready plots

├── insights.md # Business and decision-focused insights

└── README.md


---

## Methodology
1. Data understanding and schema inspection
2. Cleaning and standardization of academic and binary features
3. Univariate analysis to understand feature distributions
4. Bivariate and multivariate analysis to uncover relationships
5. Insight extraction and documentation

All decisions and assumptions are explicitly documented in notebooks.

---

## Key Findings
- Internship experience is the strongest positive indicator of placement
- Communication skills correlate more strongly with placement than marginal CGPA improvements
- Backlogs reduce placement probability but do not eliminate it
- Practical exposure compounds employability outcomes

Detailed insights are available in `insights.md`.

---

## Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

---

## Why This Project Matters
This analysis can help:
- Students prioritize skill-building and internships
- Placement cells design targeted interventions
- Institutions align curriculum with industry expectations

---

## Limitations
- Dataset limited to a single cohort
- Subjective skill ratings
- Observational (non-causal) analysis

---

## Author
Urja Srivastava

