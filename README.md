🎓 Student Dropout Prediction
📌 Overview

This project is a Machine Learning-based system that predicts whether a student is likely to drop out based on academic performance and personal attributes.

It helps institutions identify at-risk students early and take preventive actions to improve student retention.

🎯 Problem Statement

Student dropout is a major issue in education systems. Identifying students at risk in advance can help:

Improve academic success
Provide timely support
Reduce dropout rates

This project builds a predictive model to solve this problem.

🧠 Approach

The project follows a standard ML pipeline:

Data preprocessing
Feature selection
Handling imbalanced data using SMOTE
Model training using Random Forest Classifier
Model evaluation
Prediction using custom input
📊 Features Used
Curricular units 1st sem (grade)
Curricular units 2nd sem (grade)
Age at enrollment
Debtor status
🌲 Model Used

Random Forest Classifier

Why this model?

Handles non-linear data
Reduces overfitting
Works well with tabular datasets
📈 Output

The model predicts:

Dropout (Yes / No)
Probability of dropout (%)
Risk level (Low / Medium / High)
📂 Project Files
README.md                 # Project documentation
data.csv                  # Dataset
dropout_prediction.ipynb  # Machine learning notebook
⚙️ Installation & Setup
Clone the repository:
git clone https://github.com/your-username/student_dropout.git
cd student_dropout
Install dependencies:
pip install pandas numpy scikit-learn imbalanced-learn matplotlib
Run the notebook:
jupyter notebook
▶️ Usage
Open the notebook
Run all cells
Modify input values to test predictions

Example input:

[12, 14, 20, 0]
📊 Results
Model performs well on test data
Handles class imbalance using SMOTE
Provides probability-based predictions
🔥 Future Improvements
Add more features for better accuracy
Try advanced models (XGBoost, LightGBM)
Build a Streamlit web app
Deploy the project online
Add visualization dashboard
💡 Use Cases
Colleges & Universities
Academic advisors
Student monitoring systems
Educational analytics
👨‍💻 Author

Swaran
