### This project explores a machine learning approach to predicting housing prices in California using the California Housing dataset.  
### The goal is to demonstrate data preprocessing, feature engineering, linear regression modeling, and model evaluation

Source: [California Housing Prices Dataset](https://www.kaggle.com/datasets/camnugent/california-housing-prices)  

Target Variable: `median_house_value` — the median house price in each district  

Features Used:  
Geographic data: `longitude`, `latitude`  
Socioeconomic: `median_income`  
Household information: `total_rooms`, `total_bedrooms`, `population`, `households`  
Categorical: `ocean_proximity` (converted via one-hot encoding)  
Engineered: `bedroom_ratio`, `household_rooms`  


### 📈 Model Results

- **Model**: Linear Regression
- **R² Score**: `0.63`
  > This means the model explains 63% of the variance in housing prices.  
  > While it provides a solid baseline, performance could be improved with more advanced models.

### 🖼 Visualizations

- Actual vs Predicted scatter plot
- Correlation heatmap (optional)
- House prices mapped by location (latitude vs longitude)
