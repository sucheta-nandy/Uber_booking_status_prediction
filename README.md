# Uber Booking Status Prediction

## Project Overview

This project involves building an end-to-end supervised classification pipeline in Python to predict the outcome of Uber ride bookings (e.g., Completed, Cancelled, or No Cars Available). By analyzing a dataset of over **150,000 ride bookings**, the project demonstrates the application of feature engineering, class imbalance handling, and advanced machine learning algorithms to solve a high-volume logistics prediction problem.

## Key Features

* **Comprehensive Data Analysis:** Exploratory Data Analysis (EDA) of 150,000+ ride records to identify key drivers of booking cancellations and availability gaps.
* **Predictive Modeling:** Comparison of multiple classification architectures, including **Logistic Regression**, **Random Forest**, and **XGBoost**.
* **Advanced Preprocessing:**
* **Feature Engineering:** Deriving temporal and spatial features to improve model signal.
* **Class Imbalance Handling:** Implementing **SMOTE** (Synthetic Minority Over-sampling Technique) to address skewed booking outcomes.
* **Hyperparameter Tuning:** Systematic optimization of model parameters to maximize predictive power.



## Results

* **Performance Gain:** Achieved a **22% improvement** over the baseline model performance.
* **High Precision:** The optimized XGBoost model achieved **99.7% test accuracy**, demonstrating robust generalization to unseen data.

## Technologies Used

* **Language:** Python
* **Data Libraries:** Pandas, NumPy
* **Machine Learning:** Scikit-learn, XGBoost, Imbalanced-learn (SMOTE)
* **Visualization:** Matplotlib, Plotly, Seaborn
