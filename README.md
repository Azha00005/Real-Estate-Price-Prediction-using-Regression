Project 3: Real Estate Price Prediction (Regression)

Goal: Build a machine learning model to predict housing prices based on their characteristics.

Data
* Name: Ames Housing Dataset (AmesHousing.csv).

Completed Tasks
1. Feature Engineering:
* Created new features: Total House Area, House Age.
* Converted categorical data to numeric (One-Hot Encoding).
2. Modeling:
* Trained Linear Regression model.
* Applied Lasso and Ridge regularization to improve model stability.
3. Results:
* R2 Score: ~0.85 (Model explains 85% of price variation).
* MAE (Mean Error): ~$18,500.
* Key factors: Total House Area and finish quality (Overall Qual) have the highest impact on price.

Tech Stack
* Language: Python 3.x
* Libraries:
* pandas, numpy — Data Processing.
* matplotlib, seaborn — Visualization.
* scipy.stats — Statistical Tests.
* scikit-learn — Machine Learning.
