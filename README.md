# Home Price Prediction Using Linear Regression
## Overview

This project applies linear regression to predict home prices based on various features such as square footage, number of bedrooms, and location. Using Python's Scikit-Learn library, we build and evaluate a linear regression model to estimate home prices and assess the model's performance.
## Features

* Load and preprocess home price data from a CSV file
* Build and train a linear regression model using Scikit-Learn
* Evaluate the model's performance with metrics such as Mean Squared Error (MSE) and R-squared
* Visualize predictions and residuals to understand model performance

## Prerequisites

* Python 3.7 or higher
* pip (Python package installer)

## Installation

1. Clone the repository:

        git clone https://github.com/yourusername/Home_price_analysis.git

2. Navigate to the project directory:

        cd Home_price_analysis

3. Create a virtual environment (optional but recommended):

        python -m venv venv

4. Activate the virtual environment:

        Windows: venv\Scripts\activate

        MacOS/Linux: source venv/bin/activate

5. Install the required packages:

        pip install -r requirements.txt

## Data

* CSV File: The project expects a CSV file with home price data. Ensure the CSV file includes columns such as SquareFootage, Bedrooms, Bathrooms, Location, and Price. Place this file in the data directory and name it house_data.csv.

## Results

* Model Performance: Evaluation metrics including Mean Squared Error (MSE) and R-squared score to assess model accuracy.
* Visualizations: Scatter plot comparing actual vs. predicted home prices, showing the model's performance and residuals.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
## Acknowledgments
* Scikit-Learn for machine learning algorithms and tools.
* Pandas for data manipulation.
* Matplotlib for data visualization.
