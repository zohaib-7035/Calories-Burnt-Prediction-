# Calories Burnt Prediction

This repository contains a machine learning model to predict calories burnt based on exercise and personal data using XGBoost Regressor.

## Dataset
The dataset consists of:
- Exercise-related attributes (e.g., Age, Height, Weight, Duration, Heart Rate, Body Temperature)
- Gender information (encoded as 0 for male, 1 for female)
- Calories burnt (target variable)

## Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost

## Steps in the Project
1. Load the dataset (`data.csv` and `exercise.csv`).
2. Merge the datasets based on relevant columns.
3. Perform data preprocessing:
   - Handle missing values
   - Encode categorical variables
   - Split data into training and testing sets
4. Train the XGBoost Regressor model.
5. Evaluate model performance using Mean Absolute Error (MAE).

## Results
The model predicts calories burnt with an MAE of **1.4**, indicating a high level of accuracy.

## Contributing
Feel free to fork this repository and submit pull requests for improvements!
