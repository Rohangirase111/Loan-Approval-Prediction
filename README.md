# Loan Approval Prediction Using Random Forest

## 1. Project Overview

The Loan Approval Prediction project is a Machine Learning-based classification system developed to predict whether a loan application will be approved or rejected based on applicant information.

The project uses the **Random Forest Classifier** algorithm to analyze applicant details such as income, credit score, loan amount, and asset values to make predictions.

## 2. Objectives

- Understand and analyze the loan approval dataset.
- Perform data preprocessing and exploratory data analysis (EDA).
- Identify important features influencing loan approval.
- Build a Machine Learning classification model using Random Forest.
- Evaluate the model's performance using appropriate evaluation metrics.
- Save the trained model for future predictions.

## 3. Technologies and Libraries Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Pickle

## 4. Dataset Information

**Dataset Name:** loan_approval_dataset.csv

The dataset contains applicant-related information used to predict loan approval status.

Some important features include:

- Applicant Income
- Credit Score
- Loan Amount
- Residential Assets Value
- Commercial Assets Value
- Luxury Assets Value
- Bank Asset Value
- Loan Status

## 5. Machine Learning Algorithm

**Random Forest Classifier**

Random Forest is a supervised Machine Learning algorithm that uses multiple decision trees to perform classification.

The algorithm combines predictions from multiple decision trees to generate the final prediction.

It is used in this project to classify loan applications into approved or rejected categories.

## 6. Project Workflow

1. Import required Python libraries.
2. Load the loan approval dataset.
3. Understand the dataset structure and features.
4. Perform data cleaning and preprocessing.
5. Conduct Exploratory Data Analysis (EDA).
6. Perform feature selection and prepare the data.
7. Split the dataset into training and testing sets.
8. Train the Random Forest classification model.
9. Evaluate model performance.
10. Analyze feature importance.
11. Save the trained model using Pickle.

## 7. Model Evaluation

The trained model is evaluated using classification performance metrics such as:

- Accuracy Score
- Confusion Matrix
- Classification Report
- Precision
- Recall
- F1-Score

These metrics help assess how effectively the model predicts loan approval outcomes.

## 8. Project Structure

```text
Loan_Approval_Prediction/
│
├── loan_approval_dataset.csv
├── Loan_Approval_Prediction_RF.ipynb
├── loan_approval_model.pkl
├── Project_Report.pdf
├── README.md
└── requirements.txt
```

## 9. How to Run the Project

**Step 1:** Clone the repository.

```bash
git clone <your-github-repository-link>
```

**Step 2:** Navigate to the project directory.

```bash
cd Loan_Approval_Prediction
```

**Step 3:** Install the required libraries.

```bash
pip install -r requirements.txt
```

**Step 4:** Open Jupyter Notebook.

```bash
jupyter notebook
```

**Step 5:** Open `Loan_Approval_Prediction_RF.ipynb` and run the notebook cells.

## 10. Conclusion

The Loan Approval Prediction project demonstrates the application of Machine Learning using the Random Forest classification algorithm.

The project covers dataset understanding, data preprocessing, exploratory data analysis, model training, and performance evaluation.

The trained model predicts whether a loan application is likely to be approved or rejected based on applicant information. Feature importance analysis also provides insights into the attributes influencing the model's predictions.

This project demonstrates how Machine Learning can support automated classification tasks. Further improvements could include training and testing with real-world datasets and exploring additional classification algorithms.

---

**Project Title:** Loan Approval Prediction Using Random Forest  
**Domain:** Machine Learning  
**Algorithm:** Random Forest Classifier  
**Language:** Python