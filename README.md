# Serving-up-Safety
# Serving Up Safety: Analyzing NYC Restaurant Health Grades

**Author:** Ngawang Choega  
**Program:** MS in Data Science, Pace University NYC  
**Class:** Practical Data Science

---

## 📋 Project Overview

NYC restaurants are graded by the Department of Health based on inspection results—but predicting what grade a restaurant will get is challenging. This project analyzes health inspection records to uncover risk factors and builds a predictive model so restaurants and inspectors can be proactive about food safety.

---

## 🗂️ Table of Contents

- [Project Overview](#project-overview)
- [Data](#data)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Modeling Methods](#modeling-methods)
- [Key Findings](#key-findings)
- [Business Recommendations & Next Steps](#business-recommendations--next-steps)
- [Project Materials](#project-materials)

---

## 📝 Executive Summary

- **Problem:** Predicting a restaurant’s health grade before inspection is tough, making it harder for owners to improve proactively and for inspectors to target high-risk restaurants.
- **Solution:** Built a logistic regression model using NYC’s inspection data to forecast whether a location will receive an A, B, or C.
- **Impact:**  
    - Helps restaurants fix issues before inspections.
    - Helps health officials focus on higher-risk cases.

---

## 📊 Data

- **Source:** NYC Open Data – Department of Health and Mental Hygiene ([NYC Restaurant Inspection Results])
- **Sample:** 274,740 inspection records (2015–2025), cleaned to 193,892 rows.
- **Grades:** A, B, C, Pending (P)
- **Note:** Excludes new uninspected establishments.

---

## 🔎 Exploratory Data Analysis

- Over 85,000 restaurants received A grades—good compliance overall.
- Most common violations: poorly maintained equipment, pest conditions, surface sanitation.
- Some cuisines (seafood, Chinese) and boroughs (Brooklyn, Bronx) had higher rates of non-A grades.

---

## 🤖 Modeling Methods

- **Prediction Goal:** A, B, or C grade.
- **Features:** Borough, Cuisine Type, Inspection Type (one-hot encoded).
- **Model:** Multinomial Logistic Regression (sklearn)
- **Performance:** 78% accuracy (highest for A grades; lower for B/C due to class imbalance)

---

## 🧭 Key Findings

- Location, cuisine, and inspection type are key risk factors.
- Brooklyn/Bronx and certain cuisines trend toward lower grades.
- Re-inspections are early risk warnings.

---

## 💼 Business Recommendations & Next Steps

- **Adopt model** in inspection workflow to flag at-risk locations.
- **Targeted outreach/training** for high-risk cuisines and boroughs.
- **Future Work:** Explore advanced models, address class imbalance, consider new risk factors.

---

## 🔗 Data Source

NYC Health Restaurant Grades

---

## 📫 Contact

[Ngawang Choega](mailto:your.email@domain.com) | [LinkedIn](https://www.linkedin.com/in/yourprofile)

---

*Project for Practical Data Science, MS in Data Science, Pace University NYC.*
