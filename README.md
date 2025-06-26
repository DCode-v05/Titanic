# Titanic - Machine Learning from Disaster

## Project Description
This project addresses the classic Titanic dataset challenge, aiming to predict passenger survival using a variety of machine learning techniques. The workflow covers the entire data science pipeline: from data acquisition and exploratory data analysis (EDA), through data cleaning and feature engineering, to model selection, training, evaluation, and interpretation. The project is inspired by the Kaggle competition "Titanic: Machine Learning from Disaster" and is designed as a comprehensive, educational example for beginners and intermediate data scientists.

---

## Project Details
### Problem Statement
The objective is to build a machine learning model that predicts which passengers survived the Titanic tragedy based on features such as age, sex, and class.

### Data Exploration
- Assessed data quality and missing values
- Explored the impact of features like Age, Sex, and Embarked on survival
- Visualized distributions of categorical and numerical variables

### Data Cleaning
- Removed irrelevant columns (Cabin, Name, Ticket)
- Filled missing values (numerical: median, categorical: most frequent)
- Encoded categorical variables numerically

### Model Training
- Trained and evaluated three models:
  1. Linear Regression
  2. Logistic Regression
  3. Random Forest Classifier
- Converted prediction probabilities to binary survival outcomes
- Saved predictions for each model

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

Contributions are welcome! To contribute:
1. Fork the repository
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your feature"
   ```
4. Push to your branch:
   ```bash
   git push origin feature/your-feature
   ```
5. Open a pull request describing your changes.

---

## Contact
- **GitHub:** [TensoRag](https://github.com/TensoRag)
- **Email :** denistanb05@gmail.com

