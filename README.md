💳 Fraudulent Transaction Detection
📌 Overview
This project focuses on detecting fraudulent financial transactions using machine learning techniques. With the rising number of digital transactions, it is crucial to develop intelligent systems that can identify suspicious patterns and prevent financial fraud in real time.



Data preprocessing
Feature encoding and selection
Exploratory Data Analysis (EDA)
Model training and evaluation
Addressing class imbalance

📂 Project Structure
main.ipynb: In-depth analysis with EDA, VIF analysis, PPS score visualization, feature encoding, SMOTE, and multiple classification models (LightGBM, XGBoost, Random Forest, etc.).

sample.ipynb: A cleaner, more modular version focused on pipeline creation, model training, and visualization.

📊 Dataset
Source: Fraud.csv
Target Variable: isFraud (binary classification)
The dataset includes transaction-related features such as:
Type of transaction
Amount
Origin and destination accounts
Time of transaction

🔍 Key Techniques Used
Label Encoding for categorical variables
Correlation Matrix & PPS Score to evaluate feature importance
VIF Analysis to detect multicollinearity
Visualization: KDE plots, bar charts, heatmaps
SMOTE for handling imbalanced classes

Models Used:
LightGBM
XGBoost
Random Forest
Logistic Regression
Ridge Classifier
SGD Classifier

⚙️ Model Evaluation
Models were evaluated using:
Confusion Matrix
Classification Report
Accuracy, Precision, Recall, F1-Score

