# Salary & Sponsorship Prediction Project  
Predictive modelling on the USA sponsorship and salary dataset (EDA + multiple‑models)  

## Project Overview  
This project aims to explore and model factors influencing **salaries and sponsorship status** in the USA, based on publicly‑available data. The workflow covers the full data‑science pipeline:  
- Data ingestion & cleaning  
- Exploratory Data Analysis (EDA)  
- Feature engineering  
- Model training & hyper‑parameter tuning  
- Model evaluation & comparison  
- Insights & interpretation  

The goal is to build regression (and/or classification) models to estimate salary (or sponsorship) given background attributes, and to generate actionable insights from the EDA.  

## Dataset  
- **Source:** Kaggle notebook [USA Sponsership and Salary Pred (EDA + All Models)](https://www.kaggle.com/code/rahulcris07/usa-sponsership-and-salary-pred-eda-all-models)  
- **Description:** The dataset includes information on employees (or applicants) in the USA, with features such as sponsorship status, salary, job title, employer, years of experience, etc.  
- **Use‑case:** Predict salary (as target variable) and/or sponsorship status.  
- **Key variables:**  
  - `salary` (target)  
  - `sponsorship_status`  
  - `years_experience`  
  - `job_title`  
  - `employer`  
  - `location`  
```

## Methodology  
### 1. Data Cleaning & Pre‑processing  
- Handle missing data, outliers, and data types.  
- Encode categorical features.  
- Split dataset into training and testing sets.  

### 2. Exploratory Data Analysis (EDA)  
- Analyze feature relationships with target.  
- Visualize distributions and correlations.  
- Identify key salary/sponsorship drivers.  

### 3. Feature Engineering  
- Create new derived features.  
- Apply scaling and encoding.  
- Perform dimensionality reduction if needed.  

### 4. Model Training & Comparison  
- Regression: Linear Regression, Ridge, Lasso, Random Forest, Gradient Boosting.  
- Classification (optional): Logistic Regression, Random Forest, XGBoost.  
- Evaluate with metrics: RMSE, MAE, R² for regression; Accuracy, AUC for classification.  

### 5. Model Evaluation & Insights  
- Assess model performance.  
- Visualize residuals and feature importance.  
- Interpret feature impact on salary and sponsorship.  

## Tools & Technologies  
- Python 3.x  
- Jupyter Notebook  
- pandas, numpy, matplotlib, seaborn, scikit‑learn, xgboost  
   ```  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  
3. Download dataset from Kaggle and place in `data/raw/`.  

## Results Summary  
- Best Model: Gradient Boosting Regressor 
- Top features: `years_experience`, `job_title`, `employer`, `location`  

## Limitations  
- Dataset coverage may be limited.  
- Missing or noisy data affects accuracy.  
- Correlation ≠ causation — predictions are not causal conclusions.  

## Future Work  
- Include more features such as cost‑of‑living index.  
- Build web app for salary prediction.  
- Test deep learning or ensemble stacking models.  
- Evaluate fairness and bias in predictions.  

## License & Acknowledgements  
- Dataset by [Rahul Cris07 on Kaggle](https://www.kaggle.com/code/rahulcris07/usa-sponsership-and-salary-pred-eda-all-models)  
- For educational and research purposes only.  
- Inspired by Kaggle community notebooks and contributors.  
