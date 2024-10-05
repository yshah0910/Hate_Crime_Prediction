
# Hate Crime Prediction in NYC
This project leverages machine learning models to predict hate crimes in New York City by analyzing arrest data. We focus on identifying the key factors influencing hate crime incidents and achieving reliable predictions through various data transformation and modeling techniques.

## Project Overview
Objective: To predict hate crime arrests in NYC by analyzing arrest data, focusing on location, demographics, and historical crime data.

Tools & Libraries:
Python: Pandas, NumPy, Matplotlib

Data Formats: JSON, Excel
## Key Features
### Data Collection & Preprocessing:

Gathered hate crime and arrest data specific to NYC.

Conducted thorough data cleaning and transformation to handle missing data, duplicates, and irrelevant features.

Performed comprehensive feature engineering by including key factors like location, demographics, and historical crime data to enhance the model's predictive capabilities.
### Machine Learning Models:

Decision Tree: Used for creating a model that splits data based on features.

Logistic Regression: Implemented to predict the probability of hate crime arrests.

Information Gain: Applied to identify features that contribute the most to predictions.

GINI Index: Used as a criterion to determine the best splits in decision tree models.

Gradient Descent: Employed for optimizing the model by minimizing error rates.

Maximum Likelihood: Used to estimate model parameters that best fit the data.
### Model Tuning & Optimization:

Performed hyperparameter tuning to refine model performance.
Utilized various data modeling techniques to ensure models were optimized for precision and recall.
Evaluation:

The predictive model achieved a 67.8% success rate based on the F1-score, reflecting a balance between precision and recall.
