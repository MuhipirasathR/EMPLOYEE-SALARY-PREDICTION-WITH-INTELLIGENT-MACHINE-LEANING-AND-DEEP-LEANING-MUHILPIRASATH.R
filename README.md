# EMPLOYEE-SALARY-PREDICTION-WITH-INTELLIGENT-MACHINE-LEANING-AND-DEEP-LEANING BY MUHILPIRASATH.R
💼 EMPLOYEE SALARY PREDICTION WITH INTELLIGENT MACHINE LEANING AND DEEP LEANING   This project is a Machine Learning + Deep Learning based web app that classifies whether an employee earns more than ₹50K or less than or equal to ₹50K per month based on various personal and professional attributes like age, education, experience, and job role.
🔍 Problem Statement
Predict the income class (<= ₹50K or > ₹50K) using the Adult Census Income Dataset. This is a classic binary classification task commonly used for benchmarking ML models.

📊 Features Used

Age

Education Level

Job Title
Experience (Years)

Working Hours per Week

Location

Gender

Additional features for batch prediction:

Marital Status

Relationship

Race

Capital Gain / Loss

Workclass

Native Country

🛠️ Tech Stack

Python

Pandas, NumPy

Scikit-learn, XGBoost, LightGBM

Matplotlib, Seaborn (for data visualization)

Joblib (model saving/loading)

Streamlit (web app framework)

GitHub (version control)

📂Project Structure

├── app.py                   # Streamlit web app

├── app(final_muhil).py     # Final version of the web app

├── model_training.ipynb    # Jupyter Notebook used for model building

├── model_lightgbm_v2.pkl   # Trained ML model

├── adult 3.csv             # Cleaned dataset

├── requirements.txt        # Required Python packages

└── README.md               # Project overview (this file)

🧪 Model Used
Random Forest Classifier and LightGBM Classifier

Accuracy: ~86%

Label Encoding for categorical features

Split: 80% train / 20% test

Metrics: Accuracy, Confusion Matrix, Classification Report

🖥️ Web App Features

✅ Predict income class for a single user via form input

📁 Upload CSV for batch salary classification

📈 Model Evaluation Dashboard (Error %, MSE, R²)

📥 Download predictions as CSV file

🌙 3D-style Dark Mode UI with personal branding

👨‍💻 Intern Details

Muhilpirasath R

🎓 B.E Mechatronics Engineering – Batch 2027

🏫 Sona College of Technology

🚀 IBM-Edunet Foundation AICTE Internship (6 Weeks)

🌟 Acknowledgements

UCI ML Repository
Streamlit Documentation
Scikit-learn Docs
IBM SkillsBuild Internship
Edunet Foundation

📌 Future Improvements

✨ Add Deep Learning models (e.g., Neural Networks)

☁️ Full deployment on Streamlit Cloud

🧠 Hyperparameter tuning for best results

📊 Advanced model performance dashboards




