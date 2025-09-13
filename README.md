# Churn-Customer-Prediction

## Summary
The document describes a project to build a supervised machine learning model for predicting customer churn for an online food ordering provider. The file highlights the business importance of churn prediction, noting that retaining existing customers is more cost-effective than acquiring new ones. The document then proceeds with the initial steps of the machine learning pipeline, including importing necessary libraries and creating a simulated dataset for the task.

## 1. Importing Libraries
The project begins by importing a variety of Python libraries commonly used in machine learning. These include: 

pandas and numpy for data manipulation and numerical operations. 

matplotlib.pyplot and seaborn for data visualization. 

sklearn.model_selection for splitting data into training and testing sets. 

sklearn.preprocessing for data scaling. 

sklearn.linear_model.LogisticRegression, sklearn.ensemble.RandomForestClassifier, and xgboost.XGBClassifier for the machine learning models themselves.


sklearn.metrics for evaluating model performance with metrics like a classification report, confusion matrix, and ROC curve.

## 2. Creating a Sample Dataset
The document creates a simulated dataset of 1000 customers with a random seed set for reproducibility. The dataset includes features such as: customer_id, last_order_days_ago, total_orders, avg_order_value, complaints and discount_used, 

The target variable is churn, which is a binary value where 1 indicates the customer has churned and 0 indicates they are still active.

## 3. Exploratory Data Analysis (EDA)
The document performs a preliminary analysis of the simulated data. This includes:

Printing a statistical summary of the dataset.

Creating a bar chart to visualize the distribution of churned versus non-churned customers.

Generating a correlation heatmap to show the relationships between the features.

## Conclusion
The document successfully sets up a machine learning project for customer churn prediction by defining the problem, importing relevant libraries, creating a simulated dataset, and performing initial exploratory data analysis. However, it does not show the actual model training and evaluation, so it is not possible to determine which of the mentioned models would be most effective for this task. The project is a solid foundation, but it stops short of the final implementation and performance assessment.
