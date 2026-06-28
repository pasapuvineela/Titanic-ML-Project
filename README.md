# Titanic-ML-Project
# 🚢 Titanic Survival Prediction using Machine Learning

## 📌 Project Overview

This project was developed as part of the **Pluto Academy AI & ML Internship – Project 02**.

The objective is to build, train, evaluate, and compare multiple Machine Learning models to predict whether a passenger survived the Titanic disaster based on passenger information.

## 🎯 Objective

- Load and preprocess the Titanic dataset.
- Perform Exploratory Data Analysis (EDA).
- Engineer relevant features.
- Train multiple Machine Learning models.
- Compare model performance using evaluation metrics.
- Select the best-performing model.
- Visualize the model performance using a Confusion Matrix and Feature Importance

## 📂 Dataset

**Dataset:** Titanic - Machine Learning from Disaster

Source:
https://www.kaggle.com/c/titanic

Dataset File Used:

- train.csv

## 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 📚 Machine Learning Algorithms

The following models were trained and evaluated:

1. Logistic Regression
2. Random Forest Classifier
3. K-Nearest Neighbors (KNN)

## ⚙ Data Preprocessing

The following preprocessing steps were performed:

- Loaded the dataset
- Checked missing values
- Filled missing values in Age using Median
- Filled missing values in Embarked using Mode
- Removed Cabin column due to excessive missing values
- Removed PassengerId, Name, and Ticket columns
- Encoded categorical variables using LabelEncoder
- Split dataset into 80% Training and 20% Testing

## 🔍 Feature Engineering

Feature importance and correlation analysis were performed to identify the most influential features.

Important features included:

- Sex
- Pclass
- Fare
- Age

## 📊 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score

A comparison table was created to compare the performance of all three models.

## 🏆 Best Model

Random Forest Classifier achieved the highest overall performance.

Reasons:

- Higher Accuracy
- Better F1-Score
- Handles nonlinear relationships effectively
- Captures feature interactions better than Logistic Regression and KNN

## 📈 Visualizations

The project includes:

- Correlation Heatmap
- Feature Importance Plot
- Confusion Matrix
- Model Comparison Table

## 📁 Project Structure
Titanic-ML-Project/
│
├── train.csv
├── Titanic_Survival_Prediction.ipynb
├── README.md
├── requirements.txt
├── confusion_matrix.png
├── feature_importance.png
└── comparison_table.png

## 🚀 How to Run

1. Clone the repository
git clone https://github.com/yourusername/Titanic-ML-Project.git
2. Open the project in Google Colab or Jupyter Notebook.
3. Install dependencies.
pip install -r requirements.txt
4. Run all notebook cells sequentially.



## ✅ Conclusion
- Successfully cleaned and preprocessed the Titanic dataset.
- Trained three Machine Learning models for survival prediction.
- Compared the models using standard evaluation metrics.
- Random Forest Classifier performed the best among all models.
- This project demonstrates a complete end-to-end Machine Learning workflow from data preprocessing to model evaluation.

## 👩‍💻 Author
**Name:** Vineela Pasapu
**AI & ML Internship Project**
**Pluto Academy**
