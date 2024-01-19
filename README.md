# Binary Binary Rainfall Prediction using ML


The project focuses on predicting the possibility of rainfall. We have made the use of supervised – classification-based Machine Learning algorithms predicting binary outcomes as either “Yes” or “No”. 
The data set contains several predictors and we have made the use of the following: 'Location', 'MinTemp', 'MaxTemp', 'Rainfall', 'Evaporation', 'Sunshine', 'WindGustDir', 'WindGustSpeed', 'WindDir9am', 'WindDir3pm', 'WindSpeed9am', 'WindSpeed3pm', 'Humidity9am', 'Humidity3pm', 'Pressure9am', 'Pressure3pm', 'Cloud9am', 'Cloud3pm', 'Temp9am', 'Temp3pm', 'RainToday'. 
We have made the use of supervised classification techniques for this project, the target variable being 'RainTomorrow'
The Following Supervised Machine Learning algorithms were used:
1.	Logistic Regression 
2.	Decision Tree
3.	Neural Network 
4.	Random Forest
5.	LightGBM, CatBoost & XGBoost

Exploratory Data Analysis and Machine Learning
	In order to clean and analyse the dataset we have imported the following libraries:
1.	Pandas 
2.	Numpy
3.	Seaborn
4.	Scikit-Learn

Since the dataset was imbalanced, we have performed the oversampling technique in order to balance the target variable.
 
We then removed the outliers from the dataset and performed further data cleaning. After successfully removing the noise, we apply the machine learning algorithms.
1.Logistic Regression
Performed Lasso– L1 Regression technique and was able to achieve an accuracy of 78%.

2.Decision Tree
Achieved an accuracy of 86.50%.

3.Neural Network 
Achieved an accuracy of 88.59%

4.Random Forest
Achieved an accuracy of 93.55%

5.LightGBM, CatBoost & XGBoost
Achieved an accuracy of 86.78%,94.94% & 94.64% respectively for all the three boosting techniques.

We were able to achieve the highest accuracies using Catboost and XGboost techniques which are 94.94% & 94.64% respectively. Hence Catboost has proven to be the most accurate algorithm for this data.
