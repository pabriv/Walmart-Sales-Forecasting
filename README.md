

# Walmart Sales Forecasting

## Context:
Kaggle competition sponsored by Walmart.  Competition goal is to forecast Walmart weekly sales by each department in every store.

## Key Objectives:
 
- Analyze real historical Walmart sales data for 45 Walmart stores located in different regions

- Forecast Walmart weekly sales for each department in each store

- Competition evaluated on the weighted mean absolute error, where holiday weeks are weighted 5x higher than non-holiday weeks


## Executive Summary

- Real Walmart data from 45 Stores with 100 departments each was cleansed, analyzed and used to train regression, gradient boosting, time series and ensemble models in order to predict future values (4500 distinct forecasts)

- Gradient Boosting (regression) models such as XGBoost, LightGBM had higher predictive performance than time series model.  XGBoost model performed better in Kaggle than NeuralProphet (Predictive RNN) model.

- Ensemble models tended to negatively impact score across several iterations

- Analysis facts and insights

- Correlations discussion

- Feature Engineering discussion

- Ultimately the final model Kaggle public and private scores were 2969 and 3002.

- The value of the model is that it performs higher than baseline models and can facilitate or inform strategic decision making related to supply and demand, personnel, and sales outlook

## Key recommendations:

- Consider deprioritizing low performing departments and reallocating those funds/resources to higher performing departments to optimize revenue
    
    - For example, at the Walmart store with the highest overall revenue, department x had very low sales compared to department y.  Does department x really need all that shelf space or could it be replaced with products from higher performing dept.  Does dept X really require so many personnel when it has such low annual revenue?
    
- From a data perspective, expand timeframe and number of stores to improve model performance
 
- Trial run at select stores, evaluate establishing/improving forecasting reporting standardization for business management and determine areas to expand or improve (for example adding additional anonimyzed customer data like median income or population)

- Potentially leverage model to in expansion planning - help predict sales at future new stores

---
