# 📊 Loan Approval Prediction System 🎉
![churn 1.png](https://www.idfcfirstbank.com/content/dam/idfcfirstbank/images/blog/personal-loan/how-to-apply-for-firstmoney-personal-loan-a-step-by-step-guide-717X404.jpg)

Welcome to the **Loan Approval Prediction System**, an end-to-end machine learning project designed to predict the approval status of loan applications. This project showcases expertise in **data preprocessing**, **exploratory data analysis (EDA)**, **model building**, and **interactive application deployment** using **Streamlit**.

---

## 🌟 Project Highlights

### 🎯 Key Features
- 🚀 **End-to-End Machine Learning Pipeline**:
  - 📊 **EDA**: Gained insights into data distribution and identified key patterns.
  - 🛠 **Data Preprocessing**: Handled missing values, transformed features, and ensured a clean dataset.
  - 🎨 **Feature Engineering**: Engineered critical features to improve model performance.
- 🤖 **Artificial Neural Network (ANN)**: Developed a robust ANN model for binary classification of loan approval status.
- 🌐 **Interactive User Interface**:
  - 🖥 A user-friendly **Streamlit app** allowing users to input loan details and instantly predict outcomes.
  - 📈 Visualizations to explain the decision-making process.

---

## 🛠 Technologies and Tools

- 🐍 **Programming Languages**: Python
- 📚 **Libraries**: Pandas, NumPy, Scikit-learn, TensorFlow/Keras, Matplotlib, Seaborn
- 🌐 **Deployment Platform**: Streamlit
- 🧠 **Machine Learning Techniques**:
  - Neural Networks (ANN)
  - Feature Engineering and Selection
  - Hyperparameter Tuning
- 📊 **Visualization Tools**:
  - Matplotlib and Seaborn for generating insights during EDA.

---

## 📊 Data Overview

The dataset used in this project contains features related to:
- 👤 **Applicant Information**: Age, income, employment length, and credit history.
- 💰 **Loan Details**: Amount, interest rate, and intent of the loan.
- 📜 **Other Factors**: Homeownership status, loan grade, and historical default status.

### Key Data Characteristics:
- 🧮 **Shape**: Rows = 10,000; Columns = 12
- 🔑 **Notable Features**:
  - `person_income`: Applicant's income level.
  - `loan_amnt`: Requested loan amount.
  - `cb_person_cred_hist_length`: Credit history length in years.

---

## ⚙️ Project Workflow

### 1. **Exploratory Data Analysis (EDA)** 📊
- 📈 Identified key trends and patterns in the data.
- 🔍 Highlighted relationships between features such as income and loan approval.

### 2. **Data Preprocessing** 🛠
- 🧹 Handled missing and inconsistent data.
- 🔢 Encoded categorical features like `person_home_ownership` and `loan_intent`.
- 📏 Normalized numerical features for ANN compatibility.

### 3. **Model Building** 🤖
- 🧩 Designed a **3-layer Artificial Neural Network (ANN)**.
- 📉 Optimized with techniques like **dropout** and **batch normalization**.
- 📊 Metrics: Achieved high **accuracy**, **precision**, **recall**, and **F1-score**.

### 4. **Deployment** 🌐
- 🎨 Deployed the system using **Streamlit**, allowing interactive predictions.
- 📈 Visualized model performance metrics and user inputs.

---
## 🖼 App Features
- 📝 Input Form: Enter details like age, income, loan amount, and more.
- 🔮 Dynamic Predictions: Get real-time predictions for loan approval.
- 📊 Insightful Visuals: Displays feature distributions and decision influences.
---
## Key Results
### Model Performance:
- ✅ Accuracy: 94%
- 📊 F1-score: 94%
**Insights:**
- 👷 Applicants with stable employment and lower loan-to-income ratios have higher chances of approval.
- 🚩 Default history significantly affects approval likelihood.
---
## 🌟 Why This Project?
This project bridges data science and real-world applications, showcasing:

- 💡 Proficiency in end-to-end machine learning workflows.
- 🧑‍💻 The ability to deploy user-centric solutions for impactful decision-making.
---
## 📧 Contact
For queries or collaboration, reach out:

- 📛 Name: Muhammad Umer Khan
- 📧 Email: muhammadumerk546@gmail.com
- 🔗 LinkedIn: [Muhammad Umer Khan](https://linkedin.com/in/%20muhammad-umer-khan-61729b260/)

---
## 🚀 How to Run the Project

To set up this project locally:  

1. **Clone the repository**:  
   ```bash  
   git clone https://github.com/MuhammadUmerKhan/Customer-Loan-Approval-KAGGLE-COMPETITION.git

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the recommendation system:
    ```bash
    streamlit run loan_predictor.py.py


## 🛠️ Prerequisites
- Python 3.x
- Required packages are listed in requirements.txt.

## 📄 Acknowledgments
- **[Used Datasets](https://www.kaggle.com/competitions/playground-series-s4e10)**

📝 License
This project is licensed under the MIT License. See the LICENSE file for details.
