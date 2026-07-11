# Employee Salary Prediction Using Machine Learning

## Project Overview

This project focuses on building a Machine Learning model to predict employee income based on different employee attributes.

The main goal of this project is to understand how factors like **age** and **years of experience** affect employee salary and use supervised learning algorithms to make accurate salary predictions.

This project demonstrates the complete Machine Learning workflow:
- Data loading
- Data exploration and visualization
- Data analysis
- Model training
- Model evaluation
- Drawing insights from patterns in data

---

## Dataset Description

The dataset contains employee information with the following features:

| Feature | Description |
|---|---|
| Age | Age of the employee |
| Experience | Number of years of professional experience |
| Income | Employee salary/income (Target Variable) |

The target variable for prediction is **Income**.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Machine Learning Algorithms Used

### 1. Linear Regression

Linear Regression is used to identify the relationship between employee attributes and income. It predicts salary based on the linear relationship between input features and output.

### 2. Random Forest Regression

Random Forest Regression uses multiple decision trees to improve prediction accuracy and capture complex patterns in the dataset.

---

## Exploratory Data Analysis

The project includes:

### Income Distribution Analysis
Analyzes the overall salary distribution and identifies common income ranges.

### Experience vs Income Analysis
Shows the relationship between years of experience and employee income.

### Correlation Analysis
Helps understand the relationship between numerical features and determines how strongly they affect income.

---

## Model Evaluation

The models are evaluated using:

### Mean Absolute Error (MAE)
Measures the average difference between actual and predicted values.

### Mean Squared Error (MSE)
Measures the average squared difference between actual and predicted values.

### R² Score
Shows how well the model explains the variation in employee income.

---

## Project Structure

```
Employee-Salary-Prediction/
│
├── Employee_Salary_Prediction.ipynb
├── employee_income.csv
└── README.md
```

---

## Key Insights

- Employee experience has a strong relationship with income.
- Salary generally increases as professional experience increases.
- Data visualization helps identify important patterns before model training.
- Regression algorithms can effectively predict continuous salary values.
- Machine learning can support salary estimation and business decision-making.

---

## Future Improvements

- Add more features like education, job role, location, and skills.
- Apply advanced regression algorithms.
- Create a web application for real-time salary prediction.
- Deploy the trained model using Flask or Streamlit.

---

## Author

Dhruv Khandelwal
