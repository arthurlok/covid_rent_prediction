covid_rent_prediction
==============================

Predicting rent prices given various demographic factors and COVID levels.

Abstract:

The onset of Covid-19 has caused drastic and unpredictable changes in both job markets and costs of living. Rent prices are no exception, and the pandemic has created similar volatility in housing costs for many New Yorkers. In this project, we build a model that can predict median rent prices of apartments of varying layouts in different NYC zip codes by taking Covid-19 data, demographic data from the Census Bureau, previous median rent prices, and inventory data into consideration. We hypothesise that the addition of Covid-19 data will increase the model performance as compared to the baseline model which predicts the previous month’s rent. We test a total of five models out of which Random Forest has the best performance, with mean absolute error of $88. 

Full write-up: https://docs.google.com/document/d/1dwjVLmPUbaoTx4KZQATAZLcohHWSVmptjySCntjx6UE/edit?usp=sharing

Project Organization
------------

    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    └── notebooks          <- Jupyter notebooks.

--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
