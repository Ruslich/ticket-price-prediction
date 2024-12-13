
# Airline Flights Price Prediction

## Overview

This repository focuses on predicting airline flight prices using various machine learning models. By leveraging historical flight data, this project aims to provide insights into ticket pricing and improve prediction accuracy for better planning and decision-making.

## Features

- **Machine Learning Models**: Linear Regression, Random Forest, XGBoost, Extra Trees, and more.
- **Hyperparameter Tuning**: Grid Search, Randomized Search, and HyperOpt for optimization.
- **Visualization**: Data analysis and insights through visualizations.
- **Interactive Tools**: Jupyter Notebooks and data visualizations.

## Dataset

The dataset contains flight booking information from the website Easemytrip for travel between India's top six metro cities. It includes:
- **300,261 data points** across 11 features.
- Data collected over 50 days (February 11 – March 31, 2022).
- Business and economy class ticket details.

### Key Features
- **Airline, Flight Code**: Airline company and specific flight.
- **Source & Destination Cities**: Starting and landing points.
- **Departure & Arrival Time**: Grouped into categories.
- **Stops, Class, Duration**: Details about stops, seat class, and travel time.
- **Days Left**: Days between booking and travel.

## Notebooks and Code

### Jupyter Notebooks
1. **Data Cleaning**: Handling missing values, encoding categorical features, and feature engineering.
2. **Exploratory Data Analysis (EDA)**: Visualization of trends and insights.
3. **Model Building**: Training and evaluating models.
4. **Feature Importance**: Analyzing influential features.

### Key Python Libraries
- Pandas, NumPy for data manipulation.
- Matplotlib, Seaborn for visualization.
- Scikit-learn, XGBoost for machine learning.

## Visualizations

Key visualizations include:
- Price distributions, trends over time.
- Effects of departure/arrival time and cities on ticket prices.
- Analysis of class and cancellation trends.

## Performance

Performance metrics used:
- R2 Score
- Root Mean Square Error (RMSE)
- Mean Absolute Error (MAE)
- Mean Absolute Percentage Error (MAPE)

### Best Model Results
- **Random Forest**: R2 = 0.96, RMSE = 4330.
- **XGBoost**: R2 = 0.96, RMSE = 4338.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/AirlineFlightsPrediction.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebooks for data analysis and model training.

## Contributors

- [Veronika Rybak](https://www.linkedin.com/in/veronika-rybak-55379a337/)
- [Ruslan Tsibirov](https://www.linkedin.com/in/ruslan-tsibirov-6bb6a2262/)
- Olga Ivanova
