# SC1015 FCSG Team 9 Mini-Project
This is a mini projcect for module SC1015 by Lab Group FCSG Team 9.
Our group will be focusing on a heart disease problem with data from kaggle.
The dataset is retrieved from https://www.kaggle.com/code/andls555/heart-disease-prediction/input

# Problem definition
- What factor has the greatest importance when predicting presence of heart disease?
- Which machine learning model would be the best at predicting this?

# Order of our project
1. Data cleaning
2. Exploratory Data Analysis
3. SVM,
4. KNN
5. Logistic Regression
6. Random Forest
7. Categorical Naive Bayes

# Data Cleaning
The original data set had 300 variables so data cleaning was done to choose 5 variables : GenHealth, Stroke, DiffWalking, AgeCategory and PhysicalHealth

# Exploratory Data Analysis
Exploratory Data Anaalysis was done to study the trends in the different categories.

# Models used
The dataset was initially unbalanced with a way higher number of samples with the response variable being HeartDisease: No. Therefore, for each model, we trained the unbalanced data set as well as the balanced data set (with an equal number of datasets with the response variable being HeartDisease: No and HeartDisease: Yes) to observe how the accuracy changed. 

# Conclusion
Categorical Naive Bayes has the highest classification accuracy with 74.2% 

# What we learnt
- How to work wth categorical data and do eta on categorical data
- We learnt the various types of models that can be used for machine learning, especially what kind of models are relevant specifically for datasets wth a huge amount of categorical data. 

# References

https://medium.com/@gridflowai/part-3-categorical-naive-bayes-deep-dive-with-code-example-c759725e76c5#:~:text=Categorical%20Naive%20Bayes%20is%20designed,distinctly%20separated%20into%20multiple%20categories. <br>

# Contributions
Guan Xiang - Data cleaning, SVM, KNN, Logistic Regression <br>
Sheereen - Exploratory Data Analysis, Random Forest <br>
Deepika - Exploratory Data Analysis, Naive Bayes <br>


