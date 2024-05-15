# Customer Churn Prediction using Decision Tree 🌳🔍

## Project Overview

This project aims to build a Decision Tree model to predict customer churn for a service-providing company. Customer churn refers to customers who have decided to end their relationship with the company. The goal is to determine whether customers will renew their subscription for the coming year.

## Business Objective 🎯

The project involves building a decision tree model to classify whether customers will churn or not based on their interaction data with the service.

## Data Description 📊

The dataset consists of approximately 2000 rows and 16 columns with the following features:

1. `Year`: The year of subscription 📅
2. `Customer_id`: Unique identifier for each customer 🆔
3. `Phone_no`: Customer's phone number 📞
4. `Gender`: Gender of the customer (Male/Female) 🚹🚺
5. `Age`: Age of the customer 🎂
6. `No_of_days_subscribed`: Number of days since the subscription 🗓️
7. `Multi_screen`: Indicates if the customer has a single or multiple screen subscription 📺
8. `Mail_subscription`: Indicates if the customer receives emails 📧
9. `Weekly_mins_watched`: Number of minutes watched weekly ⏱️
10. `Minimum_daily_mins`: Minimum daily minutes watched 📉
11. `Maximum_daily_mins`: Maximum daily minutes watched 📈
12. `Weekly_nights_max_mins`: Number of minutes watched at night time 🌙
13. `Videos_watched`: Total number of videos watched 🎥
14. `Maximum_days_inactive`: Days since last active ⏳
15. `Customer_support_calls`: Number of customer support calls made 📞
16. `Churn`: Indicates if the customer churned (1-Yes, 0-No) ❌✅

## Aim 🎯

Build a decision tree model to determine whether the customer will churn based on the provided features.

## Tech Stack 💻

- **Language**: Python 🐍
- **Libraries**: NumPy, pandas, matplotlib, sklearn, pickle, imblearn 📚

## Project Structure 📁

Once you unzip the modular_code.zip file, you will find the following folders:

1. **input**: Contains all the data used for analysis (`Data_regression.csv`).
2. **src**: Contains all the modularized code.
    - `Engine.py`
    - `ML_Pipeline`: Contains various Python files for different functions.
3. **output**: Contains the best-fitted models that were trained. These models can be used for future use without retraining.
4. **lib**: Reference folder containing the original Jupyter notebook and a reference PowerPoint presentation.

## Approach 🚀

1. **Importing Libraries and Reading the Dataset**: Load the necessary libraries and read the dataset.
2. **Feature Engineering**: Drop unwanted columns and preprocess the data.
3. **Model Building**:
    - Perform train-test split
    - Build a Decision Tree Model
4. **Model Validation**:
    - Accuracy score 📈
    - Confusion matrix 🧩
    - ROC and AUC 📉
    - Recall score 🔁
    - Precision score 🎯
    - F1-score ⚖️
5. **Feature Importance**: Identify and plot important features 🌟

## Key Functions and Modules 🔑

- **Engine.py**: Main file that calls all other functions.
- **ML_Pipeline**: Contains functions for data preprocessing, model training, evaluation, and feature importance.

## Usage 🛠️

1. **Clone the repository**:
    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```

2. **Install the required libraries**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the engine.py** to train the model on the entire dataset:
    ```bash
    python src/Engine.py
    ```

4. **Outputs**: The trained models will be saved in the `output` folder.

## Results 📊

- The ROC curve for the Decision Tree model shows an AUC of 0.71, indicating the model's performance in distinguishing between churn and non-churn customers.

## Conclusion 📝

This project provides an end-to-end solution for predicting customer churn using a Decision Tree model. The approach includes data preprocessing, model building, evaluation, and feature importance analysis.

## References 🔗

- [Churn Analysis for Streaming App using Logistic Regression](https://www.projectpro.io/project-use-case/churn-analysis-logistic-regression)
- The project utilizes Python libraries such as sklearn, matplotlib, and imbalanced-learn for various tasks including data processing, model training, and evaluation.

## License 📜

This project is licensed under the MIT License - see the LICENSE file for details.
