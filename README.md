# Heart-Failure-Survival-Project
This project focuses on predicting the survival of patients with heart failure using various machine learning algorithms. The dataset contains several clinical features that are used to train and evaluate the models.

**Introduction**
Heart failure is a common clinical syndrome characterized by the inability of the heart to pump sufficient blood to meet the body's needs. This project aims to predict the survival of patients with heart failure based on various clinical features using machine learning techniques.

**Dataset**
The dataset used in this project is the Heart Failure Clinical Records dataset. It includes 13 clinical features for 5000 patients:

age
anaemia
creatinine phosphokinase
diabetes
ejection fraction
high blood pressure
platelets
serum creatinine
serum sodium
sex
smoking
time
DEATH_EVENT (target variable)



**Data Preprocessing**
The data preprocessing steps include:

Handling missing values, duplicates, and outliers.
Encoding categorical variables.
Scaling numerical features.
Feature Selection
Relevant features are selected based on their correlation with the target variable and their significance in predicting heart failure survival.

**Model Training and Evaluation**
Several machine learning models were trained and evaluated:

Logistic Regression
Random Forest Classifier
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)
Models were evaluated using metrics such as accuracy, precision, recall, F1 score, and ROC-AUC.

**Results**
The results of the model evaluations are summarized below:

 1) Logistic Regression: Achieved significant predictive performance with simplicity and interpretability.
 2) Random Forest Classifier: Provided insights into feature importance and handled non-linear relationships effectively.
 3) Support Vector Machine (SVM): Maximized the margin between classes, enhancing classification performance.
 4) K-Nearest Neighbors (KNN): Offered straightforward approach and effectiveness in certain scenarios.

**Insights and Learning Outcomes**
 1) Data Preprocessing and Cleaning: Handled missing values, duplicates, and outliers to ensure data integrity.
 2) Feature Selection and Engineering: Identified and selected relevant features, transforming existing ones to improve model performance.
 3) Model Training and Evaluation: Trained multiple models and evaluated their performance using various metrics.
 4) Data Analysis Insights: Discovered key factors such as age, serum creatinine, and ejection fraction that significantly impact heart failure survival.
