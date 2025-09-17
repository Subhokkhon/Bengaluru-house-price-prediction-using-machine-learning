# Bengaluru-house-price-prediction-using-machine-learning
This project is a machine learning regression application that predicts the price of houses in Bangalore based on various features like location, size, number of bedrooms (BHK), and square footage. It demonstrates the end-to-end data science workflow: data cleaning, feature engineering, model training and evaluation.
📊 Dataset

Source: Bengaluru House Prices dataset

Key Features:

location – Area in Bangalore

size – Number of bedrooms (e.g., 2 BHK, 3 BHK)

total_sqft – Total square feet of the property

bath – Number of bathrooms

balcony – Number of balconies

price – Target variable (in lakhs INR)

⚙️ Workflow

Data Cleaning

Removed unnecessary columns (area_type, society, balcony, availability)

Handled missing values

Feature Engineering

Extracted numerical features from text (e.g., size → bhk)

Converted total_sqft into a uniform numeric format

Created derived features like price_per_sqft

Reduced dimensionality by grouping locations with very few data points

Outlier Removal

Removed extreme values in price_per_sqft

Removed BHK and bathroom outliers

Model Building

Used Linear Regression, Lasso, Ridge, and other regression models

Applied GridSearchCV for hyperparameter tuning

Selected the best-performing model

Model Evaluation

Evaluated models using R² Score and Cross-Validation

Final model achieves good accuracy for price prediction.
🛠️ Tech Stack

Python (Pandas, NumPy, Matplotlib, Scikit-learn)

Machine Learning (Regression, GridSearchCV)

📈 Results

Successfully predicts house prices with good accuracy

Handles categorical and numerical data effectively

Robust against outliers after preprocessing
