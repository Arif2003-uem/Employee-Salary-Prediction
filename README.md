💼 Fair Salary Assessment & Anomaly Detection System

A Machine Learning–based web application built using Streamlit that predicts employee salary categories and helps identify potential salary anomalies.
This project aims to assist HR teams and analysts in making data-driven and fair compensation decisions.

📌 Project Overview:
This system predicts whether an employee earns:
≤ 50K
> 50K
based on demographic and employment-related features such as age, education, occupation, working hours, and more.
The application supports:
Individual salary prediction
Batch prediction via CSV upload
Feature importance visualization
Fairness and anomaly analysis

🚀 Features:

✅ Real-time Salary Prediction
✅ Batch Prediction using CSV Upload
✅ ML Pipeline with Scaling & Classification
✅ Feature Importance Visualization
✅ Clean & Interactive Streamlit UI
✅ End-to-End ML Deployment

🧠 Machine Learning Details
Dataset: Adult Census Income Dataset
Algorithm: Gradient Boosting Classifier
Preprocessing:
Missing value handling
Outlier removal
Label encoding
Feature scaling

Model Storage: joblib

Pipeline Used:

StandardScaler → GradientBoostingClassifier

🛠️ Tech Stack
Category	Tools
Language	Python
Frontend	Streamlit
ML	Scikit-learn
Data Handling	Pandas, NumPy
Visualization	Matplotlib, Seaborn
Model Saving	Joblib
📂 Project Structure
📁 Salary-Prediction-App
│
├── app.py                  # Streamlit application
├── best_model.pkl          # Trained ML model
├── adult.csv               # Dataset
├── requirements.txt        # Dependencies
└── README.md               # Project documentation

▶️ How to Run the Project
1️⃣ Install Dependencies
pip install streamlit pandas scikit-learn matplotlib seaborn joblib

2️⃣ Run the Application
streamlit run app.py

3️⃣ Open in Browser

The app will open automatically at:

http://localhost:8501

📊 Application Features
🔹 Individual Prediction
Input employee details
Get salary class prediction
View prediction confidence

🔹 Batch Prediction
Upload CSV file
Automatic preprocessing
Download result file

🔹 Feature Importance

Visual explanation of model decisions
Helps detect bias & salary imbalance

🎯 Use Cases

✔ HR Salary Analysis
✔ Fair Pay Assessment
✔ Machine Learning Portfolio Project
✔ Data Science Demonstration
✔ Academic Submission

📌 Future Enhancements
Add SHAP explainability
Deploy on Streamlit Cloud
Improve encoding using saved encoders
Add salary range prediction
Role-based dashboard

👨‍💻 Author

Arif Mondal
B.Tech CSE (AI & ML)
Institute of Engineering & Management, Kolkata
