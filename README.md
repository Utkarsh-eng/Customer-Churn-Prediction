📌 Customer Churn Prediction

This project predicts customer churn in the telecom industry, i.e., whether a customer will discontinue using the company’s services. Retaining customers is far more cost-effective than acquiring new ones, so churn prediction helps businesses design targeted retention strategies.

🚀 Project Overview

Built a machine learning model to identify at-risk customers.

Used the Telco Customer Churn dataset containing demographic, account, and service usage details.

Performed EDA, preprocessing, and class balancing to improve model performance.

Implemented and compared Decision Tree, Random Forest, and XGBoost classifiers.

Achieved 81.7% accuracy with improved precision using Random Forest.

📂 Dataset

The dataset is the WA_Fn-UseC_-Telco-Customer-Churn.csv, which contains:

Demographic info: Gender, senior citizen, partner, dependents.

Account details: Tenure, contract type, payment method, monthly/total charges.

Services subscribed: Phone service, multiple lines, internet service, streaming, etc.

Target variable: Churn (Yes/No).

🛠️ Tech Stack

Language: Python

Libraries:

pandas, numpy → Data handling

matplotlib, seaborn → Data visualization

scikit-learn → ML models, preprocessing, evaluation

imblearn (SMOTE) → Handling class imbalance

xgboost → Boosting classifier

pickle → Model saving

🔎 Methodology

Exploratory Data Analysis (EDA)

Checked dataset distribution and churn patterns using visualizations.

Data Preprocessing

Verified no missing values.

Applied Label Encoding for categorical features.

Balanced the dataset with SMOTE.

Modeling

Implemented Decision Tree, Random Forest, XGBoost.

Validated using k-fold cross-validation and accuracy.

Evaluation

Compared model accuracies.

Generated confusion matrix & classification report for Random Forest.

Random Forest achieved 81.7% accuracy with better churn prediction precision.

Model Saving

Exported the trained model using pickle for future use.

📊 Results

Random Forest Classifier outperformed Decision Tree and XGBoost.

Final Accuracy: 81.7%

Best Model: Random Forest (selected due to higher accuracy and precision).

💡 Purpose

To predict customer churn for telecom companies.

Help businesses retain customers by identifying high-risk users early.

Showcase end-to-end ML pipeline skills: EDA → preprocessing → modeling → evaluation → deployment.

📌 How to Run

Clone the repository

git clone https://github.com/Utkarsh-eng/Customer-Churn-Prediction.git
cd Customer-Churn-Prediction


Install dependencies

pip install -r requirements.txt


Run the Jupyter notebook

jupyter notebook churn.ipynb

✨ Future Improvements

Hyperparameter tuning for Random Forest & XGBoost.

Deployment with Flask / FastAPI or a web dashboard.

Adding business cost-based metrics (recall-focused).

👤 Author

Developed by Utkarsh

📧 Email: utkarsh@example.com

🌐 GitHub
