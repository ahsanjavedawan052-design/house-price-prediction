# house-price-prediction
# California House Price Prediction 🏠

This project implements a complete Machine Learning pipeline to predict median house values in California. It compares **Linear Regression** and **Random Forest Regressor** models, utilizing hyperparameter tuning for optimization.

## 🚀 Features
* **Data EDA:** Visualizing correlations and distributions using Seaborn.
* **Feature Engineering:** Log transformations and creating ratios (e.g., bedrooms per room).
* **Model Tuning:** Grid Search CV to find optimal Random Forest parameters.
* **Evaluation:** Metrics include $R^2$, MAE, and RMSE.

## 📊 Dataset
The [California Housing Dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html) contains 20,640 samples with 8 features including:
* Median Income
* House Age
* Average Rooms/Bedrooms
* Population & Location (Lat/Long)

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* **Environment:** Google Colab / Jupyter Notebook

## 📈 Results
The **Random Forest Regressor** outperformed the baseline Linear Regression model.
* **Best R^2 Score:** [Insert your score here, e.g., 0.81]
* **Top Predictor:** Median Income (MedInc)

## 📂 Project Structure
* `House_Price_Prediction.ipynb`: The main Colab notebook.
* `california_housing_model.pkl`: The trained model file.
* `requirements.txt`: List of dependencies.
