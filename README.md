# Energy Consumption Time Series Forecasting

## Task Objective
Forecast short-term household energy usage using historical time-based patterns to identify trends and improve consumption insights.

## Approach
- **Data Loading & Preprocessing:** Parsed and resampled the Household Power Consumption dataset; handled missing values.  
- **Feature Engineering:** Created time-based features like hour of day, weekday/weekend, and lag features.  
- **Modeling:** Built and compared ARIMA, Prophet, and XGBoost models.  
- **Evaluation:** Assessed models using MAE and RMSE metrics.  

## Results & Findings
- XGBoost captured non-linear patterns better than ARIMA and Prophet for short-term forecasting.  
- Visualizations of actual vs. forecasted energy usage demonstrate model performance and highlight daily and weekly consumption trends.  
- The analysis provides actionable insights for energy management at the household level.
