

# Walmart Sales Forecasting

## Key Objectives:
 
- Analyze real historical Walmart sales data for 45 Walmart stores located in different regions

- Forecast Walmart weekly sales for each department in each store

- Competition evaluated by weighted mean absolute error (WMAE), where holiday weeks are weighted 5x higher than non-holiday weeks


## Executive Summary

- Real Walmart data from 45 Stores with 100 departments each was cleansed, analyzed and used to train regression, gradient boosting, time series and ensemble models in order to predict future values (4500 distinct forecasts)

- Gradient Boosting models such as XGBoost, LightGBM had higher predictive performance than time series model.  XGBoost model performed better in Kaggle than NeuralProphet (Predictive RNN) model

- Positive linear relationship observed between average weekly sales and store size.  In addition, data analysis revealed consistent grouping for average overall sales within each store (limited variance) across three full years

- Additional store/area criteria such as temperature, weekly fuel price, unemployment rate, CPI, and week of year were reviewed and seen to have low correlation with a weekly sales.  Next, engineered features such as Department Ranking and Climate Zone (store temp ranking) showed favorable correlations with weekly sales and were helpful in improving forecast performance

- Ultimately the final model Kaggle public and private scores were 2930 and 2985. Model value is that it performs higher than baseline models and can facilitate or inform strategic decision-making related to supply and demand, personnel, and sales outlook

## Key recommendations:

- Consider deprioritizing low performing departments and reallocating those funds/resources to higher performing departments to optimize revenue
    
    - For example, do the departments with consistently low sales performance across years genuinely require the current allocated shelf space or could it be replaced with products from higher performing departments? Moreover, do those lower performing departmetns require the concurrent personnel allotment, or are there optimizations to be achieved?  For example, the bicycle department may require above-average headcount for assembly but is the cost-benefit analysis still favorable across stores?
    
- From a data perspective, expand timeframe and number of stores to improve model performance and continue ingesting and training model
 
- Trial run at select stores, evaluate establishing/improving forecasting reporting standardization for business management and determine areas to expand or improve (for example adding additional anonimyzed customer data like median income or population)

- Potentially leverage model to inform annual strategic planning intitiatives or expansion planning - help predict sales at future new stores

---

<a href="https://imgur.com/h7fDaCx"><img src="https://i.imgur.com/h7fDaCx.png" title="source: imgur.com" /></a>

<a href="https://imgur.com/yVPTuWM"><img src="https://i.imgur.com/yVPTuWM.png" title="source: imgur.com" /></a>

<a href="https://imgur.com/0f3Zx4F"><img src="https://i.imgur.com/0f3Zx4F.png" title="source: imgur.com" /></a>

<a href="https://imgur.com/1wRYMFe"><img src="https://i.imgur.com/1wRYMFe.png" title="source: imgur.com" /></a>

<a href="https://imgur.com/SW4Joq7"><img src="https://i.imgur.com/SW4Joq7.png" title="source: imgur.com" /></a>
