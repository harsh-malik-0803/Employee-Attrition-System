# Employee-Attrition-System

Attrition = resignation from a workforce.

Organizations spend many resources in hiring talented employees and training them. Every employee is critical to a company’s success. 
My goal is to predict employee attrition and identify the factors contributing to an employee leaving a workforce. 
I trained various classification models on our dataset and assessed their performance using different metrics such as accuracy, precision, recall and F1 Score. 
I also analyzed the dataset to identify key factors contributing to an employee leaving a workforce. 
My project will assist organizations in gaining fresh insights into what drives attrition and thus enhance retention rate.

Dataset (35 *  1472) : https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset

I trained and evaluated 7 supervised machine learning classification models.

1. Logistic Regression
2. Naive Bayes
3. Decision Tree
4. Random Forest
5. AdaBoost
6. Support Vector Machine
7. K-Nearest Neighbors

I trained our models on 6 different datasets: Imabalanced , Undersampled , Oversampled , PCA

To get the best performance : 
1) hyperparameter tuning was carried out using RandomSearchCV and GridSearchCV.
2) K-fold cross-validation with 5 folds was also performed on the training set.

Evaluation metrics: accuracy, precision, recall and F1 Score.

Best Model : Random Forest Model with PCA and Oversampling 
Accuracy of 99.3%,
Precision of 98.2%
Recall of 99.6% 
F1 Score : 99.2%.
