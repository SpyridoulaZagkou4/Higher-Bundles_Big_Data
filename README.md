# Higher-Bundles_Big_Data

# Description
The scope of the project is the end-to-end automation pipeline to model the propensity of customers who are more likely to purchase a higher-value bundle the next month in terms of an adhoc campaign to increase revenues. So, I analyze Prepay customers' usage, billing, status, demographics data and by training a classification Machine Learning model I can a extract a shortlist to target customer base with high propensity to do this migration.

# Requirements
1. pandas
2. numpy
3. imblearn
4. math
5. sklearn
6. lightgbm 
7. datetime 
8. matplotlib

-> for pyspark implementation on GCP:
9. pyspark
10. subprocess


# RESULTS

### Classification Report
![classification_report](https://github.com/SpyridoulaZagkou4/Higher-Bundles_Big_Data/assets/81852029/ab54969a-fea4-4795-9d32-2aaf3a5fa445)

For this case we give emphasis to recall metric because we want to detect as more customers as we can that are more likely to buy a higher-value bundle.
As we can see the model can detect efficiently the 78% of customers they did the migration 
###  Shap - Feature Importance 
Here we can se the most important variables that help the model to decide:
These features are like if is student or not, data usage, average recharges value, monthly bundle revenue, days with incoming calls etc..

![shap1](https://github.com/SpyridoulaZagkou4/Higher-Bundles_Big_Data/assets/81852029/c47bd9d5-9f0a-4dd1-a6de-f4ffb0fff3cd)
![shap2](https://github.com/SpyridoulaZagkou4/Higher-Bundles_Big_Data/assets/81852029/fd0f5266-6df1-48ed-8060-6fe60dd5d0d0)
