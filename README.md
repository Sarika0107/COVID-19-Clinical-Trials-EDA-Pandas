# COVID-19 Clinical Trials Analysis & Status Prediction

## Project Overview

The COVID-19 pandemic triggered an unprecedented number of clinical trials worldwide to evaluate treatments, vaccines, and preventive measures. This project analyzes COVID-19 clinical trial data to understand research trends, study characteristics, funding patterns, and trial progress. Additionally, machine learning models are developed to predict clinical trial status based on various study attributes.

---

## Objectives

- Analyze COVID-19 clinical trial data.
- Study trends in clinical research activities.
- Examine trial phases, study types, and funding patterns.
- Perform exploratory data analysis (EDA).
- Build machine learning models to predict trial status.
- Compare model performance.
- Identify key factors influencing clinical trial outcomes.

---

## Dataset

The dataset contains information related to COVID-19 clinical trials conducted globally.

### Features Include

- Status
- Study Type
- Gender
- Age
- Enrollment
- Phases
- Funded Bys
- Start Date
- Completion Date
- Conditions
- Interventions

### Target Variable

- Status (Clinical Trial Status)

---

## Data Preprocessing

The following preprocessing steps were performed:

- Missing value analysis.
- Removal of highly missing and irrelevant columns.
- Duplicate record checking.
- Date conversion and extraction of year/month features.
- Missing value imputation.
- Label Encoding of categorical variables.
- Feature selection for machine learning.

---

## Exploratory Data Analysis (EDA)

### Key Insights

- Certain trial statuses dominate COVID-19 research activities.
- Interventional studies account for a major portion of clinical trials.
- Trial phases vary significantly across studies.
- Funding sources influence research activity distribution.
- Clinical trial registrations increased rapidly during the pandemic period.

### Visualizations Performed

- Missing Value Analysis
- Clinical Trial Status Distribution
- Study Type Distribution
- Funding Source Analysis
- Trial Phase Distribution
- Monthly Clinical Trial Trend
- Feature Importance Analysis

---

## Machine Learning Approach

### Models Implemented

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

### Key Techniques

- Feature Engineering
- Label Encoding
- Train-Test Split
- Classification Modeling
- Model Comparison

---

## Model Evaluation

The models were evaluated using:

- Accuracy Score
- Classification Report
- Feature Importance Analysis

### Performance Summary

- Logistic Regression Accuracy: 48.49%
- Decision Tree Accuracy: 43.82%
- Random Forest Accuracy: 50.04%

Random Forest achieved the highest accuracy among all models.

---

## Feature Importance

The most influential features affecting clinical trial status prediction include:

- Enrollment
- Study Type
- Trial Phase
- Funding Source
- Start Year
- Start Month
- Gender
- Age

These variables play a significant role in determining clinical trial progression and status.

---

## Applications

This project can help:

- Healthcare Researchers
- Clinical Research Organizations
- Pharmaceutical Companies
- Public Health Agencies
- Policy Makers

Potential applications include:

- Clinical Trial Monitoring
- Research Trend Analysis
- Resource Allocation
- Trial Planning and Management
- Healthcare Research Analytics

---

## Limitations

- Dataset contains missing information in several attributes.
- Clinical trial status can change over time.
- External regulatory and healthcare factors are not included.
- Prediction accuracy depends on available study characteristics.
- Results should be interpreted as analytical insights rather than definitive predictions.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
- Jupyter Notebook

---

## Repository Contents

- COVID19(s).ipynb → Complete analysis and machine learning workflow
- COVID Clinical Trials.csv → Dataset
- README.md → Project documentation

---

## Author

**Sarika T A**  
Aspiring Data Analyst / Data Scientist

---

## Conclusion

This project analyzed COVID-19 clinical trial data using exploratory data analysis and machine learning techniques to understand research trends and predict clinical trial status. The analysis revealed important patterns related to study types, funding sources, trial phases, and temporal trends in research activity during the pandemic.

Machine learning models including Logistic Regression, Decision Tree, and Random Forest were developed to predict trial status. Among these models, Random Forest achieved the highest accuracy of approximately 50%, demonstrating its ability to capture complex relationships within clinical trial data. Feature importance analysis highlighted the significance of enrollment, study type, funding source, and trial phase in determining trial status.

Overall, the project demonstrates how data analytics and machine learning can support healthcare research by identifying trends, improving understanding of clinical trial characteristics, and assisting in research management decisions.

---

## Future Improvements

- Incorporate more recent clinical trial datasets.
- Apply advanced machine learning algorithms such as XGBoost and LightGBM.
- Perform hyperparameter tuning for improved accuracy.
- Include additional healthcare and regulatory variables.
- Develop interactive dashboards using Power BI or Tableau.
- Implement real-time clinical trial monitoring systems.
- Explore deep learning approaches for status prediction.
- Expand analysis to include treatment effectiveness and outcome prediction.

---
