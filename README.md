# 🚢 Titanic - Machine Learning from Disaster

[🔗 GitHub Repository](https://github.com/Denistanb/Titanic)

This project is based on the famous **Titanic: Machine Learning from Disaster** Kaggle competition.  
It covers the full pipeline from **EDA**, **data cleaning**, and **visualizations** to **model training and prediction** using various ML algorithms.

---

## 📘 Problem Statement

The sinking of the Titanic is one of the most infamous shipwrecks in history.  
The goal is to build a **machine learning model** that predicts which passengers survived the tragedy based on features like age, sex, class, etc.

---

## 📂 Project Structure

- `train.csv`: Training dataset containing passenger details and survival status
- `test.csv`: Testing dataset without survival status
- `Titanic_EDA_Model.ipynb`: Jupyter Notebook containing the entire workflow

---

## 📊 Exploratory Data Analysis (EDA)

Performed detailed EDA to understand:
- Null values and data quality
- Impact of features like **Age**, **Sex**, **Embarked** on survival
- Distribution of categorical and numerical variables

### 📈 Key Visualizations

- **Age vs Survival** (Countplot)
- **Sex vs Survival** (Bar Chart)
- **Embarked vs Survival** (Bar Chart)

---

## 🧹 Data Cleaning

- Dropped irrelevant columns like `Cabin`, `Name`, and `Ticket`
- Filled missing values:
  - Numerical columns with **median**
  - Categorical columns with **most frequent**
- Encoded categorical columns to numeric using label encoding logic

---

## 🤖 Model Training

Trained three models using the cleaned dataset:

1. **Linear Regression**
2. **Logistic Regression**
3. **Random Forest Classifier**

### 🎯 Prediction Output

Converted prediction probabilities to binary (`0` or `1`) for survival:
- `Survived = 1` → Passenger survived
- `Survived = 0` → Passenger did not survive

Saved predictions into three separate DataFrames:
- `Linpre`
- `Logpre`
- `Ranpre`

---

## 🧰 Technologies Used

- Python 🐍
- Pandas & NumPy 🔢
- Seaborn & Matplotlib 📊
- Scikit-learn 🤖
- Jupyter Notebook 📓

---

## ▶️ How to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Denistanb/Titanic.git
   cd Titanic
2. **Install Required Packages**:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
3. **Run the Jupyter Notebook**:
   ```bash
   jupyter notebook Titanic.ipynb
