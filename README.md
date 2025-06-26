# 📊 A/B Testing: Simulated Marketing Campaign Analysis

This project analyzes a simulated A/B test comparing two email marketing campaigns (Group A and Group B). The goal is to determine which campaign was more effective in driving user engagement and conversions.

---

## Project Overview

- **Objective**: Evaluate which campaign leads to better overall conversion.
- **Data**: Simulated dataset with user-level activity across three funnel stages:
  - Email Opened
  - Link Clicked
  - Purchase Made

---

## What I Did

### 1. Exploratory Data Analysis
- Checked for missing data and validated group balance
- Computed group sizes and conversion metrics across the funnel

### 2. Funnel Analysis
- Open Rate
- Click-Through Rate (CTR)
- Purchase Rate (among users who clicked)
- Overall Conversion Rate (from email sent to purchase)

### 3. Statistical Testing
- Ran **z-tests** for proportions at each stage
- Set up reusable test functions using `statsmodels`

### 4. Stretch Goal – Bayesian A/B Testing
- Modeled conversion uncertainty using **Beta distributions**
- Simulated 100,000 posterior samples per group
- Computed **P(Group B > Group A)** as a decision metric
- Visualized posterior curves with `matplotlib`

---

## Key Takeaways

- **No statistically significant difference** was found between the two campaigns at any funnel stage.
- Bayesian analysis also showed **only 34.05% probability** that Group B outperforms Group A overall.
- Recommendation: **Do not roll out Group B**, consider testing a more differentiated variation.

---

## Tools & Libraries

- Python, Jupyter Notebook
- `pandas`, `numpy`, `matplotlib`
- `statsmodels` for z-tests
- `scipy.stats.beta` for Bayesian simulation

---

## 📁 Files in This Repository

- `A_B_Testing_Notebook.ipynb` → Full project notebook with code, charts, and markdowns
- `README.md` → This file

---

## ✅ Skills Demonstrated

- A/B test design and interpretation
- Statistical hypothesis testing (frequentist and Bayesian)
- Data storytelling and decision-making
- Clean, modular code and reproducibility

---

## 📌 Author

**[Pratiti Soumya]**  
[LinkedIn](https://linkedin.com/in/pratitisoumya) • [Portfolio](https://yourportfolio.com) • [Email](mailto:pratitisoumya11@outlook.com)

---

