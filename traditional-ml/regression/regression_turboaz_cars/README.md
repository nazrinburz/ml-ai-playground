# Car Price Prediction Project

This project explores the task of predicting car prices using a dataset from Kaggle. Completed in 2024, this was one of the first opportunities which gave me a chance to apply and refine a full machine learning workflow from data ingestion to model evaluation.

## Dataset

The dataset used in this project is available on Kaggle: [turboaz-cars-project](https://www.kaggle.com/datasets/sehriyarmemmedli/turboaz-cars-project)

---

## Notebook Contents

The accompanying Colab notebook (`regression_turboaz_2024.ipynb`) provides a comprehensive walkthrough of the project, including the following key stages:

- **Data Loading and Cleaning**: Initial steps to handle raw data, including managing missing values and duplicates.
- **Feature Engineering**: Creating new, more informative features from the raw data to improve model performance.
- **Data Preprocessing and Pipelines**: Building robust, reproducible pipelines for data transformation.
- **Model Training and Evaluation**: Training and comparing various regression models, including **Linear Regression**, **XGBoost**, and **Ridge Regression**.
- **Cross-Validation**: Implementing cross-validation to obtain a more reliable estimate of model performance and ensure stability.
- **Feature Importance Analysis**: Analyzing the trained models to understand which features were most influential in the predictions.

---

## How to Run the Notebook

1. Clone this repository to your local machine.
2. Open the `car_price_prediction.ipynb` file in a Jupyter-compatible environment like Google Colab, JupyterLab, or VS Code.
3. If you're using Google Colab, you'll need to set up your Kaggle API credentials in the Colab Secrets to download the dataset directly. Instructions are provided within the notebook.
4. Execute the code cells sequentially.

---

## Libraries Used

This project utilizes several key Python libraries for data science and machine learning, including:

- pandas
- numpy
- scikit-learn
- xgboost
- matplotlib
- seaborn