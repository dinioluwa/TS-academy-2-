# TS-academy-2-
This project builds a machine learning model to predict California house price using Linear Regression and EDA. It covers end-to-end data analysis, from exploratory data analysis (EDA) to building and evaluating a Linear Regression model. Dataset: 20,640 districts, 10 features including ocean proximity.



## Objectives
- Perform exploratory data analysis (EDA) to understand the data
- Handle missing values in `total_bedrooms`
- Identify key features that influence house prices
- Build a Linear Regression model to predict median house values
- Evaluate model performance using standard regression metrics

---

## Tech Stack
| Tool | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data manipulation |
| NumPy | Numerical computing |
| Matplotlib / Seaborn | Data visualization |
| Scikit-learn | Machine learning (Linear Regression) |
| Jupyter Notebook | Development environment |

---

## Exploratory Data Analysis
Key analyses performed:
- Distribution of `median_house_value`
- Missing data analysis
- Relationship between `median_income` and house prices
- `ocean_proximity` category analysis

---

## Modelling
- **Algorithm:** Linear Regression
- **Train/Test Split:** 80% train / 20% test
- **Preprocessing:**
  - Missing value imputation (`total_bedrooms`)
  - Encoding of `ocean_proximity` (categorical)
- **Evaluation Metrics:**
  - MAE (Mean Absolute Error)
  - R² Score

---


## Results
| Metric | Score |
|---|---|
| MAE | *(24.83)* |
| R² Score | *(0.64)* |

---

# Future Work
- Try advanced models (Random Forest, XGBoost, Ridge/Lasso Regression)
- Engineer new features (rooms per household, bedrooms per room)
- Explore geographical clustering
- Hyperparameter tuning
