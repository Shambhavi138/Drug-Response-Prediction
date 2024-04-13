**Drug Response Prediction Model**<br>
_Overview_<br>
This repository contains a machine learning model to predict the appropriate medication for patients suffering from a specific illness based on their demographic and health data. The model utilizes a decision tree classifier trained on a dataset of patients who responded to one of five medications: Drug A, Drug B, Drug C, Drug X, and Drug Y.

_Dataset_<br>
The dataset comprises patient records with the following features:
Age
Sex
Blood Pressure
Cholesterol
Each patient in the dataset is labeled with the medication they responded to, which serves as the target variable for the classification task.

_Methodology_<br>
The model development process involves:<br>
-Data preprocessing: Handling missing values, encoding categorical variables, and scaling numerical features.<br>
-Model training: Building a decision tree classifier using the training data.<br>
-Model evaluation: Assessing the performance of the trained model using appropriate metrics such as accuracy, precision, recall, and F1-score.<br>
-Prediction: Using the trained model to predict the appropriate medication for new patients based on their features.<br>
