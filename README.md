# Insurance Cost Prediction using Machine Learning

## Project Overview

This project focuses on predicting medical insurance charges using machine learning regression techniques. The objective is to analyze how factors such as age, BMI, smoking status, gender, number of children, and region influence insurance costs and to build a model capable of accurately estimating future charges.

The project follows a complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and model evaluation.

---

## Dataset

The dataset contains information about individuals and their corresponding medical insurance charges.

### Features

* **Age** – Age of the individual
* **Sex** – Gender of the individual
* **BMI** – Body Mass Index
* **Children** – Number of dependents covered by insurance
* **Smoker** – Smoking status
* **Region** – Residential region
* **Charges** – Medical insurance cost (Target Variable)

---

## Project Workflow

### 1. Data Exploration

* Dataset inspection
* Missing value analysis
* Statistical summary
* Feature distribution analysis

### 2. Exploratory Data Analysis (EDA)

* Charges by gender
* Charges by smoking status
* Charges by region
* Charges by age groups
* Correlation analysis

### 3. Feature Engineering

* Created Age Group categories
* Converted categorical variables into numerical format

### 4. Model Training

The following regression models were trained and evaluated:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Gradient Boosting Regressor
* XGBoost Regressor

### 5. Model Evaluation

Models were compared using:

* MAE (Mean Absolute Error)
* RMSE (Root Mean Squared Error)
* R² Score

---

## Results

The trained models were compared based on their predictive performance.

| Model                       |     MAE    |    RMSE   | R² Score|
| --------------------------- | ---        | ----      | --------|
| Linear Regression           |  4186.08   |  5787.83  |  0.784  |
| Decision Tree Regressor     |  2996.56	 |  6509.30  |	0.727  | 
| Random Forest Regressor     |  2543.57   |	4616.81  |	0.862  |
| Gradient Boosting Regressor |  2447.18   |	4352.17  |	0.861  |
| XGBoost Regressor           |  2791.83   |	4822.99  |	0.844  | 


---

## Key Findings

* Smoking status has a significant impact on insurance charges.
* Higher BMI is generally associated with increased medical costs.
* Age plays an important role in determining insurance expenses.
* Ensemble models outperform basic linear models on this dataset.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost
* Jupyter Notebook

---

## Repository Structure

```text
Insurance-Cost-Prediction/
│
├── Insurance-price-prediction.ipynb
├── insurance.csv
├── README.md
```

---

## Future Improvements

* Hyperparameter tuning using GridSearchCV
* Cross-validation for robust evaluation
* Additional feature engineering
* Model deployment using Flask or FastAPI
* Experimenting with LightGBM and CatBoost

---

## Author

Shivani Lokinindi

Aspiring AI/ML Engineer passionate about machine learning, data science, and building real-world predictive models.
