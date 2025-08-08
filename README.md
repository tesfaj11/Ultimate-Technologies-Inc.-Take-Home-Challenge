# Ultimate-Technologies-Inc.-Take-Home-Challenge


This repository contains a complete solution to the take-home data science challenge provided by Ultimate Technologies Inc. The challenge is divided into three main parts:

1. **Exploratory Data Analysis (EDA)**  
2. **Experiment and Metrics Design**  
3. **Predictive Modeling for User Retention**  

--

## Problem Overview

Ultimate Inc. aims to improve user engagement and retention across two cities by:

- Understanding user login behavior
- Designing a policy experiment to increase driver availability
- Predicting which users are likely to be retained after the first 30 days

---

## Part 1 - Exploratory Data Analysis

Using `logins.json`, login events were grouped into 15-minute intervals to uncover temporal patterns in user activity.

Highlights:
- Daily and weekly seasonality observed
- Peak activity occurs during evenings and weekends
- Data quality was assessed and no major issues were found

Technologies used: pandas, matplotlib, seaborn

---

## Part 2 - Experiment and Metrics Design

Goal: Determine whether reimbursing toll costs helps encourage drivers to operate in both Gotham and Metropolis.

- Chosen Metric: Increase in the number of drivers active in both cities
- Method: Randomized Controlled Trial (RCT)
- Analysis: Two-sample t-test (or Mann-Whitney U test if non-normal distribution)

The proposal includes detailed implementation steps, control/treatment assignment, and success criteria.

---

## Part 3 - Predictive Modeling

Objective: Predict user retention using the `ultimate_data_challenge.json` dataset.

Steps completed:
- Data cleaning and feature engineering
- Binary classification modeling using logistic regression and random forest
- Advanced modeling using XGBoost and optional BERT/transformers
- Feature importance analysis
- Evaluation using accuracy, precision, recall, F1-score

Top predictors included average distance, surge usage, and weekday percentage usage.

---

## Tools and Libraries

- Python 3.x
- pandas, numpy
- scikit-learn, xgboost
- matplotlib, seaborn
- nltk, transformers (for advanced modeling)

---

## Project Extensions

- Use BERT or transformer-based models for text-based user metadata
- Deploy a web interface for real-time prediction
- Extend the analysis to multi-language datasets
