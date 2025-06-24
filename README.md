# Titanic-Survival-Prediction-using-Logistic-Regression



# Titanic Survival Prediction using Logistic Regression

By Amandeep Randhawa

📅 **Date:** June 19, 2025

---

## 📘 Overview

This project applies **logistic regression modeling** to the Titanic dataset to predict passenger survival using demographic and fare-related features. The analysis integrates **data preprocessing**, **feature engineering**, **model interpretation**, and **rich visual storytelling** to derive insights and validate model performance.

---

## 📂 Files

* `train.csv`: Training dataset with survival labels
* `test.csv`: Test dataset used for prediction
* `gender_submission.csv`: Baseline submission file
* `Group3_AR_DD_JK_AM_LogisticsRegression.Rmd`: Full R Markdown script for analysis
* `titanic_logistic_submission.csv`: Final model output (optional)

---

## 🔍 Objectives

* Build a logistic regression model to predict Titanic passenger survival
* Identify statistically significant predictors
* Evaluate model accuracy, residuals, ROC curve, and AUC
* Visualize survival trends across gender, class, age, and other variables
* Validate model robustness using VIF (Variance Inflation Factor)

---

## 📊 Key Steps

### 1. **Data Preparation**

* Handled missing values in `Age` and `Fare`
* Converted categorical variables to factors
* Engineered new feature: `FamilySize = SibSp + Parch + 1`

### 2. **Model Building**

* Logistic regression with predictors: `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`
* Model summary used to evaluate p-values, coefficients, and deviance metrics

### 3. **Evaluation**

* **Confusion Matrix Accuracy:** 79.35%
* **AUC (Area Under Curve):** 0.856 – *Excellent classification performance*
* **VIF Analysis:** All VIFs < 5 – *No multicollinearity concerns*

### 4. **Visual Insights**

* Survival rates by **Gender**, **Class**, and **Age**
* **Mosaic**, **Violin**, **Density**, **Alluvial**, and **Heatmap** plots for deeper insight
* Model diagnostic: Residual plot, ROC curve, and probability distributions

---

## 📈 Notable Findings

* **Sex & Class**: Females and 1st-class passengers had the highest survival odds
* **Age**: Children and young adults fared better
* **Family Size**: Small families (2–4 members) had better survival rates
* **Model Quality**: Strong predictive power and interpretability

---

## 📌 Tools & Libraries

* `dplyr`, `ggplot2`, `caret`, `corrplot`, `gmodels`, `ggmosaic`, `ggalluvial`, `pROC`, `car`

---

## ✅ Final Output

The final predictions are saved as a submission-ready CSV file with:

```
PassengerId | Survived
```

---

## 📬 Contact

For any questions or collaboration:
**Amandeep Kaur Randhawa** – [amandeepkrandhawa@gmail.com](mailto:amandeepkrandhawa@gmail.com)

