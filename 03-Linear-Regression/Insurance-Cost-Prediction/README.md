
# Insurance Cost Prediction Using Linear Regression

## Project Overview

This project uses Machine Learning to predict medical insurance costs based on personal information such as age, BMI, number of children, smoking habits, gender, and region.

The main objective is to understand and implement **Linear Regression**, a supervised machine learning algorithm, to predict continuous numerical values.

## Objectives

- Understand the concept of Linear Regression.
- Perform data loading and exploratory data analysis (EDA).
- Clean and preprocess the dataset.
- Convert categorical variables into numerical values.
- Train a Linear Regression model.
- Evaluate model performance using regression metrics.
- Predict insurance charges for new data.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## Dataset

The project uses a medical insurance dataset containing information about individuals and their insurance charges.

Common features include:

| Feature | Description |
|---|---|
| age | Age of the individual |
| sex | Gender of the individual |
| bmi | Body Mass Index |
| children | Number of children |
| smoker | Smoking status |
| region | Residential region |
| charges | Medical insurance cost (target variable) |

*Note: The exact columns depend on the dataset used in this project.*

## Machine Learning Algorithm

### Linear Regression

Linear Regression is a supervised learning algorithm used to predict continuous numerical values by learning the relationship between input features and a target variable.

In this project:

- **Input features:** Age, BMI, children, smoking status, gender, and region.
- **Target variable:** Insurance charges.

The model learns patterns from the training data and uses them to predict insurance costs for unseen data.

## Project Workflow

1. Import the required libraries.
2. Load the insurance dataset.
3. Explore the dataset using Pandas.
4. Check for missing values and duplicate records.
5. Perform exploratory data analysis using visualizations.
6. Encode categorical features.
7. Separate features and target variable.
8. Split the data into training and testing sets.
9. Train the Linear Regression model.
10. Generate predictions on the test data.
11. Evaluate the model using MAE, MSE, RMSE, and R² score.
12. Analyze the results.

## Model Evaluation

The following metrics can be used to evaluate the model:

- **MAE (Mean Absolute Error):** Measures the average absolute difference between actual and predicted charges.
- **MSE (Mean Squared Error):** Measures the average squared prediction error.
- **RMSE (Root Mean Squared Error):** Represents prediction error in the target variable's units.
- **R² Score:** Measures how much of the variation in the target variable is explained by the model.

Actual evaluation results should be added after training the model.

## Project Structure

```text
03-Linear-Regression/
└── Insurance-Cost-Prediction/
    ├── README.md
    ├── insurance.csv
    └── insurance_cost_prediction.ipynb
```

*Your actual folder and file names may differ.*

## Key Learnings

- Fundamentals of supervised machine learning.
- Data preprocessing and feature encoding.
- Exploratory data analysis and visualization.
- Training and testing a regression model.
- Understanding regression evaluation metrics.
- Making predictions using Scikit-learn.

## Future Improvements

- Compare Linear Regression with other regression algorithms.
- Perform feature engineering.
- Apply cross-validation and hyperparameter tuning where appropriate.
- Build a simple web application for insurance cost prediction.
- Deploy the trained model.

## Conclusion

This project demonstrates how Linear Regression can be applied to a real-world regression problem. It provides practical experience with data preprocessing, model training, prediction, and evaluation using Python's machine learning libraries.

---

**Author:** Ayush Jugseniye

**Repository:** ML-Journey

**Topic:** Machine Learning — Linear Regression
