
# Air Fare Price Prediction

This project aims to predict airfare prices based on historical data and various influencing factors such as airline, source, destination, date of travel, and more. The goal is to develop a machine learning model that can accurately forecast ticket prices to help travelers make informed decisions and airlines optimize pricing strategies.

## Project Overview
Airline ticket prices fluctuate based on several variables, including travel season, demand, time before departure, and other factors. This project explores various machine learning algorithms to predict airfare prices and provides insights into which features are most important in influencing prices.

## Key Analysis Performed:
* Collect and clean historical flight data, including ticket prices, routes, and airline information.
* Identify key features affecting price fluctuations.
* Build and evaluate multiple machine learning models to predict flight prices.
* Compare model performance to select the best approach for price prediction.

## Data Sources:
The dataset used for this project contains information such as:
* Airline: Name of the airline operating the flight.
* Date_of_Jurney: The travel date.
* Source and Destination: The starting and ending points of the journey.
* Arrival/Departure Time: Influence of time of day on airfare prices.
* Duration: The total flight duration.
* Total Stops: Number of Stops: Whether the flight is direct or has layovers.

## Technologies used:
**Python:** Core language used for data analysis and model building.
**Pandas & NumPy:** For data manipulation and preprocessing.
**Scikit-learn:** For implementing various machine learning models.
**Matplotlib & Seaborn: ** For data visualization and analysis.


## Model Evaluation Metrics:
* R² Score: To evaluate the goodness of fit.
* Mean Absolute Error (MAE): To assess prediction accuracy.
* Root Mean Squared Error (RMSE): To measure prediction error.
