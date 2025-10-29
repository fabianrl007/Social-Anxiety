# Social-Anxiety
# Project: Predicting High-Potential Users for a Mental Health App

## 1. Project Charter

### Problem Statement
A new mental health mobile app needs to acquire users efficiently on a limited marketing budget. We need to move beyond broad-audience advertising and identify specific, high-potential user segments. This project aims to analyze the "Social Anxiety Dataset" to understand which demographic and social media usage patterns are the strongest predictors of social anxiety.

### Project Goals & Key Performance Indicators (KPIs)
The primary goal is to build a classification model that identifies high-potential users, enabling the marketing team to create highly targeted ad campaigns that lower acquisition costs and attract a relevant user base.

**Business KPIs (Target):**
* **Customer Acquisition Cost (CAC):** 15% reduction in CAC for targeted campaigns.
* **Click-to-Install Conversion Rate:** Increase from 2% to 4%.
* **New User Activation Rate:** 10% increase in users completing onboarding within 24 hours.

**Model Performance KPIs (Target):**
* **Precision (High Anxiety Class):** 80%+
* **Recall (High Anxiety Class):** 75%+
* **F1-Score (High Anxiety Class):** 0.75+

### Scope

| In Scope | Out of Scope |
| :--- | :--- |
| Use *only* the Kaggle "Social Anxiety Dataset". | Will **not** be used as a clinical diagnostic tool. |
| Exploratory Data Analysis (EDA) to find correlations. | Will **not** attempt to prove causation (e.g., "TikTok causes anxiety"). |
| Build a binary classification model (high/low anxiety). | Will **not** be deployed into a live production ad platform. |
| Optimize model for Precision, Recall, and F1-Score. | Will **not** be used to create the final ad copy or creative. |
| Final deliverable is the model & a summary report. | Will **not** be used to build in-app features (e.t., content recommendations). |

### Key Assumptions & Risks

* **Assumptions:**
  1. **Data Honesty:** We assume survey participants answered truthfully about their anxiety and screen time.
  2. **Sample Representation:** We assume the dataset's participants are representative of the app's target market.
  3. **Feature Sufficiency:** We assume the provided features are sufficient to build a predictive model.

* **Potential Risks:**
  1. **Self-Report Bias:** A high risk that users under-reported anxiety or misestimated screen time.
  2. **Data Imbalance:** A risk that the "high anxiety" group is very small, making it difficult to build an accurate model.
  3. **Ethical Risk:** The model could inadvertently learn to discriminate based on a demographic proxy, requiring careful feature selection and testing.

---

## 2. Project Files
*(Your project content, like EDA notebooks, model files, etc., would go here)*

## 3. How to Run
*(Instructions on how to set up and run your code)*

## 4. Data Source

* **Author:** ZHANG CHENYUAN
* **Title:** Social Anxiety Dataset
* **Year:** 2025 (Updated)
* **Source:** Kaggle
* **URL:** `https://www.kaggle.com/datasets/natezhang123/social-anxiety-dataset`
