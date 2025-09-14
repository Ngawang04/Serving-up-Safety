# 🍽️ Serving Up Safety: Analyzing NYC Restaurant Health Grades

[![Project Status: Active](https://img.shields.io/badge/status-active-brightgreen.svg)]()
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)]()

**Author:** Ngawang Choega  
**Degree:** MS in Data Science, Pace University NYC  
**Course:** Practical Data Science  
**Semester:** March–April 2025

---

## 📖 Overview

NYC restaurants are graded by the Department of Health based on inspection results—but predicting a restaurant’s grade is complex. This project analyzes health inspection records to uncover key risk factors and builds a predictive model to help restaurants and health officials be more proactive about food safety.

---

## 🗂️ Table of Contents

- [Overview](#overview)
- [Data](#data)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Modeling Methods](#modeling-methods)
- [Key Findings](#key-findings)
- [Business Recommendations & Next Steps](#business-recommendations--next-steps)
- [Project Materials](#project-materials)
- [Contact](#contact)

---

## 📝 Executive Summary

- **Problem:** Restaurant owners struggle to predict health inspection grades; officials want better ways to flag risk.
- **Solution:** Logistic regression model using NYC’s open inspection data to forecast A, B, or C outcomes.
- **Impact:**  
  - Proactive risk reduction for restaurants  
  - Smarter targeting for health inspectors

---

## 📊 Data

- **Source:** [NYC Open Data – Department of Health and Mental Hygiene](https://data.cityofnewyork.us/Health/Restaurant-Inspection-Results/43nn-pn8j)
- **2015–2025:** 274,740 inspection records, cleaned to 193,892
- **Grades:** A, B, C, Pending
- **Note:** Each row = one violation per inspection; new/uninspected establishments excluded

---

## 🔎 Exploratory Data Analysis

- 🏆 **85,000+ restaurants** scored "A"
- ❌ Most common issues: sanitation, pest conditions, equipment maintenance
- 🍣 **Seafood & Chinese** cuisines and 🏢 **Brooklyn/Bronx** locations had higher B/C rates
- ⏳ Many "Pending" grades, especially in Manhattan and Brooklyn

---

## 🤖 Modeling Methods

- **Goal:** Predict grade (A/B/C)
- **Features:** Borough, Cuisine Type, Inspection Type (one-hot encoded)
- **Model:** Multinomial Logistic Regression (`scikit-learn`)
- **Performance:**  
  - 78% overall accuracy  
  - Best at predicting "A" grades  
  - Lower accuracy for "B"/"C" (due to class imbalance)

---

## 🧭 Key Findings

- 📍 Location, 🍽️ cuisine, and 🕵️‍♂️ inspection type are strong predictors
- Brooklyn, Bronx, and certain cuisines more likely to get B/C grades
- Re-inspections = early warning for risk

---

## 💼 Business Recommendations & Next Steps

- 🏢 **Use model** in city workflows to flag high-risk locations
- 🎯 **Targeted outreach/training** for high-risk groups
- 🚀 **Explore advanced models** and address class imbalance
- 🧩 Integrate new features and risk factors

---

## 📦 Project Materials

- **[Jupyter Notebook(s)](code/ServingUpSafety.ipynb)**
- **[PDF Slides: EDA & Findings](decks/Phase01_%20Data%26EDA.pdf)**
- **[PDF Slides: Methods & Recommendations](decks/Phase02_%20Methods,%20Findings%20and%20Recommendations.pdf)**
- **Project images:** see `data_vizs_image/` folder

---

## 🔗 Data Source

[NYC Health Restaurant Grades](https://data.cityofnewyork.us/Health/Restaurant-Inspection-Results/43nn-pn8j)

---

## 📫 Contact

[Ngawang Choega](mailto:ngachoe2002@gmail.com) • [LinkedIn](https://www.linkedin.com/in/ngawang-choega/)

---

*Project for Practical Data Science, MS in Data Science, Pace University NYC.*

