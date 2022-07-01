# Credit_Risk_Analysis

## Overview of the analysis: 
The purpose of this analysis is to: (1)Use Resampling Models to Predict Credit Risk; (2)Use the SMOTEENN Algorithm to Predict Credit Risk; and (3)Use Ensemble Classifiers to Predict Credit Risk

The deliverables can be found here:
https://github.com/legeren/Credit_Risk_Analysis/blob/9f00b9130b8f8fc22a6f21e2dc8b4ea7928e467f/credit_risk_resampling.ipynb
https://github.com/legeren/Credit_Risk_Analysis/blob/9f00b9130b8f8fc22a6f21e2dc8b4ea7928e467f/credit_risk_ensemble.ipynb


## Results: 
1. Random Over Sampling - The balanced accuracy score is 64%.  The high risk precision is 1% only with 62% sensitivity which makes a F1 of 2%.

![image](https://user-images.githubusercontent.com/100737452/176973685-30ba2df6-fba3-481d-a680-448e3be5f8be.png)

2. SMOTE Over Sampling - The balanced accuracy score is 63%.  The high risk precision is 1% only with 62% sensitivity which makes a F1 of 2%.

![image](https://user-images.githubusercontent.com/100737452/176973727-0a2210ad-9d44-4e13-8cc3-3900a0aac978.png)

3. Under Sampling - The balanced accuracy score is 51%.  The high risk precision is 1% only with 56% sensitivity which makes a F1 of 1%.

![image](https://user-images.githubusercontent.com/100737452/176973784-27bd9082-80da-460c-b863-404219d76228.png)

4. Combination Over/Under Sampling - The balanced accuracy score is 62%.  The high risk precision is 1% only with 71% sensitivity which makes a F1 of 2%.

![image](https://user-images.githubusercontent.com/100737452/176973824-32e9b880-d8e3-4e7b-8d49-b46fb849bb4a.png)

5. Balanced Random Forest Classifier - The balanced accuracy score is 78%.  The high risk precision is 4% only with 67% sensitivity which makes a F1 of -%.

![image](https://user-images.githubusercontent.com/100737452/176973990-d84d13f5-08c3-4419-9f85-23c9f2cca886.png)

6. Easy Ensemble Classifier - The balanced accuracy score is 93%.  The high risk precision is 9%  with 92% sensitivity which makes a F1 of 16%.

![image](https://user-images.githubusercontent.com/100737452/176973878-791ea31f-75e1-4b44-8ecc-561fefdbb86e.png)


## Summary: 

In summary, although machine learning may help someone predict credit risk, all models used in this project's analysis still show weak precision to determine high credit risk.  I would recommend the ensemble models to use only because they have a higher precision (4% and 9% respectively vs 1% for others) compared to the other models.
