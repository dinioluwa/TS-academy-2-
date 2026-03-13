#  California House Price Prediction
---

**Project Description:**
California house price prediction using Linear Regression, Decision
Tree, and Random Forest. Includes EDA, encoding, pipelines, feature importance analysis, and model comparison with R² and MAE metrics.

---

## Overview
An end-to-end machine learning project to predict median house prices
across California districts. The project covers exploratory data
analysis (EDA), data cleaning, multiple regression models and advanced
preprocessing techniques including encoding, pipelines, and
hyperparameter tuning.


---

## Dataset
- **Source:** California Housing Dataset
- **Rows:** 20,640 districts
- **Features:** 9 input features + 1 target variable

| Column | Description | Type |
|---|---|---|
| `longitude` | Geographical longitude of district | float64 |
| `latitude` | Geographical latitude of district | float64 |
| `housing_median_age` | Median age of houses in district | float64 |
| `total_rooms` | Total number of rooms in district | float64 |
| `total_bedrooms` | Total number of bedrooms (207 missing) | float64 |
| `population` | Total population of district | float64 |
| `households` | Total number of households | float64 |
| `median_income` | Median income of households (in $10,000s) | float64 |
| `ocean_proximity` | Location relative to ocean | object |
| `median_house_value` | **Target** — Median house value in USD | float64 |

---

## Objectives
- Perform EDA to understand data distributions and relationships
- Handle missing values and encode categorical variables
- Build and compare multiple regression models
- Apply preprocessing pipelines for cleaner workflows
- Tune hyperparameters using GridSearchCV
- Evaluate models using R² and MAE metrics
- Identify the most important features driving house prices

---

## Tech Stack
| Tool | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical computing |
| Matplotlib / Seaborn | Data visualization |
| Scikit-learn | Machine learning models |
| Jupyter Notebook | Development environment |

---

## Notebooks

### 1. housing.ipynb — EDA & Linear Regression
- Data exploration and visualisation
- Missing value handling
- Correlation analysis
- Linear Regression model
- Model evaluation (R², MAE)

### 2. housing_models.ipynb — Decision Tree & Random Forest
- Decision Tree Regression
  - Model training and evaluation
  - R² and MAE scores
  - Feature importance
- Random Forest Regression
  - Model training and evaluation
  - R² and MAE scores
  - Feature importance
 
### 3. housing_adv.ipynb — Encoding, Pipeline & GridSearchCV
- LabelEncoder for ordinal categorical variables
- OneHotEncoder for nominal categorical variables
- Pipeline for streamlined preprocessing and modelling
- GridSearchCV for hyperparameter tuning
- Model evaluation (R², MAE)
---

## Model Comparison
| Model | R² Score | MAE |
|---|---|---|
| Linear Regression | 0.64 | 51372.67 |
| Decision Tree | 0.7312 | 40685.62 |
| Random Forest | 0.7791 | 36640.07 |
| Tuned Model (GridSearchCV) | 0.735 | 38972.93 |
---

##  Feature Importance
Top features identified by Random Forest:
1. Median income
2. Longitude
3. Latitude

---
