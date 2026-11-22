# Loan Approval Prediction Using Machine Learning

## Project Overview
This project was developed as part of the Machine Learning for Data Science (DS2401) course at Umm Al-Qura University.

The project aims to predict whether loan applications will be approved or rejected using machine learning classification algorithms. Two models, Random Forest and Decision Tree, were implemented and compared to evaluate their predictive performance.

## Dataset
- **Source:** [Loan Approval Prediction Dataset – Kaggle](https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset)
- **Records:** 4,269
- **Attributes:** 13
- **Target Variable:** `loan_status`

The dataset includes applicant information such as annual income, loan amount, CIBIL score, education, employment status, and asset values.

## Technologies and Tools
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Google Colab

## Project Workflow
1. **Data Exploration:** Examined the dataset structure, statistical summaries, missing values, and loan approval distribution.
2. **Data Preprocessing:** Selected relevant features and encoded categorical variables.
3. **Data Splitting:** Used 80% of the dataset for training and 20% for validation.
4. **Model Training:** Implemented Random Forest and Decision Tree classifiers.
5. **Model Evaluation:** Compared model performance using accuracy, confusion matrices, precision, recall, and F1-score.
6. **Feature Importance:** Analyzed the factors influencing loan approval predictions.

## Model Performance

| Model | Accuracy |
|---|---|
| Random Forest | 95.78% |
| Decision Tree | 92.97% |

Random Forest achieved the highest accuracy. Feature importance analysis identified the CIBIL score as the most influential predictor.

## Teamwork and My Contributions
This project was completed by a three-member student team.

**My individual contributions:**
- Reviewed, reorganized, and refined the existing machine learning code to improve its structure, consistency, and quality.
- Updated the implementation and reviewed the resulting outputs to ensure consistency between the code and the reported results.
- Independently prepared the complete technical report, documenting the methodology, model evaluation, findings, and conclusions.

## Project Files
- [Machine Learning Notebook](Loan_Approval_Prediction_GitHub.ipynb)
- [Loan Approval Dataset](loan_approval_dataset.csv)
- [Project Report](Loan_Approval_Prediction_GitHub_Report_Ready.pdf)

## How to Run
1. Open the notebook in Google Colab.
2. Upload `loan_approval_dataset.csv` to the Colab session.
3. Run the notebook cells in order to reproduce the analysis, model training, and evaluation results.

## Academic Information
- **University:** Umm Al-Qura University
- **Department:** Data Science
- **Course:** Machine Learning for Data Science (DS2401)
- **Project Type:** Academic Team Project (3 Members)
- **Year:** 2026
