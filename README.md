# Project-HR_case_study_ML
Use ML models to predict the decision of employees are leave or stay in company. Find important feature that they should make to their workplace, in order to get most of their employees to stay.

1.datasets from Kaggle: https://www.kaggle.com/datasets/vjchoudhary7/hr-analytics-case-study

2. Flow
- Import data, import library: NumPy, Pandas, Matplotlib, Scikitlearn...
- Pre-Processing data: missing value, outlier, data type, merged tables
- EDA: visualize data to find correlation of features
- Determine the problem: Supervise learning, Classification, select features
- Built Machine learning models: Split train-test set, Onehot, Scaler data, Traning model, Fit with test set, Accuracy rating
- Conclusion

3. EDA:

- Consider the difference of column attrition

<img align="top" alt="Atrition" width="600px" src="https://github.com/duydk-DA/Ecommerce_sales_report/assets/132973078/9e8ee4c8-2b3c-45d2-a67a-d8571bbb4c79" />

- Distribution of data on the decision to leave work of 2 sexes Male and female by age

<img align="top" alt="Age" width="600px" src="https://github.com/duydk-DA/Ecommerce_sales_report/assets/132973078/732563e1-dc7f-43c5-9e82-307c569a284a" />

- Distribution of data by income

<img align="top" alt="Age" width="600px" src="https://github.com/duydk-DA/Ecommerce_sales_report/assets/132973078/5016ddbf-1b50-4f3c-a12a-53ef0497d7e2" />

- Distribution of data by TotalWorkingYears

<img align="top" alt="Age" width="600px" src="https://github.com/duydk-DA/Ecommerce_sales_report/assets/132973078/9a08c248-4c81-4b60-add5-b684c6494f44" />

- Employee Survey

<img align="top" alt="Age" width="1000px" src="https://github.com/duydk-DA/Ecommerce_sales_report/assets/132973078/9bb9ae8a-d7ea-4373-86d3-0f6e1ede2510" />

4. Machine Learning Models

<img align="top" alt="Age" width="800px" src="https://github.com/duydk-DA/Ecommerce_sales_report/assets/132973078/648de5da-cf94-4710-b37f-e80900d058e9" />

<img align="top" alt="Age" width="800px" src="https://github.com/duydk-DA/Ecommerce_sales_report/assets/132973078/9dfcaa07-ac03-4f78-a47b-3abf2bace132" />

<img align="top" alt="Age" width="800px" src="https://github.com/duydk-DA/Ecommerce_sales_report/assets/132973078/5364b45a-2534-4dfb-9784-ca535cca0a66" />

5. Conclusion
- Random forest model is best model for this dataset with best accuracy = 95.69%, and best F1 score = 85.77%. However KNN and Decision tree are good models, its so completely applicable to this data set
- Featrue Important that company shoud make to their workplace: Salary, Enviroment, Training, Age and year experience of employee or candidate when the company hiring




