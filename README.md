# Expedia Hotel Recommendations Analysis
In this project, we analyze the Expedia customer hotel search and booking dataset, available on Kaggle: Expedia Hotel Recommendations Dataset.
https://www.kaggle.com/competitions/expedia-hotel-recommendations/data?select=test.csv

### Project Overview
Our goal is to explore the dataset to understand customer behavior and preferences when searching for hotels on Expedia and to develop a model that can accurately recommend hotels to customers based on their search queries.

### Workflow
##### Step 1: Dataset Exploration
- Identify potential collinearity among features.
- Determine which features significantly influence hotel bookings.
- Assess the extent of missing values and strategize how to handle them.

##### Step 2: Feature Engineering and Data Preprocessing
- Creating new features informed by domain knowledge and insights gained from initial dataset exploration.
- Evaluating and addressing missing values through imputation or removal.
- Normalizing and encoding the dataset to prepare for machine learning model input, tailoring these steps to the nature of different features.

##### Step 3: Model Selection and Construction
- Considering the dataset characteristics and project objectives, we decide to implement a RandomForestClassifier model. This choice is motivated by the model's ability to handle complex interactions and non-linear relationships between features.

##### Step 4: Model Tuning
- Conduct analysis using edlbow plot to select the optimal number of estimators (n_estimators).
- Utilize GridSearchCV for comprehensive hyperparameters tuning, ensuring the best possible model performance.

