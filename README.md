# Bank Marketing Campaign Prediction

This project focuses on predicting whether a customer will subscribe to a term deposit product based on various demographic and behavioral attributes. The prediction is performed using a Decision Tree Classifier.

## 📌 Objective

To help financial institutions identify potential customers more likely to respond positively to a marketing campaign, thereby improving targeting efficiency and campaign success.

### 📂 Dataset Details
Source: UCI Machine Learning Repository – Bank Marketing Dataset

Total Records: 45,211

Features: 16 input variables (numeric and categorical) + 1 output variable (y)

Target Variable:

y: Whether the client subscribed to a term deposit (binary: yes or no)

#### Key Features Include:
age: Age of the client

job: Type of job

marital: Marital status

education: Education level

default: Has credit in default?

housing: Has a housing loan?

loan: Has a personal loan?

contact: Contact communication type

month: Last contact month

day_of_week: Last contact day of the week

duration: Last contact duration

campaign: Number of contacts during this campaign

pdays: Days since client was last contacted

previous: Number of contacts before this campaign

poutcome: Outcome of the previous campaign

## 🧰 Tools & Libraries Used
Python

Pandas, NumPy

Scikit-learn

Seaborn, Matplotlib

## 🔄 Workflow Summary: 
Data Loading

Exploratory Data Analysis (EDA)

Handling Missing Values

Label Encoding Categorical Variables

Feature Selection & Data Splitting

Model Building with Decision Tree

Model Evaluation using Accuracy, Confusion Matrix, and Classification Report

Decision Tree and Confusion Matrix Visualization

## 📊 Outcome
The final model provides:

Clear interpretation of decision rules using a decision tree

Classification performance metrics for model evaluation

Insight into key factors that influence customer subscription behavior
