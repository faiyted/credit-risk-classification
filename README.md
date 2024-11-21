# credit-risk-classification

### Instructions
The instructions for this Challenge are divided into the following subsections:
- Split the Data into Training and Testing Sets
- Create a Logistic Regression Model with the Original Data
- Write a Credit Risk Analysis Report

### Split the Data into Training and Testing Sets
Open the starter code notebook and use it to complete the following steps:
- Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
- Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
- Split the data into training and testing datasets by using train_test_split.

### Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:
- Fit a logistic regression model by using the training data (X_train and y_train).
- Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
- Generate a confusion matrix.
- Print the classification report.
- Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

### Write a Credit Risk Analysis Report

- An overview of the analysis: The purpose of this analysis is to create and evaluate the accuracy of a data model that predicts the credity worthiness of potential borrowers from peer-to-peer lending services
- The results:
  - Accuracy Score: The overall accuracy of the model is 99%.
  - F1-score:
    - Class 0: 100% 
    - Class 1: 90% 
  - Precision Score:
    - Class 0: 1.00 (Healthy loans).
    - Class 1: 0.86 (High-risk loans).
    - Macro average: 0.93.
    - Weighted average: 0.99
  - Recall Score:
    - Class 0: 0.99 
    - Class 1: 0.94 
- Summary: The dataset contains a significant class imbalance (15001 healthy loans vs. 507 high-risk loans). Despite this, the model maintains high recall and precision for the minority class, demonstrating its effectiveness in handling real-world, imbalanced datasets. Overal, this model indicates good balance between identifying high-risk loans and accurately classifying healthy loans, making it a valuable tool for the company’s loan evaluation processes. 
