# Real Estate Price Prediction: Linear Regression vs K-Nearest Neighbors

## Project Overview
This project aims to predict real estate prices using machine learning techniques, specifically Linear Regression and K-Nearest Neighbors (KNN). We conduct exploratory data analysis and compare the performance of these models to provide insights into factors influencing house prices.

## Methodology

### Exploratory Data Analysis (EDA)
- Analyzed the dataset to understand patterns and factors influencing real estate prices
- Utilized visualizations and statistical techniques to uncover valuable insights

### Linear Regression
- Implemented to establish relationships between various features and house prices
- Explored assumptions, model evaluation, and interpretation of results

### K-Nearest Neighbors (KNN)
- Applied for its versatility in regression tasks
- Explored the intuition behind KNN, selection of k, and impact of feature scaling

## Key Findings

### Linear Regression Results
- Significant factors: house age, distance to nearest MRT station, number of convenience stores, latitude, and longitude
- R-squared value: 0.675, indicating moderate predictive performance

### KNN Model Results
- Best-performing hyperparameter: K=2
- R-squared value: 0.704, outperforming linear regression
- Explained approximately 70.4% of the variance in house prices

### Model Comparison
- KNN with hyperparameter tuning demonstrated superior performance
- Highlighted the importance of hyperparameter optimization in machine learning

## Conclusion
- The tuned KNN model emerged as the best choice for predicting house prices
- Achieved an R-squared value of 0.704, outperforming linear regression
- Hyperparameter tuning played a pivotal role in improving model performance

## Technologies Used
- Python
- Scikit-learn for machine learning models
- Pandas for data manipulation
- Matplotlib/Seaborn for data visualization

## How to Use
1. Clone the repository
2. Install required dependencies: `pip install -r requirements.txt`
3. Run the Jupyter notebook or Python script

## Future Work
- Explore additional machine learning algorithms for comparison
- Investigate the impact of feature engineering on model performance
- Consider developing a user-friendly interface for real estate price prediction



This project demonstrates the application of machine learning techniques in real estate price prediction, providing valuable insights for buyers, sellers, and investors in the real estate market.
