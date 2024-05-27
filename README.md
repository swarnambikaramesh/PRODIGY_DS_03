# PRODIGY_DS_03
Decision tree classifier based on behavioral and demographic data

## Overview
This project analyzes the Bank Marketing dataset from kaggle. The goal is to predict whether a customer will subscribe to a term deposit based on their demographic and behavioral data using a Decision Tree classifier. The project includes data cleaning, exploratory data analysis (EDA), and model training and visualization.
## Dataset
The dataset contains various attributes related to bank customers and their interactions with the bank's marketing campaigns. The primary columns include:
- `age`: Age of the customer.
- `job`: Type of job.
- `marital`: Marital status.
- `education`: Education level.
- `default`: Has credit in default?
- `balance`: Average yearly balance.
- `housing`: Has housing loan?
- `loan`: Has personal loan?
- `contact`: Contact communication type.
- `day`: Last contact day of the month.
- `month`: Last contact month of the year.
- `duration`: Last contact duration.
- `campaign`: Number of contacts performed during this campaign.
- `pdays`: Number of days since the client was last contacted from a previous campaign.
- `previous`: Number of contacts performed before this campaign.
- `poutcome`: Outcome of the previous marketing campaign.
- `deposit`: Target variable indicating whether the client subscribed to a term deposit.
- ## Requirements
To run the analysis and model training, you need the following Python libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- ## Model Training
A Decision Tree classifier was trained to predict whether a customer will subscribe to a term deposit. The model was trained using the following steps:
1. Split the data into training and testing sets.
2. Train the model using the training data.
3. Evaluate the model using the testing data.
  ## Conclusion
This project demonstrates the use of a Decision Tree classifier to predict customer behavior in a bank marketing campaign. The visualizations provide insights into the data and model performance, highlighting important features and their impact on the prediction.
