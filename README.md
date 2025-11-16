🌦️ Weather Data Analysis using Python & Machine Learning

This project analyzes a real-world weather dataset and builds a simple regression model to predict temperature patterns.
It includes exploratory data analysis (EDA), data visualization, and a Linear Regression model.

📁 Project Structure
basic/
│── weather_data_analysis.ipynb      # Jupyter Notebook (main analysis)
│── weather_data_analysis.py         # Python script version
│── weather.csv                      # Weather dataset
│── requirements.txt                 # Required Python libraries
│── instructions.txt                 # Notes & task description
│── README.md                        # Project documentation
│── .venv/                           # Virtual environment (ignored)

🎯 Objectives

Load and analyze the weather dataset

Perform exploratory data analysis (EDA)

Visualize trends in temperature, rainfall, sunshine, evaporation, and more

Build a Linear Regression model

Evaluate model accuracy using MSE

Provide a clean, reproducible workflow

🧪 Exploratory Data Analysis

The project performs:

Head, info(), describe()

Missing value inspection

Distribution plots

Correlation heatmap

Temperature trend visualization

Scatterplots for Weather ↔ Temperature relationships

📊 Visualizations Included

Temperature distributions

Rainfall vs Evaporation patterns

Sunshine effect on MaxTemp

Correlation matrix (Seaborn heatmap)

Residuals distribution

Model regression line

🤖 Machine Learning Model

Algorithm Used: Linear Regression
From sklearn.linear_model

Steps

Train-Test Split

Fit the regression model

Predict temperature

Calculate model performance using:

Mean Squared Error (MSE)

Residual Analysis

📦 Installation & Requirements
Create Virtual Environment
python3 -m venv .venv
source .venv/bin/activate     # macOS

Install Requirements
pip install -r requirements.txt

▶️ How to Run
Run the Notebook:
jupyter notebook weather_data_analysis.ipynb

Or run the Python script:
python weather_data_analysis.py

📝 Dataset Description

The dataset (weather.csv) contains daily weather observations, typically including:

MinTemp

MaxTemp

Rainfall

Evaporation

Sunshine

WindGustDir

WindGustSpeed

Humidity

Pressure

Cloud cover

📈 Model Evaluation

The Linear Regression model was evaluated using:

Mean Squared Error (MSE)

Residual plots

Predicted vs Actual comparison

🚀 Future Improvements

Add multiple ML models (Random Forest, XGBoost)

Build a Flask API for predictions

Deploy as a Streamlit dashboard

Add time-series forecasting (ARIMA/LSTM)

👨‍💻 Author

Finny Daniel
MSc Cybersecurity & Data Science
ESAIP — France
