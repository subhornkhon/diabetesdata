# Exploratory data analysis 
## data set
   diabetes data set  is originally from the National Institute of Diabetes and Digestive and Kidney Diseases.The datasets consist of several medical predictor (independent) variables and one target (dependent) variable, Outcome. Independent variables include the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.
   (https://www.kaggle.com/uciml/pima-indians-diabetes-database/version/1)
## Data visualization and pre-processing
  In this process, I use seaborn pairplot to visualize relationships between two independent variables.
## Feature selection
  I check the correlation between dependent variable (Outcome) and each independent variable and display in the form of heatmap. This is a quick and easy way to see the correlation. In order to create a model, I pick the most import features by using feature selection from extra tree classifier and display them in bar chart
  
  ## Classification
  I used various types of machine learning such as  K Nearest Neighbor(KNN),Decision Tree,  Logistic Regression and Support vector machine to build classification model and evaluate each model using jaccard similarity score
