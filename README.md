# Expedia-Hotel-Recommendation-Classification

In this project, we use the Expedia customer hotel searching and booking dataset from kaggle:
https://www.kaggle.com/competitions/expedia-hotel-recommendations/data?select=test.csv

Step 1: Explore the dataset
 - if there are any colinearity among features
 - which features impact booking
 - the percentage of null value

step 2: Feature engineering and Data processing
- create new features based on domain knowledge and previous dataset exploration
- Check the missing value
- Impute or drop the missing value
- Normalized and encoded dataset based on different features

step 3: select and build model
- based on the dataset and the task requirement, we create the RandomForestClassifier model
  
step 4: Feature tunning 
- draw study curve to choose the best n_estimators
- apply GridSearch to choose the rest hyperparameters



