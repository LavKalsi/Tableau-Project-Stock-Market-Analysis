# Tableau Project: Stock Market Analysis

A comprehensive Tableau dashboard demonstrating the four key types of data analytics: **Descriptive**, **Diagnostic**, **Predictive**, and **Prescriptive**. This project leverages Python for data preprocessing and stock price prediction, offering insights into stock market trends.

## Features

- **Descriptive Analytics**: Historical data visualization for trend analysis.
- **Diagnostic Analytics**: Insights into past market behaviors.
- **Predictive Analytics**: Uses an LSTM model to forecast stock prices.
- **Prescriptive Analytics**: Offers potential strategies based on predictive insights.

## Prediction Model

The LSTM model, built in Python, processes and scales data from Yahoo Finance to predict future prices. Results are saved to a CSV for Tableau integration.

## Installation

Clone the repository:

```bash
git clone https://github.com/LavKalsi/Tableau-Project-Stock-Market-Analysis.git
cd Tableau-Project-Stock-Market-Analysis

## Data Preparation

Execute the `prediction.py` script to generate predicted stock prices:

```bash
python prediction.py

## Tableau Dashboard

Import the generated CSV file into Tableau to display and analyze the predictions.

## Visualizations

Screenshots of descriptive, diagnostic, predictive, and prescriptive dashboards created in Tableau:

![Descriptive Dashboard](path_to_descriptive_dashboard_screenshot)  
![Diagnostic Dashboard](path_to_diagnostic_dashboard_screenshot)  
![Predictive Dashboard](path_to_predictive_dashboard_screenshot)  
![Prescriptive Dashboard](path_to_prescriptive_dashboard_screenshot)  
