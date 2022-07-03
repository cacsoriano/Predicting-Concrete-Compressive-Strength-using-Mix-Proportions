# Halo-Halo! Predicting Concrete Compressive Strength using Mix Proportions

A data science project on predicting the compressive strength of concrete using different proportions of ingredients with regression models. Open the `Technical_Report.ipynb` to view the full report.

### Highlights
1. Concrete compressive strength is non-linear because linear models perform poorly when it is fitted.

2. For the full dataset, the best model is Random Forest with `$R^2 = 0.9205$` and age as the top predictor.

3. For the `$age >= 28$`, the best model is Random Forest with an R2 of 0.9049 for the full dataset and wc_ratio as the top predictor.

A distinction was made between the inclusion of partially cured concrete due to different use cases.

Implementation uses GridSearchCV, RepeatedKFold and Pipeline from the scikit-learn library not discussed in class.


A partial fulfillment for the requirements for AIM MSDS 2022 Machine Learning 1 under Prof. Chris Monterola.
