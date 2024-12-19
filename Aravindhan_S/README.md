---

# FutureCart: AI-Driven Demand Prediction for Smarter Retail  

## Project Statement  
In the realm of e-commerce, demand forecasting plays a pivotal role in ensuring business success. This project aims to develop a demand forecasting model for e-commerce businesses that predicts future product demand by leveraging time series analysis and multivariate regression. The model is based on historical sales data, along with Google Analytics KPIs such as Google clicks and Facebook impressions, which are valuable indicators of customer interest.  

### Outcomes  
- **Improved Inventory Management**: More accurate demand forecasts lead to better inventory decisions, potentially reducing stock-outs and excess inventory.  
- **Enhanced Marketing Efficiency**: Identify periods of high demand for targeted marketing campaigns, optimizing resource allocation.  
- **Data-Driven Decision Making**: Reliable forecasts provide a basis for business decisions, such as pricing adjustments or product promotions.  
- **Accurate Demand Predictions**: Implement a forecasting model that achieves high accuracy in predicting future demands, thereby improving customer service levels.  
- **Scalable Solution**: Develop a solution that can scale to handle large datasets and varying demand patterns across multiple products.  

---

## Modules to be Implemented  

### 1. Data Collection  
**Milestone 1: Week 1**  
- Understand the problem statement.  
- Gather sales data from relevant sources (e.g., database, store records).  
- Collect Google Analytics and Facebook Impressions data.  

---

### 2. Exploratory Data Analysis (EDA) and Data Preprocessing  
**Milestone 1: Week 2**  
- Ensure the sales data is in a time-series format (e.g., daily, weekly, monthly) with timestamps.  
- Clean and format data, handling missing values and outliers using appropriate techniques (e.g., imputation or elimination).  
- Plot distribution plots for independent variables.  
- Create visualizations to understand trends, seasonality, and correlations.  
- Provide statistical summaries.  

---

### 3. Time Series Modelling  
**Milestone 2: Week 3**  

**Sub-Module 3.1: Model Selection**  
- Explore univariate models within time series modeling.  

**Sub-Module 3.2: Model Fitting**  
- Identify optimal model parameters by trying different parameter combinations and selecting the one with the lowest error metric.  

---

**Milestone 2: Week 4**  

**Sub-Module 4.1: Model Evaluation**  
- Visualize the model fit by plotting predicted values against actual sales data.  

**Sub-Module 4.2: Model Diagnostics**  
- Evaluate model performance using metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and Mean Absolute Percentage Error (MAPE).  
- Check residual plots to ensure no systematic errors remain.  

---

### 4. Multivariate Regression (Dynamic)  
**Milestone 3: Week 5**  

**Sub-Module 5.1: Understanding Dynamic Regression & Data Preparation**  
- Dynamic regression incorporates lagged values of the dependent variable (e.g., sales) and potentially lagged values of other predictors.  
- Create lagged variables for sales, Google clicks, and Facebook impressions by shifting them by one or more time periods.  
- Consider interactions between predictors if appropriate (e.g., clicks during high-season periods may have greater impact).  

---

**Milestone 3: Week 6**  

**Sub-Module 6.1: Model Construction**  
- Investigate functions to build dynamic regression models.  
- Start with simple models and progressively add complexity or interactions on training data.  

**Sub-Module 6.2: Model Evaluation**  
- Assess model fit using metrics such as Adjusted R-squared, RMSE, and MAE.  
- Visualize residuals and compare dynamic regression performance to a basic multiple regression model.  

---

### 5. Project Presentation & Documentation  
Prepare and present the project with clear documentation, including model insights, evaluations, and recommendations for implementation.  

---

This README provides an overview of the project's objectives, outcomes, and step-by-step milestones.


