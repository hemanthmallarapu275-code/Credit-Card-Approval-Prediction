# 💳 Credit Card Approval Prediction

A Machine Learning and Flask-based web application that predicts whether a credit card application is likely to be **Approved** or **Rejected** based on an applicant's financial and personal details. The application helps automate the credit card approval process by providing fast, accurate, and data-driven predictions using Machine Learning models.

---

# 📖 Project Overview

Credit card approval is one of the most important processes in the banking and financial sector. Traditional manual evaluation of applications can be time-consuming and prone to human error. This project uses Machine Learning techniques to predict whether a credit card application will be approved based on applicant information.

The system performs data preprocessing, feature engineering, exploratory data analysis (EDA), and model training using multiple classification algorithms. The best-performing model is integrated into a Flask web application and deployed on **Render**, enabling users to obtain real-time credit card approval predictions through an intuitive web interface.

---

# 🎯 Objectives

- Predict credit card approval using Machine Learning.
- Reduce manual verification efforts.
- Improve the accuracy of approval decisions.
- Assist financial institutions with faster decision-making.
- Provide an easy-to-use web application for prediction.
- Deploy the application for online access using Render.

---

# ✨ Features

- 💳 Credit Card Approval Prediction
- 🤖 Machine Learning-Based Decision Making
- 📊 Exploratory Data Analysis (EDA)
- 🧹 Data Preprocessing & Feature Engineering
- 💻 User-Friendly Flask Web Application
- ⚡ Real-Time Prediction Results
- 📈 Multiple Machine Learning Models
- ☁️ Cloud Deployment using Render

---

# 🛠️ Technologies Used

## Programming Language
- Python 3.x

## Machine Learning
- Scikit-learn
- XGBoost

## Data Processing
- Pandas
- NumPy

## Data Visualization
- Matplotlib
- Seaborn

## Web Framework
- Flask

## Frontend
- HTML5
- CSS3

## Development Tools
- Google Colab
- Visual Studio Code (VS Code)

## Version Control
- Git
- GitHub

## Cloud Deployment
- Render

---

# 📂 Project Structure

```
Credit-Card-Approval-Prediction/
│
├── screenshots/
│   ├── home_page.png
│   ├── applicant_details_form.png
│   ├── running_locally_vscode.png
│   └── rejected_prediction.png
│
├── static/
│   └── style.css
│
├── templates/
│   └── index.html
│
├── app.py
├── best_model.pkl
├── scaler.pkl
├── encoders.pkl
├── requirements.txt
├── application_record.csv
├── Credit_Card_Approval_Prediction.ipynb
├── README.md
└── .gitignore
```

---

# 📊 Input Parameters

The application accepts applicant information such as:

| Parameter | Description |
|-----------|-------------|
| Gender | Applicant Gender |
| Income Type | Source of Income |
| Annual Income | Applicant Annual Income |
| Employment Duration | Years of Employment |
| Education Level | Applicant Education |
| Marital Status | Applicant Marital Status |
| Housing Type | Type of Housing |
| Family Members | Number of Family Members |
| Occupation | Applicant Occupation |
| Other Financial Details | Additional Applicant Information |

---

# 💳 Output

The application predicts whether the credit card application will be:

- ✅ Credit Card Approved

or

- ❌ Credit Card Rejected

---

# ⚙️ Installation

## 1. Clone the Repository

```bash
git clone https://github.com/hemanthmallarapu275-code/Credit-Card-Approval-Prediction
```

## 2. Navigate to the Project Folder

```bash
cd Credit-Card-Approval-Prediction
```

## 3. Install Required Packages

```bash
pip install -r requirements.txt
```

## 4. Run the Application

```bash
python app.py
```

## 5. Open in Browser

```
http://127.0.0.1:5000
```
---

# 🚀 Live Demo

The application has been deployed on **Render**.

**Deployment Platform:** Render Cloud

**Live Application:** https://credit-card-approval-prediction-4-hk05.onrender.com

**Demo Video:** https://drive.google.com/file/d/1nyYJeGXYrsCjHB1mCV42r1z3ZlsVV6Uo/view?usp=drivesdk

---

# 🔄 Machine Learning Workflow

- Dataset Collection
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Training
- Model Evaluation
- Best Model Selection
- Save Trained Model (.pkl)
- Flask Integration
- Real-Time Credit Card Approval Prediction

---

# 🤖 Machine Learning Algorithms

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier

The best-performing model is selected based on evaluation metrics and saved as a Pickle (.pkl) file for deployment.

---

# 📈 Future Enhancements

- Improve model accuracy using larger datasets.
- Integrate real-world banking datasets.
- Develop a mobile-friendly interface.
- Add Explainable AI (XAI) for prediction interpretation.
- Enhance scalability and performance.
- Add user authentication and authorization.

---

# 👨‍💻 Team Members

| Name | Role |
|------|------|
| M Hemanth | Team Lead |
| M K Tharun Sai | Team Member |
| K Rajesh | Team Member |
| Kanike Siddhartha | Team Member |

---

# 📜 License

This project was developed for academic and educational purposes as part of the **APSCHE Skill Wallet Internship Program**.

---

# 🤝 Contributing

Contributions, suggestions, and improvements are welcome. Feel free to fork the repository and submit a pull request.

---

# 📧 Contact

**M Hemanth**

**GitHub:** https://github.com/hemanthmallarapu275-code

**Repository:** https://github.com/hemanthmallarapu275-code/Credit-Card-Approval-Prediction
