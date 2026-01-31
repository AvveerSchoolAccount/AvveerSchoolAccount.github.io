---
layout: post
title: 'Test Prediction LightGBM'
---

**CLICK SUB TITTLE TO OPEN PROJECT**

This is the latest and the most advanged regression model I have learnt. I have only made one model but that model boosted my score to 8.7 the top 100 have scores. This model is great with large datasets, lots of features and tabular data.

## [Model 1](https://avveerschoolaccount.github.io/Kraggle_Test_Scores_Comp_L1/)

This project uses a LightGBM regression model to predict students’ exam scores based on demographic, academic, and environmental factors. The dataset includes both numerical and categorical features such as gender, course, study method, sleep quality, internet access, exam difficulty, and facility rating. All categorical variables are handled natively by LightGBM, avoiding manual encoding and keeping the pipeline efficient.

- The model is trained using 5-fold cross-validation to ensure reliable performance.
- Early stopping is applied to prevent overfitting.
- Model performance is evaluated using Root Mean Squared Error (RMSE).
- This approach allows the model to generalize well while making full use of the training data.

A better one would have been to apply me lessons on feature engineering here, adding the hypothetical features since this is a model that benifits from a lot more features.
