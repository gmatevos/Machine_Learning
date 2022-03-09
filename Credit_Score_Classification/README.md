# Description

This notebook builds a classification model using sklearn for classifying customers with good and bad credit.  
Data description can be found at https://www.openml.org/d/31

Results:
1. Data set came with cost matrix, therefore sampling frequency were adjusted to the cost weights during train / test split.
2. Problem states that it's worse to class a bad customer as good than to class good customer as bad, therefore Good was a positive class and precision was prioritized over the rest.
3. Tried Logistic Regression (Elastic, L1, L2), SVC and Random Forest.  Out of which Linear models performed the best with positive class precision of 0.91 for Elastic net.

## Contents
1. EDA - analysis of categorical and continous features
2. Models - Logistic Regression, SVM, Random Forest and Gradient Boosting
3. Model tuning and probability calibrations
4. Feature reduction

<b>P.S. convergence errors occured during grid search.  The covergence errors resulted in lower scores, therefore those warnings can be ignored.</b>
