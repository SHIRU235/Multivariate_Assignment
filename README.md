# Multivariate_Assignment
# Diabetes Progression Prediction using Machine Learning

This project builds and compares multiple machine learning models to predict the **disease progression** in diabetic patients **one year after baseline**. The goal is to develop a model that can assist physicians in identifying patients at high risk of diabetes progression.

---

## Dataset

We use the **Diabetes Dataset** from Scikit-Learn's toy datasets, which contains 442 samples with 10 features, including:
- Age
- BMI
- Blood pressure
- Serum measurements, etc.

Target variable: **Disease progression one year after baseline** (a continuous value).

---

##  Project Structure

- `diabetes.ipynb`: Main Jupyter notebook with code, visualizations, and model training
- `requirements.txt`: List of Python dependencies
- `README.md`: Project overview and usage instructions

---

## Installation

1. Clone this repository:
   
   git clone https://github.com/SHIRU235/Multivariate_Assignment.git .

2. Create & Activate Virtual Environment
    python -m venv venv
    
    ./venv/scripts/activate

3. pip install -r requirements.txt

#### Models Used ###:
The notebook explores the following regression models:

Part A: Simple Linear Regression
Univariate regression using BMI as a single feature.

Part B: Evaluation on Validation and Test Sets
Comparison of model performance using R², MAE, and MAPE.

Part C: Multivariate Regression Models
Polynomial Regression (Degree 1 and 2)

Decision Tree Regression (Max depth 3 and 5)

k-Nearest Neighbors Regression (k = 3 and 5)

### Evaluation Metrics ###:
Each model is evaluated using:

R² Score: Measures goodness of fit.

MAE (Mean Absolute Error): Measures average magnitude of error.

MAPE (Mean Absolute Percentage Error): Measures error in percentage.

### Final Outcome ###:
The best performing model was Polynomial Regression (Degree 1) using four features (bmi, bp, s1, s5), achieving the highest R² score on validation and test data.

HTML PAGES : https://shiru235.github.io/Multivariate_Assignment/diabetes.html
