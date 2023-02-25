
# Healthcare-Insurance-Analysis

Regression project using RandomForest, SGDRegressor and XGBoost

## Cost Prediction:

A significant public health concern is the rising cost of healthcare. Therefore, it's crucial to be able to predict future costs and gain a solid understanding of their causes. The insurance industry must also take this analysis seriously. This analysis may be used by healthcare insurance providers to make a variety of strategic and tactical decisions.

Data science methods have the potential to benefit other scientific fields by shedding new light on common questions. One such task isto help make predictions on medical data. Machine learning is an emerging scientific field indata science dealing with the ways in which machines learn from experience. The aim of this project is to develop a system which can perform early prediction of cost for a patient with a higher accuracy by combining the results of different machine learning techniques

## Data Preprocessing:
1. Collate the files so that all the information is in one place
2. Check for missing values in the dataset
3. Find the percentage of rows that have trivial value (for example, ?), and delete such rows if
they do not contain significant information
4. Use the necessary transformation methods to deal with the nominal and ordinal
categorical variables in the dataset
5. The dataset has State ID, which has around 16 states. All states are not represented in
equal proportions in the data. Creating dummy variables for all regions may also result in
too many insignificant predictors. Nevertheless, only R1011, R1012, and R1013 are worth
investigating further. Create a suitable strategy to create dummy variables with these
restraints.
6. The variable NumberOfMajorSurgeries also appears to have string values. Apply a suitable
method to clean up this variable.
Note: Use Excel as well as Python to complete the tasks
7. Age appears to be a significant factor in this analysis. Calculate the patients' ages based on
their dates of birth.
8. The gender of the patient may be an important factor in determining the cost of
hospitalization. The salutations in a beneficiary's name can be used to determine their
gender. Make a new field for the beneficiary's gender.
9. You should also visualize the distribution of costs using a histogram, box and whisker plot,
and swarm plot.
10. State how the distribution is different across gender and tiers of hospitals
11. Create a radar chart to showcase the median hospitalization cost for each tier of hospitals
12. Create a frequency table and a stacked bar chart to visualize the count of people in the
different tiers of cities and hospitals
Note: Use Excel as well as Python to complete the tasks

## Data science/data analysis
13. Test the following null hypotheses:
a. The average hospitalization costs for the three types of hospitals are not significantly
different
b. The average hospitalization costs for the three types of cities are not significantly
different
c. The average hospitalization cost for smokers is not significantly different from the
average cost for nonsmokers
d. Smoking and heart issues are independent
Note: Use Excel as well as Python to complete the tasks

## Machine Learning
1. Examine the correlation between predictors to identify highly correlated predictors. Use a
heatmap to visualize this.
2. Develop and evaluate the final model using regression with a stochastic gradient descent
optimizer. Also, ensure that you apply all the following suggestions:
Note:
• Perform the stratified 5-fold cross-validation technique for model building and validation
• Use standardization and hyperparameter tuning effectively
• Use sklearn-pipelines
• Use appropriate regularization techniques to address the bias-variance trade-off
a. Create five folds in the data, and introduce a variable to identify the folds
b. For each fold, run a for loop and ensure that 80 percent of the data is used to train the model
and the remaining 20 percent is used to validate it in each iteration
c. Develop five distinct models and five distinct validation scores (root mean squared error values)
d. Determine the variable importance scores, and identify the redundant variables
3. Use random forest and extreme gradient boosting for cost prediction, share your crossvalidation results, and calculate the variable importance scores
4. Case scenario:
Estimate the cost of hospitalization for Christopher, Ms. Jayna (her date of birth is
12/28/1988, height is 170 cm, and weight is 85 kgs). She lives in a tier-1 city and her state’s
State ID is R1011. She lives with her partner and two children. She was found to be
nondiabetic (HbA1c = 5.8). She smokes but is otherwise healthy. She has had no
transplants or major surgeries. Her father died of lung cancer. Hospitalization costs will be
estimated using tier-1 hospitals.
5. Find the predicted hospitalization cost using all five models. The predicted value should be
the mean of the five models' predicted values.

## Algortihms used:

• Random Forest Regressor
• XGBoost Regressor


