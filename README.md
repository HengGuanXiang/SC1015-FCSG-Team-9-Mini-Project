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
3. SVM
4. KNN
5. Logistic Regression
6. Random Forest
7. Categorical Naive Bayes
8. Conclusion

# Data Cleaning
The original data set had 300 variables so data cleaning was done to choose 5 variables : GenHealth, Stroke, DiffWalking, AgeCategory and PhysicalHealth

# Exploratory Data Analysis
Exploratory Data Analysis was done to study the trends in the different categories.

# Models used
The dataset was initially unbalanced with a way higher number of samples with the response variable being HeartDisease: No. Therefore, for each model, we trained the unbalanced data set as well as the balanced data set (with an equal number of datasets with the response variable being HeartDisease: No and HeartDisease: Yes) to observe how the accuracy changed. 

# Conclusion
Through this project, we have figured out that the best model to predict the presence of heart disease is SVM and KNN.  <br>
The variables that have the highest indication of heart disease is general health and especially age.

#Possible improvements
Gridsearch for all models utilised, certain models we did are not optimised by gridsearch
Further exploratory of other datas that were not selected could have highlighted some useful features we could have missed out

# What we learnt
- How to work wth categorical data such as correlation (chi-square) and do eta on categorical data
- We learnt the various types of models that can be used for machine learning, especially what kind of models are relevant specifically for datasets wth a huge amount of categorical data.
- The sensitivity and how certain models are more basic vs complex
- How to use classification report to determine the best machine learning model
  

# References

https://medium.com/@gridflowai/part-3-categorical-naive-bayes-deep-dive-with-code-example-c759725e76c5#:~:text=Categorical%20Naive%20Bayes%20is%20designed,distinctly%20separated%20into%20multiple%20categories. <br>

https://www.bhf.org.uk/-/media/files/for-professionals/research/heart-statistics/bhf-cvd-statistics-global-factsheet.pdf?rev=f323972183254ca0a1043683a9707a01&hash=5AA21565EEE5D85691D37157B31E4AAA#:~:text=Coronary%20(ischaemic)%20heart%20disease%20is,commonly%20diagnosed%20heart%20disease%20worldwide.&text=It%27s%20estimated%20around%20200%20million%20people%20are%20living%20with%20coronary%20heart%20disease.&text=Globally%20around%20110%20million%20men,women%20have%20coronary%20heart%20disease  <br>

https://medium.com/@manindersingh120996/understanding-categorical-correlations-with-chi-square-test-and-cramers-v-a54fe153b1d6<br>

https://towardsdatascience.com/machine-learning-basics-with-the-k-nearest-neighbors-algorithm-6a6e71d01761<br>

https://www.geeksforgeeks.org/support-vector-machine-algorithm/<br>

https://www.datacamp.com/tutorial/random-forests-classifier-python  <br>

# Contributions
Guan Xiang - Data cleaning, SVM, KNN, Logistic Regression <br>
Sheereen - Exploratory Data Analysis, Random Forest <br>
Deepika - Exploratory Data Analysis, Naive Bayes <br>


