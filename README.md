📌 Predictive Analytics for Customer Churn in a Subscription-Based Business


📖 Project Overview

This project aims to build a predictive model to identify customers likely to churn (cancel their subscription) in a subscription-based business. By leveraging machine learning techniques, we analyze key factors that contribute to churn and help businesses take proactive measures to retain customers.

🎯 Objective

Develop a machine learning model to predict customer churn.
Perform Exploratory Data Analysis (EDA) to uncover trends and correlations.
Evaluate model performance using various metrics.
Use SHAP/LIME to interpret model predictions and identify churn drivers.

🛠️ Tech Stack

Programming Language: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, SHAP, LIME

Visualization: Power BI, Matplotlib

Machine Learning Models: Logistic Regression, Random Forest

📂 Project Structure

📦 Predictive-Customer-Churn
├── 📁 data                 # Dataset files

│   ├── customer_churn.csv  # Raw dataset

│   ├── processed_data.csv  # Processed dataset

├── 📁 notebooks            # Jupyter Notebooks for analysis

│   ├── 01_EDA.ipynb        # Exploratory Data Analysis

│   ├── 02_Preprocessing.ipynb  # Data Preprocessing

│   ├── 03_Model_Building.ipynb # Model Training & Evaluation

├── 📁 reports              # Visualizations and reports

│   ├── churn_analysis.pbix # Power BI Report

├── 📄 requirements.txt      # Required Python libraries

├── 📄 README.md             # Project documentation


🔬 Project Workflow

1️⃣ Data Collection

Used Telco Customer Churn Dataset from Kaggle.

2️⃣ Exploratory Data Analysis (EDA)

Visualized churn vs. non-churn customer distribution.

Identified correlations between features and churn rate.

Key Insights: Higher churn in low-tenure customers & high monthly charges.

3️⃣ Data Preprocessing

Handled missing values & outliers.

Encoded categorical variables using One-Hot Encoding.

Normalized numerical features.

Split data into training (80%) & testing (20%) sets.

4️⃣ Model Building & Evaluation

Trained Logistic Regression & Random Forest models.

Evaluated models using:

Accuracy

Precision, Recall, F1-Score

ROC-AUC Curve

5️⃣ Model Interpretation

Used SHAP & LIME for explainability.

Found key churn factors:

High Monthly Charges 📉

Low Customer Tenure ⏳

Poor Customer Support ☎️

📊 Results & Insights

Random Forest outperformed Logistic Regression with higher precision & recall.

Business Impact: Insights can help reduce churn by targeting high-risk customers.

🚀 How to Run the Project?

🔹 Prerequisites:

Install Python (>=3.8)

Install dependencies:

pip install -r requirements.txt

Run the Jupyter Notebooks step by step.

🔹 Run Model Training:

python model_training.py

🤝 Contributing

Contributions are welcome! Feel free to submit a pull request.


📬 Contact

📧 Email: hamzaaslam276jb@gmail.com

💼 LinkedIn: www.linkedin.com/in/hamza-aslam-987272318

🔗 GitHub: github.com/hamzaaslam276

