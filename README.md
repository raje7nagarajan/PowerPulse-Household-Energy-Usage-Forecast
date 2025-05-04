# PowerPulse-Household-Energy-Usage-Forecast

In the modern world, energy management is a critical concern for both households and energy providers. Accurately predicting energy consumption not only empowers consumers to understand and optimize their usage but also helps utility providers manage load and resources more effectively. This project leverages machine learning to forecast household energy consumption based on historical data. The outcome is a predictive model that supports actionable insights, enhances energy efficiency, and contributes to smarter energy systems.

## Steps Followed

### 1. Data Understanding and Exploration
- Loaded and inspected the dataset.
- Performed **Exploratory Data Analysis (EDA)** to identify trends, correlations, and outliers.

### 2. Data Preprocessing
- Handled missing values and inconsistencies.
- Engineered new features such as **date-based insights, daily averages, and peak-hour indicators**.
- Normalized/scaled relevant features for optimal model performance.

### 3. Feature Engineering
- Selected relevant features for predicting **global active power consumption**, ensuring strong correlation with the target variable.

### 4. Model Development
- **Split** the dataset into **training and test sets** (80%-20% split).
- **Trained multiple models**, including:
  - Linear Regression
  - Random Forest
  - Gradient Boosting Regressor
  - Neural Networks

## Model Evaluation & Selection
- Used metrics such as **Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² Score** for comparison.
- Identified the **best-performing model** based on accuracy and generalization ability.

## Project File
- household.ipynb: Main Jupyter Notebook containing data processing, modelling, and visualization code.
- Input file is also included for reference purposes.

## How to use
- Clone this repository or download the files.
- Install required libraries:

        pip install pandas numpy matplotlib seaborn scikit-learn
- Open household.ipynb in Jupyter Notebook or any compatible IDE.
- Run the cells sequentially to reproduce the analysis and model training.
