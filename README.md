# machine_learning_project-supervised-learning

## Project Goal
- Supervised Learning: use supervised learning techniques to build a machine learning model that can predict whether a patient has diabetes or not, based on certain diagnostic measurements.The project involves three main parts: exploratory data analysis, preprocessing and feature engineering, and training a machine learning model. 
### Duration:
Approximately 3 hours and 20 minutes.
### Project Process:
1. Load dataset
2. EDA
- Examine for null data
- Looking at the distribution of features through pairplot and examine the relationshiop of predictor to the outcome distribution and outlier
3. (i) Data processing 
- Eliminate invalid data
3. (ii) Feature engineering
- Split the data into train and test data with sklearn
- Standardize features(X_train, X_test) with sklearn Standardscaler
4. Modelling
- Create a logistic regression model to classify the outcome with feature with the train data through sklearn
- Create a random forest model to classify the outcome with feature with the train data through sklearn
5. Model Evaluation
- Create confusion matrix and ROC curve with sklearn
- Calculate accuracy_score, recall_score, precision_score, F1_score with sklearn.metrics
### Results
Random forest is a more accurate model.
### Challenges
Time constraint with less than a day to work on the project, only a base model is create with less time spending to examine the fit of the model. 
### Future Goals
Only create a base model due to the time constraint. Data process can be enhance with more time spend to examine and processing possible outlier or extreme cause that can lead to false positive or false negative in the classification to enhance the accuracy of the model. Model fitting can be improve with more time spending on model evaluation. More time to examine whether the model overfit or underfit epecially with random forest, hyperparameter can be examine to see the fit of the base model. More supervised learning model can be create to determine the best model that can be generalize to the real data and examine with an actual real data set.


