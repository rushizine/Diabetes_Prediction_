# Diabetes_Prediction_

## Project Title Diabetes Prediction Using Logistic Regression

## Project Overview
This project aims to predict whether a person is diabetic or not using various health-related attributes such as age, gender, hypertension, heart disease, BMI, HbA1c level, blood glucose level, and smoking history.

We use Machine Learning models to analyze the dataset and predict diabetes risk, which can help in early detection and preventive healthcare.

Dataset Description Structure of the Dataset Number of records: 100000 Number of columns: 9 The dataset used in this project contains the following features :-

## Feature Description :-
gender :- Gender of the patient (Male/Female) age :- Age of the patient hypertension :- 0 = No Hypertension, 1 = Hypertension heart_disease :- 0 = No Heart Disease, 1 = Heart Disease smoking_history :- Smoking status (never, former, current, No Info) bmi :- Body Mass Index HbA1c_level :- Average blood sugar over last 3 months blood_glucose_level :- Current blood glucose level diabetes :- (Target) 0 = Not Diabetic, 1 = Diabetic

## Project Workflow
Data Preprocessing • Checked for missing values and handled them appropriately.

• Converted categorical variables into numerical format using one-hot encoding.(e.g., gender, smoking history)

• Feature scaling (Standardization/Normalization)

Exploratory Data Analysis (EDA) • Statistical summaries

• Created a correlation heatmap to understand relationships between features.

• Data visualization (boxplots, heatmaps)

Model Selection and Building A logistic regression model was chosen for its simplicity and effectiveness in binary classification problems. Parameters such as max_iter=1000 were set to ensure convergence.

Model Training and Evaluation • Split the dataset into training and testing subsets. • Trained the logistic regression on training data. • Evaluated model performance using accuracy, confusion matrix, precision, recall, and F1-score.

## Results & Insights
The model achieved an accuracy of 95% on the test set. The confusion matrix showed a balanced prediction performance. Some features showed strong correlation with diabetes occurrence.

## Conclusion
This project successfully demonstrated diabetes prediction using logistic regression. For future work, more complex models like Random Forest or Neural Networks could be explored, and additional feature engineering could improve accuracy.

Technologies Used Python (NumPy, Pandas, Matplotlib, Seaborn)

Scikit-learn (ML models & evaluation)

Jupyter Notebook
