# CodeAlpha Data Science Internship

## Task 3: Car Price Prediction with Machine Learning

## Project Overview

This project was completed as part of the **CodeAlpha Data Science Internship**. The objective is to develop a machine learning model capable of predicting car prices based on various vehicle attributes such as brand, mileage, horsepower, fuel type, age, and other relevant features.

By leveraging regression techniques, the project demonstrates how machine learning can be applied to real-world pricing problems in the automotive industry.

---

## Objectives

* Analyze car-related data and identify factors affecting car prices.
* Perform data cleaning and preprocessing.
* Apply feature engineering techniques to improve model performance.
* Train a machine learning regression model to predict car prices.
* Evaluate model performance using standard regression metrics.
* Visualize feature importance and prediction results.

---

## Dataset Description

The dataset contains information about cars and their corresponding prices.

### Example Features

* Car Name / Brand
* Year
* Selling Price
* Present Price
* Kilometers Driven
* Fuel Type
* Seller Type
* Transmission
* Ownership
* Mileage
* Horsepower

### Target Variable

* Car Price / Selling Price

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab / Jupyter Notebook

---

## Project Workflow

### 1. Data Collection

* Loaded the car dataset.
* Explored the dataset structure and features.

### 2. Data Preprocessing

* Handled missing values.
* Removed unnecessary columns.
* Encoded categorical variables.
* Prepared data for model training.

### 3. Exploratory Data Analysis (EDA)

* Analyzed relationships between features and car prices.
* Identified key factors affecting vehicle value.

### 4. Model Building

* Split the dataset into training and testing sets.
* Trained a Random Forest Regression model.

### 5. Model Evaluation

Evaluated the model using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

### 6. Visualization

Generated visualizations including:

* Feature Importance Chart
* Actual vs Predicted Prices Plot

---

## Results

The machine learning model successfully predicted car prices with strong accuracy.

### Evaluation Metrics

* MAE (Mean Absolute Error)
* RMSE (Root Mean Squared Error)
* R² Score

A higher R² score indicates better prediction performance.

---

## Key Insights

* Vehicle age significantly impacts resale value.
* Present market price strongly influences selling price.
* Mileage and fuel type contribute to pricing variations.
* Brand reputation affects overall car valuation.
* Machine learning can effectively estimate car prices using historical data.

---

## How to Run the Project

### Install Required Libraries

```bash
pip install pandas numpy matplotlib scikit-learn
```

### Run the Notebook

1. Open Google Colab or Jupyter Notebook.
2. Upload the dataset.
3. Execute all cells sequentially.
4. Review the evaluation metrics and visualizations.

```
## Future Improvements

* Experiment with XGBoost and Gradient Boosting models.
* Perform hyperparameter tuning.
* Deploy the model as a web application.
* Build an interactive dashboard for price prediction.

---

## Conclusion

This project demonstrates the practical application of machine learning in predicting car prices. By utilizing regression techniques and data preprocessing methods, the model can estimate vehicle prices with high accuracy, providing valuable insights for buyers, sellers, and automotive businesses.

---

**Internship:** CodeAlpha Data Science Internship

**Task:** Task 3 – Car Price Prediction with Machine Learning

**Tools Used:** Python, Pandas, NumPy, Matplotlib, Scikit-learn

**Author:** Srinivas Konakalla
