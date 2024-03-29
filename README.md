# Calories-Burnt-Prediction
## Data Preparation:
1. Two datasets, calories.csv and exercise.csv, are loaded into pandas DataFrames.
2. These DataFrames are concatenated to form a single DataFrame calories_data that combines exercise data with the calories burned.
3. Preliminary data exploration includes checking the DataFrame's size, missing values, and basic statistical measures.
4. The dataset consists of 15,000 instances, each with 9 features including User_ID, Gender, Age, Height, Weight, Duration, Heart_Rate, Body_Temp, and Calories.
## Data Analysis:
1. Visual analysis of the dataset includes count plots and distribution plots for various features like Gender, Age, Height, Weight, and Duration.
2. The Gender column is encoded from categorical (male, female) to numerical (0, 1).
3. The correlation between different features is visualized using a heatmap.
## Feature Selection and Preprocessing:
1. Features and the target variable (Calories burned) are separated.
2. The User_ID column is dropped as it's not relevant for predicting calories burned.
## Model Training:
1. The dataset is split into training (80%) and testing (20%) sets.
2. An XGBoost regressor model is instantiated and trained on the training data.
## Model Evaluation:
Predictions are made on the test set, and the model's performance is evaluated using the mean absolute error (MAE). The MAE in this case is approximately 1.48, indicating that on average, the predicted calories burned are within 1.48 calories of the actual values, which suggests a good model performance.
## Contributions:
Encourages contributions such as issue reporting or suggestions for improvements.Offers a detailed guide for setting up the environment, running the code, and contributing to the project.
