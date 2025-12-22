# \# CodeAlpha\_Credit\_Scoring\_Prediction

# \### Creditworthiness Prediction from Financial Data

# 

# This project focuses on predicting the likelihood of financial default by analyzing structured financial history. It serves as part of the \*\*CodeAlpha Machine Learning Internship\*\* program and follows the methodology used in high-stakes disease prediction.

# 

# \## Objective

# The goal is to apply advanced classification techniques to financial datasets to provide accurate creditworthiness possibilities based on individual metrics.

# 

# \## Approach \& Technologies

# We implemented a complete machine learning pipeline including data cleaning, feature scaling, and model benchmarking.

# 

# \- \*\*Data Source:\*\* "Give Me Some Credit" dataset (Industry Standard Repository).

# \- \*\*Preprocessing:\*\* Handled missing income/debt values via median imputation and performed feature scaling using 'StandardScaler'.

# \- \*\*Algorithms Used:\*\*

# &nbsp; - Random Forest (Best performing for non-linear risk)

# &nbsp; - Logistic Regression (Baseline)

# 

# \## Key Features \& Financial Metrics

# The model utilizes various financial "symptoms" to make predictions:

# \- \*\*Debt Ratio:\*\* Total debt divided by gross income.

# \- \*\*Revolving Utilization:\*\* Total balance on credit cards divided by credit limits.

# \- \*\*Age \& Income:\*\* Demographic factors affecting repayment stability.

# 

# \## Results \& Batch Audit

# The performance was verified using an internal validation split and Gini coefficient analysis.

# 

# | Task | Best Performing Model | ROC-AUC | Gini |

# | :--- | :--- | :--- | :--- |

# | Credit Scoring | Random Forest | 83.9% | 0.68 |

# 

# \*\*Note:\*\* The model has been optimized using \*\*Balanced Class Weights\*\* to improve recall for high-risk individuals.

# 

# \## File Structure

# \- `Credit\_Scoring.ipynb`: Main notebook with source code.

# \- `requirements.txt`: Necessary libraries to run the project.

# \- `models/`: Folder containing persisted `.joblib` files for models and scalers.

# 

# \*\*Internship:\*\* CodeAlpha ML Internship  

# \*\*Intern:\*\* GANESH KUMAR  

# \*\*Tag:\*\* @CodeAlpha

