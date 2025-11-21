# House Price Prediction using Linear Regression

## Project Overview
This project aims to predict housing prices in California using a linear regression model. The dataset contains housing information such as median income, number of rooms, population, and proximity to the ocean. The objective is to explore the data, clean it, perform exploratory data analysis (EDA), build a predictive model, and evaluate its performance.

## Dataset
- Source: California Housing Prices
- Format: CSV
- Columns: longitude, latitude, housing_median_age, total_rooms, total_bedrooms, population, households, median_income, median_house_value, ocean_proximity

## Data Preprocessing
- Missing values in `total_bedrooms` filled with the median value.
- Categorical column `ocean_proximity` encoded using label encoding.

## Exploratory Data Analysis (EDA)
- Distribution of house prices
- House price variation with location
- Correlation heatmap of numerical features
- Impact of ocean proximity on house prices

## Model
- Linear Regression was used to predict `median_house_value`.
- Features include: all columns except the target.

## Results
- R² Score: (insert your R² score here)
- RMSE: (insert your RMSE here)
- Insights:
  - Higher median income strongly increases housing price.
  - Houses closer to the ocean tend to be more expensive.
  - Geographic location affects housing price clusters.

## Conclusion
The linear regression model provides a reasonable prediction of house prices using simple features. For better accuracy, more advanced models (Random Forest, Gradient Boosting) could be used. This project demonstrates the basic steps of data cleaning, EDA, predictive modeling, and evaluation.

## Notebook
The final `.ipynb` file containing all code, visualizations, and analysis is included in this repository.

## Author
Group 4
# California-Housing-Price-Prediction
