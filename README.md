# Product Demand Forecasting using Machine Learning


Using historical data and other information, demand forecasting is the process of making estimations about future customer demand over a defined period.
Usually organisations follow tranditional forecasting techniques/algorithms such as Auto Arima, Auto Arima, Sarima, Simple moving average and many more.

## Contents

- [Objective](#objective)
- [Workflow](#workflow)
- [Result](#result)
- [Tech Stack](#techstack)


## Objective <a name = "objective"></a>

Significant efforts are needed to tune traditional algorithms but Machine Learning gives an quicker approach. In the world of AI, many companies have started researching the possibility of using machine learning in place of tranditional approach.



### Dataset

The dataset comprised of units sold on a daily basis along with details regarding the sales, eg. SKU(product id), Store, price etc.

*record_ID,	week,	store_id,	sku_id,	total_price,	base_price,	is_featured_sku,	is_display_sku,	units_sold*


## Workflow <a name = "workflow"></a>

- Handling missing values
- Feature selection based on my previous experience in Supply chain domain
- Converting dataset into time series format to apply supervised learning approach.
- Regression Modeling
  - Random Forest
  - XGBoost
- Hyperparameter Tuning

## Result <a name = "result"></a>
- Random Forest Regression gave an score of 0.679 .
- XGBoost Regression gave an score of 0.556 .



## Tech Stack <a name = "techstack"></a>

- numpy
- pandas
- sklearn
- easypreprocessing 
- seaborn 
- matplotlib
- xgboost
- Power BI

