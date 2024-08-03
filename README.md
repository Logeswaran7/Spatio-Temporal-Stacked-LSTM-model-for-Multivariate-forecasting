# Spatio-Temporal-Stacked-LSTM-model for Multivariate forecasting
## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [License](#license)

## Introduction
This project is about Stacked Long Short-Term Memory (LSTM) neural networks to forecast weather conditions such as rainfall, temperature, humidity, and wind speed using time series data collected over a period of 3 months.

Forecast results, particularly rainfall exceeding a specified threshold, are automatically sent to a designated Telegram chat using a Telegram bot, providing timely weather updates

## Features
- **Spatio-Temporal Forecasting**: Utilizes stacked LSTM models to capture both spatial and temporal dependencies in weather data, enhancing the accuracy of 
   forecasts across multiple locations.
- **Automated Notifications**: Integrates with Telegram to send automated messages when forecasted rainfall exceeds a threshold, ensuring users receive prompt 
   alerts about significant weather changes.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/Logeswaran7/Spatio-Temporal-Stacked-LSTM-model-for-Multivariate-forecasting.git
    cd Spatio-Temporal-Stacked-LSTM-model-for-Multivariate-forecasting
    ```
## Dataset
1.The original dataset has been feature engineered from various subsets,diverse weather and rainfall data for the original dataset has been collected from https://www.ncdc.noaa.gov/cdo-web/datasets and IMD official site

2.We conducted experiments using a limited subset of corrected dataset along with their corresponding ground truth labels, which have been included in the repository

## Model-architecture
1.To know more about the modified model architecture you can go through our survey paper https://icicc-conf.com/icicc24

## results
![Telegram Notification Output](Telegram%20notification%20output.png)

