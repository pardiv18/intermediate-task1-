# Project Give Life: Predict Blood Donations

## Project Description

"Blood is the most precious gift that anyone can give to another person — the gift of life." ~ World Health Organization

Forecasting blood supply is a critical and ongoing challenge for blood collection managers. For instance, in January 2019, the Red Cross experienced 27,000 fewer blood donations nationwide during the holidays compared to other times of the year. By leveraging machine learning, we can identify patterns in donation data to predict future blood donations and, consequently, save more lives.

In this project, you will work with data from the Blood Transfusion Service Center in Hsin-Chu City, Taiwan. The center sends its blood transfusion service bus to a university in Hsin-Chu City approximately every three months to collect blood donations. The dataset, sourced from the UCI Machine Learning Repository, consists of a random sample of 748 donors. Your task is to predict whether a blood donor will donate within a given time window. You will go through the complete model-building process, from inspecting the dataset to using the TPOT library to automate your machine learning pipeline.

To successfully complete this project, you should be familiar with Python, pandas, and logistic regression. We recommend familiarity with DataCamp's courses on "Manipulating DataFrames with pandas," "Preprocessing for Machine Learning in Python," and "Foundations of Predictive Analytics in Python (Part 1)."

## Project Tasks

### 1. Inspecting `transfusion.data` File
Before loading the data, examine the contents of the `transfusion.data` file to understand its structure and the type of data you will be working with.

### 2. Loading the Blood Donations Data
Load the blood donation data into a pandas DataFrame for further analysis and processing.

### 3. Inspecting the `transfusion` DataFrame
Explore the DataFrame to understand its structure, including the columns, data types, and basic statistics.

### 4. Creating the Target Column
Create a target column that indicates whether a donor will donate within a specified time window. This will be your prediction target for the model.

### 5. Checking Target Incidence
Calculate the incidence rate of the target variable to understand the distribution of donors who donate within the given time window versus those who do not.

### 6. Splitting `transfusion` into Train and Test Datasets
Split the data into training and testing datasets to evaluate the model's performance.

### 7. Selecting a Model Using TPOT
Use the TPOT library to automate the process of selecting the best machine learning model and hyperparameters for the given data.

### 8. Checking the Variance
Assess the variance in the data to identify potential issues with model generalization.

### 9. Log Normalization
Apply log normalization to the data to handle skewed distributions and improve model performance.

### 10. Training the Logistic Regression Model
Train a logistic regression model using the prepared data and evaluate its performance on the test set.

### 11. Conclusion
Summarize the findings, including model performance and potential next steps for further improving blood donation predictions.

By following these steps, you will build a robust machine learning model to predict blood donations, aiding blood collection managers in better forecasting and ensuring a steady blood supply.
