# Titanic - Machine Learning from Disaster

## Project Description
This project addresses the classic Titanic dataset challenge, aiming to predict passenger survival using a variety of machine learning techniques. The workflow covers the entire data science pipeline: from data acquisition and exploratory data analysis (EDA), through data cleaning and feature engineering, to model selection, training, evaluation, and interpretation. The project is inspired by the Kaggle competition "Titanic: Machine Learning from Disaster" and is designed as a comprehensive, educational example for beginners and intermediate data scientists.

---

## Problem Statement
The sinking of the RMS Titanic in 1912 is one of the most infamous shipwrecks in history. The goal of this project is to build a predictive model that determines whether a passenger survived the disaster, based on features such as age, sex, ticket class, and more. This problem is a binary classification task and serves as a popular introduction to machine learning and data science.

---

## Features
- **End-to-End Data Science Workflow:** Includes all steps from raw data to final predictions.
- **Comprehensive EDA:** Visual and statistical exploration of the dataset to uncover patterns and relationships.
- **Data Cleaning:** Handling missing values, removing irrelevant features, and preparing data for modeling.
- **Feature Engineering:** Creating new features and encoding categorical variables to improve model performance.
- **Multiple Model Training:** Implementation and comparison of Linear Regression, Logistic Regression, and Random Forest Classifier.
- **Model Evaluation:** Assessment using accuracy, precision, recall, F1-score, and confusion matrix.
- **Visualization:** Clear plots and charts to illustrate key findings and model results.
- **Reproducible Notebook:** All code and analysis are contained in a single, well-documented Jupyter Notebook.

---

## Tech Stack
- **Programming Language:** Python 3.x
- **Data Analysis:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Environment:** Jupyter Notebook

---

## Getting Started

### Prerequisites
- Python 3.x installed on your system
- Jupyter Notebook (install via Anaconda or pip)

### 1. Clone the Repository
```bash
git clone https://github.com/TensoRag/Titanic.git
cd Titanic
```

### 2. Install Dependencies
Install the required Python packages using pip:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 3. Launch the Notebook
Start Jupyter Notebook in your browser:
```bash
jupyter notebook Titanic.ipynb
```

---

## Usage
1. **Open `Titanic.ipynb` in Jupyter Notebook.**
2. **Run the cells sequentially:**
   - **Data Loading:** Loads the Titanic dataset (`Titanic-Dataset.csv`).
   - **Exploratory Data Analysis:** Visualizes distributions, relationships, and missing values.
   - **Data Cleaning:** Handles missing data, drops irrelevant columns, and encodes categorical variables.
   - **Feature Engineering:** Creates new features or transforms existing ones for better model performance.
   - **Model Training:** Trains Linear Regression, Logistic Regression, and Random Forest models.
   - **Model Evaluation:** Compares models using various metrics and visualizations.
   - **Prediction:** Outputs survival predictions and interprets results.
3. **Modify or extend the notebook** to experiment with new features, models, or visualizations.

---

## Project Structure
```
Titanic/
├── Titanic.ipynb           # Main Jupyter Notebook with full workflow, code, and analysis
├── Titanic-Dataset.csv     # Titanic dataset (combined train/test)
├── README.md               # Project documentation (this file)
```
- **Titanic.ipynb:** Contains all code, visualizations, and explanations. Well-commented for learning and reproducibility.
- **Titanic-Dataset.csv:** The dataset used for analysis and modeling. Contains passenger information, survival status, and relevant features.
- **README.md:** Detailed project documentation, setup instructions, and guidelines.

---

## Results
- **Best Model:** The Random Forest Classifier achieved the highest accuracy among the tested models.
- **Key Insights:**
  - Female passengers had a much higher survival rate than males.
  - Passengers in higher classes (1st class) were more likely to survive.
  - Younger passengers and children had a higher chance of survival.
- **Model Metrics:**
  - Accuracy, precision, recall, and F1-score are reported for each model in the notebook.
  - Confusion matrices and classification reports are provided for detailed evaluation.

---

## Contributing
We welcome contributions from the community! To contribute:
1. **Fork the repository** on GitHub.
2. **Create a new branch** for your feature or bugfix.
3. **Commit your changes** with clear messages.
4. **Push to your fork** and submit a pull request.
5. **Describe your changes** in detail in the pull request.

If you have suggestions for improvements, new features, or find any bugs, please open an issue or submit a pull request.

---

## Contact
- **GitHub Profile:** [TensoRag](https://github.com/TensoRag)
- **Email:** denistanb05@gmail.com

