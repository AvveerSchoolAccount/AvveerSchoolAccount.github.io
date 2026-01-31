---
layout: post
title: 'Test Prediction Linear Regression'
---

**CLICK SUB TITTLE TO OPEN PROJECT**

This is about all the linear regression models I made for the Kaggle Contest. I spent a lot of time leearning this algorithum and even though I unerstand it pretty well, I am not very good at multivarient linear regression. I ended up getting a score of 12 which is not good since the the top ones are around 8.5. (I switched over to lightgbm later)

## [Model 1](https://avveerschoolaccount.github.io/Kraggle_Test_Scores_Comp_L1/)

For this project, I built a basic predictive model to estimate student exam scores using only study hours as a feature. I used linear regression to capture the general trend: students who studied more tended to score higher.

After training the model on the provided dataset, I generated predictions for the test data. To introduce a bit of variation and account for uncertainty in real-world performance, I added a small randomized adjustment to each predicted score, depending on the number of study hours.

The final predictions were rounded to one decimal place and exported as a CSV for submission. This project was my first hands-on experience with regression modeling and taught me how to preprocess data, fit a model, visualize results, and generate predictions programmatically.


## [Model 2](https://avveerschoolaccount.github.io/Kraggle_Test_Scores_Comp_L2/)

In this project, I built a simple predictive model to estimate student exam scores using study hours as the sole feature. I used linear regression to capture the general trend: more study hours generally lead to higher exam scores.

After training the model, I generated predictions for the test dataset. To simulate real-world variation in student performance, I applied a small randomized adjustment to each prediction, while ensuring scores stayed within realistic limits (0–100).

The final predictions were rounded to one decimal place and saved as a CSV file for submission. This model reinforced my understanding of linear regression, prediction pipelines, and handling output constraints, and it helped me gain confidence in applying machine learning to real data.



## [Model 3](https://avveerschoolaccount.github.io/Kraggle_Test_Scores_Comp_L3/)

For my final model, I aimed to improve prediction accuracy by incorporating both study hours and class attendance. I trained two separate linear regression models: one predicting exam scores from study hours, and another from class attendance.

To generate the final predictions, I combined the outputs from the two models using a weighted average:

For predicted scores ≤ 75, study hours were weighted more heavily (~76%), while class attendance contributed the rest (~24%).

For scores > 75, study hours dominated even more (~90%) to reflect its stronger correlation with exam performance.

This approach allowed the model to capture the primary influence of study habits while still considering class participation. The final predictions were rounded to one decimal place and exported for submission.

This project demonstrated the importance of feature selection, model combination, and data-driven weighting, marking a major step forward in my machine learning journey.
