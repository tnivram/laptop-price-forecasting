# **Laptop Price Forecasting💻**

The project demonstrates skills in data processing, data visualization, and machine learning model building.

Objective: The goal of this project is to build a machine learning model to forecast the price of a laptop based on its features. 


The project is divided into four main parts:

1. **Data Preprocessing/Feature Engineering:**
   - **Handling Missing Values and Duplicates:** Filling in any null values and removing duplicate columns to clean the dataset.
   - **String Transformation:** Converting noisy string columns into formats that are easier for the model to process.

2. **Exploratory Data Analysis (EDA):**
   - **Visualizations:** Creating plots such as countplots, boxplots, and barplots to analyze data patterns and distributions.
   - **Price Transformation:** Observing that the price distribution is right-skewed, applying a natural logarithm transformation to achieve a more normal distribution, which is beneficial for the machine learning algorithm.

3. **Model Building:**
   - **Model Development:** Building and training several machine learning models namely Linear Regression, Support Vector Regression (SVR), Random Forest, and XGBoost.
   - **Model Evaluation:** Comparing the performance of these models using various evaluation metrics to determine the best-performing model.

4. **Forecasting:**
   - **User Input Interface:** Developing an input page where users can enter their laptop specifications.
   - **Price Prediction:** Using the input data to predict the laptop price based on the trained model.
