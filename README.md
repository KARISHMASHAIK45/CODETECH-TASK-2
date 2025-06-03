PREDICTIVE ANALYSIS  USING MACHINE LEARNING

COMPANY: CODETECH IT SOLUTIONS

NAME: SHAIK KARISHMA

INTERN ID : CT08DL1400

DOMAIN: DATA ANALYTICS

TASK: PREDIVTIVE ANALYSIS 

DURATION: 8 WEEKS

MENTOR: NEELA SANTOSH

DESCRIPTION


🎯 Objective
The primary objective of this project is to analyze historical credit card client data and build a predictive model that can determine whether a customer will default on their payment in the next month. Accurate credit default prediction helps banks and financial institutions manage risk, improve lending strategies, and protect revenue.


📁 Dataset
Name: UCI Credit Card Default Dataset

Format: .xlsx (Excel), with an alternative CSV loading method included

Source: Kaggle / UCI Machine Learning Repository

Target Variable: default.payment.next.month

Features: Includes demographic, financial, and historical repayment data such as LIMIT_BAL, SEX, EDUCATION, MARRIAGE, AGE, and past payment and billing amounts over six months.

This dataset is widely used for binary classification tasks and credit risk modeling.


🧰 Tools & Technologies Used
Tool	Purpose
Python	Programming language for data science
Pandas	Data manipulation and analysis
NumPy	Numerical computations
Scikit-learn	Machine learning library for model building
Matplotlib & Seaborn	Visualization libraries
OpenPyXL	Read Excel files in .xlsx format


💻 Platform
Development Environment: Google Colab

Dataset Source: Kaggle

Google Colab was used for its ease of setup, free access to computational resources, and seamless library management.


🔑 Key Steps in the Pipeline
Library Installation & Imports
All necessary libraries were installed and imported for data loading, analysis, preprocessing, and modeling.

Data Loading & Fallback Handling

Attempted to load the dataset as a CSV file.

If failed, it tried loading it as an Excel file using openpyxl.

Initial Inspection

Displayed the first few rows.

Checked the column names, shape, and data types.

Target Variable Identification

Renamed the target column from default.payment.next.month to Default for simplicity.

Data Cleaning & Preprocessing

Dropped the ID column as it's not predictive.

Checked for and filled missing values using mean for numeric and mode for categorical columns.

Identified numeric and categorical features dynamically using data types.

Train-Test Split

Split the dataset into 80% training and 20% testing using train_test_split() with stratification to maintain class balance.

Preprocessing Pipelines

Used ColumnTransformer to scale numeric features using StandardScaler.

One-hot encoded categorical features using OneHotEncoder.

Model Building with Logistic Regression

Combined preprocessing and modeling in a single pipeline.

Trained a logistic regression model using the liblinear solver.

Model Evaluation

Evaluated using accuracy_score, confusion_matrix, classification_report, and roc_auc_score.

Visualized the confusion matrix using a heatmap.

Prediction on New Data

Predicted using a sample of the test set.

Displayed both class predictions and probabilities for further interpretation.


🌐 Applications
This project has various practical applications in:

Banking and Finance: Assessing customer creditworthiness before loan approvals.

Credit Risk Management: Improving underwriting decisions and reducing default-related losses.

Data Science Education: Demonstrating a complete machine learning workflow—from raw data to prediction.

Model Prototyping: Serving as a starting point for deploying credit scoring models.


✅ Conclusion
This project demonstrates a full machine learning pipeline for binary classification using logistic regression. It shows how to clean and prepare data, handle missing values, scale and encode features, train a model, evaluate it with meaningful metrics, and visualize results. The final model offers interpretable output and lays the foundation for further experimentation or production deployment.


  OUTPUT 

![Image](https://github.com/user-attachments/assets/558c2634-176d-456c-8e49-ff08ed5f24e0)
![Image](https://github.com/user-attachments/assets/3bafc88c-8489-478e-b266-22b800fa7c09)
![Image](https://github.com/user-attachments/assets/062cf200-f5c2-43f0-81f8-7a9c8e55e696)
![Image](https://github.com/user-attachments/assets/6460c369-9865-45cf-9dce-32fd8615e1f4)
![Image](https://github.com/user-attachments/assets/83ff4d8e-250b-4024-ad21-305a23e15d85)
![Image](https://github.com/user-attachments/assets/9853e80c-ea8f-42ba-bfa7-a8edf0308da2)
