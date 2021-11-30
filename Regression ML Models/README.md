# Description
There are 2 notebooks that build models for predicting car prices on craiglist posts.  
1. Feature selection notebook starts with EDA and continues to preprocessing and building models (Linear, Ridge, Lasso, ElasticNet, SVM, Random Forest and Gradient Boosting).  Feature selection procedure was completed at the end after the models were inspected and tuned.
2. Feature extraction notebook starts with EDA and continues to feature extraction using KMeans and Gaussian Mixture.  Linear regression models are then ran on data along with new features. 

## Data
Data can be downloaded from Kaggle:  https://www.kaggle.com/austinreese/craigslist-carstrucks-data

P.S. convergence errors occured during grid search. The covergence errors resulted in lower scores, therefore those warnings can be ignored.
