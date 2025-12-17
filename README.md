# The Impact of AI on the CS Job Market – Forecasting Model

## Project Overview
This project analyzes the impact of Artificial Intelligence (AI) on the Computer Science (CS) job market by building machine learning models to classify AI-related job postings and forecast future job trends. Using real-world job posting data, we explore which features most strongly indicate AI involvement and how AI-related job demand is expected to change over time.

The project combines **classification models** (Logistic Regression, Random Forest, XGBoost) with **time-series forecasting** (Facebook Prophet) to provide both short-term predictive performance and long-term trend analysis.

## Dataset
- **Source:** Kaggle – Global AI Job Market & Salary Trends  
- **Time Range:** 2024–2025  
- **Size:** ~15,000 job postings  

### Key Features
- `job_title`
- `required_skills`
- `experience_level`
- `employment_type`
- `salary_currency`
- `company_location`
- `industry`
- `posting_date`
- `application_deadline`

### Feature Engineering
- Label encoding for categorical variables
- Bag-of-words vectorization for `required_skills`
- Date-based features (posting year, posting month, deadline days)

### Classification Models
- Logistic Regression (baseline)
- Random Forest Classifier
- XGBoost Classifier
- Stacked Ensemble (Random Forest + XGBoost)

### Forecasting
- Facebook Prophet is used to forecast trends in AI-related job postings using monthly aggregates.


## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Feature importance (tree-based models)
- Time-series trend visualization (Prophet forecast)

## How to Run the Project

### 1️⃣ Environment Setup
Recommended: **Anaconda**
