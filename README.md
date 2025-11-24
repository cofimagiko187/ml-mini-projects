# Machine Learning Mini-Projects: Regression Methods in Real-World Healthcare Data

## Overview
This repository contains two academic machine learning projects focused on regression methods applied to real-world healthcare datasets. The primary goal is to explore and compare different regression techniques by designing practical prediction models, analyzing feature relationships, and evaluating model performance using standard metrics.

Both projects were completed as part of a university course assignment.  
The code contains extensive inline comments strictly because **detailed commenting was a mandatory grading requirement**, not a stylistic or tutorial-purpose choice.

---

## Projects Included

### 1) Life Expectancy — Linear Regression Analysis
This project applies **multiple linear regression** (Ordinary Least Squares) to predict global life expectancy based on economic, demographic and health indicators.

Key elements:
- Feature selection using correlation analysis
- Standardization using `StandardScaler`
- Model evaluation using MAE, RMSE, and R²
- Residual diagnostics and regression visualization

**Objective:** Investigate how socio-economic conditions (such as education and resource distribution) influence life expectancy.

---

### 2) Cancer Mortality — Decision Tree Regression
This project applies a **Decision Tree Regressor** to predict cancer mortality rates in the United States using demographic and socio-economic attributes.

Key elements:
- Selection of the single strongest predictor using correlation
- Tree structure interpretation with `plot_tree`
- Depth control via `max_depth` for generalization and readability
- Performance evaluation using MAE, RMSE, and R²

**Objective:** Examine the interpretability and predictive behavior of decision trees on public health data.

---

## Datasets Used
| Dataset | Description | Target Variable |
|---------|-------------|----------------|
| Life Expectancy Data | Global demographic and health attributes | `Life expectancy` |
| U.S. Cancer Mortality | Socio-economic and demographic indicators by county | `TARGET_deathRate` |

Both datasets were cleaned, filtered for valid targets, and prepared for modeling based on academic requirements.

---

## Machine Learning Techniques Applied
| Technique | Project | Purpose |
|-----------|---------|---------|
| Multiple Linear Regression (OLS) | Life Expectancy | Modeling linear relationships and coefficient interpretation |
| Decision Tree Regression | Cancer Mortality | Interpretable non-linear modeling with hierarchical splits |

---

## Evaluation Metrics
Both models were assessed using:
- **MAE (Mean Absolute Error)**
- **RMSE (Root Mean Squared Error)**
- **R² (Coefficient of Determination)**

These metrics provide a balanced view of error magnitude and model explanatory power.

---

## Academic Note
These projects were completed as part of a university module dedicated to machine learning fundamentals.  
The emphasis of the assignments was on:
- model reasoning and interpretability,
- step-by-step methodology,
- evaluation and discussion of results.

For this reason, **detailed commenting throughout the code was mandatory and graded**.

---

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-Learn, StatsModels
- Seaborn, Matplotlib

---


---

## Author
Developed as part of a university course on machine learning and applied statistical modeling.
