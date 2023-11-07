# Stock Market Prediction using Linear Regression

This repository contains a Python-based project for predicting stock market closing prices using Linear Regression. In this project, we will use historical stock market data to train a Linear Regression model and then use it to predict the closing prices for the next 100 days.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Predicting stock market prices is a challenging task, and various factors can influence the prices, such as market sentiment, economic indicators, and news events. This project utilizes a simple Linear Regression model to make predictions based on historical stock market data. Keep in mind that this is a basic example and may not result in highly accurate predictions. More advanced models and data preprocessing techniques can be explored for improved accuracy.

## Dataset

The dataset used for this project consists of historical stock market data with the following columns:

- Date: The historical date.
- Open: Opening asset price for the day.
- High: Highest asset price for the day.
- Low: Lowest asset price for the day.
- Close*: Closing asset price for the day (to be predicted).
- Adj Close: Adjusted closing price (considering dividends).
- Volume: Volume traded for the day.
- Dividend: Dividend yield for the day.
- Stock Splits: Announced stock split (0 if none)

*The closing price reflects the price after considering stock-splits.

The historical data is located in the "TRAIN" folder, with 50 files, each containing 3000 rows of data.

## Project Structure

The project is organized as follows:

- `Dataset`: This directory contains the historical stock market data files.
- `Linear_Regression.ipynb`: This directory contains the source code for data preprocessing, model training, and prediction.

## Installation

To set up the project environment, you can use the following steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/stock-market-prediction.git
   cd stock-market-prediction
   ```

2. Create a virtual environment (optional but recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use "venv\Scripts\activate"
   ```

   ```

## Usage

To train the Linear Regression model and make predictions for the next 100 days, follow these steps:

1. Place your historical stock market data files in the `Dataset` folder.

2. Use the provided Python notebook to preprocess the data, train the model, and make predictions. Refer to the notebook  for detailed usage instructions.



## Results

After training the model and making predictions, you can evaluate the performance and analyze the results. Keep in mind that this is a basic example, and the accuracy of predictions may vary based on data quality and model complexity.

