![cars](../images/cars.jpg)
Sourced: [dreamstime.com](https://www.dreamstime.com/photos-images/sale-car.html)

## Description 🚗
The project builds a model for predicting car pricing from Craigslist postings.  Data can be downloaded from [Kaggle](https://www.kaggle.com/austinreese/craigslist-carstrucks-data).  
There are 2 notebooks that build models for predicting car prices on craiglist posts and both start with Exploratory Data Analysis (EDA).  I've left comments on my interpretations of the analysis and underlying conclusions.  

## Processes

<b>Feature Selection</b>

Notebook starts with EDA and continues to modeling.  This notebook was designed to try majority of mainstream regression models to compare performances and pitfalls of each.

<ins>The following regression models were compared:</ins>
1. Linear Regression (R<sup>2</sup> = 0.657)
2. Ridge (R<sup>2</sup> = 0.666) 😱 interesting score!!
3. Lasso (R<sup>2</sup> = 0.637)
4. ElasticNet (R<sup>2</sup> = 0.616)
5. LinearSVR (R<sup>2</sup> = 0.556)
6. SVR 3rd degree (R<sup>2</sup> = 0.637)
7. Random Forest (R<sup>2</sup> = 0.809)
8. Gradient Boosting (R<sup>2</sup> = 0.738)

Tree based algorithms were also evaluated for feature importances.  Notebook walks through the process and indicates the most important features.


<b>Feature Extraction</b>

This notebook is supplemental to the Feature Selection.  Only a few models were used to inspect the impact of extracted features.  <b>Feel free to build additional models with derived features and compare the results to the previous notebook.</b>

After EDA I've created additional feature to account for outliers within odometer distribution.  Additional feature was derived by clustering odometer readings vs year with 3 clusters.  Once the clusters were assigned, cluster # was utilized as a categorical feature.  Model scores were improved accross the board (compare with feature selection notebook).  

Additionally, I've tried different scalers to inspect the impact they have on the model score and picked the best scaler for the data.

<ins>The following regression models were compared:</ins>
1. Linear Regression (R<sup>2</sup> = 0.705)
2. ElasticNet (R<sup>2</sup> = 0.704)


<b>P.S. convergence errors occured during grid search. The covergence errors resulted in lower scores, therefore those warnings can be ignored.</b>
