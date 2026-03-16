# Employee Salary Prediction (AI & Machine Learning Project)

## 📌 Project Overview
Employee Salary Prediction is an Artificial Intelligence and Machine Learning project developed using Python. The goal of this project is to predict whether an employee earns more than or less than 50K per year based on various demographic and work-related attributes.

This project demonstrates how machine learning algorithms can be used to analyze employee data and build predictive models for salary classification.

---

## 🎯 Objective
The objective of this project is to build and evaluate multiple machine learning models to predict employee salary categories using historical employee data.

---

## 🤖 Machine Learning Algorithms Used
The following machine learning algorithms were implemented and compared:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Random Forest
- Gradient Boosting

---

## 🛠 Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📁 Dataset
The dataset contains employee-related information used to train the machine learning models. Key features include:

- Age
- Workclass
- Education
- Occupation
- Hours per week
- Capital gain
- Capital loss
- Marital status
- Native country

The target variable predicts whether an employee earns **>50K or ≤50K salary**.

---

## 📊 Model Performance

Multiple machine learning models were trained and evaluated.

| Model | Accuracy |
|------|---------|
| Logistic Regression | 77.77% |
| K-Nearest Neighbors | 77.04% |
| Naive Bayes | 78.71% |
| Random Forest | 85.04% |
| Gradient Boosting | **85.71% (Best Model)** |

### Best Model: Gradient Boosting

Evaluation Metrics:

- Accuracy: **85.71%**
- Precision (>50K): **0.78**
- Recall (>50K): **0.60**
- F1 Score (>50K): **0.68**

Gradient Boosting achieved the best performance and was selected as the final model.

---

## 📊 Project Workflow

1. Data Collection  
2. Data Cleaning & Preprocessing  
3. Exploratory Data Analysis (EDA)  
4. Feature Encoding & Selection  
5. Model Training  
6. Model Evaluation  
7. Salary Prediction

---

## 📂 Project Structure

Employee-Salary-Prediction

│  
├── Employee Salary Prediction.ipynb  
├── dataset.csv  
└── README.md  

---

## ▶️ How to Run the Project

### 1. Clone the repository

git clone https://github.com/SohamRajwani/Employee-Salary-Prediction--Soham.git

### 2. Install required libraries

pip install pandas numpy scikit-learn matplotlib seaborn

### 3. Run the notebook

jupyter notebook

---

## 📈 Future Improvements

- Improve model accuracy using advanced techniques
- Perform hyperparameter tuning
- Deploy the model as a web application
- Build an interactive dashboard

---

## 👨‍💻 Author

Soham Rajwani

---

⭐ If you found this project useful, please give it a star on GitHub!
