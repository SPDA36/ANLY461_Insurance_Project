# PURPOSE
* The purpose of this notebook is to explore an insurance dataset to determine the predictive performance and important features that govern the performance.  Note, there will not be any cross validation being conducted.  The entire dataset will be used for fitting the models.  It is acknowledged that overfitting is going to occur.  This notebook is not about standard practices but for gaining feature importance for the entire dataset.  Also, the notebook is supporting a college course which is not machine learning centric, so the additional attention will go unnoticed.  
## CONCLUSION
* EDA was conducted and in all examples, Smoking was a significant feature that was obvious.
* An ANOVA test was conducted, two OLS models, and a XGBoost model.  In all test, smoking was a significant feature.
* OLS regression was not able to capture enough variance to provide reliable predictive performance.
* XGBoost had significantly better performance as expected.  
* Cross validation needs to be conducted to ensure the model generalizes well.  Additionally, feature selection might imporve model fit times.
* Finally, the categorical variables were mean target encoded on the full dataset for the XGBoost model.  This is problematic for obvious reasons.  So, in the future the data needs split first and mean target encoded on training data only.
* Brandon Johnson
